# Git Basics

This document outlines the basic fundamentals of Git, including common commands and their usage.

```bash
# Initial Setup

# Configure Git with your identity:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Check your configuration:
git config --list


# Creating a Repository

# Initialize a new Git repository:
git init

# Clone an existing repository:
git clone <repository_url>


# Basic Workflow

# Check the status of your working directory:
git status

# Add files to the staging area:
git add <file_name>
# Or to add all changes:
git add .

# Commit changes to the repository:
git commit -m "Your commit message"

# Push changes to a remote repository:
git push origin <branch_name>

# Pull changes from a remote repository:
git pull origin <branch_name>


# Branching

# Create a new branch:
git branch <new_branch_name>

# Switch to an existing branch:
git checkout <branch_name>

# Create and switch to a new branch in one command:
git checkout -b <new_branch_name>

# Merge a branch into the current branch:
git merge <branch_name>

# Delete a branch:
git branch -d <branch_name>


# Viewing Commit History

# Show commit history:
git log

# Show a single line per commit:
git log --oneline


# Undoing Changes

# Unstage files (remove from staging area):
git reset <file_name>

# Undo changes in a file (revert to last commit):
git checkout -- <file_name>

# Reset to a previous commit:
git reset --hard <commit_hash>


# Working with Remote Repositories

# Add a remote repository:
git remote add origin <repository_url>

# List all remotes:
git remote -v

# Remove a remote:
git remote remove <remote_name>


# Stashing

# Stash changes (save without committing):
git stash

# Apply stashed changes:
git stash apply

# List stashes:
git stash list

# Drop a stash:
git stash drop

