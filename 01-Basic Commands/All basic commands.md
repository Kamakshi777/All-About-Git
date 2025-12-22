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
git add <file>  
git add.  
git rm <file>  
git mv <src> <dest> 

## Committing Changes

git commit -m "Commit message"  
git commit -a -m "Commit message" 
git commit --amend             

## Viewing History

git log          
git log --oneline 
git log -p       

## Branching & Merging

git branch              
git branch <branch_name> 
git checkout <branch>    
git checkout -b <branch> 
git merge <branch>      
git branch -d <branch>   

## Remote Repositories

git remote -v         
git remote add <name> <url> 
git fetch <remote>      
git pull <remote> <branch> 
git push <remote> <branch> 

## Tagging

git tag <tag_name>          
git tag -a <tag_name> -m "Message" 
git push origin <tag_name>   


