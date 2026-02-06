# Lab3 - 2/6/26

## Before lab begins
1. Open up vscode
2. Control + shift + 'p' to open command prompt (command + shift + p on apple)
3. Start typing 'Connect to...' and the 'Connect current window to host' menu item will pop up. Select it
4. If asked, connect to 'ron.sr.edu host'
5. Enter your RON username if prompted
6. Enter your RON password when prompted
7. Go to 'File --> Open folder'
8. Select your 'gen711-811' directory
9. If you haven't done so already, save your workspace to this directory (File --> save directory as --> enter)
10. Take your notes in 'Markdown' format. See the readme.txt for taking notes for this lab below. 

### Your Notes Here: 
Seperate notes by an empty line, or they'll get pasted together

- Using a dash is helpful for lists
1. And numbers for lists

The pound sign is used for 'sections'. A single pound (or hashtag) in front of a word makes it appear bigger/bold to show a new section. See below

# My Notes:

To change directories, use 'cd' and then hit tab two times to see directories in my current directory

## Commands

- ```pwd``` - Print Working Directory. Shows open directories. Like a map showing where within the files you're working.
-  ```ls``` - List. Shows all folders in working directory.
    - ```ls lrth``` shows many useful things
- ```clear``` - Clears past commands out of the terminal.
- ' ' Quotes represent a search area. You may get stuck in carrots if you accidentally open a quote without closing it.
- cntrl c - escape
- tab - autocomplete. Saves a lot of time and errors.
- ```cd file``` - change directories. Type directory name after cd.
    - ```cd ~``` brings you back to your home directory
- ../ - back up one step in directories
- ```head``` - print out first few lines of files to screen. Must specifiy file.
- ```cat file``` - print whole file. Proceed with caution.
- ```rm file``` - remove/delete. Careful!
- ```history``` - shows entire history of commands
- ```grep '@' file``` - searches a file for given text. Must specifiy in quotes what you're looking for and file to look in.
- ```> file``` redirect. Sends information to a place other than printing it to the screen. Added to the end of a grep or other printing command.
- ```|``` sends output to a dfferent command.
- ```WC``` - shows line, word, and character count
- ```less``` shows some but not all of the content of a file; more of a preview than head.

### Complete the questions below when intrstructed. Push the changes to this document to recive credit for attending the lab

#### 1. What are 3 ways to change directories to your home directory from the  untrimmed_fastq directory?
1. ```cd ~``` Sends you  home from any directory.
2. ```cd $HOME``` Brings you home by opening a variable that is holding the address of the home directory.
3. ```cd ../../../``` Backstepping enough will bring you back to where you started.
4. ```cd home/users/cmb1451``` Brings me back to my directory. This adress can be found using ```pwd```.

#### 3b. How many programs in /bin 
2. Do each of the following tasks from your current directory using a single ls command for each:
    - List all of the files in /bin that start with the letter ‘c’.
    - List all of the files in /bin that contain the letter ‘a’.
    - List all of the files in /bin that end with the letter ‘o’.
    - Bonus: List all of the files in /bin that contain the letter ‘a’ or the letter ‘c’.

#### Answers here
- Start with the letter c __```ls c*```__
- Start with the letter a __```ls a*```__
- Start with the letter o __```ls o*```__
- Contain the letter ‘a’ or the letter ‘c’ ____

#### What command/commands would you use to find the line number in your history for the command that listed all the '.fastq' files using the absolute path. Paste your answer below.
