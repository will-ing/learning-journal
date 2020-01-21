# Git notes

[Git tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Git Overview

> **What is Git?** - Git is used for collaboration and store files in snapshots. Keeps snapshots of your coe at points in time.

* It keeps track of the history of your files.
* It records states of your files. With git e can view apply and remove the changes.
* Keeps all of your projuct files in one repository.

~*Without version control you have to rename the file and save it. This takes up more space.*~

> **Commits** - are a the changes made to each file. Equivalent of "save as". Each commit has a "HEAD". A head is equal to the meaning that you are hear. You can also give commits messages. The messages are like writing captions to your snapshot.

~*The efficiency of Git is that it can take snapshot. This uses less data. You can make changes in your first draft and it will effect your other layers.*~

> **Github** - is a centralized way for all developers to share code. Its online so your code is backed up.
* You can have lots of team members work togethre on the same files, without messing each other up.
* Keep a history of each file over tme.
* Work on code on your computer and sync it online

Statuses|Desc
---- | -----
Commmited| Data is securely stored in a local database
Modified| File has been changed but not committed to the database
Staged| File has been changed but not committed to the database

### Repositiories

> **Repositories** - A place of storage for your files that you told Git to pay attention to.
* Usually one project = one repository
* Really large projects mitht have multiple repos for different parts of their system
* Can live on Github or your computer.

Steps for creating projects
1. Using git clone
2. type "git clone **URL**" in terminal
3. mkdir crates a folder
4. touch creates files in folders

~*git will automatically give the name origin to the server you are cloning. It will name your local branch master*~

## Gitflow and ACP 

*acp = add, commit, push

Input in terminal| What it does
------- | -------
 git status| will tell you what is commited and what is not
1. git add "file"| will commit to and change green. It will start tracking
2. git commit -m "messatge"| save the changes and commit
3. git push origin master| send it to the master online. Your computer and Github are synced. sends snapshot to the cloud.
 git fetch| updates and lets you know if the repo has any changes
git fetch origin| to pull down any new changes that were pushed to the server since you cloned 
git pull origin master| to pull the changes from github to your computer. 
git diff origin master | Tell you the changes from the cloud to the computer. 
git remote rename old-name new-name| This changes the old name to the new one.
git remote rm filename| this will remove the file.
git commit --amend| when you make a mistake on a file or forgot to add some files. ~*if no changes were made since the newest commit*~
git reset HEAD filename| Unstage changes made to a file ~*"When git reset --hard" is used, Git overwrites all changes in the working directory, permanently destroying any uncommitted changes*~
git revert| To undo changes resulting from a particular commit
git checkout -- filename| To have a file return to its state when you last committed



> **Fetching** - Pulling datat that you don't have from a remote project.

> **Pushing** - to move your changes “upstream” for sharing. 

>


#### Life cycle of files

![Life cycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

Beginging Status| Change| New status
----- | -------- | -------
Untracked| Add the file| Unmodified
Unmodified| edit file| Modified 
Modifed| Stage file| Staged (git add "filename")
Staged| Commit file| Unmodified (git commit -m "Leave a mesaage")
Unmodified| Remove files| Untracked

~*check file statues with git status as you go throught*~



## Table of contents
[Learning Text Editor](https://will-ing.github.io/learning-journal/learn-text-editor)

[Learning Markdown](https://will-ing.github.io/learning-journal/learning-markdown)

[Main page](https://will-ing.github.io/learning-journal/)




