# Version Control Practice Project

This project is to demonstrate my understanding of Git and GitHub.

## 🔧 What I Did

- Initialized a Git repository
- Created a new branch for feature development
- Made multiple commits on different branches
- Pushed commits to GitHub
- Opened and merged a Pull Request
- Reverted a commit using git revert
- Practiced pushing and pulling changes between local and remote repositories

---

## 🧪 Git Commands Used

```bash
# Initialize repo
git init

# Add remote
git remote add origin <repo-url>

# Add and commit
git add .
git commit -m "Initial commit"

# Push to main branch
git push -u origin main

# Create and switch to new branch
git checkout -b feature-about

# Push new branch
git push -u origin feature-about

# Merge pull request (done on GitHub)

# Fetch latest changes
git fetch

# Revert a commit
git revert <commit-id>

# Switch back to main and pull merged branch
git checkout main
git pull origin main