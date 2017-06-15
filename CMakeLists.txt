cmake_minimum_required(VERSION 3.7)
project(RSA)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp BigInt.cpp Key.cpp RSA.cpp StringTrans.cpp PrimeGen.cpp)
add_executable(RSA ${SOURCE_FILES})