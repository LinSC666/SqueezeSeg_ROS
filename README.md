# SqueezeSeg_Ros
This is a ros package that implement the SqueezeSeg

# Usage

**clone code**

```
cd ~/catkin_ws/src
git clone https://github.com/andylei77/SqueezeSeg_Ros.git
cd ~/catkin_ws/
```

**prepare data**

- download  `lidar_2d.tar.gz` from https://pan.baidu.com/s/1kxZxrjGHDmTt-9QRMd_kOA
- `tar -zxvf lidar_2d.tar.gz -C ~/catkin_ws/src/SqueezeSeg_Ros/script/data`

**compile and run**

```
catkin_make
roslaunch squeezeseg_ros squeeze_seg_ros.launch
```
