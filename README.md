# 2024 Capstone
Capstone design project

## Enviroments
Doosan-Robotics collaborative robot m1013 <br>
Intel-RealSense 435i<br>
SCHUNK EGP gripper<br>

## Build
This program is implemented at Ubuntu 20.04 - ROS-Noetic

#### 0) ROS-Noetic
[http://wiki.ros.org/noetic/Installation/Ubuntu](http://wiki.ros.org/noetic/Installation/Ubuntu)<br>

Our project needs the packages written below.<br>

#### 1) Doosan-Robotics noetic-devel 
[https://github.com/doosan-robotics/doosan-robot#overview](https://github.com/doosan-robotics/doosan-robot#overview)<br>

#### 2) Intel-Realsense
[https://github.com/IntelRealSense/realsense-ros/tree/ros1-legacy](https://github.com/IntelRealSense/realsense-ros/tree/ros1-legacy)<br>

#### 3) PCL
[https://github.com/PointCloudLibrary/pcl](https://github.com/PointCloudLibrary/pcl)<br>

Cuda environment is **cuda 12.1+cudnn 8.9.0** <br>
Pytorch version is **2.2.2+cu121**

#### 4) Yolo v7

[https://gitlab.com/Alsrbile/2023-capstone/-/tree/main/catkin_test/src/yolov7-u7/src/seg?ref_type=heads](https://gitlab.com/Alsrbile/2023-capstone/-/tree/main/catkin_test/src/yolov7-u7?ref_type=heads)<br>

You should download this package.<br>
You only need this package from the original repository.<br>
Put **"predict_ui.py"** in the etc folder to this path **"/catkin_test/src/yolov7-u7/src/seg/segment"**.

# How to use?

1. Create ROS workspace in the place you want.

2. Clone [this repository] inside the src directory.

3. Install required package.

## Reference

* https://github.com/jerry800416/3dbinpacking

## License

[APACHE2.0]
