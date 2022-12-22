# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

FILE(GLOB_RECURSE app_sources ${CMAKE_SOURCE_DIR}/src/*.*)
set(SOURCES main.cpp)
idf_component_register(SRCS ${SOURCES})
