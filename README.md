# \# Git Workflow Practice Repository

# 

# This repository was created to practice a complete Git workflow, including branching, commits, pull requests, merge conflicts, and workflow documentation.

# 

# \## Workflow Used

# 

# This project follows a Trunk-Based Development workflow.

# 

# \### Branch Strategy

# 

# \- `main` – Stable production branch

# \- `feature-login` – Login feature implementation

# \- `jwt-implement` – JWT authentication feature

# 

# Each new feature was developed in its own branch before being merged into `main`.

# 

# \## Development Workflow

# 

# 1\. Create a feature branch from `main`

# 2\. Implement the feature with multiple commits

# 3\. Push the branch to GitHub

# 4\. Open a Pull Request

# 5\. Review the changes

# 6\. Merge into `main`

# 7\. Resolve merge conflicts if necessary

# 

# \## Git Commands Used

# 

# ```bash

# git checkout -b feature-login

# git add .

# git commit -m "Add login feature"

# git push origin feature-login

# 

# git checkout main

# git merge feature-login

# ```

# 

# \## Merge Conflict Practice

# 

# An intentional merge conflict was created by modifying the same file (`app.txt`) in different branches.

# 

# The conflict was resolved manually before completing the merge.

# 

# \## Repository Structure

# 

# ```

# main

# ├── feature-login

# └── jwt-implement

# ```

# 

# \## Skills Practiced

# 

# \- Repository initialization

# \- Branch creation

# \- Feature development

# \- Multiple commits

# \- Pull Requests

# \- Merge conflicts

# \- Conflict resolution

# \- Branch merging

# \- Git history visualization

