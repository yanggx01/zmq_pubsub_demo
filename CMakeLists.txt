cmake_minimum_required(VERSION 3.5)

project(zmq_demo LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

ADD_SUBDIRECTORY(zmq_server)
ADD_SUBDIRECTORY(zmq_client)
