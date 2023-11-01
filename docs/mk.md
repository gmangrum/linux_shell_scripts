# mk
Learn how to use the `mk` command

--------------------
## The Basics
`-f`: creates a file [Link](https://github.com/gmangrum/linux_shell_scripts/blob/main/docs/mk.md#-f-option)

`-d`: creates a directory [Link](https://github.com/gmangrum/linux_shell_scripts/blob/main/docs/mk.md#-d-option)

`-c`: creates a shell script [Link](https://github.com/gmangrum/linux_shell_scripts/blob/main/docs/mk.md#-c-option)

## -f option
You can create a file with the `-f` option.

*Syntax*: `mk -f filename.txt`

*Description*: Creates an empty file in your working directory.

*Notes*: You can also use the `-f` option without specifying the option, simply write `mk filename.txt`.
Finally, you can specify a directory by doing `mk -f /path/filename.txt` or `mk -f ~/path/filename.txt`.
## -d option
You can create a directory with the `-d` option.

*Syntax*: `mk -d folder`

*Description*: Creates an empty directory inside your working directory.

*Notes*: Like with the `-f` option, you can specify the file path.

## -c option
You can create a shell script file in your working directory.

*Syntax*: `mk -c 755 command`

*Description*: Creates and sets permissions for a shell script file.

*Notes*: After command, navigate to the file and edit it. There will be a line that says `#!/bin/bash/` at the beggining.
Please do not remove it. If yu are inside a priviliged directory, run the command and it should work.
