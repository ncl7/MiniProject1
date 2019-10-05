# Git Remote

In this section, I will introduce Git Commands(**Remote Add/Show/Remove**) for working with remote repositories

### Remote Add

There are a couple ways to retrieve a remote repository from its source location and add to your local directory. One way is to use **git clone**. Git clone is an independent copy of a remote repository and different from forking. By using git clone, it adds a remote repository into your local working directory. This method allows for you to work independently on your own copy without disturbing the master branch. The second way to add a repository is to use git remote add <link to repository> url. Both methods are helpful when working in groups within the same repository. This is an advantage of using Git, version control.

![remoteadd](/images/images/GitCommands/gitclone.png)

### Remote Remove

If you want to remove a repository because you are not working on it or for some other reason, use git remote remove. You can use the git remove by doing the following to get rid of a remote repository. Keep in mind,that once you remove a remote repository, all associated branches, files etc, will be deleted.

### Remote Show

Because Git allows you to collaborate with others, it is important to learn how to manage other remote repositories. A remote repository is a repository located somewhere other than your local computer. To show which remote repository you can edit, use git remote. This command will output a list of remotes being used to collaborate with others.

![gitshow](/images/images/GitCommands/remoteshow.png)


**Learn more Git Commands**
* [Git Push](https://github.com/Shannon-NJIT/MiniProject1/blob/master/GitCommands/GitPush.md)
* [Git Status](https://github.com/Shannon-NJIT/MiniProject1/blob/master/GitCommands/GitStatus.md)
