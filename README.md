# Networking with ROS on RaspBerry PI 3B+

Images were transferred and streamed in video using ROS(Robot Operating System) over ethernet and wifi networks from RaspBerry Pi 3B+ to workstation for processing.

## Steps to get networking done in your system

### Dependencies
1. Install ROS Kinetic [Link](http://wiki.ros.org/kinetic/Installation/Ubuntu)
2. Install ROS on Raspbian [Link](http://wiki.ros.org/ROSberryPi/Setting%20up%20ROS%20on%20RaspberryPi)
3. Install OpenCV on your system as well as on RaspBerry Pi [Link](https://www.learnopencv.com/install-opencv3-on-ubuntu/)
4. Install cv_bridge

### Now you are ready to use this repo

Clone the repo to your desired directory
```
$ cd {Your directory}
$ git clone https://github.com/Shubham-Sahoo/drone_networking.git
```
Make a catkin workspace, if you already don't have it
```
$ mkdir -p ~/catkin_ws/src
$ cd catkin_ws/
$ catkin_make
$ cd catkin_ws/src/
$ catkin_create_pkg networking rospy roscpp std_msgs OpenCV cv_bridge
```





## To fit plane in the 3D plot

```python 
ranplanefit.py
```
![Ransac Plane Fitted](https://github.com/Shubham-Sahoo/SLAM/blob/master/Plane_fit.png)

