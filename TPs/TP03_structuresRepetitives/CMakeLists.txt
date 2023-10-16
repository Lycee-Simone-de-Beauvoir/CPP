cmake_minimum_required(VERSION 3.25)
project(TP03_structuresRepetitives)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_EXE_LINKER_FLAGS "-static")

add_executable(TP03 main.cpp)
add_executable(Somme 01_somme.cpp)
add_executable(MultiplesOuNon 02_multiples.cpp)
add_executable(CalculMoyenne 03_moyenne.cpp)
add_executable(Factorielle 04_factorielle.cpp)
add_executable(SuiteDeFibonacci 05_fibonacci.cpp)
