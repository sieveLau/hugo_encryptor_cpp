cmake_minimum_required(VERSION 3.8)

project(hugo_encryptor_cpp)
include_directories(external/googletest/googletest/include)
set(CXX_STANDARD_REQUIRED 17)
add_subdirectory(external/googletest)
add_subdirectory(md5)
add_subdirectory(base64)
add_subdirectory(util)