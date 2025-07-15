# 🧬 Git Essentials

A collection of essential Git commands for daily use and productivity.

## 🔍 Inspecting Repository

```bash
git status
```
> Show current branch, staged/unstaged changes.

```bash
git log --oneline --graph --decorate
```
> Compact, visual representation of commit history.

```bash
git diff
```
> See what has changed before staging.

## 📝 Commit & Stage

```bash
git add .
```
> Stage all changes.

```bash
git commit -m "Your message"
```
> Commit staged changes.

```bash
git reset --soft HEAD~1
```
> Undo last commit, keep changes staged.

## 🔄 Branching & Merging

```bash
git branch
git checkout -b feature-xyz
git merge main
```

## 🔄 Stash

```bash
git stash -u
git stash pop
```

## 🧹 Cleanup

```bash
git clean -fd
```
> Remove untracked files and directories.