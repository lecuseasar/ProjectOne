﻿# CMakeList.txt : CMake project for ProjectOne, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_executable (ProjectOne "main.c" "recdir.c" "sha256.c" "stb_ds.h")

# TODO: Add tests and install targets if needed.
