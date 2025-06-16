# Linux 101👷🏻

## Exercise 1
  - [ ] What is the difference between `cat` and `touch` commands.
  - [ ] Create a file using the `cat` and the `touch` commands.

**Answer**
  cat is mainly used for reading, writing, and combining files. You can use it to create a file while simultaneously adding content.
  touch is used to create empty files or update the last modified timestamp of an existing file. It does not open the file for editing.



## Exercise 2: 
  - [ ] What are file permissions in linux and what are the various ways of displaying the file permissions in linux.
  **Answer**
  User (Owner)
  Group
  Others (Everyone else)

  - [ ] What is the default `permissions` given to a file when its created.
  **Answer**
  Owner has read and write
  everyone else has just read
  - [ ] What is the default `permissions` given to a folder when its created.
  owner has everything
  **Answer**
  everyone else can only read and execute
  - [ ] How do you create `a folder` in linux.
  **Answer**
  mkdir
## Exercise 3
  - [ ] Firstly, research and find the command used to print the number of lines, words and characters in a file.
  **Answer**
  wc filename
  - [ ] Secondly, apply the command to the `animals.txt` file attached to this exercises.
  **Answer**
  image is in image folder
## Exercise 4
  - [ ] Using a `linux command`, get the first 3 lines in the `animals.txt`
  - [ ] In addition to getting the first 3 lines, count only the words within this range.🫣
## Exercise 5
  - [ ] There is a command in linux that starts with `g`, that has the capability to search through fiiles. What is the `command`?
  **Answer**
  grep
  - [ ] Using this command, search for the words, `Nutshell`, `Perl` and `Dansoman` in `animals.txt`
## Exercise 6
  - [ ] What `command` is used to list all files in a directory?
  **Answer**
  ls
  - [ ] Wait a minute....what is a `directory` in linux 😅?
  **Answer**
  It is a storage location like a folder
## Exercise 7
  - [ ] What is the `pwd` command what does it do?
  **Answer**
  it prints the working directory
  - [ ] What is the difference between `echo` and `cd` command?
  cd changes the working directory
  **Answer**
  echo is used to print to the terminal
## Exercise 8
  - [ ] What is the `dirs` command in linux and what does it do? 
  **Answer**
  - The dirs command in Linux is used to display the list of directories in the shell's directory stack.

  - [ ] I need to find out what the command `mv` does, what command do I need to use to find out more about the `mv` command in linux.
  **Answer**
  - the mv command  is used to move or rename files and directories
- man mv → Opens the manual page for mv, providing detailed documentation.
- info mv → Displays more in-depth information about the mv command.
- mv --help → Shows a brief summary of how the command works and its available options.


## Exercise 9
  - [ ] Using the `date` command, print out the current day in the terminal.
  **Answer**
  $ date
Wed Jun  4 12:28:18 GST 2025

  - [ ] What is the difference between `awk` and `grep` commands? Please provide examples.
  **Answer**
- grep is used primarily for searching text patterns in files.
- awk is a full-fledged text-processing tool, allowing filtering, formatting, and mathematical operations on structured text.

## Exercise 10
  - [ ] What are environment variables? List out 5 env variables(There is a command to list them out in your terminal.😜)
  **Answer**
  printenv or env 
  Environment variables are dynamic values that affect how processes and applications run in the system. They store system-wide settings, configurations, and user preferences.
 PATH  HOME USER SHELL PWD.

  - [ ] What is the difference between `more` and `less` commands.
  **Answer**
  more only allows forward navigation
  les allows forward and backward navigation
## Exercise 11
  - [ ] There is a command in linux for seeing a type of a file in a directory what command is that?
  **Answer**
  file
## Exercise 12
  - [ ] The Unix system has a filesystem tree what is it called and list 3 important folders in this tree.
   root directory tree.
  **Answer**
  /home 
  /etc 
  /var 

## Exercise 13
  - In unix are 2 commands `head` and `tail`. Kindly illustrate how this is used in the git bas terminal.
  **Answer**
  Head shows the first 10 lines of a file
  Tail shows the last 10 lines of a file


## Exercise 14
  - [ ] Create a file called students.txt with the following content:
  ```
    John Doe,Computer Science,3.8
    Jane Smith,Mathematics,3.9
    Bob Johnson,Physics,3.7
    Alice Brown,Computer Science,3.6
  ```
  NB: add screenshots for solutions to the ff questions
  - [ ] Display the entire contents of the file
  - [ ] Display only the first 2 lines
  - [ ] Display only the last 2 lines
  - [ ] Count the number of lines, words, and characters in the file
  - [ ] Search for all lines containing "Computer Science"
  - [ ] Create a new file with only the Computer Science students
  - [ ] Sort the file by GPA (last column)
  - [ ] Replace all occurrences of "Computer Science" with "CS" and check the final output.

## Exercise 15
  - [ ] Create a log file called server.log with this content:
    ```
      2023-01-15 10:30:25 INFO User login successful
      2023-01-15 10:31:15 ERROR Database connection failed
      2023-01-15 10:32:10 INFO User logout
      2023-01-15 10:33:45 WARNING Low disk space
      2023-01-15 10:34:20 ERROR Authentication failed
      2023-01-15 10:35:05 INFO System backup completed
    ```
    NB: add screenshots for solutions to the ff questions
  - [ ] Find all ERROR entries
  - [ ] Count how many WARNING entries exist
  - [ ] Extract all timestamps (first two columns)
  - [ ] Find lines that contain either "login" or "logout"
