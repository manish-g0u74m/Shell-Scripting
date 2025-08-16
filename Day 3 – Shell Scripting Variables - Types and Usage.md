# Day 3 – Shell Scripting Variables: Types and Usage

## Variable 
A variable is like a container that stores data temporarily.

In shell scripting, variables are used to store, reuse, and manipulate values.

Example: names, numbers, file paths, command outputs, etc.

## Types of Variables

### 1. User Defined Variables 
Variables that we create ourselves.

Example:
```bash
name="Manish"
age=22
echo "My name is $name and my age is $age"
```

### 2. System Defined Variables (Environment Variables)
Predefined by the system.

Usually in uppercase (like HOME, USER, PATH, SHELL).

Example:
```bash
echo $HOME
echo $USER
echo $PATH
```

### 3. Command Substitution Variables

When we store the output of a command in a variable.

Syntax: variable=$(command)

Example:
```bash
today=$(date)
mydir=$(pwd)

echo "Today is $today"
echo "Current directory is $mydir"
```
