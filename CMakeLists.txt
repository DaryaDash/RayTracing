cmake_minimum_required(VERSION 3.5.0)
project(ray_traysing VERSION 0.1.0 LANGUAGES C CXX)

add_executable(ray_traysing main.cpp vec3.h color.h)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
