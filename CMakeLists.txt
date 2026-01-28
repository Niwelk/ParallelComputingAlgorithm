cmake_minimum_required(VERSION 3.10)
project(ParallelComputingAlgorithm)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(ParallelComputingAlgorithm
        BlockingQueue.h
        ThreadPool.cpp
)

target_include_directories(ParallelComputingAlgorithm PRIVATE .)