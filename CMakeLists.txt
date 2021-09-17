cmake_minimum_required(VERSION 3.10)

project(reconcycle_franka_control)

find_package(catkin REQUIRED COMPONENTS
  franka_control
)

catkin_package(
  INCLUDE_DIRS 
  LIBRARIES 
  CATKIN_DEPENDS
    franka_control
  DEPENDS 
)

 
