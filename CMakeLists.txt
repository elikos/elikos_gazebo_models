cmake_minimum_required(VERSION 2.8.3)
project(elikos_gazebo_models)
set(CMAKE_CXX_FLAGS "-std=c++11 ${CMAKE_CXX_FLAGS}")

find_package(catkin REQUIRED COMPONENTS
#  roscpp
)

catkin_package(
#	CATKIN_DEPENDS roscpp
)
