cmake_minimum_required(VERSION 3.16)
project(factory_pattern
  VERSION 0.0.1
  LANGUAGES CXX
)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_subdirectory(source)
