cmake_minimum_required(VERSION 3.6)
project(TaxiClient)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp TaxiClient.cpp TaxiClient.h)
add_executable(TaxiClient ${SOURCE_FILES})