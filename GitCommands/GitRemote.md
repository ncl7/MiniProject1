# Git Remote

In this section, I will introduce Git commands (**Remote Add/Show/Remove**) for working with remote repositories.

### Remote Add

There are a couple ways to retrieve a remote repository from its source location and add to your local directory. One way, **Git clone**. Git clone is different from [Fork](https://github.com/Shannon-NJIT/MiniProject1/blob/master/GitCommands/Fork.md), as it is an independent copy of a remote repository. This method allows a developer to work independently on their own copy without disturbing the master branch. A second way to add a repository is **Git remote add** < link to repository>. Both methods are helpful when collaborating within one repository. This is an advantage of using Git, version control.

The below image, highlights by using remote add/git clone you are copying a remote repository into your local directory.

![remoteadd](/images/images/GitCommands/gitclone.png)

### Remote Remove

If you want to remove a repository because you are not working on it, use **Git remote remove**. Git remote remove is a command to get rid of a remote repository. Keep in mind that once you remove a remote repository, all associated branches, files etc, will be deleted. To use this command, type *git remote remove* < name> in the command line.

### Remote Show

Because Git allows you to collaborate with others, it is important to learn how to manage other remote repositories. A remote repository is a repository located somewhere other than your local computer. To show which remote repository you can edit, use **Git remote**. This command will output a list of remotes being used to collaborate with others.

As shown, use git remote to output repositories you have access to.
![gitshow](/images/images/GitCommands/remoteshow.png)


**Learn more Git Commands and Terminology**
* [Git Push](https://github.com/Shannon-NJIT/MiniProject1/blob/master/GitCommands/GitPush.md)
* [Git Status](https://github.com/Shannon-NJIT/MiniProject1/blob/master/GitCommands/GitStatus.md)
