# Github Commands

This repo contains the aggregated most used commands for Github. It also refers to the blogs with examples.

## SETUP & INIT

Configuring information, initializing and cloning repositories

| Command           | Description                                                  |
| ----------------- | ------------------------------------------------------------ |
| `git init`        | Initialize an existing directory as a Git repository         |
| `git clone [url]` | Retrieve an entire repository from a hosted location via URL |

## STAGE & SNAPSHOT

Working with snapshots and the Git staging area

| Command                                 | Description                                                           |
| --------------------------------------- | --------------------------------------------------------------------- |
| `git status`                            | show modified files in working directory, staged for your next commit |
| `git add [file]`                        | add a file as it looks now to your next commit (stage)                |
| `git reset [file]`                      | unstage a file while retaining the changes in working directory       |
| `git diff`                              | diff of what is changed but not staged                                |
| `git diff --staged`                     | diff of what is staged but not yet commited                           |
| `git commit -m “[descriptive message]”` | commit your staged content as a new commit snapshot                   |

## BRANCH & MERGE

Isolating work in branches, changing context, and integrating changes

| Command                    | Description                                                              |
| -------------------------- | ------------------------------------------------------------------------ |
| `git branch`               | list your branches. a \* will appear next to the currently active branch |
| `git branch [branch-name]` | create a new branch at the current commit                                |
| `git checkout`             | switch to another branch and check it out into your working directory    |
| `git merge [branch]`       | merge the specified branch’s history into the current one                |
| `git log`                  | show all commits in the current branch’s history                         |

## SHARE & UPDATE

Retrieving updates from another repository and updating local repos

| Command                        | Description                                                           |
| ------------------------------ | --------------------------------------------------------------------- |
| `git remote add [alias] [url]` | add a git URL as an alias                                             |
| `git fetch [alias]`            | fetch down all the branches from that Git remote                      |
| `git merge [alias]/[branch]`   | merge a remote branch into your current branch to bring it up to date |
| `git push [alias] [branch]`    | Transmit local branch commits to the remote repository branch         |
| `git pull`                     | fetch and merge any commits from the tracking remote branch           |

## TEMPORARY COMMITS

Temporarily store modified, tracked files in order to change branches

| Command          | Description                                 |
| ---------------- | ------------------------------------------- |
| `git stash`      | Save modified and staged changes            |
| `git stash list` | list stack-order of stashed file changes    |
| `git stash pop`  | write working from top of stash stack       |
| `git stash drop` | discard the changes from top of stash stack |

# Most Used Commands by Developers

Use the following reference to find the most used commands by developers.

[10 Important git commands for every developer](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/)

[20 git commands with examples](https://dzone.com/articles/top-20-git-commands-with-examples)
