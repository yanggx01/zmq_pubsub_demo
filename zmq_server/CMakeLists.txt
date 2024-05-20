cmake_minimum_required(VERSION 3.5)

project(zmq_server LANGUAGES CXX)

find_package(cppzmq)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(zmq_server main.cpp)

target_link_libraries( zmq_server cppzmq)
target_link_libraries( zmq_server zmqpp)
