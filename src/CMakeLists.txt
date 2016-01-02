set(PRO_SOURCE
	main.cpp
	udpclient.cpp
	udpclient.h
)

include_directories(${CMAKE_SOURCE_DIR})
include_directories(${CMAKE_CURRENT_BINARY_DIR})

ADD_EXECUTABLE(test_client
    ${PRO_SOURCE}
    )
