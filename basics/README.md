# holbertonschool-shell

This repository contains a collection of Bash scripts created as part of the Holberton School curriculum. This project covers the fundamentals of shell usage including filesystem navigation, file manipulation and working with basic shell commands.

## Requirements
- Allowed editors: `vi`, `vim`and `emacs`
- All scripts will be tested on Ubuntu 22.04 LTS
- All scripts should be exactly two lines long (`$ wc -l file` should print 2)
- The first line of all files should be exactly `#!/bin/bash`
- `||`, `&&`, `;` or backticks are not allowed
- All files must be executable

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

## Scripts descriptions :
- `0-current_working_directory`: prints the absolute path name of the current working directory
- `1-listit`: display the contents list of your current directory
- `2-bring_me_home`: change the working directory to the user's home directory
- `3-listfiles`: display current directory contents in a long format
- `4-listmorefiles`: display current directory contents, including hidden files
- `5-listfilesdigitonly`: display current directory contents as long format, with user and group IDs displayed numerically and hidden files
- `6-first-directory`: create a directory named 'my_first_directory' in the /tmp directory
- `7-movethatfile`: move the file betty fro /tmp to /tmp/my_first_directory
- `8-firstdelete`: delete the file betty into the tmp/my_first_directory
- `9-firstdirdeletion`: delete the directory my_first_directory that in the /tmp directory
- `10-back`: change the working directory to the previous one
- `11-lists`: list all files in the current directory and the parent of the working directory and the /boot
- `12-file_type`: print the type of the file named iamafile
- `13-symbolic_link`: create a symbolic link to /bin/ls named __ls__
- `14-copy_html`: copy all the html in the current directory to the parent directory
- `15-lets_move`: move all files begining with an uppercase lettre to the directory /tmp/u
- `16-clean_emacs`: delete all files in the current working directory that ends with ~
- `17-tree`: create the directories welcome/ welcome/to/ welcome/to/school in the current directory

## Authors
- Vaudet Guillaume [github profile](https://github.com/GuillaumeVaudet)