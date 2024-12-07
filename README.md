# Tiny-Unix-Shell

# Overview

Tiny Unix Shell is a custom implementation of a Unix-like command-line interface (CLI) written in C. It supports external and internal commands, redirection, pipes, environment variables, and history functionality. This shell simulates the behavior of a Unix shell, allowing users to execute commands, navigate the file system, and interact with the environment via a prompt interface.

# Features

External Command Execution: Supports executing common external commands like ls, clear, vi, etc.
Internal Commands: Implements basic internal commands such as cd (change directory) and pwd (print working directory).
Environment Variables: Initialize and manage environment variables.
Echo Command: Print environment variables using the echo command.
Redirection: Supports input/output redirection (>, >>, <, 2>) for both STDIN, STDOUT, and STDERR.
History Command: Access command history using history, and execute previous commands with ! (e.g., !!, !-1, !10, etc.).
Pipes: Supports piping multiple commands with the | operator (e.g., ls | grep 'a' | wc).
