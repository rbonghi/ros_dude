cmake_minimum_required(VERSION 2.8.3)
project(ros_dude_description)

set(ROS_BUILD_TYPE Debug)
set(CMAKE_BUILD_TYPE Debug)

find_package(catkin REQUIRED COMPONENTS tf )

# Declare our catkin package.
catkin_package(CATKIN_DEPENDS tf )


