cmake_minimum_required(VERSION 3.19)
project(SAP_OS)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(SAP_OS
        defs.h
        global.cpp
        os.cpp
        resource.cpp
        rtos_api.h
        sys.h
        task.cpp
        test.cpp events.cpp)
