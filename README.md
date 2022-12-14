# SLAM_by_fusing_multiple_IMU_sonsors_and_a_LIDAR_sensor_using_Extended_Kalman_Filter-ROS-
To fuse noisy IMU sensors (to replicate physical scenarios) for Simultaneous localization and mapping (SLAM)


# Usage
Clone the codes
```ruby
cd catkin_ws/
```
```ruby
cd src/
```
```ruby
git clone https://github.com/ROBOTIS-GIT/turtlebot3

Copy files turtlebot3_burger.urdf.xacro and turtlebot3_burger.gazebo.xacro from the repository and repplace with the file in the >>turtlebot3 >> turtlebot3_description>>urdf>>

```
```ruby
cd ..
```
Build the ROS packages
```ruby
catkin_make
```
```ruby
source /devel/setup.bash
```

PS: install slam_gmapping package before running the gmapping.launch
```ruby
git clone https://github.com/ros-perception/slam_gmapping.git
```
Then run catkin_make for the new package
