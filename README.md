# GitHub

## Git Cheat Sheet
___
setup your local Git profile in the terminal:

```
git config --global user.name "your-name"
git config --global user.email "your-email"
```

Check if Git is already configured you can type:

```
git config --list
```
Navigate to your working folder

```
cd [name of your folder]
```

Initialize a git repository

```
git init
```

Check Status

```
git status
```

Add all files for tracking

```
git add .
```

Add selected files for tracking

```
git add [file or folder name]
```

Unstage all files

```
git reset
```

Unstage a particular file

```
git reset [file or folder name]
```

Persisting your work

```
git commit -m "first commit"
```

Connect your local Git repo with GitHub

```
git remote add origin https://github.com/username/repository_name.git
```

Send local files to GitHub

```
git push -u origin main
```

To add more changes

```
git add .
git commit -m "type your commit message here"
git push
```

### Collaborate

Create a branch

```
git branch [branch-name]
```

Switch to working branch

```
git switch [branch-name]
```

Do work

```
git add .
git commit -m "my changes"
```

Combine your work with the main branch

```
git switch main
git pull
```

At this point you want to make sure that any conflicts, situations where Git can't easily combine the changes happens in your working branch. Therefore run the following commands:

```
git switch [branch_name]
git merge main
```

Send your work to GitHub

```
git push --set-upstream origin [branch-name]
```

Clean up

```
git branch -d [branch-name]
```
___
Reference: 

https://github.com/microsoft/Web-Dev-For-Beginners/tree/main/1-getting-started-lessons/2-github-basics
