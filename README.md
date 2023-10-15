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
