# 0x0C. Python - Almost a circle

## Overview

This project, "Almost a circle," is part of the Holberton School's higher-level programming curriculum, specifically focusing on Python. The primary goal of this project is to implement classes and inheritance in Python to create a robust representation of geometric shapes, with a particular emphasis on rectangles and squares.

## Description

The project consists of several Python scripts and a main Python class:

- `base.py`: Defines the `Base` class, which serves as the base class for all other geometric shapes. It includes a class attribute to keep track of the number of instances created and methods for serialization and deserialization of JSON.

- `rectangle.py`: Implements the `Rectangle` class, a subclass of `Base`, representing rectangles. It includes validation of attributes, getter and setter methods, and a method to calculate the area.

- `square.py`: Inherits from `Rectangle` and represents squares. It ensures the validity of attributes and inherits methods from both `Rectangle` and `Base`.

- `main_files/`: Contains Python scripts to test and showcase the functionality of the implemented classes.

## Usage

To use and test the functionality of the classes, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/0x0C-Python-Almost-a-circle.git
Navigate to the project directory:

bash
Copy code
cd 0x0C-Python-Almost-a-circle
Run the desired Python scripts in the main_files/ directory to see the classes in action.

Requirements
The project is developed using Python 3.7 and adheres to the Holberton School's style guide (PEP 8).

Author

Masehla Tshoane Respect
