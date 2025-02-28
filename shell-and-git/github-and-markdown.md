# Git & GitHub

## Cloning a GitHub repo on your computer

1. Click on “Code” dropdown button → SSH → download repo
2. `git clone [repo link]`
3. You get your cloned repository in your current directory in bash

## Git commands

`git add [file]`
`git commit -m [message]`
`git push [remote repository] [branch]`
`git status` gives you a summary of your file whereabouts:
- on branch [branch name] → tell you where your file is
- your branch is up to date with [remote repository]/[branch] → tells you your branch is up to date with the one in the cloud 
- changes to be commited → shows what changes will be committed
`git log` → tells you the history of what happened until now (exit with q)
`git log --oneline` → a condensed version of git log
`git fetch` → to get news on your repo
`git status` → to know what happened after fetch
`git pull` → to get the updates on your local machine
`git checkout` → changes branch or commit stage
`git switch -c [feature-name]` → creates and switches to the branch
`git switch [feature-name]` → switch to the branch
`git push [remote repository] [feature-name]`
`git branch -d [feature-name]` → deletes branch
