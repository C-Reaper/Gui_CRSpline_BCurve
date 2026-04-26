# Project README

## Overview
The project is a simple C application that visualizes and manipulates control points for cubic Bézier splines. The application features an interactive window where users can create, manipulate, and visualize spline curves using mouse controls.

## Features
- Creation of cubic Bézier splines with multiple control points.
- Interactive manipulation of control points to adjust the shape of the spline.
- Display of the current position along the spline.
- Real-time update of the spline visualization based on user input.

## Project Structure
### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
To build and run the project:
1. Navigate to the project directory.
2. Use `make -f Makefile.linux all` for Linux.
3. Use `make -f Makefile.windows all` for Windows.
4. Execute the application with `make -f Makefile.(os) exe`.

### Additional Build Options
- `make -f Makefile.(os) do`: Builds and executes the application.
- `make -f Makefile.(os) clean`: Removes build artifacts.

This README provides a straightforward overview of the project's structure and how to build and run it on different operating systems.