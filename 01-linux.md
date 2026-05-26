# Linux Notes

## Section 2 - Linux Basics / Working Through the CLI

### What I understood

Linux is very important for DevOps because most servers and DevOps tools are designed to run on Linux first.

In real companies, many servers do not have a graphical interface. DevOps engineers usually connect to servers through the command line.

The Linux command line interface is called the shell.

Different shells exist, such as:
- sh
- bash
- zsh
- csh

Bash is one of the most common shells and supports more advanced features than older shells.

### Why Linux matters for DevOps

Linux is used heavily in:
- cloud servers
- Docker
- Kubernetes
- Ansible
- CI/CD runners
- monitoring systems
- production environments

For my Cloud/DevOps goal, I need to become comfortable using Linux commands without relying on a graphical interface.

### Basic commands learned

- `echo`: prints text or environment variables
- `ls`: lists files and folders
- `cd`: changes directory
- `pwd`: shows the current directory
- `mkdir`: creates a directory
- `mkdir -p`: creates a full directory tree
- `touch`: creates an empty file
- `cat`: displays file content or writes content into a file
- `cp`: copies files
- `cp -r`: copies directories recursively
- `mv`: moves or renames files
- `rm`: removes files
- `rm -r`: removes directories and their contents

### Important concepts

The terminal is not optional in DevOps.  
Most real server work happens through commands.

A shell is the program that interprets the commands I type.

Environment variables can be printed with `echo`, for example:

```bash
echo $SHELL