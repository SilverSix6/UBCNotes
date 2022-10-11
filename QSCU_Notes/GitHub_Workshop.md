# Git Workshop - QSCU
---

## Switching Branches
`git checkout branch-name` will switch to branch that exists
`git checkout -b branch-name` creates a branch and switches to it

## Merging Branches
`git merge side-branch` will merge specified branch with current working branch 

## Merge Conflicts
- Occur when a file conflicts from multiple versions of itself. 
- Must indicate to Git which conflicting file to keep, most of the time it will be seperate lines of both.
- `======` - Conflict Divider

## Remote Repositories
- GitHub is the most popular remote repository used today.
- Alternatives exist like BitBucket and GitLab

## Remote Repositories vs. Local Repositories
- Remote Repositories are stored on servers like GitHub/Alternatives
- Local Repositories are stored on the PC and can be a clone of a Remote Repository
	- If you don't push a Local Repository it will stay Local and not become Remote

## Working with Repositories
- `git remote add origin https://github.com/txlon5/somerepo` will upload a local repoitory to a remote url
- `git clone https://github.com/txlon5/somerepo` will clone a remote repository and create a local copy on your computer
- `git push origin branch-name` will push to a specific branch, you can specify `master` if you want the default branch
- `git pull origin master` will download any changes made to the remote repository into the local repository on your computer

## Pull Requests
- Merging branches on the remote repository rather than the local repository
- Submitting a Pull Request you can view the files being requested and can check for any conflicts before accepting the Pull Request

## Other Git Commands
- `git revert <commit-id>` will revert any commits that you have pushed to a remote repository, by reverting it will make a new current commit stating you have reverted (tldr: makes a clone of the old commit as a current one)
- `git reset <commit-id>` will just go back to the previous commit without making any additonal commits; erasing any changes made after that commit you have reverted to
- `git diff myfile.txt` will show added/removed lines from a specified file
- `git log`  is helpful for seeing logs and more specifically commits done

