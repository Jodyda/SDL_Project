cmake_minimum_required(VERSION 3.20.2)
project(SDL_Project)

set(CMAKE_CXX_STANDARD 14)


set(SDL2_INCLUDE_DIR C:/SDL/include)
set(SDL2_LIB_DIR C:/SDL/lib/x86)

include_directories(${SDL2_INCLUDE_DIR})
link_directories(${SDL2_LIB_DIR})

add_executable(SDL_Project main.cpp)
target_link_libraries(${PROJECT_NAME} SDL2main SDL2)
