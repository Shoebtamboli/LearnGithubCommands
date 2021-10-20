# Github Commands

## Create a new repository

```
git init
```

## Add files to the repository

```
git add README.md
```

## Commit the changes

```
git commit -m "first commit"
```

## Create a new branch

```
git checkout -b dev
```

## Checkout to the master branch

```
git checkout master
```

## Merge the dev branch into the master branch

```
git merge dev
```

## Push the changes to the remote repository

```
git push origin master
```

## Create a new remote repository

```
git remote add origin
```

## Clone the remote repository

```
git clone
```

--

### Getting & Creating Projects

| Command                                                           | Description                                |
| ----------------------------------------------------------------- | ------------------------------------------ |
| `git init`                                                        | Initialize a local Git repository          |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command                            | Description                                       |
| ---------------------------------- | ------------------------------------------------- |
| `git status`                       | Check status                                      |
| `git add [file-name.txt]`          | Add a file to the staging area                    |
| `git add -A`                       | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes                                    |
| `git rm -r [file-name.txt]`        | Remove a file (or folder)                         |
