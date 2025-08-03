# Git-and-GitHub-
## Git & GitHub Basics

### 1. Difference Between Git and GitHub
- **Git** is a local version control system that tracks code changes.
- **GitHub** is a cloud platform to host Git repositories and collaborate with others.

### 2. Difference Between `git pull` and `git fetch`
- `git fetch`: Downloads updates from the remote repo **without** changing your local files.
- `git pull`: Fetches and **merges** changes into your current branch.

### 3. Purpose of `.gitignore`
- It tells Git which files or folders to **ignore** (e.g., `node_modules`, `.env`) and not track in version control.

### 4. Steps to Contribute to an Open-Source Project
1. **Fork** the repository on GitHub.
2. **Clone** it to your machine: `git clone <repo-url>`
3. **Create a branch**: `git checkout -b feature-name`
4. **Make changes** and **commit**: `git commit -m "Describe your change"`
5. **Push** your branch: `git push origin feature-name`
6. **Create a Pull Request** on GitHub.
