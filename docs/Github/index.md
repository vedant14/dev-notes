# My Github notes
- I use github as my default git versioning system. In fact, I suspect like most devs, I haven't even used any other version control systems.


## Common commands I use
### Initialise a git repo 
- This will create a git repo inside the directory you are currently in.
```
git init
```

### Create a branch from master
- From master meaning, the new branch that will be created will at first be identical to master
- You need to run git push after this so that these changes are reflected in github too.
```
git checkout -b new-model
```

### Check the branches created for a particular repo
- If you want to find what are the various branches in an existing repo, then use this command.
```
git branch
```

### Checkout to an existing branch
```
git checkout <branchname>
```

