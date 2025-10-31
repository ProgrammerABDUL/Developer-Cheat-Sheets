# 🚀 Git Cheat Sheet
**Version:** 1.0.0  
![Last Updated][badge]

A complete collection of Git & GitHub commands — from setup to advanced collaboration — all in one place.

> 🧠 Learn. Build. Contribute.

---

### ⚙ Getting Started & Configuration

| 🧩 Command                                                | 📝 Description                                     |
| -------------------------------------------------------- | ------------------------------------------------- |
| `git config --global user.name "Your Name"`              | 👤 Set Git username globally for all repositories. |
| `git config --global user.email "youremail@example.com"` | 📧 Set Git email address globally.                 |
| `git config --list`                                      | 📋 List current Git configuration settings.        |
| `git help`                                               | 💡 Show help for Git commands.                     |

---

### 🏁 Repository Initialization

| 🧩 Command                           | 📝 Description                              |
| ----------------------------------- | ------------------------------------------ |
| `git init`                          | 📋 Initialize a new Git repository.         |
| `git clone <repository_url>`        | 🔄 Clone a repository from a remote server. |
| `git clone --branch <branch> <url>` | 🌿 Clone a specific branch from the remote. |

---

### 🧠 Basic Workflow

| 🧩 Command             | 📝 Description                                |
| --------------------- | -------------------------------------------- |
| `git add <file>`      | ➕ Add a specific file to the staging area.   |
| `git add .`           | 📦 Add all changes in the current directory.  |
| `git status`          | 🔍 Show the status of your working directory. |
| `git diff`            | 📜 Show unstaged changes.                     |
| `git commit -m "msg"` | 💬 Commit staged changes with a message.      |
| `git log`             | 🕓 View commit history.                       |

---

### 🌿 Branching & Merging

| 🧩 Command                | 📝 Description                          |
| ------------------------ | -------------------------------------- |
| `git branch`             | 🌱 List all local branches.             |
| `git branch <name>`      | 🌿 Create a new branch.                 |
| `git branch -d <name>`   | ❌ Delete a local branch.               |
| `git checkout <branch>`  | 🔄 Switch to specified branch.          |
| `git checkout -b <name>` | 🚀 Create and switch to a new branch.   |
| `git merge <branch>`     | 🔗 Merge a branch into the current one. |

---

### 🌐 Remote Repositories

| 🧩 Command                     | 📝 Description                              |
| ----------------------------- | ------------------------------------------ |
| `git remote add origin <url>` | 🌍 Add a remote repository called "origin." |
| `git remote -v`               | 👀 View remote connections.                 |
| `git pull`                    | ⬇️ Fetch and merge updates from the remote. |
| `git push`                    | ⬆️ Push your commits to the remote.         |
| `git push -u origin <branch>` | 🔗 Push branch and track it on remote.      |

---

### 🔄 Reviewing & Undoing Changes

| 🧩 Command                   | 📝 Description                                                         |
| --------------------------- | --------------------------------------------------------------------- |
| `git reset <file>`          | 🧹 Unstage a file.                                                     |
| `git reset --hard <commit>` | ⚠️ Reset working directory and staging area to a commit (destructive). |
| `git restore <file>`        | ♻️ Restore file to last commit state.                                  |
| `git rm <file>`             | 🗑️ Remove file from working directory and stage removal.               |
| `git revert <commit>`       | 🔁 Create a new commit that undoes `<commit>`.                         |

---

### 🤝🏻 Advanced and Collaboration

| 🧩 Command                         | 📝 Description                                       |
| --------------------------------- | --------------------------------------------------- |
| `git fetch`                       | 📥 Download refs and objects from remote (no merge). |
| `git stash`                       | 💾 Save uncommitted changes for later use.           |
| `git stash pop`                   | 🎯 Apply and remove the latest stash.                |
| `git log --graph --oneline --all` | 🧩 View graphical commit history.                    |
| `git cherry-pick <commit>`        | 🍒 Apply changes from a particular commit.           |
| `git tag <tag>`                   | 🏷️ Add a tag to the latest commit.                   |
| `git clean -f`                    | 🧽 Remove untracked files.                           |

---

## ✍🏻 Created By
**Abdul Rehman Jiwani**  
💻 Full-Stack Developer | 🌐 Next.js | React.js | Node.js | MongoDB

📫 [Connect on LinkedIn][LinkedIn Profile] • ⭐ [Follow on X][X Profile]


## ⚡ About this Cheat Sheet

This cheat sheet is made to help developers quickly recall essential Git commands and workflows — perfect for beginners, students, and professionals who want to **boost their productivity with Git**.

If you find it useful,  
👉🏻 **Star this repo** 🌟 and **share it with your dev friends!**

## 📜 License

This cheat sheet is an open-source and free to use for learning and teaching purposes.
© 2025 Abdul Rehman Jiwani

<!-- Links -->
[Badge]: https://img.shields.io/badge/Last%20Updated-October%202025-blue?style=flat-square

[LinkedIn Profile]: https://pk.linkedin.com/in/abdul-rehman-jiwani

[X Profile]: https://x.com/iamabdulrehman5