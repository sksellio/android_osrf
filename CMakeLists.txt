cmake_minimum_required(VERSION 2.8.3)
project(android_osrf)

find_package(catkin REQUIRED rosjava_tools)

catkin_rosjava_setup(install)

catkin_package()
