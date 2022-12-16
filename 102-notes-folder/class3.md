
# notes: Git Tutorial: A Comprehensive Guide

Git is a distributed version control system: tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows. 
Git is very helpful for coordinating work among programmers. It keeps track of all the changes that have been made to the files, so everyone can see what has been changed and when.
Git is a distributed version control system that helps programmers keep track of changes to files. Git is a great way to keep track of changes to files, especially during software development.

 ## Local Version Control
1. A Local Version Control System (LVCS) is a system where changes to files are kept on a single computer.

2. A Local VCS is useful if you want to work on the same project with several people and don't want to worry about losing track of changes.

# what is Git?

*Snapshots*

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

*Local Operations*

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

*Tracking Changes*

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

*Loss of Data*

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

*States*

Files in Git can reside in three main states: committed, modified and staged.

*Committed*

Data is securely stored in a local database

*Modified*

File has been changed but not committed to the database

# Check Settings
To check settings, use the git config --list command.

Example:

$ git config --list

user.name=Jane Smith

user.email=example@email.com

color.status=auto

color.branch=auto

color.interactive=auto

## *Cloning*

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

$ git clone https://github.com/test
By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

$ git clone https://github.com/test mydirectory
The command above makes a copy of the target repository in a directory named “mydirectory.”

Check File Status
To determine the state of files, utilize the git status command:

$ git status
On branch master

nothing to commit, working directory clean

*This information indicates which branch you’re on (we will cover branches in a later section) and states “working directory clean,” which means that files have tracked or modified status at the moment. Also, no untracked files are present because Git has not listed any.

Committing All Changes
$ git commit -a
*This command commits a snapshot of all modifications to tracked files in the working directory.
What i'd like to know more about. 
1. Become more used to using Git
Practice iTerm more to become better at it. 
Git merging, fetching, list branches, unstaging files, commit mistakes. renaming/ removing remotes, 

Source: https://blog.udemy.com/git-tutorial-a-comprehensive-guide/

https://github.com/JaseadamsDev