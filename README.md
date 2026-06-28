# CSE467-assignment-3
CSE467: Computer Security | Spring 2026 | Cryptography

                            Solution will be added soon.




Memory Corruption and Exploit Development

This project explores memory corruption vulnerabilities and exploit development techniques in C programs. The assignment focuses on understanding low-level program behavior, stack memory layouts, shellcode execution, and control-flow hijacking through a series of progressively challenging targets.

## Features

* Multiple vulnerable target programs
* Shellcode generation
* Automated build scripts
* Helper utilities for exploit development
* Progressive exploitation challenges
* Practical analysis of memory safety issues

## Repository Structure

```text
.
├── CSE467_assignment_3.pdf   # Assignment specification
├── README.md                 # Repository documentation
├── build.py                  # Python build automation
├── build.sh                  # Shell build script
├── helper.c                  # Utility functions
├── shellcode.py              # Shellcode generation utilities
├── target0.c
├── target1.c
├── target2.c
├── target3.c
├── target4.c
├── target5.c
├── target6.c
└── target7.c                 # Vulnerable challenge programs
```

## Components

### Target Programs

The assignment consists of eight independent targets:

* `target0.c`
* `target1.c`
* `target2.c`
* `target3.c`
* `target4.c`
* `target5.c`
* `target6.c`
* `target7.c`

Each target introduces increasingly advanced concepts related to memory corruption and low-level program behavior.

### Shellcode Utilities

`shellcode.py` contains utilities for generating and testing shellcode used throughout the assignment.

### Helper Functions

`helper.c` provides supporting functionality shared across multiple targets and experiments.

### Build Scripts

* `build.sh` provides shell-based compilation.
* `build.py` automates project setup and building tasks.

## Topics Covered

The project explores:

* Stack memory organization
* Buffer overflows
* Function call mechanics
* Memory corruption vulnerabilities
* Control-flow manipulation
* Shellcode execution
* Low-level debugging and analysis
* Secure programming considerations

## Building

Compile the project using:

```bash
./build.sh
```

or

```bash
python3 build.py
```

Depending on the assignment configuration, additional target binaries may be generated automatically.

## Main Files

### shellcode.py

Implements shellcode generation and related utilities.

### helper.c

Contains shared helper functions used by the target programs.

### target*.c

Provide progressively challenging exercises involving memory corruption and exploit analysis.

### build.py / build.sh

Automate compilation and project setup.

## Technologies

* C
* Python 3
* GCC
* Linux system programming tools

## Course Information

**Course:** CSE467 Computer Security
