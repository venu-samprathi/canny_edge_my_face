Image Processing using ROS and OpenCV

1)Subscribe the images from Camera driver
2)Convert ROS images to OpenCV image type using CvBridge
3) Processing OpenCV image using its APIs to find the edges on the image
4)Converting the OpenCV image type of edge detection to ROS image messages and publish


After building the folder in your catkin workspace:
Launch: roslaunch canny_edge_my_face camera_face.launch
Run in a seperate window: rosrun canny_edge_my_face cv_camera

Enjoy! Canny-edging

I've built and run this package on Ubuntu(14.04) and ROS-Indigo
