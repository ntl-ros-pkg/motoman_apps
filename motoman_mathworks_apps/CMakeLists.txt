cmake_minimum_required(VERSION 2.8.3)
project(motoman_mathworks_apps)

find_package(catkin REQUIRED)

catkin_package(
 LIBRARIES ${PROJECT_NAME}
)

# Install
foreach(dir launch)
  install(DIRECTORY ${dir}/
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/${dir})
endforeach(dir)

# Test
if (CATKIN_ENABLE_TESTING)
  find_package(roslaunch REQUIRED)
  roslaunch_add_file_check(launch)
endif()
