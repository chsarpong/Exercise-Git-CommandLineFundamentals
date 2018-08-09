# Exercise-Git-CommandLineFundamentals
+ Get Git installed(if you don't have), we will cover basic commands
+ Git is a Distributed version control system and not a Central version control system
+ Distributed Version control is safer (in terms of back ups) compared to Central version control system (no back ups)
+ After installing Git (if you have) -Open Git Bash - Type git --version
+ I have git version 2.18.0 windows.1 installed
+ Set CONFIG VALUES bacause it enables developers to identify each other when changes and merges occur
+ Type git config --global user.name "your name"
+ Type get config --global user.email "your email"
+ To check type get config --list 
+ NEED HELP type get help config or git config --help
+ Getting started (two common scenario) i. Existing project which i want to start tracking. ii Initialize a repository from existing code
+ iExample type ls, type cd Reponame, type ls - la. To track type git init, type ls - la. To stop tracking type git rm - rf .git, type ls - la, type git init, type ls - la.
+ iiExample type git status, type touch.gitignore. To add git ignore file; type .DS_store, type .project, type *.pyc. 
+ To check saved gitignore file, type git status
+ To add files to staging area, type git add .gitignore, type git status, type git add -A (to add to staging), type git status
+ To remove files  from staging area, type git reset calc.py, type git status, type git reset (to remove), type add -a
+ To clone a remote repo, type git clone <url> <where to clone> 
+ Video Link https://youtu.be/HVsySz-h9r4
+ Web Link to working exercise, go to setting - scroll down to GitHub pages  https://chsarpong.github.io/Exercise-Git-CommandLineFundamentals/
