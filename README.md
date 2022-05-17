# simple_shell

# Table of contents.

Description

File Structure

Requirements

Installation

Usage

Example of Use

Bugs

Authors

License

# Description

simple_shell is a command line interpreter, or shell, in the tradition of the first Unix shell written by Ken Thompson in 1971. This shell is intentionally minimalistic, yet includes the basic functionality of a traditional Unix-like command line user interface. Standard functions and system calls employed in simple_shell include: access, execve, exit, fork, free, fstat, getline, malloc, perror, signal, stat, wait, write.

# File Structure

AUTHORS - List of contributors to this repository

man_1_simple_shell - Manual page for the simple_shell

shell.h - program header file

builtins.c - major builtin functions

check_for_builtins - checks to see if the user's command matches a builtin



# Installation

Clone this repository: git clone "https://github.com/marylizkarumba/simple_shell.git"

Change directories into the repository: cd simple_shell

Compile: gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

Run the shell in interactive mode: ./hsh

Or run the shell in non-interactive mode: example echo "/bin/ls" | ./hsh

# Example of Use

Run the executable in your terminal after compiling:

$ ./hsh

$ # This is our rendition of the shell

$ ls -al
