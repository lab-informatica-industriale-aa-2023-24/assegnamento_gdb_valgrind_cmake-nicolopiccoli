cmake_minimum_required(VERSION 3.22.1)

project(assegnamento_CMake
	VERSION 0.9
	LANGUAGES C
	DESCRIPTION "Compilazione programmi valgrind")
	
add_executable(valgrind1 src/valgrind1.c)
add_executable(valgrind2 src/valgrind2.c)
add_executable(valgrind3 src/valgrind3.c)
add_executable(valgrind4 src/valgrind4.c)

