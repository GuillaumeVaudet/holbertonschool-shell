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
- [`0-iam_betty`](./0-iam_betty): Switches the current user to the user betty\
- [`1-who_am_i`](./1-who_am_i): Prints the effective username of the current user\
- [`2-groups`](./2-groups): Prints all the groups the current user is part of\
- [`3-new_owner`](./3-new_owner): Changes the owner of the file `hello` to the user betty\
- [`4-empty`](./4-empty): Creates an empty file called `hello`\
- [`5-execute`](./5-execute): Adds execute permission to the owner of the file `hello`\
- [`6-multiple_permissions`](./6-multiple_permissions): Adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`\
- [`7-everybody`](./7-everybody): Adds execution permission to the owner, the group and the other users, to the file `hello`\
- [`8-Jame_Bond`](./8-James_Bond): Sets the permission to the file `hello` as follow :\
    - Owner: no permission at all\
    - Group: no permission at all\
    - Other users: all the permissions\
- [`9-John_Doe`](./9-John_Doe): Sets the mode of the file `hello`to this:\
```bash
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```
- [`10-mirror_permissions`](./10-mirror_permissions): Sets the mode of the file `hello` the same as `olleh`'s mode\
- [`11-directories_permissions`](./11-directories_permissions): Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users\
- [`12-directory_permissions`](./12-directory_permissions): Creates a directory called `my_dir` with permissions 751 in the working directory\
- [`13-change_group`](./13-change_group): Changes the group owner to `school` for the `hello`\
- [`14-change_owner_and_group`](./14-change_owner_and_group): Changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory\
- [`15-symbolic_link_permissions`](./15-symbolic_link_permissions): Changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively :\
    - The file `_hello` is in the working directory
    - The file `_hello` is a symbolic link
- [`16-if_only`](./16-if_only): Changes the owner of the file `hello` to `vincent` only if it is owned by the user `guillaume`\

## Authors
- Vaudet Guillaume [github profile](https://github.com/GuillaumeVaudet)
