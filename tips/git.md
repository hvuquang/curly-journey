# Basic Usage of Git

### Reference
1. Learn the Basics of Git in Under 10 Minutes[https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/]

### Initialize Git
```
    code README.md # To create a README file
    git init
```

### Add files to the Staging Area for commit
```
    git add .
    # Adds alls the files in local repo and stages them for commit

    OR

    git add README.md
    # To add a specific file
```

### See what files are staged
```
    git status # Lists all new or modified files to be committed
```

### Commot Changes to Git Repo
```
    git commit -m 'First commit'
    # the message should be based on the Conventional Commits
```

### Uncommit
```
    git reset HEAD~1
    # remove the most recent commit
    # commit again!
```

### Add a remote origin and PUSH
```
    git remote add origin remote_repository_URL

    # git remote can create, view and delete connections to other repositories

    git remote -v
    # List the remote connections you have

    git push -u origin main 
    # Pushes the changes in your local repository up to the remote repository (origin)
```






