# Git Commands 

This table provides a list of common Git and GitHub commands along with brief descriptions of their functionalities. These commands are essential for **version control** and collaboration when working with Git repositories. Understanding and using these commands effectively can greatly enhance your productivity and workflow in **software development projects**.

![image](https://github.com/Adr4563/Workshop-Git-And-Github/assets/135796378/c40b3b9a-fd65-4a8c-9b41-a03f2266a5c0)

# List of Git and GitHub Commands

| Command | Description |
|---------|-------------|
| `git init` | Initializes a new local repository. This command creates a new Git repository in the specified directory by creating a .git subdirectory with the necessary files for Git to operate. |
| `git clone` | Clones a remote repository into a local directory. This command creates a copy of an existing Git repository, including all branches and commit history, into a new directory on your local machine. |
| `git add <file>`| Adds file changes to the staging area. This command adds modifications made to one or more specified files to the staging area, preparing them to be included in the next commit. |
| `git diff` | Shows the differences between the working directory and the staging area. This command displays the differences between the changes in the working directory and the files currently staged for commit. |
| `git commit -m "message"` | Commits changes to the repository with a message. This command records changes to the repository along with a descriptive message explaining the changes made in the commit. |
| `git status` | Shows the status of files in the repository. This command displays the current state of the working directory and staging area, including any modifications, additions, or deletions not yet committed. |
| `git branch` | Lists all branches in the repository. This command lists all local branches in the repository, indicating the current branch and highlighting branches that have been checked out. |
| `git checkout <branch>` | Switches to the specified branch. This command updates the working directory to reflect the specified branch, allowing you to navigate between different branches in the repository. |
| `git merge <branch>` | Merges changes from the specified branch into the current branch. This command integrates changes from the specified branch into the current branch, combining the commit histories and resolving any conflicts. |
| `git pull` | Fetches changes from a remote repository and merges them. This command retrieves new changes from the remote repository, updating the local repository with the latest commits and automatically merging them into the current branch. |
| `git push` | Pushes local changes to the remote repository. This command uploads local commits to the remote repository, updating the remote branch with any changes made locally. |
| `git rm <file>` | Removes files from the staging area and the repository. This command removes the specified file(s) from both the working directory and the staging area, and also stages the removal for commit. |
| `git log` | Displays the commit history. This command shows a chronological list of commits in the repository, including details such as commit hashes, authors, dates, and commit messages. |
| `git reset --hard HEAD` | Resets the current branch to the last commit. This command resets the current branch to the specified commit, discarding all changes made after that commit and reverting the working directory to match the state of the specified commit. |
| `git revert <commit>` | Reverts a commit by creating a new commit. This command undoes the changes introduced by the specified commit, creating a new commit that reflects the inverse of the specified commit's changes. |
| `git fetch` | Fetches changes from a remote repository. This command retrieves new commits and updates branch references from the remote repository, without automatically merging them into the local repository. |
| `git remote add origin <repository_url>` | Sets the remote repository for the project. This command adds a new remote repository with the specified name and URL to the local repository, allowing you to push and pull changes to and from the remote repository. |



