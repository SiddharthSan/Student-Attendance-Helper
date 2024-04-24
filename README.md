# Student Attendance Manager

## Description
This program, written in C++, is a Student Attendance Manager that demonstrates the use of polymorphism and inheritance. It allows users to input attendance details for students on a specific date and in a particular section of a classroom. Users can then display attendance details for a given date and section. The program employs polymorphism and inheritance through the use of base class `Person` and derived class `Student`, allowing for the management of student objects within the classroom.

## Features
- **Polymorphism**: Utilizes polymorphism by defining a base class `Person` with a pure virtual function `displayDetails()`, which is overridden in the derived class `Student`.
- **Inheritance**: Demonstrates inheritance by extending the base class `Person` to create the derived class `Student`, inheriting its attributes and behaviors.
- **Dynamic Memory Allocation**: Utilizes dynamic memory allocation to create and manage `Student` objects, ensuring efficient memory usage and cleanup.

## Usage
1. Run the program.
2. Choose from the following options:
    - **Enter details**: Allows users to input attendance details for students on a specific date and in a particular section.
    - **Display attendance details**: Displays attendance details for a given date and section.
    - **Exit**: Exits the program.
3. Follow the prompts to input data or view attendance details.

## Instructions
- When entering attendance details, provide the date, section, student names, and their attendance status (present or absent).
- Ensure to select valid options from the menu to avoid errors.
- Clean up dynamically allocated memory by choosing the exit option before terminating the program.

## Requirements
- C++ compiler (supporting C++11)
- Standard C++ libraries
