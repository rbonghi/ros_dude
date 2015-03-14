cmake_minimum_required(VERSION 2.8.3)
project(ros_dude)

set(ROS_BUILD_TYPE Debug)
set(CMAKE_BUILD_TYPE Debug)

find_package(catkin REQUIRED COMPONENTS
  	tf
)

# Declare our catkin package.
catkin_package(
   CATKIN_DEPENDS tf
)

#########################################################
# SOURCES
#set(${PROJECT_NAME}_SRC
#	src/myzharbot_tf_node.cpp
#)

#########################################################
# EXECUTABLE
#add_executable( 
#        myzharbot_tf_node
#	${${PROJECT_NAME}_SRC}
#)
#add_dependencies(
#        myzharbot_tf_node
#	${PROJECT_NAME}_generate_messages_cpp
#)
#target_link_libraries(
#        myzharbot_tf_node
#	${catkin_LIBRARIES}	
#)


