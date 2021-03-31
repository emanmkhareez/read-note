# Git-Intro
& eman
Git Intro
. Version control  is 
systems are software tools that help software teams manage changes to source code over time. 
. A Local VCS
 entails one database on your hard disk that stores changes to files.Centralized Version Control
Centralized Version Control
that enable programmer to share the file to collaborate with each other and his system entails a single server storing all changes and file versions,
A Distributed Version Control systems 
addresses the major vulnerability of the CVS the server as a single point of failure
this means if this server failure all member can not do work

Git
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
to download Git  on follow this instruction .


To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:
Switch to the target project’s directory
Example:

$ cd test (cd = change directory)
Use the git init command
$ git init
Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

To start tracking these repository files, perform an initial commit by typing the following:
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”
