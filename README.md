# Minimal FreeRTOS simulator for POSIX

## Motivation
I couldn't find a simplified boilerplate for FreeRTOS on POSIX systems which, so I decided to make my own :)

## Note 
- This simulator is intended to run on Posix systems (includes Ubuntu and other Linux distros)
- Other platforms may not be supported
  
## Steps to run
1. Add your additional header files to the `include` folder
2. Add your additional source files to the `src/app` folder and edit the `CMakeLists.txt` to add the source files
3. Fill in `main.cpp` to call the functions defined in your additional source and header files
4. Go back to the root folder of the repo
5. Open terminal and type the steps below 
6. `mkdir build`
7. `cd build && cmake ..`
8. `make`
9. `cd build/src/app/`
10. `./FreeRTOS_App`
