cmake_minimum_required(VERSION 3.24)

project(myprogram LANGUAGES CXX VERSION 1.0.0)

include(GNUInstallDirs)

add_executable(${PROJECT_NAME} src/main.cpp)
install(TARGETS ${PROJECT_NAME} RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR})
