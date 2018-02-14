cmake_minimum_required(VERSION 2.8.3)
project(crane_x7_simulation)

find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
