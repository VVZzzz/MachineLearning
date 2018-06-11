cmake_minimum_required(VERSION 3.10)
project(DecisionTree)

set(CMAKE_CXX_STANDARD 11)

add_executable(DecisionTree main.cpp decisiontree_id3.cpp decisiontree_id3.h)