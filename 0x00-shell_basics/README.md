## <u>Mandatory Tasks</u>
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
> Creates a directory named `my_first_directory` in the `/tmp/` directory

### 7-movethatfile
> Move file _betty_ from `/tmp/` to `/tmp/my_first_directory`

### 8-firstdelete
> Delete the file `betty`

### 9-firstdirdeletion
> Delete dir `my_first_directory` in `/tmp/` dir

### 10-back
> Changes the working directory to previous one

### 11-lists
> List all files (including hidden ones) in current dir and the parent of the working dir and the `/boot/` dir ( in this order), in long format

### 12-file_type
> Print the type of file named `iamafile`

### 13-symbolic_link
> Creates a symbolic link to `/bin/ls`, named `__ls__`

### 14-copy_html
> Copies all HTML files from current working dir to parent of working dir, but only copies files that did not exist in parent of working dir or were newer versions in the parent of working dir


## <u>Optional Tasks</u>
### 100-lets_move
> Moves all files beginning with an uppercase letter to the dir `/tmp/u`

### 101-clean_emacs
> Delete all files in current dir that end with the character `~`

### 102-tree
> Creates the dirs `welcome/`, `welcome/to/` and `welcome/to/school`

### 103-commas
> Lists all files and dirs of the current dir, separated by commas(`,`).
* Directory names should end with a slash (`/`)
* Files and directories starting with a dot (`.`) should be listed
* The listing should be alpha ordered, except for the directories `.` and `..` which should be listed at the very beginning
* Only digits and letters are used to sort; Digits should come first
* You can assume that all the files we will test with will have at least one letter or one digit
* The listing should end with a new line

### school.mgc
> Create a magic file `school.mgc` that can be used with the command `file` to detect `School` data files.

