# Git commands cheat-sheet: the most useful comments

## 1. Nagivate to your git project folder

Usee `cd` to  move between folders. E.g:
```
cd workSpace
cd bdl02 sinclair_git_cheatsheet
```

## 2. Check the status of the project

I can use the comments ***anytime** to inspect the project.

- `git status`

with `git Status` i can see if some changes have happened and if some files are ready to be committed.
It gives me an overview of the project at that specific moment in time.

Messages given by `git status`:
> working tree clean
This means that no change has happened in our project since our last `git commit`

- `git log`
- `git diff`

# 3. Initializing a git Project 
if any `git`command when we run gives the following output:
>fatal: not a git repository (or any of the parent directories): .git

it means that **we are not inside a git project**.
In such case we can:

1. Make sure that we are inside the right folder (and navigate to it, if necessary)
2. Initialize a git Project

To initialize git run ( run it down)
```

`git init`.
```
This command creates an empty Git repository. From now on, we can make changes to our files and permanently  save the changes

# 4. Save Changes

1. `git add .` (or `git add -A`). 

2. `git commit -m "Meaningful message here"`

A commit is the Git equivalent of save

3. `git push` i have time

This comment sends the committed changes to a server. It is used to upload local repository content to a remote repository