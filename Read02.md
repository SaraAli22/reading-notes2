"**Git Tutorial: A Comprehensive Guide**
TABLE OF CONTENTS:
1. Introduction to Git
2. GETTING STARTED
3. SETTING UP A GIT REPOSITORY
4. WORKFLOW
5. REMOTE REPOSITORIES

**1.Introduction to Git**
-what is Git?
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
![Image](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

**2.GETTING STARTED**
-Download Git
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.
Git can be installed in three ways:
-Install as a package
-Install via another installer
-Download and compile the source code.

  **Mac**
You can download Git by visiting this link and following the posted directions:
(Link)[http://git-scm.com/download/mac]

   **Windows**
You can download Git by visiting this link and following the posted directions:
(Link)[http://git-scm.com/download/win]


**3.SETTING UP A GIT REPOSITORY**
Importing
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:
-Switch to the target project’s directory
Example:
$ cd test (cd = change directory)
Use the git init command
$ git init
*Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.*

-To start tracking these repository files, perform an initial commit by typing the following:
1. $ git add *.c
2. $ git add LICENSE
3. $ git commit -m “any message here”
*Now, your files are tracked and there’s an initial commit. We will discuss the particular commands in detail soon.*

** 4.WORKFLOW**
The local Git repository has three components:
![Image](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

-Saving Changes
1. Tracked
2. UnTracked

-The Life Cycle of File Status:
![Image](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

-Check File Status
To determine the state of files, utilize the git status command: $ git status

-Tracking and Staging a New File
1. Single File : git add filename
2. All Files :$ git add *

-Committing a File
$ git commit -m “made change x,y,z”

-Committing All Changes
$ git commit -a

-Pushing Changes
$ git push origin master

**5.Remote Repositories**
-Cloned Repositories
As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.


