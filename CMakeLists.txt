project(hello)
cmake_minimum_required(VERSION 2.8)
add_executable(hello hello.cpp)
install(TARGETS  hello DESTINATION bin)
