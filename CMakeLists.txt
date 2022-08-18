cmake_minimum_required(VERSION 3.8)

PROJECT(CppVerbalExpressions VERSION 1.0.0 LANGUAGES CXX)

#SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3 -std=c++17 -Wall -pedantic")

ADD_LIBRARY(VerbalExpressionsCpp verbalexpressions.hpp)
set_target_properties(VerbalExpressionsCpp PROPERTIES LINKER_LANGUAGE CXX)