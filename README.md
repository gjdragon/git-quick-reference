---

# 📘 Git Quick Reference

A minimal, fast‑access list of essential Git commands.

---

## 🏁 Basics
```bash
git init
git clone <url>
git status
git add .
git commit -m "msg"
git push
git pull
```

## 🌿 Branching
```bash
git branch <name>
git switch <name>
git merge <name>
git branch -d <name>
```

## 🏷️ Tags
```bash
git tag v1.0.0
git tag -a v1.0.0 -m "msg"
git push origin v1.0.0
git tag -d v1.0.0
git push origin --delete v1.0.0
```

## 🔄 Stash
```bash
git stash
git stash list
git stash apply
git stash drop
```

## 🧹 Undo / Clean
```bash
git restore <file>
git reset --soft HEAD~1
git reset --hard HEAD~1
git clean -fd
```

## 📦 Remotes
```bash
git remote -v
git remote add origin <url>
git remote remove origin
git fetch
```

## 🧭 Logs / Diff
```bash
git log --oneline --graph
git diff
git blame <file>
```

## 🛠️ Advanced
```bash
git rebase <branch>
git rebase -i HEAD~N
git cherry-pick <hash>
git commit --amend
git bisect start
```

## ⚙️ Config
```bash
git config --global user.name "Name"
git config --global user.email "Email"
git config --global alias.st "status"
```

---
