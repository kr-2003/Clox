cmake_minimum_required(VERSION 3.0)
project(CLOX)

# Add the include directory to the search path
include_directories(include)

# Add your source files
add_executable(main src/chunk.c src/main.c src/memory.c src/debug.c src/value.c src/vm.c src/compiler.c src/scanner.c src/object.c src/table.c)