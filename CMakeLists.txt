
CMAKE_MINIMUM_REQUIRED( VERSION 2.8.11 )
message ("-------------------START-----------------------------" )
project( trace_test )
set (CMAKE_CXX_STANDARD 17)

add_executable( ${PROJECT_NAME}
	main.cpp
)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -save-temps -std=c++1z -Wall -Wextra")

message ("-------------------END-----------------------------" )
