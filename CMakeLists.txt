cmake_minimum_required(VERSION 3.25)

project(vsghouseviewer)

find_package(vsg REQUIRED)
find_package(vsgXchange REQUIRED)

add_executable(${PROJECT_NAME} vsghouseviewer.cpp)

set_target_properties(${PROJECT_NAME} PROPERTIES CXX_STANDARD 17)
    
target_link_libraries(${PROJECT_NAME} vsg::vsg)
target_link_libraries(${PROJECT_NAME} vsgXchange::vsgXchange)
