cmake_minimum_required(VERSION 3.24)

set(SOURCES main.cpp)
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)


add_executable(Arithmetic ${SOURCES})

target_include_directories(Arithmetic PUBLIC ${MY_INCLUDE_DIR})