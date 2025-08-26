# Git Basics

## Initialize & first commit
```bash
git init
git add .
git commit -m "Initial commit"
```

## Branching
```bash
git checkout -b feature/docs
git push -u origin feature/docs
```

## Useful
- `git status` — what changed
- `git log --oneline --graph --decorate --all` — visualize history