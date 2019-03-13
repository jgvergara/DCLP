
PROJECT(DCLP)

# Using C++ 11
SET(CMAKE_CXX_STANDARD 11)
SET(CMAKE_CXX_STANDARD_REQUIRED ON) # Required
SET(CMAKE_CXX_EXTENSIONS ON) # with compiler extensions like gnu++11

set(CMAKE_CXX_FLAGS_DEBUG "-pthread")
set(CMAKE_CXX_FLAGS_RELEASE "-pthread")

add_executable (DCLP dclp.cpp)
