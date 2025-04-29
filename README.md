# 🔧 Custom Linux Shell

A lightweight custom shell for Linux that mimics core BASH functionalities. Built using C and Linux system programming concepts, this shell supports command execution, job control, pipelining, signal handling, and background process management.

## 🚀 Features

- **Command Execution**: Run basic commands like `ls`, `cat`, etc., similar to BASH.
- **Pipelining**: Support for pipelines (e.g., `ls | wc`).
- **Job Control**: Handle foreground and background jobs using `&`.
- **Signal Handling**: Custom handling for signals like `Ctrl+C` (`SIGINT`).
- **Background Process Management**: Track and manage background tasks.
- **Extensible Architecture**: Designed for adding features like:
  - Command history
  - Auto-completion
  - Scripting support

## 🧰 Technologies Used

- C Programming
- Linux System Calls (`fork()`, `execvp()`, `waitpid()`, etc.)
- Interprocess Communication (IPC)
- Signal Handling APIs
- File Descriptors & Redirection



