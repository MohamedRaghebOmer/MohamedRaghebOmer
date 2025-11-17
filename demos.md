# Git & GitHub Demos

## Branches
### Create a new branch
git checkout -b feature-login

### Switch between branches
git checkout main
git checkout feature-login

### List all branches
git branch
git branch -a

---

## Merges
### Merge a branch into main
git checkout main
git merge feature-login

### Resolve a merge conflict
# Edit conflicting files manually
git add <file>
git commit -m "Resolve merge conflict"

### Fast-forward merge
git checkout main
git merge --ff-only feature-login

---

## Workflows
### Push changes to GitHub
git add .
git commit -m "Add new feature"
git push origin feature-login

### Pull changes from GitHub
git pull origin main

### Basic Pull Request Workflow
1. Create a branch
2. Make commits
3. Push branch to GitHub
4. Open a Pull Request
5. Merge PR after review
