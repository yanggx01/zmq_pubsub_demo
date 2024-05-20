cmake_minimum_required(VERSION 3.5)

project(zmq_client LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(cppzmq)

add_executable(zmq_client main.cpp)

target_link_libraries( zmq_client cppzmq)
target_link_libraries( zmq_client zmqpp)
