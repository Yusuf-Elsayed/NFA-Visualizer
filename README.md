# NFA Visualizer

NFA Visualizer is a Python application that allows users to visualize Nondeterministic Finite Automata (NFA) and validate regular expressions against input strings.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This application provides an intuitive GUI for constructing and visualizing Nondeterministic Finite Automata from regular expressions. It also allows users to test input strings against the NFA to determine acceptance.

## Features

- **User-friendly GUI**: Facilitates seamless interaction and usability through tkinter and customtkinter integration, ensuring an intuitive interface for users.
  
- **Regular Expression Validation**: Ensures syntactic correctness of user-input regular expressions, preventing errors during NFA construction.
  
- **String Acceptance Checking**: Enables users to verify NFA functionality by testing acceptance of input strings against expected outcomes.
  
- **Comprehensive Error Handling**: Guides users with informative error messages for invalid inputs and transitions, enhancing overall usability.
  
- **Regular Expression to NFA Conversion**: Converts user-provided regular expressions into visual NFA diagrams for observation of structure and behavior.
  
- **NFA Visualization**: Aids in understanding NFA behavior and facilitates debugging through graphical visualization.

## Installation

To install and run the NFA Visualizer, follow these steps:

1. Clone this repository to your local machine using `git clone`.
2. Navigate to the project directory.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Run the main script using `python main.py`.

## Usage

Upon launching the application, users are presented with a GUI where they can input a regular expression and a test string. They can then visualize the constructed NFA and check if the input string is accepted by the NFA.

## File Structure

```
nfa-visualizer/
├── images/                    # Folder for storing images
├── parser_1.py                # Regular expression parser
├── NFA.py                     # NFA construction and validation
├── GUI.py                     # Graphical User Interface
├── main.py                    # Main script to run the application
├── README.md                  # This README file
└── requirements.txt           # List of dependencies
```

## Contributing

1. Youssef Sameh Zainhom
2. Youssef Khaled Mohamed
3. Mohamed Tarek Mohamed
4. Hager Ahmed Farag
5. Mai Kamel AbdelFattah
