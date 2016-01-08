cmake_minimum_required(VERSION 3.3)
project(pa5game)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp
        Game.h
        Piece.h
        Agent.h
        Simple.h
        Strategic.h
        Resource.h
        Food.h
        Advantage.h
        GamingTests.cpp GamingTests.h
        ErrorContext.cpp ErrorContext.h
        Exceptions.h
        Strategy.h
        DefaultAgentStrategy.h
        Gaming.h
        AggressiveAgentStrategy.h)
add_executable(pa5game ${SOURCE_FILES})