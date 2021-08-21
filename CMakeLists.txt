cmake_minimum_required(VERSION 3.0.2)
project(birdsview_map)


find_package(catkin REQUIRED COMPONENTS
  rospy
  gazebo_ros_2Dmap_plugin
  ros_maps_to_pedsim
  map_saver
)

catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)

