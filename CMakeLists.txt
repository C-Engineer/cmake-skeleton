cmake_minimum_required(VERSION 2.6)
set(CMAKE_BUILD_TYPE Debug)

project(skeleton)

set (PROJECT_INCLUDE_DIR
	${PROJECT_SOURCE_DIR}/include
)

set (PROJECT_SRCS
	${PROJECT_SOURCE_DIR}/source/main.c
)

include_directories(${PROJECT_INCLUDE_DIR})
add_executable(skeleton ${PROJECT_SRCS})

install(TARGETS skeleton RUNTIME DESTINATION bin)