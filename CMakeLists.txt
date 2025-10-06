cmake_minimum_required(VERSION 3.10)
project(lv_port_f_and_s_picocoremx93)

set(LV_BUILD_CONF_PATH ${CMAKE_CURRENT_LIST_DIR}/lv_conf.h CACHE PATH
    "Use this to specify the location of and/or filename of lv_conf.h" FORCE)

add_subdirectory(${CMAKE_CURRENT_LIST_DIR}/lv_port_linux)
