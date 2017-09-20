cmake_minimum_required(VERSION 3.8)
project(libvterm)

add_custom_target(bla ALL COMMAND make
        WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}
        )