# Get Next Line Project

The Get Next Line (GNL) project is a coding challenge that tests your understanding of file reading and memory management in C programming. The aim of this project is to create a function that reads a line ending with a newline character ('\n') from a file descriptor, no matter the size of either the line or the file.

This project is perfect for reinforcing concepts of static variables, dynamic memory allocation, and file operations in C. It challenges you to consider edge cases and optimize for memory and speed efficiency.

## Table of Contents
- [Installation](#installation)
- [Features](#features)
- [How-It-Works](#how-It-Works)
- [Usage](#usage)
- [Challenges-and-Learnings](#challenges-and-learnings)

## Installation

```
1. Clone the repository
- https://github.com/Safwaan-GitHub/GNLSUB.git

2. Change directory
- cd GNLSUB
```

## Features

Line-by-Line Reading: Efficiently reads from a file or standard input, one line at a time, until the end of the file.
Memory Efficiency: Carefully manages memory to avoid leaks, ensuring that all allocated memory is freed appropriately.
Modular Design: Designed to be easily included in larger projects, making file reading tasks straightforward and efficient.
Error Handling: Implements robust error handling to manage scenarios where reading from the file descriptor is not possible.

## How-It-Works

Function Prototype: char *get_next_line(int fd);
Return Value: Returns a line read from a file descriptor, fd. The return line includes the terminating newline character, except if the file ended without a newline. If there is nothing else to read or an error occurs, it returns NULL.
Multiple File Descriptors: Capable of managing multiple file descriptors simultaneously, allowing you to read from multiple sources in an interleaved fashion.

## Usage

Compilation: To use the Get Next Line function in your project, compile it along with your files, ensuring you link any necessary libraries.

Calling the Function: Simply call get_next_line with a valid file descriptor to read the next line from your file or input stream.

## Challenges-and-Learnings

Static Variables: Understanding the use and scope of static variables in C.
Memory Management: Mastering dynamic memory allocation and deallocation to avoid memory leaks.
File Operations: Gaining insights into low-level file operations in C, including working with file descriptors.
