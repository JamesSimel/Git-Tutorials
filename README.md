# GIT COMMANDS
1. git clone

This command is always written with an option of the URL where you host you project e.g., from Github.

```git clone https://github.com/JamesSimel/Git-Tutorials.git```

git clones copies the repository files from a remote place to you local machine where you can access it.

2. git status

Displays the state of the working directory and the staging area.

It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.


3. git branch

Has some uses:
- checks which branch you are in.
- when passed with another switch/ or option like ``git branch new-branch``, it will create a new branch called the **new-branch**.
4. git checkout -b <branch name>

```git checkout -b <branch name>```
The command above creates a new branch and also checkout to the new branch.
When you ommit the *-b* flag, you will be change or switching branches. e.g., changing from main branch to new branch.
5. git switch

Changes from one branch to another.

6. git push
Publishes all the changes made locally to  the remote repository, by staging all the changes! :).
7. git pull

Downloads all the changes made to the parent repo that is available remotely to the local repo if there are any changes. If there are any conficts, it will try to automerge and if they are automergable, the maintainer or person pulling has to figure this out.
8. git rebase

9. git branch --delete <branch name>
This deletes branches availabale localy.

10. git add 

This command stages(makes the changes ready) the changes made to a local repository.
It accepts names of the files changed e.g.,
```git add index.js ``` or ```git add index.html index.js``` or so on.
If you need to stage all the changes you just add a period **.** as below:
```git add . ```
We can also add a path:
```git add views/components/App.js```

11. git commit

This command declares to git that we are making this changes by writing a message of **what we are committing** and **why we are committing** for others to understand.
We can write a message right after the commit word by adding a flag **-m** and we add as many as we want. Example:
```git commit -m "First message" -m "Second Mesaage..."```

12. git log

Outputs the information regarding the comiited project history or committed snapshots. It lists the projects history, filter it, and search for specific changes.

13. git tag
Tags are ref's that point to specific points in Git history.
```git tag``` is generally used to capture a point in history that is used for a marked version release (i.e. v1.0.1).

14. git blame
when given a file e.g., ``` git blame Reame.MD ```
It will display the Metadata of the file attache to specific committed lines. 

It is used to explore the history of specific code, and answer questions about what, how, and why the code was added to the repo.


Thanks for reading!

Let us Hack!