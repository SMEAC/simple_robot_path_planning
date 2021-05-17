# simple_robot_path_planning

This ROS package provides a significant step up on the simple_robot_LIDAR model, by adding the move_base and AMCL packages.

Included in the package are:
* Package.xml and CMakeLists.txt files
* a xacro and gazebo file, enhanced slightly from the simple_robot package to include different colors for each wheel, in order to allow easier debugging from RVIZ.  Additionally the appropriate velocity controllers are appied inside the gazebo file.
* a world file for gazebo with moveable walls.
* a config file for the velocity controllers
* a launch file for Gazebo and Rviz
* a config file for Rviz
