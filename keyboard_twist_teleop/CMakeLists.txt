cmake_minimum_required(VERSION 3.0.2)
project(keyboard_twist_teleop)

find_package(catkin REQUIRED COMPONENTS
  rospy
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

catkin_install_python(PROGRAMS scripts/teleop.py
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
