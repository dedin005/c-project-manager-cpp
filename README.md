# c-project-manager-cpp

Create cpp projects, add source files, and update your makefile automatically with this tool

`c-project-manager-cpp.py` scans for new .cpp/.h files and updates the makefile for the c project in the current directory
`c-project-manager-cpp.py test` scans for new .cpp/.h files and updates the makefile for the c project in the `test` directory
`c-project-manager-cpp.py --new test` creates a new c++ project in the `test` directory
`c-project-manager-cpp.py --add code` creates code.cpp and code.h within the src directory of the c project in the current directory and updates the makefile

Makefile commands
`make` builds the project using optimized settings
`make optimized` builds the project using optimized settings
`make debug` builds the project using debug settings
`make run` builds the project using optimized settings and runs the program
`make gdb` builds the project using debug settings and runs the program within gdb
