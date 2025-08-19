# 📘 Week 15: Syncing Forks & Managing Upstream Updates

## 🎯 Objectives

- Understand the difference between origin and upstream
- Configure your fork to track changes from the original repo
- Pull updates from upstream into your fork
- Avoid merge conflicts by syncing early and often
  
---

## 🧠 Key Terms

| Term    | Meaning                                        |
| ---------- | ---------------------------------------------- |
| `origin`   | Your fork of the repo (on your GitHub account) |
| `upstream` | The original repository you forked from        |

## 🛠️ Step-by-Step: Set Up and Sync Your Fork

### ✅ 1. Add the Upstream Remote (One-Time Setup)

If you've forked a repo (e.g., `to-do-service-sp25`) and cloned it to your machine:

### 1. Open VS Code Terminal or your Git terminal

### 2. Check your remotes

```bash
git remote -v
```

### 3. Add the original repo as `upstream`

```bash
git remote add upstream https://github.com/UWC2-APIDOC/to-do-service-sp25.git
```

### 4. Confirm

```bash
git remote -v
```

You should now see both `origin` (your fork) and `upstream`.

## 🔁 2. Sync with Upstream

This pulls changes from the original repo into your local copy

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

### ✅ Tip: If there are no conflicts, your local copy is now synced

## 🚀 3. Push Your Updated Local Copy to Your Fork

```bash
git push origin main
```

This updates your GitHub fork so it matches the latest changes from the original repo

### 🎯 Optional GUI Shortcut: GitHub Desktop Sync

If you're using GitHub Desktop:

### 1. Menu > Repository > Repository Settings

### 2. Under Remotes, add

- Name: `upstream`

- URL: Original repo link

### 3. Use the "Fetch origin" button and manually merge upstream changes via Terminal or CLI if needed

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

## 📝 Week 15 Notes

```bash
## Highlights

- Reviewed a Pull Request using line-by-line feedback
- Left a suggestion with improved phrasing
- Approved and merged the PR like a content lead
- Learned to balance editorial feedback with technical accuracy
```
  
## 📋 Task Checklist

- [x] Added upstream remote to your fork
- [x] Fetched and merged upstream changes into main
- [x] Pushed changes back to your fork (origin)
- [x] Verified that your repo is up to date

---

🔁 Commit Log
