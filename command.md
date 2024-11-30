# Git Commands Reference

## Initializing a Repository
- Initialize a new Git repository:
  `git init`

## Checking the Status
- Check the status of the repository:
  `git status`

## Adding Files to Staging Area
- Add a single file to the staging area:
  `git add <filename>`
- Add all files in the current directory to the staging area:
  `git add .`

## Committing Changes
- Commit staged changes with a message:
  `git commit -m "Your commit message"`

## Viewing Commit History
- Show the commit history:
  `git log`

## Creating and Switching Branches
- Create a new branch:
  `git branch <branch-name>`
- Switch to a specific branch:
  `git checkout <branch-name>`
- Create and switch to a new branch:
  `git checkout -b <branch-name>`

## Merging Branches
- Merge another branch into the current branch:
  `git merge <branch-name>`

## Pushing Changes
- Push changes to the remote repository:
  `git push origin <branch-name>`
- Set upstream for a branch and push changes:
  `git push -u origin <branch-name>`

## Pulling Changes
- Pull changes from the remote repository:
  `git pull origin <branch-name>`

## Remote Repository Management
- Add a remote repository:
  `git remote add origin <repository-url>`
- Check the configured remotes:
  `git remote -v`

## Cloning a Repository
- Clone a repository to your local machine:
  `git clone <repository-url>`

## Resolving Conflicts
- Check for conflicts after a pull or merge:
  `git status`
- Edit conflicted files, then add them to the staging area:
  `git add <filename>`
- Commit the resolved changes:
  `git commit -m "Resolved conflicts"`

## Deleting a Branch
- Delete a local branch:
  `git branch -d <branch-name>`
- Delete a remote branch:
  `git push origin --delete <branch-name>`

## Checking Branches
- List all local branches:
  `git branch`
- List remote branches:
  `git branch -r`

## Force Push (Caution)
- Force push changes to overwrite remote history:
  `git push -f origin <branch-name>`

---

Save this as `command.md` in your project folder. 😊

