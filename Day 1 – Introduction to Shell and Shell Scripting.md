# Task 1: Shell and Shell Scripting  

## Description  
In this task, we will understand **what a Shell is, the different types of Shell, what Shell Scripting means, and how to create and run a basic shell script.**  

## Instructions  

1. **What is a Shell?**  
   A shell is a **command-line interpreter** that acts as an interface between the user and the operating system. Through the shell, we can execute commands and interact with the OS.  

2. **Types of Shell in Linux/Unix:**  
   - Bourne Shell (sh)  
   - Bourne Again Shell (bash) – most common  
   - C Shell (csh)  
   - Korn Shell (ksh)  
   - Z Shell (zsh)  
   - Fish Shell (Friendly Interactive Shell)  

3. **What is Shell Scripting?**  
   Shell scripting is a **script/program written for the shell.** It automates tasks by executing commands sequentially.  

4. **How to Create and Run a Shell Script?**  

   - **Step 1: Create a file**  
     ```sh
     nano first_script.sh
     ```

   - **Step 2: Write the script**  
     ```sh
     #!/bin/bash
     echo "Hello, Manish!"
     ```
     👉 `#!/bin/bash` → tells the system to run the script using the Bash shell.  

   - **Step 3: Make the file executable (give permissions)**  
     ```sh
     chmod +x first_script.sh
     ```

   - **Step 4: Run the script**  
     ```sh
     ./first_script.sh
     ```

   📸 **Example Output:** 
     '''sh
      Hello, Manish!
     ''' 
