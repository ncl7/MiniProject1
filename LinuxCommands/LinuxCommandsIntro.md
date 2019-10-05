
# Introduction to Linux Commands

Here is a list of six Linux commands to be introduced:

1. pwd
1. cd
1. mkdir
1. cp
1. mv
1. rm

**Print working directory (*pwd*)** - Use it to output your current working directory path. It alerts where you are currently working within the file hierarchy.It is beneficial because sometimes a user can forget where he/she is working.

> Type pwd on the command line
![pwd](/images/images/LinuxCommands/pwd.png)

**Change directory (*cd*)** - Consider your files like a hierarchy. Navigate around your hierarchy using cd command. It is used to direct a user into a directory where he/she wants to work in, also called a working directory. 

> To go forward in a path, type cd  < destination >
> To go backwards in your hierarchy type cd ..  
![cd](/images/images/LinuxCommands/cd.png)

**Make directory (*mkdir*)** - Create a new directory within your current working directory with mkdir. Mkdir helps keep your work organized by storing similar files/directories in one place. It works by using the mkdir command followed by a name of the directory you want to create.

> Notice once a directory is created, it is highlighted (see example)
![mkdir](/images/images/LinuxCommands/mkdir.png)

**Copy (*cp*)** - Use the cp command to copy content of one file into another. It is similar to ‘copy and paste’. Instead of retyping content that is in one file, can ‘copy and paste’ content from one destination to another with one command.

![cpboth](/images/images/LinuxCommands/cpboth.png)

> *Used cp to copy all content within ‘travel.txt’ into culture.txt’*

![cpculture](/images/images/LinuxCommands/cpculture.png)

> *As a result, culture.txt has the same content as travel.txt*

**Move (*mv*)** - The mv command is used to move from one location to another and rename files or directories. The difference between mv and cp is cp copies content from one source file into another (copy and paste). The mv command moves a file, in its entirety, to a different location. For developers, this is great to ‘lift and shift’ files and directories from one folder into another.

> As seen in the example below, mv was used to relocate berlin.txt into *cities* directory.
![mv2](/images/images/LinuxCommands/mv2.png)

> *Note directories are highlighted in a different color than files (cities and berlin.txt)*

**mv is also used to rename a file**
> As shown, mv was used to rename berlin.txt into munich.txt
![mv3](/images/images/LinuxCommands/mv3.png)

**Remove (*rm*)** - When a user wants to remove a file or directory, use rm command. Keep in mind, once you remove either a file or directory, it is gone for good. It is useful when a folder has unnecessary files/directories that can be removed. Now the developer can focus on only important files/directories.

> The example illustrates using rm to remove music.txt
![rm2](/images/images/LinuxCommands/rm2.png)
> *Helpful hint: use rm –r to remove a directory*
![rm3](/images/images/LinuxCommands/rm3.png)



**Learn more Linux Commands**
* [Linux Commands 2](https://github.com/Shannon-NJIT/MiniProject1/blob/master/LinuxCommands/LinuxCommands2.md)
