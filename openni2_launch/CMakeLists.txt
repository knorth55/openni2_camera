cmake_minimum_required(VERSION 2.8.3)
project(openni2_launch)

find_package(catkin)
catkin_python_setup()
catkin_package()

install(DIRECTORY launch
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/
)

