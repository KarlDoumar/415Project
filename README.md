## 415Project
ECSE415 final project

---
# Shared resources

Please share useful links here (tutorials, code, similar projects, anything that can be useful):

[Resources doc](https://docs.google.com/document/d/1Nvzx0PymDpfRmiMvE4xAT1Px9sKov4FtiUlVOIAyJ2g/edit?usp=sharing)

---

# Git instructions:

**cloning** 

In the terminal/command line, navigate to the folder where you want to store the project files:

`git clone https://github.com/Aljulanda9/415Project.git`

**workflow**

`git pull` to update your local repository with the most recent changes

DO WORK

`git status` to see which files YOU changed

`git add CHANGED_FILES` or `git add .` to add all files (stage files to be committed)

`git commit -m'Descripe the changes/work you want to commit'`

`git push`

In case you edit a piece of code that someone else originally pushed, you might get a conflict which you would have to resolve. Git will ask which version of the code you want to keep (yours or the older one)

**force pull**

Use the following command to overwrite your local files with the files that are in the remote repository. You will lose whatever changes/code that you haven't pushed yet to the remote repository. So be careful.

`git fetch origin master`

`git reset —hard FETCH_HEAD`

`git clean -df`
