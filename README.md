# GIT E GITHUB

Guide for beginners.

This README I've done watching this video: https://www.youtube.com/watch?v=2alg7MQ6_sI

I've followed/noted things presented in the video while doing them to learn how to use Git.

### Installation

https://git-scm.com/download

# SCENES

- To quit log, press "q"

- If you add a file to commit and change before commit, it doens't commit the changes after `add` 

- To see infos of all changes made (
    `git status`
)

- way to start git ( `git init` )

- Before commit it's needed to add the files to the commit (the point in the story of the project), it's like a space that you put the files you want to create a point in the story, the way to do that is using ( 
    `git add "file"`
    shorthand to add all files in folder
    `git add . `
)

- a way to check the commits made is by ( 
    `git log` 
)

- [x] Way to create points on the story of production of your project (
    `git commit -m "description of commit"` (-m == message I think)
)
- [x] Way to verify changes made into project ( 
    `git show`
)

- [x] Way to start a new functionality in the project without messing with what have been made 
( command 
    `git branch "name of the branch"`
- branch is a copy of the project and it's not the original, you don't change the original by changing the branch. 

Also to switch between main/master and branch, you can use 
    `git checkout "name of the branch"`

To check branches of your repository, you can use just 
    `git branch `
)

- To check files in repository/branches

    `ls -al` ('-al' adds more info to shown files)

- [x] Way to add news functionalities to your project in production (command 
    `git merge "branch's name of the branch you want to apply/merge to main/master repository"` (I think you need to be at the repository you want o merge the branch)
)

- [x] Way to delete a branch of the new functionality after applying it to your project. (command to delete a branch
    `git branch -D "branch name you want to delte"`
)

- [] Way to upload repository to cloud
    `git remote add origin "link of repository created in GitHub"`

To check remote repositories (
    `git remote -v`
)

To push/upload repository "master" to the one created in GitHub (
    `git push -u "name of repository"`
)