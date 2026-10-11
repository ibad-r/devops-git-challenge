# DevOps Class Activity – Proof of Work

**Student Name:** Ibad ur Rehman  
**SAP ID:** 56468  
**Repository:** https://github.com/ibad-r/devops-git-challenge

## 1. Git Commit History

Command used: `git log --oneline`

a2c93bc (HEAD -> main, origin/main, origin/HEAD) fix: resolve main branch merge conflict
be93297 Merge pull request #1 from ibad-r/development
aa14bc9 (backup-main) fix: staging label
0bd52c6 (origin/development, development) feat: development deployment label
075d862 (origin/staging, staging) fix: staging label
d291a9a feat: development deployment label
57c6808 feat: updated script with staging env
5f684bc feat: initial commit with deploy script
33b3e93 Initial commit


## 2. Reflection Questions

### Q1. What is the difference between Git and GitHub?

Git is a version control tool that helps us track changes in our project files. It works locally, so we can create commits and branches without an internet connection. GitHub is an online platform where we can upload our Git repositories. It also helps developers collaborate through pull requests and code reviews.

### Q2. Explain the Working Directory, Staging Area, and Local Repository.

The Working Directory is where we create and edit our project files. The Staging Area holds the changes we select using the `git add` command. The Local Repository stores our committed changes using `git commit`. These three stages help us organize and track our project work properly.

### Q3. What is the difference between git stash pop and git stash apply?

Both commands restore changes that we temporarily saved using `git stash`. The `git stash pop` command restores those changes and removes the stash entry if applied successfully. The `git stash apply` command restores the changes but keeps the stash entry saved. We use `apply` when we might need to reuse the same saved changes later.

### Q4. What is the difference between git fetch and git pull?

The `git fetch` command downloads updates from the remote repository without merging them into our current branch. This lets us review the changes before applying them. The `git pull` command downloads the updates and integrates them into our current branch. We use `pull` when we want our local branch to include the remote changes.