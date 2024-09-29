# Chapter 1: Exploring Basic Terminal Commands

This chapter of *Redhat Enterprise Linux 9 for Beginners* introduces some basic terminal commands

## Commands Covered

1. **`who`**  
  - Displays who is currently logged into the system.  
   ```bash
   who
   # Output example: 
   # user1  pts/0  2024-09-28 10:15 (192.168.0.100)
   ```

2. **`pwd` (Print Working Directory)**  
  - Shows the full path of the current directory you're working in.  
   ```bash
   pwd
   # Output example:
   # /home/user1/Documents
   ```

3. **`ls` (List Files and Directories)**  
   - Lists the contents of the current directory, including files and subdirectories.  
   - You can use various options with `ls`, such as `ls -l` for a detailed list or `ls -a` to show hidden files.
   ```bash
   ls
   # Output example:
   # file1.txt  file2.txt  folder1/
   ```

4. **`cd` (Change Directory)**  
   - Allows you to move between directories.  
   - Use `cd ..` to go up one level or specify a path to navigate to a specific folder.
   
   ```bash
   cd /path/to/directory
   # Example: cd /home/user1/Documents
   ```

5. **`mkdir` (Make Directory)**  
   - Creates a new directory.  
   
   ```bash
   mkdir new_folder
   # Creates a directory called 'new_folder' in the current location
   ```

6. **`rm` (Remove Files)**  
   - Deletes files.  
   - Be cautious with this command, as files deleted using `rm` are not recoverable without backups. For directories, use `rm -r` to remove them recursively.
   
   ```bash
   rm file.txt
   # Deletes the file 'file.txt'
   ```

7. **`rmdir` (Remove Directory)**  
   - Removes an empty directory.  
   - If the directory contains files, you must use `rm -r` instead to delete the directory and its contents.
   
   ```bash
   rmdir empty_folder
   # Removes the directory 'empty_folder', which must be empty.
   ```

8. **`call`**  
   - This command is used to execute scripts or commands in some environments, but may not be standard on all Linux systems.  
   - If running scripts directly, ensure they have execute permissions (`chmod +x script.sh`).
   
   ```bash
   call ./script.sh
   # Executes 'script.sh' in the current directory.
   ```

9. **`uname`**  
   - Displays basic information about the system, such as the operating system and hardware architecture.  
   - You can add options like `-a` for all available details.
   
   ```bash
   uname
   # Output example:
   # Linux
   ```

10. **`uname -r`**  
    - Shows the current kernel version.  
    
    ```bash
    uname -r
    # Output example:
    # 5.14.0-70.13.1.el9_0.x86_64
    ```

11. **`man` (Manual Pages)**  
    - Opens the manual pages for any command, providing detailed information on how to use it.  
    
    ```bash
    man ls
    # Opens the manual page for the 'ls' command.
    ```

12. **`echo`**  
    - Outputs the given text or variables to the terminal.  
    
    ```bash
    echo "Hello, Red Hat!"
    # Output example:
    # Hello, Red Hat!
    ```

13. **`date`**  
    - Displays the current date and time.  
    
    ```bash
    date
    # Output example:
    # Sat Sep 28 12:45:01 UTC 2024
    ```

<div align="center">
  <img src="screenshot/1.png" width=""/>
</div>




