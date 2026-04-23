# AGENTS.md

This file provides guidance for AI coding agents working in this repository.

## Project Overview

This repository contains two projects:
1. A simple Python project ("ABC") that demonstrates basic print statements.
2. A CMake-based C++ HelloWorld project.

## Repository Structure

- `main.py` — Main Python script
- `main.cpp` — C++ HelloWorld source file
- `CMakeLists.txt` — CMake configuration file
- `README.md` — Project readme
- `ddd` — Miscellaneous file
- `build/` — CMake build directory (created during build)

## Development Guidelines

### Running the Code

**Python project:**
```bash
python main.py
```

**C++ CMake project:**
```bash
mkdir -p build
cd build
cmake ..
cmake --build .
./HelloWorld
```

### Making Changes

- Keep changes minimal and focused.
- Follow existing code style (plain Python, no external dependencies).
- Test your changes by running `python main.py` and verifying the output.

### Build and Test

- The Python project has no build or test pipeline. Validate changes manually by running the script.
- The C++ project uses CMake as its build system. Build and test by running the commands shown above.
