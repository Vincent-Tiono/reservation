# README for Study Group Reservation System

**Author:** 張甡源 b11901123  
**Date:** 11/07/2024  

=====  
## Synopsis:

This project is a reservation system for a computer programming study group. Users can log in as either a Teaching Assistant (TA) or a Student to manage or view available study times with professors.

=====  
## Project Structure:

The project is organized into several files and directories:

- `main.cpp`: The main entry point for the program.
- `hsieh/hsieh.cpp` and `hsieh/hsieh.h`: Source and header files for Professor Hsieh's schedule.
- `lin/lin.cpp` and `lin/lin.h`: Source and header files for Professor Lin's schedule.
- `wei/wei.cpp` and `wei/wei.h`: Source and header files for Professor Wei's schedule.
- `reservation/reservation.cpp` and `reservation/reservation.h`: Files for handling reservations and user data.

=====  
## Prerequisites:

To compile and run this project, you need:

- A C++ compiler, such as `g++`
- Make (to use the provided `Makefile`)

=====  
## HOW TO COMPILE:

To compile the project, navigate to the root directory of the project and simply type:

```bash
make
```

=====  
## HOW TO RUN::

To run the program, navigate to the bin/ directory and run the file:

```bash
Copy code
cd bin/
./main
```
