---
title:  "BNHR Internship | Getting Started with Git & Github"
mathjax: false
layout: post
categories: page
---


Installation on Windows

Open the [link](https://git-scm.com/download/win). The download should automatically begin, and you will arrive at the confirmation page shown. Execute the download exe file to begin the installation. 


![S1](https://user-images.githubusercontent.com/90082311/135712513-ce845d9d-2679-4b7e-ace3-79652b039e64.png)



Setting up Git

To set up Git, open Git Bash (for Windows systems) or the default console window (for Linux/MacOS or Windows systems that modified their PATH environment). In the command prompt, just tell Git your name and email address: 

$ git config --global user.name "danicaramirez"

$ git config --global user.email "danicadanissecondat.rmirez@bicol-u.edu.ph" 



To start a project, you should

•	Create the directory containing your project 

•	Navigate into the directory 

•	Initialize a Git repository 

Open Git Bash (from the Apps list or the contextual menu), and type in those commands: 

![s2](https://user-images.githubusercontent.com/90082311/135717639-b82d47cf-9ff7-4c20-a549-84cab86914e5.png)

mkdir is a command used to create a directory; it is short for “make directory.” cd is the command used to navigate between directories; it is short for “change directory.” Finally, git init is short for “Git initialize.” Git will create a directory called “.git” that will contain all your changesets and snapshots. If you want to check it out, you will have to show hidden files from your file explorer’s settings. Each file you work on is on the Working Directory or the empty area outside the “.git” 


![s3](https://user-images.githubusercontent.com/90082311/135717668-24821be3-e471-490e-aa81-88cf4cbd2d70.png)

Git will detect any new file you will place in the Working Directory. And you check the status of the directory by using the Git command “status.” 

![s4](https://user-images.githubusercontent.com/90082311/135717740-7efbf1b8-afde-4b7d-8012-416384184988.png)


If we create a new file called index.html in the Working Directory, we will see that Git will know that the project has changed. Then we get the untracked files. Those are the files we modified (in this instance, created). The Staging Area is where your files go before the snapshots are taken. 
To add a file to the Staging Area, we use the Git command “add.” 

![s5](https://user-images.githubusercontent.com/90082311/135717800-127dd1b5-a718-44d3-9647-3a8d42af6355.png)


You can unstage a file using the Git command “git rm” with the option “--cached.” 

![s6](https://user-images.githubusercontent.com/90082311/135717826-3d5ff509-d4de-40cf-8d96-484753bc6eb6.png)


A commit also contains information about the “author” of the content and the “commiter” or who put the changeset into the repository. 
To commit all the changes we made, we use “git commit.” This will take a snapshot of our current state of the project. 

![s7](https://user-images.githubusercontent.com/90082311/135717881-c7ed73c7-3cf0-4de9-991f-2e48509e8c9a.png)


If we execute this command, it will open our default editor and ask us for a commit message. A commit message is a short description of what has changed in the commit compared to the previous one. 

Checking logs and history 

The commit log will list (from the most recent to the oldest) all the snapshots you or other people committed. It also includes, for each commit 

•	The name (unique, obtained by hash) 

•	The author 

•	The date 

•	The description 

![s8](https://user-images.githubusercontent.com/90082311/135717908-1b8661d4-3968-46bd-89c5-65b2d196df5a.png)



To show and learn what changes have been done to your project, you just use the “git show” command followed by the name of the commit. 

![s9](https://user-images.githubusercontent.com/90082311/135717931-8fb96955-b80e-4a11-b2c8-91d32f57aacc.png)


Reviewing the current changes 
Checking differences between the last commit and the current working directory is an essential feature of Git. The command to check differences is 

$ git diff 















