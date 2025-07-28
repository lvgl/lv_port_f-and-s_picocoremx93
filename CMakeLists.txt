cmake_minimum_required(VERSION 3.10)
project(lv_port_f_and_s_picocoremx93)

# include(${CMAKE_CURRENT_LIST_DIR}/lv_port_linux/CMakeLists.txt)
add_subdirectory(${CMAKE_CURRENT_LIST_DIR}/lv_port_linux)

add_compile_definitions(-DLV_CONF_PATH=${CMAKE_CURRENT_LIST_DIR}/lv_conf.h)
