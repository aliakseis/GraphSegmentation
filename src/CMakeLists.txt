find_package(OpenCV REQUIRED)

include_directories(
    /usr/local/include
    /usr/include/gdal)
ADD_LIBRARY( GraphSegmentation

          pedro
	      )

target_link_libraries(GraphSegmentation ${OpenCV_LIBS} )
