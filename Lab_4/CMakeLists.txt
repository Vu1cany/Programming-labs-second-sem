cmake_minimum_required(VERSION 3.23)
project(Lab_4)

set(CMAKE_CXX_STANDARD 14)

add_executable(Lab_4 main.cpp Interfaces.h GeoShapes/Rectangle.cpp GeoShapes/Rectangle.h GeoShapes/Ellipse.cpp GeoShapes/Ellipse.h Menu.cpp Menu.h)
