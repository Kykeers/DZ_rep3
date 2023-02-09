# Git Manual #

## First start commands: ##

- **git version** - check the version of Git

- **git config --global user.name** - introduce yourself to Git

- **git config --global user.email** - add your email

## Start working in folder: ##

- *git init* - initializing the repository

- *git add file.name* - add untracked file to repository

- *git status* - check the status of git and fails

- *git commit -m "comment"* - create a commit with comment

## Work with commits: ##

- **git log** - output a list of commits

- **git checkout first.four.symbols.commit** - go to a specific commit

- **git checkout master** - go to an actual version of file

- **git diff** - shows the difference between last commit and unsaved changes

## Algorithm of actions: ##

1. git init
2. Create a file
3. git add file.name
4. Make changes in the file
5. Ctrl+S
6. git add file.name
7. git commit -m "comment"
8. git status (for checking fails)

***
## To work with remote repository

- git clone link_to_rep - to clone remote repository to your local computer

- git remote add origin link_to_rep - to connect your local repository with remote one

- git push -u origin - to first download your local repository to remote one

- git pull - to download changes in remote repository to your local one

