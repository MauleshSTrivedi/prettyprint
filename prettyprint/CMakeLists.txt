cmake_minimum_required(VERSION 2.8.3)
project(prettyprint)
find_package(catkin REQUIRED)

catkin_package(INCLUDE_DIRS include)

install(DIRECTORY include/cxx-prettyprint/
  DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
  FILES_MATCHING PATTERN "*.h"
)
