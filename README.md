# Progate-CL-Course:

## This repository has unix command-line and git cheatsheet/documentation.

**1) CREATING FILES:**

- General Syntax:

> $ touch file_name

- Example:

> $ touch sample.txt

**2) Displaying content of a file:**

- General Syntax:

> $ cat file_name

- Example:

> $ cat sample.txt

#content-Hello World

**3) Creating a directory:**

- General Syntax:

> $ mkdir directory_name

- Example:

> $ mkdir html

**4) Moving between directories:**

- General Syntax:

> $ cd directory_name

- Example:

> $ cd html

html $-->current directory is displayed here

**5) Checking the current directory:**

- General Syntax:

> $ pwd

**6) Displaying a list of files:**

- General Syntax:

> $ ls

**7) Parent Directory:**

- General Syntax:

> $ cd ..

**8) Home Directory:**

- General Syntax:

> $ cd

**9) Moving files and directories:**

*Moving a file:*

- General Syntax:

> $ mv file_to_move destination_directory

- Example:

> $ mv beginner.txt html

#here beginner.txt=file

#html=directory

*Moving Directory:*

- General Syntax:

> $ mv directory_to_move destination_directory

- Example:

> $ mv html ruby

**10) Renaming files and directories:**

- General Syntax:

> $ mv old_file_name new_file_name

- Example:

> $ mv ss.txt mm.txt

**11) Copying files and directories:**

- General Syntax:

> $ cp file_to_copy new_file_name

- Example:

> $ cp dojo.txt project.txt

**12) Removing files and directories:**

- General Syntax:

> $ rm file_to_remove

- Example:

> $ rm index.txt

# [To practice the Command Line visit this link](https://progate.com/commandline/study/1/13#/32)

# Progate-git-course:

**1) Creating a new empty repository**

- General Syntax:

> $ git init

**2) Selecting files to share**

- General Syntax:

> $ git add file_name

- Example:

> $ git add index.html

**3) Saving the added files**

- General Syntax:

> $ git commit -m "Commit message"

- Example:

> $ git commit -m "Create index.html"

**4) Adding remote repository**

<img src="https://lh3.googleusercontent.com/69cf8dWTmfWTrM794I4xOulxtN5MulzH1RlcbK9F_-XkFzg54GJGoApSdSLQ58-1s9iKBg=s116" height="250px" width="250px" alt="Reference">

- General Syntax:

> $ git remote add remote_name remote _URL

- Example:

> $ git remote add origin https://prog-8.com/mysite.git

**5) Uploading files**

- General Syntax:

> $ git push remote_name master

- Example:

> $ git push origin master

**6) Downloading files from remote**

- Example:

> $ git pull origin master

**7) Git flow review**

<img src="https://lh3.googleusercontent.com/zgY43xtN6BAfKE38-Ff86olmqJb0FUu24X6cZZfv0GjklZ5w4qqH-z24txWCzplS8wftzw=s116" height="250px" width="250px">

**8) Recognizing modified files**

- General Syntax:

> $ git status

**9) Recognizing content changes:**

- General Syntax:

> $ git diff

**10) Checking added files**

<img src="https://lh3.googleusercontent.com/_e2fstq1hjIoJ2PIOZ0E3sXv5y00BJXSiTusDzNNJIKwhePjRHD9iFeyw9AxEkcDDnOz0Q=s116" width="250px" height="250px">

- Green color line:files that are added

- Red color line:files that are not added

**11) To make changes in the editor**

- General Syntax:

> $ code .

### By using this syntax , you will be automatically redirected to VS Code and we can modify the code.






