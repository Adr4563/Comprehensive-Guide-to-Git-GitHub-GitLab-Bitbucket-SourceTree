# Guide of Git Commands
<details>
  <summary>Click👆</summary>
  <pre>
  <img src="https://github.com/Adr4563/Workshop-Git-And-Github/assets/135796378/8d0dfc67-c34f-4a76-92e2-b360ff05e884" width="700" height="600"/>
  </pre>
</details>

### Clone the Repositorie from Github repository
```
# Initialize a new Git repository in your local directory (optional)
git init

# Clone the repository from GitHub to your local machine
git clone 'link-repository-github'
```
### Update changes from Repositorie Github to Repositorie Local

```
# Merge changes from a specified branch into your current branch
git merge branch-name

# Push the changes to the remote repository
git push
```

### Update changes from Local Github to Repositorie Local

```
# This command shows which files are staged, unstaged, or untracked
git status

# This command prepares the changes in the specified files for commit
git add 'file name'

# This command records the changes made to the files in the local repository with a commit message
git commit -m "Update the file README.md"

git push
```

### Management of development lines "BRANCH"
```
# Create and switch to a new branch
git checkout -b branch-name

# Switch to an existing branch
git checkout branch-name

# List all branches
git branch

# Merge a branch into the current branch
git merge branch-name
```

### Restore 
```
# Discard changes in a specific file
git checkout -- file-name

# Discard all uncommitted changes
git reset --hard
```

### Delete files from Git to Github repository

```
# This command shows which files are staged, unstaged, or untracked
git status

# This command stages the removal of the file and deletes it from the working directory
git rm 'file name'

# This command stages the removal of the directory and all its contents
git rm -r directory-name

# This command records the deletion of the file(s) in the local repository with a commit message
git commit -m 'Delete file name'

git push
```
