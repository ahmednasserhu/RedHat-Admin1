# RedHat-Admin1

## lab3

### 1. Using vi write your CV in the file mycv. Your CV should include your name, age, school,college, experience,...
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/1.png)

### 2. Open mycv file using vi command then: Without using arrows state how to:
#### a. Move the cursor down one line at time.
##### j
#####
#### b. Move the cursor up one line at time.
##### k
#####
#### c. Search for word age
##### /age
#####
#### d. Step to line 5 ().
##### :5
#####
#### e. Delete the line you are on and line 5.
#####  to delete the current line, type dd.
####   to move to line 5, type :5 and press Enter.
####   to delete line 5, type dd.
#####
#### f. How to step to the end of line and change to writing mode in one-step.
#####  $
#####

### 3. List the available shells in your system.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/3.png)

### 4. List the environment variables in your current shell.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/4.png)

### 5. List all of the environment variables for the bash shell.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/5.png)

### 6. What are the commands that list the value of a specific variable?
#### you can use echo $ENV_VARIABLE or printenv ENV_VARIABLE

### 7. Display your current shell name.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/7.png)

### 8.. State the initialization files of: sh, ksh, bash.
####    /etc/profile (system-wide)
####     ~/.bash_profile or ~/.bash_login or ~/.profile (user-specific, only the first one found is executed)
####     ~/.bashrc (sourced by interactive non-login shells)

### 9.Edit in your profile to display date at login and change your prompt permanently.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/9.png)

### 10.Execute the following command :
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/10.png)

### 11.Create a Bash shell alias named ls for the “ls –l” command
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB3/11.png)

## lab 4

#### 1.List the user commands and redirect the output to /tmp/commands.list
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/1.png)

#### 2.Count the number of user commands
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/2.png)

#### 3.Get all the users names whose first character in their login is ‘g’.
#### 4.Get the logins name and full names (comment) of logins starts with “g”.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/3%2C4%2C5.png)
#### 5.Save the output of the last command sorted by their full names in a file.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/5.png)

#### 6.Write two commands: first: to search for all files on the system that named .bash_profile. Second: sorts the output of ls command on / recursively, Saving their output and error in 2 different files and sending them to the background.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/6.png)

#### 7. Display the number of users who is logged now to the system.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/7.png)

#### 8. Display lines 7 to line 10 of /etc/passwd file
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/8.png)

#### 9. What happens if you execute:cat filename1 | cat filename2/ls | rm/ ls /etc/passwd | wc –l
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/9.png)

#### 10. Issue the command sleep 100.
#### 11. Stop the last command.
#### 12. Resume the last command in the background
#### 13. Issue the jobs command and see its output.
#### 14. Send the sleep command to the foreground and send it again to the background.
#### 15. Kill the sleep command.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/10%2C11%2C12%2C13%2C14%2C15.png)

#### 16. Display your processes only
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/16.png)

#### 17. Display all processes except yours
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/17.png)

#### 18. Use the pgrep command to list your processes only
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/18.png)

#### 19. Kill your processes only.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB4/19.png)


## lab5
#### 1. Compress a file by compress, gzip, zip commands and decompress it again. State the differences between compress and gzip commands.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/1.png)

#### 2. What is the command used to view the content of a compressed file.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/2.png)

#### 3. Backup /etc directory using tar utility.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/3.png)

#### 4. Starting from your home directory, find all files that were modified in the last two day.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/4.png)

#### 5. Starting from /etc, find files owned by root user.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/5.png)

#### 6. Find all directories in your home directory.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/6.png)

#### 7. Write a command to search for all files on the system that, its name is “.profile”.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/7.png)

#### 8. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/8.png)

#### 9. List the inode numbers of /, /etc, /etc/hosts.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/9_1.png)
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/9_2.png)
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/9_3.png)
#### 10. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the 
#### file you copied, and then use these commands again, and check the output.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/10.png)

#### 11. Create a symbolic link of /etc/passwd in /boot.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/11.png) 

#### 12. Create a hard link of /etc/passwd in /boot. Could you? Why
##### i can't create a hardlink because iam trying to create a hard link between files that reside on different partitions.
![UNFOUND](https://github.com/ahmednasserhu/RedHat-Admin1/blob/main/LAB5/12.png)
