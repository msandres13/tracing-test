
CMAKE_MINIMUM_REQUIRED( VERSION 2.8.11 )
message ("-------------------START-----------------------------" )
project( trace_test )
set (CMAKE_CXX_STANDARD 14)

add_executable( ${PROJECT_NAME}
	trace.cpp
	main.cpp
)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra")

message ("-------------------END-----------------------------" )
