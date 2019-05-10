# Realsense calibration
Launch by navigating to "catkin_ws/build/image_pipeline/camera_calibration/catkin_generated/installspace" and start the stereo calibration:
```bash
./cameracalibrator.py --size 8x6 --square 0.0809556 right:=/stereo/right/image_raw left:=/stereo/left/image_raw
```

Camera has to publish unrectified video to the right and left topic described above using the "realsense_MT" package or playback of rosbag.




image_pipeline
==============

[![CircleCI](https://circleci.com/gh/ros-perception/image_pipeline.svg?style=svg)](https://circleci.com/gh/ros-perception/image_pipeline)

This package fills the gap between getting raw images from a camera driver and higher-level vision processing.

For more information on this metapackage and underlying packages, please see [the ROS wiki entry](http://wiki.ros.org/image_pipeline).

For examples, see the [image_pipeline tutorials entry](http://wiki.ros.org/image_pipeline/Tutorials) on the ROS Wiki.
