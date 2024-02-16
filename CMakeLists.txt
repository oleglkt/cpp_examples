cmake_minimum_required(VERSION 3.18)

project(module1)
 #   version 0.0.0
  #  DESCRIPTION "first project"
   # LANGUAGES CXX


set(CMAKE_CXX_STANDARD 17)
set(CMAKE_OBJCXX_STANDARD_REQUIRED ON)

add_executable(module1)

set(sources 
    main.cpp
)

target_sources(module1 PRIVATE ${sources})