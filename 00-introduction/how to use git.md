# Installing Git
Git comes pre-installed. Verify with:
``` git --version ```

Download and install Git from:
https://git-scm.com/download/win

## Git Configuration

``` git config --global user.name "Aashima Ahuja" ```
``` git config --global user.email "aashima@gmail.com" ```

Check your configuration:

``` git config --list --show-origin ```

## Using Multiple Git Configs
You can maintain separate configs for work and personal projects.

### Work config (~/.gitconfig-work):

[user]
name = Work User
email = work@example.com

### Personal config (~/.gitconfig-personal):

[user]
name = Personal User
email = personal@example.com

### Include in global config (~/.gitconfig):

[includeIf "gitdir:~/work/"]
    path = ~/.gitconfig-work

[includeIf "gitdir:~/personal/"]
    path = ~/.gitconfig-personal

### Verify active config:

git config --list

## Initializing a Git Repository

``` git init ```

A .git folder is created
Git starts tracking your project files

## Adding .gitignore

used to exclude files or directories from tracking

## Pushing Project to Remote (GitHub)

### Pushing an Existing Project

**1** Add remote repository
``` git remote add origin <remote_repo_url> ```
**2** Push your branch
``` git push -u origin main ```
**3** Check remote
``` git remote -v ```
**4** Rename remote (if needed):
```git remote rename origin upstream ```

## Cloning a Project from GitHub

``` git clone <remote_repo_url> ```

