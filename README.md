# Get Next Line

## Introduction

The **Get Next Line** project introduces a convenient and reusable function that reads a line from a file descriptor.
This task offers an opportunity to learn and use **static variables**, a powerful feature in C programming. Upon completion,
this function can be added to your **libft** for future use in reading files or inputs line by line.

## Project Description

The goal of this project is to implement the `get_next_line` function, which reads from a file descriptor and returns the next line,
including the newline character. This function handles various scenarios, such as files of different sizes, standard input,
and adjustable buffer sizes.

### Function Prototype

```c
char *get_next_line(int fd);
