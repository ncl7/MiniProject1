# LINUX COMMANDS CONTINUED

In this next section, we will be discussing:

1. The history command
2. The Linux home directory and ~
3. File paths in Linux
4. Using the tab key to complete file paths
5. Using up and down arrow for history

Refer to [LinuxCommandsIntro](https://github.com/Shannon-NJIT/MiniProject1/blob/master/LinuxCommands/LinuxCommandsIntro.md) for the previous section.


## HISTORY

The **history** command is used to show what was previously executed. This is helpful when the user wants to see a list of the commands that were completed and could help greatly with troubleshooting. There are numerous tags for the history command and shortcuts below:

“-c” clears the history list
“-a” adds history lines from the current session to the history file
“-n” reads all history lines that are not already read from the history file
“-r” reads history file and adds its contents to the history list
“-w” write the current history to the file and add them to the history list
“!string” executes the most recent command that begins with string
“!!” re-executes the most recently executed command

An example for history from the command line is seen below in Figure 1. As you can see, the list is inclusive.

![](/desktop/history.png)
**Figure 1. History from my command line after working on MiniProject1.**

--

## HOME DIRECTORY

The **home directory** is what serves as the user’s repository and is also known as the login directory. This is where the user stores files, directories, etc. For Linux, the home directory can be accessed using 

> “cd” or “cd ~” 

It is important for the user to check that they are in the home directory (or another desired working directory) before cloning repositories, otherwise the repository may end up in the wrong location. An example of a shortcut to get a picture from the Pictures folder in the home directory would be: 

> ~/Pictures/corgi.jpg 

The image in Figure 1 was created using the code below:  

> ![](/desktop/history.png)

--

## UP AND DOWN ARROW KEYS

Using the up and down arrow keys come in handy when recalling history. The up arrow key will recall the previous command that was entered. After hitting the up arrow key a few times to see previous commands, the user can use the down key to scroll back to the more recent entered commands. The up and down arrow keys are useful when the user makes a typo error since they could recall the command and edit instead of retyping the entire command. This is also useful if the user does not want to see the entire history list and wants a quick recollection of the last entered command. For example, Figure 2 below was the result of pressing the up arrow 5 times, recalling line 442 from the history.

![](/desktop/uparrow.png)
**Figure 2. Recalling history with the up arrow and saving time**

