# DNN-Object-Detection-YOLO3
Deep learning based object detection using YOLOv3 with OpenCV

## Fork:    
https://github.com/krutikabapat/DNN-Object-Detection-YOLOv3.git  

## Requirements:

OpenCV 3.4.2 and above.  

## File structure:

1. Models.sh (contains link to model files).
2. build_608_yolo.cpp (c++ code for yolo).
3. build_416_yolo.cpp (c++ code for yolo).
4. build_320_yolo.cpp (c++ code for yolo).
5. build_tiny_yolo.cpp (c++ code for yolo).

## Compile:

<code> g++ build_xxx_yolo.cpp -o xxx_yolo.out `pkg-config --cflags --libs opencv` </code>

Example: g++ build_608_yolo.cpp -o 608_yolo.out `pkg-config --cflags --libs opencv`

## Run

<code> ./xxx_yolo.out "path-to-img" </code>

Example: ./608_yolo.out "test_img4.jpg"
