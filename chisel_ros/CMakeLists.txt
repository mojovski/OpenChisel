cmake_minimum_required(VERSION 2.8.3)
project(chisel_ros)
 
# if (DEFINED CATKIN_TOPLEVEL OR (NOT ("$ENV{ROS_DISTRO}" STREQUAL "fuerte")))
#     include(${PROJECT_SOURCE_DIR}/catkin.cmake)
# else ()
#     include(${PROJECT_SOURCE_DIR}/rosbuild.cmake)
# endif ()

include(${PROJECT_SOURCE_DIR}/rosbuild.cmake)