# Git-Cheat-Sheet
A cheat sheet for common Git commands

## Branches
| Command              | Description                      |
| -------------------- | -------------------------------- |
| `git branch name`    | Create a new branch              |
| `git branch -d name` | Deletes a branch                 |
| `git checkout name`  | Use `git switch` instead         |
| `git merge name`     | Merge branch into current branch |

## Pulling
| Command    | Description       |
| ---------- | ----------------- |
| `git pull` | Update repository |

## Staged Changes
| Command                 | Description                |
| ----------------------- | -------------------------- |
| `git add -A`            | Stage all files            |
| `git reset --hard HEAD` | Unstage and delete changes |

## Changing Commits
| Command      | Description                                              |
| ------------ | -------------------------------------------------------- |
| `git commit` | Commit and open editor where commit message can be added |

## View
| Command      | Description     |
| ------------ | --------------- |
| `git log`    | See commit list |
| `git status` | See status      |

## Stash
| Command         | Description        |
| --------------- | ------------------ |
| `git stash`     | Stash staged files |
| `git stash pop` | Get stashed files  |

## Remote
| Command    | Description      |
| ---------- | ---------------- |
| `git push` | Push any changes |