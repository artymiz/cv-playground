cmake_minimum_required(VERSION 2.8)
project( DisplayImage )

# add opencv cmake configuration
# set(project_path ${CMAKE_SOURCE_DIR})
# cmake_path(GET project_path PARENT_PATH PARENT_DIR)
# set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} ${PARENT_DIR}/cmake-modules)

find_package( OpenCV REQUIRED )

add_executable( DisplayImage DisplayImage.cpp )
target_link_libraries( DisplayImage ${OpenCV_LIBS} )
