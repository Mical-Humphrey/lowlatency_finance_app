# Set minimum version of CMake, probably quite old now lol
cmake_minimum_required(VERSION 3.15)

# Give the Project name. Your name? O namae desu ka, senpai
project(lowlatency_finance_app)

# Set the C++ standard to the BEST standard, 17. Though it doesn't have a std::simd library....
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add executable and specify its source file
add_executable(lowlatency_finance_app src/main.cpp)
