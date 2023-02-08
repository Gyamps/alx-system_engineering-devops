<u>## Mandatory Tasks</u>
### 0x00-shell_basics
> Prints out the absolute path name of the current working directory

### 1-listit
> Displays content list of current directory

### 2-bring_me_home
> Changes working directory to home directory

### 3-listfiles
> Displays current dir contents in long format

### 4-listmorefiles
> Displays current dir contents, including hidden files in long format

### 5-listfilesdigitonly
> Displays current directory contents in:
* Long format
* with user and group IDS displayed numerically
* and hidden files

### 6-firstdirectory
> Creates a directory named _my\_first\_directory_ in the _/tmp/_ directory

### 7-movethatfile
> Move file _betty_ from _/tmp/_ to _/tmp/my\_first\_directory_

### 8-firstdelete
> Delete the file _betty_

### 9-firstdirdeletion
> Delete dir _my\_first\_directory_ in /tmp/ dir

### 10-back
> Changes the working directory to previous one

### 11-lists
> List all files (including hidden ones) in current dir and the parent of the working dir and the _/boot/_ dir ( in this order), in long format

### 12-file_type
> Print the type of file named _iamafile_

### 13-symbolic_link
> Creates a symbolic link to _/bin/ls_, named _\_\_ls\_\__

### 14-copy_html
> Copies all HTML files from current working dir to parent of working dir, but only copies files that did not exist in paretn of working dir or were newer versions in the parent of working dir


<u>## Optional Tasks</u>
### 100-lets_move
> Moves all files beginning with an uppercase letter to the dir _/tmp/u_

### 101-clean_emacs
> Delete all files in current dir that end with the character _~_

### 102-tree
> Creates the dirs _welcome/_, _welcome/to/_ and _welcome/to/school_

### 103-commas
> Lists all files and dirs of the current dir, separated by commas(`,`).
* Directory names should end with a slash (`/`)
* Files and directories starting with a dot (`.`) should be listed
* The listing should be alpha ordered, except for the directories `.` and `..` which should be listed at the very beginning
* Only digits and letters are used to sort; Digits should come first
* You can assume that all the files we will test with will have at least one letter or one digit
* The listing should end with a new line

