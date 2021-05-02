**_Git_**

- is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit —
Git creates a snapshot of the file and stores a reference to it.

- it allows to continue work on a project even when not online or on a VPN by fetching history information from the server.
- Git makes it difficult for a snapshot of your file that is committed to be lost.
- Files in Git can reside in three main states: committed, modified and staged.

***After making sure Git has been installed, you should perform some customization steps:***
- git config: allows to set the user name and email address, which will be used for every Git commit.
- git config --list: To check settings
- git help command: to get more information on a particular command
- To import an existing project or directory into Git:  
1. $ cd test (cd = change directory)
2. $ git init
- To start tracking these repository files:

$ git add *.c


$ git add LICENSE


$ git commit -m “any message here”

- $ git clone https://github.com/test: create a copy of an existing Git repository from a particular server.
- $ git clone https://github.com/test mydirectory: To clone a repository into a directory with another name of your choosing

