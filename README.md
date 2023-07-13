## WOLF-ROS

This repository serves as a sandbox for [ROS wrapper](http://mobile_robotics.pages.iri.upc-csic.es/wolf_projects/wolf_lib/wolf-doc-sphinx/ROS_integration/_index.html) of [WOLF: A Modular Estimation Framework for Robotics](http://mobile_robotics.pages.iri.upc-csic.es/wolf_projects/wolf_lib/wolf-doc-sphinx/index.html), which is a candidate simultaneous localization and mapping (SLAM) framework using multi-scale fiducial markers.

## Installation

The overall installation procedure is the same as that of the original WOLF-ROS, as presented in its [installation manual](http://mobile_robotics.pages.iri.upc-csic.es/wolf_projects/wolf_lib/wolf-doc-sphinx/WOLF_demos/_index.html).

### Prerequisite

WOLF-ROS requires ROS1 and [WOLF](https://github.com/tag-nav/wolf).

### Build using catkin 

The following command shows an example of how to install the WOLF-ROS using [`catkin`](https://catkin-tools.readthedocs.io/en/latest/index.html).
```
$ mkdir -p catkin_ws/src && cd catkin_ws/src
$ git clone https://github.com/tag-nav/wolf_ros.git
$ cd ..
$ catkin init
$ catkin build
$ source devel/setup.bash
```

### What's changed compared to the original WOLF?

- `wolf_ros_node` now refers to [https://github.com/tag-nav/wolf_ros_node](https://github.com/tag-nav/wolf_ros_node) instead of [https://gitlab.iri.upc.edu/mobile_robotics/wolf_projects/wolf_ros/wolf_ros_node](https://gitlab.iri.upc.edu/mobile_robotics/wolf_projects/wolf_ros/wolf_ros_node).
- `wolf_demo_apriltag_imu` now refers to [https://github.com/tag-nav/wolf_ros_demo_apriltag_imu](https://github.com/tag-nav/wolf_ros_demo_apriltag_imu) instead of [https://gitlab.iri.upc.edu/mobile_robotics/wolf_projects/wolf_ros/demos/wolf_demo_apriltag_imu](https://gitlab.iri.upc.edu/mobile_robotics/wolf_projects/wolf_ros/demos/wolf_demo_apriltag_imu).