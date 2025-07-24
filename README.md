# 🚀 Git Commands Cheat Sheet

Welcome to your ultimate **Git command reference** – clean, categorized, and perfect for beginners and pros alike.

> 💡 Use this cheat sheet to speed up your development workflow and master Git faster!

---

## 📌 Setup and Configuration

```bash
git config --global user.name "Your Name"          # Set your name
git config --global user.email "you@example.com"   # Set your email
git config --global core.editor code               # Set VS Code as default editor
git config --list                                  # Show current config
```

---

## 🗂️ Repository Initialization

```bash
git init                       # Initialize new repo
git clone <repo-url>          # Clone a remote repo
```

---

## 📁 Staging & Snapshots

```bash
git status                    # Check status of working directory
git add <file>                # Stage a file
git add .                     # Stage all changes
git reset <file>              # Unstage a file
git diff                      # View unstaged changes
git diff --staged             # View staged changes
```

---

## 💾 Committing

```bash
git commit -m "Message"       # Commit with message
git commit -am "Message"      # Add & commit tracked files
```

---

## 🔄 Branching and Merging

```bash
git branch                    # List branches
git branch <branch>           # Create a new branch
git checkout <branch>         # Switch to branch
git checkout -b <branch>      # Create and switch
git merge <branch>            # Merge into current branch
git branch -d <branch>        # Delete a branch
```

---

## 🌐 Remote Repositories

```bash
git remote -v                 # List remotes
git remote add origin <url>   # Add remote repo
git push -u origin main       # Push local to remote
git push                      # Push updates
git pull                      # Pull latest changes
git fetch                     # Fetch without merge
```

---

## 🕓 History & Logs

```bash
git log                       # Full history
git log --oneline             # Compact history
git show <commit>             # Show commit details
git blame <file>              # Who changed what
```

---

## 🛠️ Undoing Mistakes

```bash
git checkout -- <file>        # Discard local changes
git reset --hard              # Reset all to last commit
git reset --soft HEAD~1       # Undo last commit (keep changes)
git revert <commit>           # Revert a commit safely
```

---

## 📦 Tagging Versions

```bash
git tag                       # List tags
git tag <tag>                 # Create tag
git push origin <tag>         # Push tag
```

---

## 🧹 Cleanup & Optimization

```bash
git clean -f                  # Remove untracked files
git gc                        # Garbage collection
```

---

## 🔐 Authentication Helpers

```bash
git config --global credential.helper cache  # Cache credentials
git config --global credential.helper store  # Store credentials
```

---

## ✅ Pro Tip

Use `git help <command>` for full docs on any command.

---

## 📄 License

This cheat sheet is open source and free to use. Contributions welcome!
