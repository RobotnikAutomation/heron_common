cmake_minimum_required(VERSION 2.8.3)
project(heron_description)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
  message_runtime
  robotnik_sensors
  std_msgs
  std_srvs
  tf
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)