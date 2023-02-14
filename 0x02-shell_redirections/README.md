Directory on basic shell redirections and piping.

## <u>Mandatory Tasks</u>
### 0-hello_world
> Prints "Hello, World", followed by a new line to the standard output

### 1-confused_smiley
> Displays a confused smiley

### 2-hellofile
> Displays content of the `/etc/passwd` file

### 3-twofiles
> Display content of `/etc/passwd/` and `/etc/hosts/`

### 4-lastlines
> Display the last 10 lines of `/etc/passwd`

### 5-firstlines
> Display first 10 lines of `/etc/passwd`

### 6-third_line
> Displays the third line of the file `iacta`

### 7-file
> Creates a file names exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line

### 8-cwd_state
> Result of command `ls -la` is written into the file `ls_cwd_content`. If the file exists, it should beoverwritten. If it does not exist, it should be created.

### 9-duplicate_last_line
> Script that duplicates the last line of the file `iacta`

### 10-no_more_js
> Script delete all regular files (directories excluded) with a `.js` extension that are present in the current directory and all its subfolders

### 11-directories
> Script counts number of firectories and sub-directories in current dir.
* Current and Parent directories are not taken into account
* Hidden directories are counted

### 12-newest_files
> Script displays 10 newest files in the current directory
Requirements:
* One file per line
* Sorted from the newest to the oldest

### 13-unique
> Takes list of words as input and prints only words that appear exactly once.
* Input format: One line, one word
* Output format: One line, one word
* Words should be sorted

### 14-findthatword
> Display lines containing the pattern 'root' from the file `/etc/passwd`

### 15-countthatword
> Display the number of lines that contain the pattern 'bin' in the file `/etc/passwd`

### 16-whatsnext
> Display lines containing the pattern 'root' and 3 lines after them in the file `/etc/passwd`

### 17-hidethisword
> Display all the lines in the file `/etc/passwd` that do not contain the pattern 'bin'

### 18-letteronly
> Display all th elines of the file `/etc/shh/shhd_config` starting with a letter.
* Inlcude capital letters as well

### 19-AZ
> Replaces all characters `A` and `c` from input to `Z` and `e` respectively

### 20-hiago
> Removes all letters `c` and `C` from input

### 21-reverse
> Script to reverse input

### 22-users_and_homes
> Displays all users and their home directories, sorted by users

### 100-empty_casks
> Finds all empty files and directories in the current directory and all sub-directories
* Only the names of the files and directories should be displayed (not the entire path)
* Hidden files should be listed
* One file name per line
* The listing should end with a new line
* You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`

### 101-gifs
> List all files with a `.gif` extension in the current directory and all its sub-directories.
* Hidden files should be listed
* Only regular files (not directories) should be listed
* The names of the files should be displayed without their extensions
* The files should be sorted by byte values, but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after file `jay`)
* One file name per line
* The listing should end with a new line
* You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`

### 102-acrostic
> Script decodes acrostics that use the first letter of each line.
* Decoded message has to end with a new line

