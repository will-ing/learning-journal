# Git notes

[Git tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

**What is Git?** - Git is used for collaboration and store files in snapshots. Keeps snapshots of your coe at points in time.

* It keeps track of the history of your files.
* It records states of your files. With git e can view apply and remove the changes.
* Keeps all of your projuct files in one repository.

Without version control you have to rename the file and save it.

**Commits** - are a the changes made to each file. Equivalent of "save as". Each commit has a "HEAD". A head is equal to the meaning that you are hear. You can also give commits messages. The messages are like writing captions to your snapshot.


*The efficiency of Git is that it can take snapshot. This uses less data. You can make changes in your first draft and it will effect your other layers.*

**Github** - is a centralized way for all developers to share code. Its online so your code is backed up.
* You can have lots of team members work togethre on the same files, without messing each other up.
* Keep a history of each file over tme.
* Work on code on your computer and sync it online

Statuses|Desc
---- | -----
Commmited| Data is securely stored in a local database
Modified| File has been changed but not committed to the database
Staged| File has been changed but not committed to the database

**Repositories** - A place of storage for your files that you told Git to pay attention to.
* Usually one project = one repository
* Really large projects mitht have multiple repos for different parts of their system
* Can live on Github or your computer.

Steps for projects
1. Using git clone
2. type git clone URL in terminal
3. mkdir crates a folder
4. touch creates files in folders

**gitflow:acp** - add, commit, push.|descripion
------- | -------
 git status| will tell you what is commited and what is not
1. git add "file"| will commit to and change green. It will start tracking
2. git commit -m "messatge"| save the changes and commit
3. git push origin master| send it to the master online. Your computer and Github are synced. sends snapshot to the cloud.
 git fetch| updates and lets you know if the repo has any changes
git pull origin master| to pull the changes from github to your computer. 
git diff origin master | Tell you the changes from the cloud to the computer. 

## table of contents
[Learning Text Editor](https://will-ing.github.io/learning-journal/learn-text-editor)

[Learning Markdown](https://will-ing.github.io/learning-journal/learning-markdown)

[Main page](https://will-ing.github.io/learning-journal/)




