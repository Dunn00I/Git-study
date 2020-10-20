# GIT E GITHUB

This is a repository of my study involving Git.

This README I've done watching this video: https://www.youtube.com/watch?v=2alg7MQ6_sI

I've followed/noted things presented in the video while doing them to learn how to use Git.

### Installation

https://git-scm.com/download

# Commands

- To quit log, press "q"

- If you add a file to commit and change before commit, it doens't commit the changes after `add` 

- To see infos of changes made before commit (  
    `git status`  
)

- Way to start git ( `git init` )

- Before commit it's needed to add the files to the commit (the point in the timeline of the project), it's like a space that you put the files you want to create a point in the timeline, the way to do that is using (  
    `git add "file"`  
    shorthand to add all files in folder  
    `git add . `  
)

- Way to check the commits made is by (  
    `git log`  
)

- `git commit` (

    Way to create points on the timeline of production of your project  
        `git commit -m "commit description"` (-m == message I think)

    To commit and at the same time add files with commit meassage  
        `git commit -am "commit description"`
        
)

- Way to verify changes made into project (  
    `git show`  
)

- `git branch` (

    Way to start a new functionality in the project without messing with what have been made  
        `git branch "name of the branch"`  
    branch is a copy of the project and it's not the original, you don't change the original by changing the branch.

    To check branches of your repository, you can use just  
        `git branch `  

    Way to delete a branch of the new functionality after applying it to your project. command to delete a branch  
        `git branch -D "branch name you want to delte"`

)

- `git checkout` (

    To switch between main/master and branch, you can use  
        `git checkout "name of the branch"`
    

    To create and go to the branch created at the same time  
        `git checkout -b "branch name"`
    

    To recover a deleted file hile you haven't commited yet  
        `git checkout -- "file name"`  
        (-- == last point commited)  
    

    To get a file from another commit and apply it, changing the present file for the one applied at the same time  
        `git checkout "commit id" -- "file name"`

)

- To check files in repository/branches

    `ls -al` ('-al' adds more info to shown files)

- Way to add news functionalities to your project in production (  
    `git merge "branch's name of the branch you want to apply/merge to main/master repository"` (I think you need to be at the repository you want o merge the branch)  
)

- `git remote` (

    Way to upload repository to cloud  
        `git remote add origin "link of repository created in GitHub"`

    To check remote repositories  
        `git remote -v`

)

- `git push` (

    To push/upload repository "master" to the one created in GitHub  
        `git push -u "name of repository"`
    

    To send alterations to remote repository  
        `git push`

)

- To get a repository from GitHub (  
    `git clone "link of repository"`  
)

- To get alterations from remote repository (  
    `git pull`  
)