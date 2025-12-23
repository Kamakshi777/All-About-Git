## when we forgot to switch branches and committed on wrong branch

**1** I am intended to work on feature-login but I forgot to switch branches and committed on main.
```git add .```
```git commit -m "Add login documentation" ```

**2** use ``` git reset --hard HEAD~1 ``` to Remove the commit from main
**3** Switch to the correct branch  ``` git checkout feature-login```

## if the Commit Is Already Pushed

**1** git checkout feature-login
**2** git cherry-pick <commit-hash>



