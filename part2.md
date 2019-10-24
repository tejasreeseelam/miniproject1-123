## What is GitFlow?
It's a branching model for Git. It acts as a wrapper around Git. It's an extension of the default git init cmman and doesnt change anyhting in your repository other than creating branches for you.
### **GitFlow Workflow**
GitFlow is an abstract idea of Git workflow. It uses two branches to record the history of the project
instead of just one. The master and Develop branch.
1. Master Branch:
Stores the official release history of the project
2. Develop Branch:
Serves as an integration branch for features.
	* The “release branch” is made off of develop.
**Steps on how to use GitFlow Workflow**
* The first step is to complement the default master with a develop branch by creating an empty develop branch locally and push it to the server.
* This Branch will contain the complete history of the project and other developers can clone the central repository to go ahead an dcommit text into it.
        a. Any new developments are built through the "feature" branch. Any additions or new input is a
ccepted to be termed as a "feature".
        b. Any form of a fix or change of the input already in the repository is termed as a "Fix".
**The only commits to master branch are the merges from release branches and fix branches.**
