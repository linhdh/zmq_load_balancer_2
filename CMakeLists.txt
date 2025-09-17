cmake_minimum_required(VERSION 4.0)
project(zmq_load_balancer_2)

set(CMAKE_CXX_STANDARD 17)

add_executable(zmq_load_balancer_2 main.cpp)

target_link_libraries(zmq_load_balancer_2 zmq)
target_link_libraries(zmq_load_balancer_2 czmq)
