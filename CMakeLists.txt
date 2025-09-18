cmake_minimum_required(VERSION 3.22)   # 要求 CMake 版本
project(Hello VERSION 1.0 LANGUAGES CXX) # 工程名+版本+语言
add_executable(main main.cpp)         # 把 main.cpp 编译成可执行文件 hello