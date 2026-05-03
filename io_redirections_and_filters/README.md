# holbertonschool-shell

This repository contains a collection of Bash scripts created as part of the Holberton School curriculum. This project covers the fundamentals of shell usage including file permissions and working with basic shell commands.

## Requirements
- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 22.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly #!/bin/bash
- A README.md file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use backticks, &&, || or ;
- All your files must be executable

## Usage
If you want to test all script you have to just add a `./` before the name of the script without space.
Example:
```bash
julien@ubuntu:/tmp/h$ ./0-hello_world
Hello, World
julien@ubuntu:/tmp/h$ ./0-hello_world | cat -e
Hello, World$
julien@ubuntu:/tmp/h$
```

## Scripts Descriptions
- [`0-hello_world`](./0-hello_world): Prints "Hello, World", followed by a new line
- [`1-confused_smiley`](./1-confused_smiley): Displays a confused smiley `"(Ôo)'`
- [`2-hellofile`](./2-hellofile): Displays the content of the `/etc/passwd`
- [`3-twofiles`](./3-twofiles): Displays the content of `/etc/passwd` and `/etc/hosts`
- [`4-lastlines`](./4-lastlines): Displays the last 10 lines of `/etc/passwd`
- [`5-firstlines`](./5-firstlines): Displays the first 10 lines of `/etc/passwd`
- [`6-third_line`](./6-third_line): Displays the third line of the file `iacta`. The file `iacta` will be in the working directory
- [`7-file`](./7-file): Creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` contaning the text `Best School` ending by a new line
- [`8-cwd_state`](./8-cwd_state): Writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `is_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, it should be create.
- [`9-duplicate_last_line`](./9-duplicate_last_line): Duplicates the last line of the file `iacta`
- [`10-no_more_js`](./10-no_more_js): Deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders
- [`11-directories`](./11-directories): Counts the number of directories and sub-directories in the current directory
- [`12-newest_files`](./12-newest_files): Displays the 10 newest files in the current directory
- [`13-unique`](./13-unique): Takes a list of words as input and prints only words that appear axactly once
    - Input format: One line, one word
    - Output format: One line, one word
    - Words should be sorted
- [`14-findthatword`](./14-findthatword): Displays lines containing the pattern "root" from the file `/etc/passwd`
- [`15-countthatword`](./15-countthatword): Dsiplays the number of lines that contain the pattern "bin" in the file `/etc/passwd`
- [`16-whatsnext`](./16-whatsnext): Displays lines contain the pattern "root" and 3 lines after them in the file `/etc/passwd`
- [`17-hidethisword`](./17-hidethisword): Dsiplays all the lines in the file `/etc/passwd` that do not contain the pattern "bin"
- [`18-letteronly`](./18-letteronly): Dsiplays all lines of the file `/etc/ssh/sshd_config` starting with a letter
- [`19-AZ`](./19-AZ): Replaces all characters `A` and `c` from input to `z` and `e` respectively
- [`20-hiago`](./20-hiago): Removes all letters `c` and `C` from input
- [`21-reverse`](./21-reverse): Reverse its input
- [`22-users_and_homes`](./22-users_and_homes): Displays all users and their home directories, sorted by users
    - Based on the `/etc/passwd`
- [`23-empty_casks`](./23-empty_casks): Finds all empty files and directories in the current directory and all sub-directories.
- [`24-gifs`](./24-gifs): Lists all the files with a `.gif` extension in the current directory and all its sub-directories (in progress)

## Authors
- Vaudet Guillaume [github profile](https://github.com/GuillaumeVaudet)
