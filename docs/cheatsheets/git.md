# Git Cheatsheet
- Init
```bash
git init && git add . && git commit -m "init"
```
- Branching
```bash
git switch -c feature/x
```
- Rebase
```bash
git fetch origin
git rebase -i origin/main
```
- Logs
```bash
git log --oneline --graph --decorate --all
```
