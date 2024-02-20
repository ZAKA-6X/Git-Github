# Git-Github:

---

## Git Quick Reference Guide

### Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

### Initialization

```bash
git init   # Initialize Git in your workspace
```

### Basic Commands

```bash
git add "file"         # Add a file to the staging area
git commit -m "message"    # Save changes with a descriptive message
git status             # Check the status of your workspace
git diff "file"        # View changes made to a file since the last commit
git diff --cached      # View changes staged for commit
```

### Viewing History

```bash
git log             # View commit history
git log -n "number"     # View the last "number" of commits
```

### Branching

```bash
git checkout "commit id"   # Move to a specific commit
git checkout master     # Switch back to the master branch
git reset HEAD^         # Undo the last commit
git branch          # List all branches
git branch name         # Create a new branch
git checkout namebranch     # Switch to a specific branch
git merge namebranch       # Merge changes from another branch into the current one
```

### Tags

```bash
git tag "name"          # Create a new tag for the last commit
git tag --delete "name"     # Delete a tag
```

### Remote Repository

```bash
git remote -v           # View remote repository links
git remote add origin repo-link   # Add a link to your remote repository
git push -u origin master      # Push modifications to your remote repository
```

### File Operations

```bash
touch "file"            # Create a new file
```

---
