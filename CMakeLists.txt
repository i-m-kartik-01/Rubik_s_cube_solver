cmake_minimum_required(VERSION 3.31)
project(Rubik_s_cube_solver)

set(CMAKE_CXX_STANDARD 20)

add_executable(Rubik_s_cube_solver main.cpp
        cmake-build-debug/Model/RubiksCube.cpp
        cmake-build-debug/Model/RubiksCube.h
        cmake-build-debug/Model/RubiksCube1DArray.cpp
        cmake-build-debug/Model/RubiksCube3DArray.cpp
        cmake-build-debug/Model/RubiksCubeBitboard.cpp
        cmake-build-debug/Solver/BFSSolver.h
        cmake-build-debug/Solver/DFSSolver.h
        cmake-build-debug/Solver/IDDFSSolver.h
        cmake-build-debug/Solver/IDAstarSolver.h
        cmake-build-debug/PatternDatabases/NibbleArray.cpp
        cmake-build-debug/PatternDatabases/NibbleArray.h
        cmake-build-debug/PatternDatabases/PatternDatabase.cpp
        cmake-build-debug/PatternDatabases/PatternDatabase.h
        cmake-build-debug/PatternDatabases/PermutationIndexer.h
        cmake-build-debug/PatternDatabases/math.cpp
        cmake-build-debug/PatternDatabases/math.h
        cmake-build-debug/PatternDatabases/CornerDBMaker.cpp
        cmake-build-debug/PatternDatabases/CornerDBMaker.h
        cmake-build-debug/PatternDatabases/CornerPatternDatabase.cpp
        cmake-build-debug/PatternDatabases/CornerPatternDatabase.h
)
