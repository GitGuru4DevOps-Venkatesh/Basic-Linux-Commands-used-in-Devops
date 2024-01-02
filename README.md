# Basic-Linux-Commands-used-in-Devops
Mostly used Basic Linux Commands in DevOps field

Certainly, here are the steps in a tabular format:

| Step | Action                                               | Description                                    |
|------|------------------------------------------------------|------------------------------------------------|
| 1    | Create Main Branch Directory                        | Create a directory called "MainBranch."        |
| 2    | Create Dir1 and Dir2                                | Create two subdirectories inside "MainBranch" named "Dir1" and "Dir2." |
| 3    | Navigate to Dir1 and Create DirA & DirB             | Go into "Dir1" and create subdirectories "DirA" and "DirB." |
| 4    | Navigate to Dir2 and Create Dirc & Dird             | Return to "MainBranch," enter "Dir2," and create subdirectories "Dirc" and "Dird." |
| 5    | Enter DirA and Create File1 & File2                | Go into "DirA" and create files "File1" and "File2." |
| 6    | Navigate Back and Select DirB                       | Return to "Dir1" and enter "DirB."              |
| 7    | Create File3 & File4 in DirB                        | Inside "DirB," create files "File3" and "File4." |
| 8    | Navigate Back and Select DirC                       | Return to "MainBranch" and enter "DirC."        |
| 9    | Create File5 & File6 in DirC                        | Inside "DirC," create files "File5" and "File6." |
| 10   | Navigate Back and Select DirD                       | Return to "MainBranch" and enter "DirD."        |
| 11   | Create File7 & File8 in DirD                        | Inside "DirD," create files "File7" and "File8." |

This table summarizes the creation of directories and files as described in your original request.

Command to do the above sample cloning Project here:
You've described a series of steps to create directories and files. Here's how you can do it:

1. Create the main branch directory:
   ```
   mkdir MainBranch
   cd MainBranch
   ```

2. Create Dir1 and Dir2:
   ```
   mkdir Dir1
   mkdir Dir2
   ```

3. Go to Dir1 and create DirA and DirB:
   ```
   cd Dir1
   mkdir DirA
   mkdir DirB
   ```

4. Go back to the main branch and go to Dir2, then create Dirc and Dird:
   ```
   cd ..
   cd Dir2
   mkdir Dirc
   mkdir Dird
   ```

5. Go to DirA and create File1 and File2:
   ```
   cd ../Dir1/DirA
   touch File1
   touch File2
   ```

6. Go back to Dir1 and select DirB, then create File3 and File4:
   ```
   cd ..
   cd DirB
   touch File3
   touch File4
   ```

7. Go back to the main branch and select DirC, then create File5 and File6:
   ```
   cd ../../
   cd Dir2/Dirc
   touch File5
   touch File6
   ```

8. Go back to the main branch and select DirD, then create File7 and File8:
   ```
   cd ../../
   cd Dir2/Dird
   touch File7
   touch File8
   ```

Now, you've created the directory structure and files according to your instructions.
----

Certainly! Here's a list of common commands used in DevOps along with explanations and use cases:

1. **`pwd` (Present Working Directory):**
   - **Explanation:** Displays the current working directory.
   - **Use Case:** Useful for confirming the current location when navigating the file system in scripts or manual operations.

2. **`cd` (Change Directory):**
   - **Explanation:** Used to change the current working directory.
   - **Use Case:** Essential for navigating the directory structure while working with code repositories, configuration files, or deployment scripts.

3. **`mkdir` (Make Directory):**
   - **Explanation:** Creates a new directory.
   - **Use Case:** Often used in automation scripts to create directories for storing logs, artifacts, or temporary files during deployment.

4. **`rm -rf` (Remove Directory/File):**
   - **Explanation:** Removes directories or files forcefully.
   - **Use Case:** Useful in cleaning up obsolete files or directories during automated cleanup processes in build or deployment pipelines.

5. **`vi` or `nano` (Text Editors):**
   - **Explanation:** Vi and Nano are text editors used to create or modify files.
   - **Use Case:** Editing configuration files, scripts, or any text-based files during configuration management or troubleshooting.

6. **`cat` (Concatenate and Display):**
   - **Explanation:** Displays the content of a file.
   - **Use Case:** Checking the content of log files, configuration files, or any other text-based files during troubleshooting or monitoring.

7. **`cp` (Copy):**
   - **Explanation:** Copies files or directories.
   - **Use Case:** Often used in deployment scripts to copy artifacts or configuration files to target servers.

8. **`mv` (Move/Rename):**
   - **Explanation:** Moves or renames files or directories.
   - **Use Case:** Renaming files, moving artifacts to appropriate directories, or organizing files in deployment processes.

9. **`ls` (List):**
   - **Explanation:** Lists files and directories in the current directory.
   - **Use Case:** Checking the contents of a directory, verifying the presence of files before and after deployments.

10. **`touch` (Create Empty File):**
   - **Explanation:** Creates an empty file.
   - **Use Case:** Often used in scripts to create placeholder files or trigger certain processes.

11. **`cp -r` (Copy with Recursive):**
   - **Explanation:** Copies directories and their contents recursively.
   - **Use Case:** Copying entire directory structures, such as deploying a set of files or configurations to multiple servers.

These commands form the foundation for many DevOps tasks, including configuration management, deployment automation, and system troubleshooting. Understanding and mastering these commands is crucial for effective DevOps practices.

Certainly! Let's go through each command with examples to provide a clearer understanding for students:

1. **`pwd` (Present Working Directory):**
   - **Example:**
     ```bash
     $ pwd
     /home/user/projects/devops
     ```
     This indicates that the current working directory is "/home/user/projects/devops."

2. **`cd` (Change Directory):**
   - **Example:**
     ```bash
     $ cd /home/user/projects/devops
     ```
     Changes the current working directory to "/home/user/projects/devops."

3. **`mkdir` (Make Directory):**
   - **Example:**
     ```bash
     $ mkdir logs
     ```
     Creates a new directory named "logs" in the current working directory.

4. **`rm -rf` (Remove Directory/File):**
   - **Example:**
     ```bash
     $ rm -rf old_logs
     ```
     Removes the directory "old_logs" and its contents forcefully.

5. **`vi` or `nano` (Text Editors):**
   - **Example (using vi):**
     ```bash
     $ vi new_file.txt
     ```
     Opens the vi editor to create or edit the file "new_file.txt."

6. **`cat` (Concatenate and Display):**
   - **Example:**
     ```bash
     $ cat log.txt
     ```
     Displays the content of the "log.txt" file on the terminal.

7. **`cp` (Copy):**
   - **Example:**
     ```bash
     $ cp app_config.conf /etc/app/
     ```
     Copies the "app_config.conf" file to the "/etc/app/" directory.

8. **`mv` (Move/Rename):**
   - **Example:**
     ```bash
     $ mv backup_logs/ /archives/
     ```
     Moves the "backup_logs" directory to the "/archives/" directory.

9. **`ls` (List):**
   - **Example:**
     ```bash
     $ ls
     ```
     Lists the files and directories in the current working directory.

10. **`touch` (Create Empty File):**
    - **Example:**
      ```bash
      $ touch placeholder.txt
      ```
      Creates an empty file named "placeholder.txt" in the current directory.

11. **`cp -r` (Copy with Recursive):**
    - **Example:**
      ```bash
      $ cp -r source_directory/ destination/
      ```
      Copies the entire "source_directory" and its contents to the "destination" directory.

These examples illustrate how each command is used in different scenarios. Understanding and practicing these commands will help students navigate the command line effectively in a DevOps environment.
----
