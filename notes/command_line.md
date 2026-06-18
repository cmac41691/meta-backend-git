# Command Line

## Purpose

The command line allows a developer to interact directly with the operating system using text commands.

It is commonly used for:

- Git
- Python
- Linux servers
- Docker
- Automation
- Backend development

---

## Basic Workflow

User Command
    ↓
Shell
    ↓
Operating System
    ↓
Output

---

## Commands Learned

### pwd

Purpose:
Shows the current working directory.

Example:

pwd

---

### ls

Purpose:
Lists files and folders in the current directory.

Example:

ls

---

### cd

Purpose:
Changes directories.

Example:

cd projects

---

### mkdir

Purpose:
Creates a new directory.

Example:

mkdir test-folder

---

### touch

Purpose:
Creates a file.

Example:

touch notes.txt

---

## Backend Connection

Developers use the command line to:

- Run Git commands
- Launch Python programs
- Manage servers
- Navigate project folders
- Deploy applications

---

## Reflection

The command line is the foundation for many backend tools.

Learning the terminal helps me understand what Git, Python, and backend systems are doing behind the scenes.

## Commands
PIPES (|)

Purpose:
Send the output of one command into another command.

Concept:

Command A
    |
    V
Command B

Example:

ls | more

List files and send output to another command.

Key Idea:
Commands can work together instead of separately.

Backend Connection:
Useful for logs, automation, servers, and shell scripts.


REDIRECTION (> >> <)

Purpose:
Control where command input and output go.

>

Overwrite a file.

Example:

ls > files.txt

Output goes into files.txt

>>

Append to a file.

Example:

echo "Hello" >> notes.txt

Adds text to end of file.

<

Take input from a file.

Key Idea:
Output doesn't always have to go to the terminal.

Backend Connection:
Used for logs, reports, automation, and scripts.


Pipe (|)
=
Output → Another Command

Redirection (>)
=
Output → File