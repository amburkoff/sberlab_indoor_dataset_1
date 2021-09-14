# SberLab indoor dataset 1

Dataset for paper DNN-BASED INDOOR SEMANTIC MAPPING FOR AUTONOMOUS NAVIGATION ROBOTS

After the article is published, the dataset will be made publicly available.

The datasets that we used was provided by Sber Robotics Laboratory, by using a robot courier with name Gleb. It has a chassis with a differential drive and is equipped with high-precision optical encoders, which together with LiDAR SLAM, give accurate localization on the map, and can be used for odometry ground truth. This dataset represents office-like area containing large open spaces and, conversely, narrow corridors, as well as the presence of many windows, reflections from the floor, and transparent objects. This all creates additional requirements for the tested solutions and allows to more accurately identify the best of them. Additionally, it contains all the needed data including RGB-D images from RealSense D455, ZED2 and Kinect2 cameras. Dataset also includes grayscale infrared stereo images, raw data from the IMU, ground truth depth values from Kinect 2.0, camera calibration parameters, and transformation matrices between the cameras. During capturing process, two datasets were made, one with the infrared projector of the RealSense D455 was turned off as the points from the projector on the grayscale images would interfere the work of Kimera-VIO. Nevertheless, another dataset was captured with a projector turned on. ROS and ROSbag were used to collect the datasets, we will publish it for further researching purposes.
