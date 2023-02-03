# Шпаргалка по Git
**Commands Git - Basic commands**

![Команды Git](https://avatars.githubusercontent.com/u/18133?s=200&v=4)

## Basic commands

1. Command "git init" - this "command init" create an emty repository

*Example 1*
![Example command "git init"](https://media.geeksforgeeks.org/wp-content/uploads/20220915184539/GitInit1.jpg)

2. Command "git add ." This command updates the index using the current content found in the working tree, to prepare the content staged for the next commit.

*Example 2*
![Example command "git add"](https://static.javatpoint.com/tutorial/git/images/git-add.png)

3. Command "git commit -m "any description text" This command represent a snapshot of the current stage/state of the project code. This allows the system to save changes in stages. Commits are used to track changes in a project over time and also help to highlight the main stages of a project.

*Example 3*
![Example command "git commit -m"text"](https://raw.githubusercontent.com/legend80s/commit-msg-linter/master/assets/demo-7-compressed.png)

4. Command "git checkout" This command is used to switch branches and check out their contents to the working directory.

*Example 4*
![Example command "git checkout"](https://static.javatpoint.com/tutorial/git/images/git-checkout.png)

5. Command "git diff" This command is used to calculate the difference between any two Git trees.

*Example 5*
![Example command "git diff"](https://media.geeksforgeeks.org/wp-content/uploads/20220217165701/Screenshot945.png)

Command "git status" This command shows the status of the files in the working directory and the index: which files have changed but not added to the index; which are pending commit in the index. In addition, hints are displayed on how to change the state of the files.

*Example 5*
![Example command "git status"](https://www.toolsqa.com/gallery/Git/1.Git%20Status%20Command%20in%20Git.png)

6. Command "git clean" This command is used to a convenient way to remove untracked files in a repository's working directory. Untracked files are files in the repository directory that have not yet been added to the indexed files section of the repository using the git add command.

*Example 6*
![Example command "git clean"](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSivHmKUY2kZKNanH7C4yfNvYV1EwIWRXSE6tTwJTfo&s)

## Another Git commands
Command | Description |

* git branch - This command list your branches, create new ones, delete and rename them.
* git merge - The git merge command is used to merge one or more branches into the current one. It then sets the current branch pointer to the resulting commit.
* git log - The git log command is used to view the history of commits, starting with the most recent and going back to the origins of the project. By default, it only shows the history of the current branch, but can be configured to show the history of other, even multiple branches at once. It can also be used to view the differences between branches at the commit level.
* git tag - The git tag command is used to set a permanent tag to a point in the history of a project. It is usually used for releases.
* git push - The git push command is used to establish a connection with a remote repository, calculate local changes that are not in it, and actually push them to the aforementioned repository. This command needs permission to write to the repository, so it uses authentication.
* git fetch - The git fetch command contacts the remote repository and fetches any changes you don't have yet and saves them locally.
* git archive - The git archive command is used to package specified commits or the entire repository into an archive.
* git show - The git show command displays an object in a simple and human-readable way. It is typically used to view information about a tag or commit.
* git bisect - The git bisect command is an extremely useful utility for finding the commit that first showed up a bug or issue using automatic binary search.

### Material taken from [link](https://proglib.io/p/git-cheatsheet)