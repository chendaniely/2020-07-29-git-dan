# 2020-07-29: Git basics class

## The basics

- `git init`: create a repository in your current folder
- `git status`: tells you everything you need to know about the current state

- `git add <path>`: adds the <path> to the staging area
- `git commit`: will open up an editor to write a commit message
    - `git commit -m "your message"`: write <message> to commit in 1 step

- `git log`: will show you the git log
    - `git log --oneline`: will give you the oneline version of the log

- `git diff`: diff the current state with the last known git state
    - `git diff --staged`: diff files in the staging area

- `HEAD`: where you are currently looking (i.e., what the files on your computer are)

## Remotes

- `git remote add <URL`: adds a remote url
- `git push origin master`: local -> remote
- `git pull origin master`: remote -> local
