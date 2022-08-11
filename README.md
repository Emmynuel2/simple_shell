# Simple Shell
 **In this project we were assigned to make a functional Shell, with its basic commands.**

## Table of contents
 * General info
 * How to install?
 * Files of our Shell!
 * How does it work?
 * Commands that works!
 * Test cases!
 * Get to know how our shell works from the inside!
 * Authors!
 
## General info
 **Our shell has as prompt "cuchuflí%", Yazmín's trace.

 Our shell does what a shell normally does, it opens files with less, creates files with touch, you can modify files with vim, compile programs with gcc, list files and directories with ls, all this along with their flags.**

## How to install?
 Installing our Shell is quite easy, go to your terminal, write:

* git clone <https://github.com/yazgiraldoa/simple_shell.git>

And it will be installed in minutes!

## Plus: how to open it?
 Run the following command in your terminal:

 * gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

it will compile the files and then you can execute the hsh program as follows :

* ./hsh

## Files of our Shell!

| File	 |Description |
| ---- | ------ |
|main.c	| Function that checks if our Shell is called in interactive or non-interactive mode. |
|main.h	 | Header file with prototypes and structures. |
|handle_sigint.c |	Function that handle signal Ctrl + C to not quit. |
|fork_process |	Function that creates a child process. |
|find_path |	Function that searches the PATH in user environment. |
\error_messages.c |	Function that prints error messages related to "not found" and "permission denied". |
|count_words.c |	Function that counts words depending on delimiters. |
|builtins.c |	Function that look for a builtin (env and exit). |
|_strncmp.c |	Function that compares two strings. |
|_strlen.c |	Function that gets the length of a string. |
|_strcmp.c |	Function that compares two strings. |
|_strdup.c |	Function that duplicates a string. |
|_strcat.c |	Function that concatenates two strings. |
|_itoa.c |	Function that reverse a string. |
|prompt.c |	Function prints a prompt and gets a string from command line.| 
|shell_interactive.c |	UNIX command line interpreter that works in interactive mode. |
|shell_no_interactive.c	| UNIX command line interpreter that works in non-interactive mode. |
|tokenizer.c |	Function that split a string. |


## Authors!
 **EMMANUEL AMALIRI**
 **LOUIS BATTY**



