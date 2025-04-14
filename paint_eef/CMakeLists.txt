cmake_minimum_required(VERSION 2.8.3)
project(concert_tool_descriptions)

find_package(catkin REQUIRED COMPONENTS roslaunch)

catkin_package()

install(
  DIRECTORY meshes urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
