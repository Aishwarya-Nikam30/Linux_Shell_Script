# 🐚 Shell Script Basics

## 📖 What is Shell Scripting?

Shell scripting is writing a series of commands for the shell (command-line interpreter) to execute automatically.  
It helps automate repetitive tasks, manage system operations, and simplify workflows.

---

## 🧠 Common Shells

- **Bash**: The most commonly used Linux shell (Bourne Again SHell).
- **Zsh**: An extended version of Bash with additional features.
- **Sh**: The original Bourne shell.

---

## 🛠️ Basic Components of a Shell Script

### 🔹 Shebang (`#!`)
The first line in a shell script that tells the system which interpreter to use.  
**Example:**
```bash
#!/bin/bash
```
> **Comments**:
> Anything following `#` is a comment and is ignored by the shell.

> **Variables**:
> Store values in a script.

> **Conditional Statements**:
> Perform different actions based on conditions.

> **Loops**:
> Repeat a block of code multiple times.

> **Functions**:
> Group commands into reusable blocks.

## How to Run a Shell Script

1. Create a file with `.sh` extension.  
   Example: `script.sh`

2. Make the script executable:
   ```bash
   chmod +x script.sh
