cmake_minimum_required(VERSION 2.8.3)
cmake_policy(SET CMP0048 NEW)
project(summit_xl_perception VERSION 0.1.0 LANGUAGES CXX)

find_package(catkin REQUIRED COMPONENTS)

catkin_package()

install(
  DIRECTORY launch config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
