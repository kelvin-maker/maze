cmake_minimum_required(VERSION 3.0.0)
project(sdl-start VERSION 0.1.0)

#include(CTest)
#enable_testing()

add_executable(sdl-start src/main.cpp)

#set(CPACK_PROJECT_NAME ${PROJECT_NAME})
#set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
#include(CPack)


target_link_libraries(sdl-start SDL2main SDL2)
set(ENV{DISPLAY} :0.0)