cmake_minimum_required(VERSION 2.8)
project( hiapp )

# find_package( OpenCV REQUIRED )
# find_package( PkgConfig REQUIRED )

# include_directories( ${OpenCV_INCLUDE_DIRS} )
# include_directories( ${LINUX_KERNEL_DIR}/include )

add_executable(hiapp hiapp.c)

# target_link_libraries( hiapp ${OpenCV_LIBS})
install(TARGETS hiapp DESTINATION bin)
