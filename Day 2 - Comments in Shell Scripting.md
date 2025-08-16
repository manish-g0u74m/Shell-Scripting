# Day 2 - Comments in Shell Scripting
Comments are non-executable lines in a script used to explain the code. They are ignored by the shell but are crucial for human readability and understanding,
especially in complex scripts or when collaborating.

In shell scripting, **comments** are used to add explanations, notes, or instructions inside the code.  

---

## 1. Single-Line Comment
Single-line comments start with the **`#`** symbol.  
Everything written after `#` on the same line is treated as a comment.

### Example:
```bash
#!/bin/bash

# This is a single-line comment
echo "Hello World"   # This comment explains the echo command
```

```bash
Hello World
```
## 2. Multi-line Comments

There are multiple ways to write multi-line comments in shell scripts.

### Method 1: Using multiple # symbols

```bash
#!/bin/bash

# This is a multi-line comment
# Each line starts with #
# It is useful for longer explanations
echo "Script executed"
```
### Method 2: Using a Here Document (** << 'EOF' **)

```bash
#!/bin/bash

<< 'END_COMMENT'
This is a multi-line comment block
It will be ignored by the shell
You can write multiple lines here
END_COMMENT

echo "Multi-line comment example"
```
Output :

```bash
Multi-line comment example
```
