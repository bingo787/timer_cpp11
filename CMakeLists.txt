cmake_minimum_required(VERSION 3.10)
project(timer)

set(CMAKE_CXX_STANDARD 14)
add_definitions(-pthread)
add_executable(timer 
	timer.hpp
	main.cc)
