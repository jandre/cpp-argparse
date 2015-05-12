cmake_minimum_required(VERSION 2.8.7)
set(PROJECT_NAME_STR argparse)
project(${PROJECT_NAME_STR} C CXX)

add_library(argparse OptionParser.cpp)
