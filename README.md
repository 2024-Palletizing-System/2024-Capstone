# 2024 Capstone
2024.Seoultech.uni.Capstone design project 

## Enviroments
Doosan-Robotics collaborative robot m1013 <br>
Intel-RealSense 435i<br>
SCHUNK EGP-64 gripper<br>

## Build
This program is implemented at Ubuntu 20.04 - ROS-Noetic

#### 0) ROS-Noetic
[http://wiki.ros.org/noetic/Installation/Ubuntu](http://wiki.ros.org/noetic/Installation/Ubuntu)<br>

Our project needs the packages written below.<br>

#### 1) PCL
[https://github.com/PointCloudLibrary/pcl](https://github.com/PointCloudLibrary/pcl)<br>

Cuda environment is **cuda 12.1+cudnn 8.9.0** <br>
Pytorch version is **2.2.2+cu121**

#### 2) Yolo v7

[https://gitlab.com/Alsrbile/2023-capstone/-/tree/main/catkin_test/src/yolov7-u7/src/seg?ref_type=heads](https://gitlab.com/Alsrbile/2023-capstone/-/tree/main/catkin_test/src/yolov7-u7?ref_type=heads)<br>

You should download this package.<br>

# How to use?

0. Create ROS workspace in the place you want.

1. Clone [this repository] inside the src directory.

2. Install required package.

3. Feel free to use!

## Reference

* https://github.com/jerry800416/3dbinpacking

## License

[APACHE2.0](https://github.com/2024-Palletizing-System/2024-Capstone/blob/97ec6a8b2618ddeaa44a3a86d2a94cd1d58d414c/LICENSE)
