## Setup & Configuration

git config --global user.name "Your Name"      
git config --global user.email "you@example.com"   
git config --global color.ui auto              
git config --list     

## Starting a Repository

git init      
git clone <url>  

## Basic File Operations

git status  
git add <file>  # Stage a file for commit
git add.  # Stage all files for commit
git rm <file>  # Remove a file from repository
git mv <src> <dest> # Rename/move a file

## Committing Changes

git commit -m "Commit message"  # Save staged changes with a message
git commit -a -m "Commit message" # Commit all modified tracked files
git commit --amend             # Edit the last commit

## Viewing History

git log          # Show commit history
git log --oneline # Short, one-line per commit
git log -p       # Show changes introduced in each commit

## Branching & Merging

git branch              # List all branches
git branch <branch_name> # Create a new branch
git checkout <branch>    # Switch to a branch
git checkout -b <branch> # Create and switch to a branch
git merge <branch>      # Merge a branch into the current branch
git branch -d <branch>   # Delete a branch

## Remote Repositories

git remote -v          # List configured remote repositories
git remote add <name> <url> # Add a remote repository
git fetch <remote>      # Fetch updates from remote (does not merge)
git pull <remote> <branch> # Fetch and merge updates from remote
git push <remote> <branch> # Push local commits to remote

## Tagging

git tag <tag_name>          # Create a tag for a specific commit
git tag -a <tag_name> -m "Message" # Annotated tag with message
git push origin <tag_name>   # Push tag to remote


