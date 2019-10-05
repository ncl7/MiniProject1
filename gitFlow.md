GitFlow is a branching model for developers using Git that was created by Vincent Driessen. The GitFlow workflow separates what is in development from what is finished work by using branches. Developers work on a feature branch and merge it back into the master branch when the code is good and ready. Collaboration is much easier using this method and makes it easy to fix something in case of emergency, since it could be caught in development before being added to the finished product. An example of the workflow can be seen in Figure 1 below.

As seen in the figure below, development branches off of the master branch. Then, feature branches branch off of the develop branch. The features and fixes that are done will be merged back into the develop branch afterwards. Release branches are created off of the develop branches when the time is ready. Afterwards, the code is deployed, tested, fixed, redeployed, and retested until the desired product is reached. A more detailed example of the workflow after branches are merged can be seen in Figure 2 below.


![](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2019/06/155993572204-gitflow.png)
**Figure 1. GitFlow Branch Strategy from Sitepoint.com**


![](https://datasift.github.io/gitflow/GitFlowMasterBranch.png)
**Figure 2. GitFlow Workflow for Release from Datasift.github.io**
