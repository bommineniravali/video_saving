cmake_minimum_required(VERSION 2.6)
project( video )
find_package( OpenCV REQUIRED )
add_executable( video video_saving.cpp )
target_link_libraries( video ${OpenCV_LIBS} )

