cmake_minimum_required(VERSION 2.8.3)
project(hamer_mini)

find_package(catkin REQUIRED)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES hamer_mini
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

install(
  DIRECTORY launch rviz
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}

)


include_directories(
# include
# ${catkin_INCLUDE_DIRS}
)

