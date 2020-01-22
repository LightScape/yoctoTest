cmake_minimum_required(VERSION 2.6)
project(yoctoTest)
add_executable(yoctoTest main.c)
install(TARGETS yoctoTest DESTINATION bin)
