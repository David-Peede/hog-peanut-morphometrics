# hog-peanut-morphometrics

## Dave's Git Workflow


__0. If there are unstaged changes, stage and commit those changes before pulling and rebasing.__
```bash
git add .
git commit -m "oops I left a mess"
```
__1. Fetch the latest changes from `main` in the `origin` remote and then rebase your current branch onto the latest `main`.__
```bash
git pull --rebase origin main
```
__2. Make some changes—i.e., code up a sick solution.__

__3. Stage all new and modified files.__
```bash
git add .
```
__4. Commit the changes to the local repository.__
```bash
git commit -m "sick commit message"
```
__5. Push the `main` branch to the remote repository to reflect the committed changes.__
```bash
git push origin main
```