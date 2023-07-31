cmake_minimum_required (VERSION 3.20)
project ("checkingTheBasicFunctionsOfTheTwo2")

add_subdirectory(../Catch2 Catch2-build)
add_executable(checkingTheBasicFunctionsOfTheTwo2  test-main.cpp )
target_link_libraries(checkingTheBasicFunctionsOfTheTwo2 PRIVATE Catch2::Catch2)