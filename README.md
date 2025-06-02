# My-Learnings-in-Git-GitHub
# 🌈 Git & GitHub Ultimate Cheat Sheet

## 🔷 **Git Basics**
| Command | Description |
|---------|-------------|
| `git init` | Initialize new Git repo |
| `git clone <url>` | Clone a repository |
| `git status` | Show changed files |
| `git add <file>` | Stage specific file |
| `git add .` | Stage all changes |
| `git commit -m "msg"` | Commit staged changes |
| `git log` | Show commit history |

## 🔶 **Branching**
| Command | Description |
|---------|-------------|
| `git branch` | List branches |
| `git branch <name>` | Create new branch |
| `git checkout <branch>` | Switch branches |
| `git checkout -b <branch>` | Create & switch branch |
| `git merge <branch>` | Merge branch into current |
## 🔶 **Advanced Branching**
| Command | Description |
|---------|-------------|
| `git branch -m old new` | Rename branch |
| `git branch --contains <commit>` | Find branches containing commit |
| `git worktree add ../new_dir` | Multiple working trees |

## 🟢 **Remote Repositories**
| Command | Description |
|---------|-------------|
| `git remote add origin <url>` | Add remote repo |
| `git push -u origin main` | First push to remote |
| `git push` | Push changes |
| `git pull` | Fetch + merge changes |
| `git fetch` | Download objects/refs |

## 🟣 **Undoing Changes**
| Command | Description |
|---------|-------------|
| `git restore <file>` | Discard unstaged changes |
| `git reset <file>` | Unstage file |
| `git reset --hard HEAD` | Discard all local changes |
| `git revert <commit>` | Create undo commit |

## 🟠 **GitHub Specific**
| Feature | Description |
|---------|-------------|
| **Fork** | Copy repo to your account |
| **Pull Request** | Propose changes to others' repos |
| **Issues** | Track bugs/enhancements |
| **Actions** | CI/CD automation |
| **Pages** | Host static websites |

## 🟡 **Advanced Git**
| Command | Description |
|---------|-------------|
| `git stash` | Temporarily save changes |
| `git rebase` | Reapply commits on new base |
| `git cherry-pick <commit>` | Apply specific commit |
| `git bisect` | Binary search for bugs |

## 🟤 **GitHub CLI (gh)**
| Command | Description |
|---------|-------------|
| `gh repo clone <repo>` | Clone repository |
| `gh pr create` | Create pull request |
| `gh issue list` | List issues |
| `gh gist create <file>` | Create gist |

## 🟪 **Git Workflow**
1. `git pull` (Get latest changes)
2. `git checkout -b feature-x`
3. Make changes → `git add .` → `git commit -m "msg"`
4. `git push origin feature-x`
5. Create PR on GitHub

## 🟥 **Common Issues Fixes**
- **Merge conflicts**: Edit conflicted files → `git add` → `git commit`
- **Detached HEAD**: `git checkout main`
- **Wrong commit**: `git commit --amend`
