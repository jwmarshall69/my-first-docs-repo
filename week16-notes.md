# 📘 Week 16: GitHub Release Tags & Versioned Docs

## 🎯 Objectives

- Understanding what Git tags are
- Create and push a version tag (`v1.0`, `v1.1`, etc)
- Create a release on GitHub
- Learn basic strategies for managing versioned documentation
  
---

## 🧠 What Are Git Tags?

A Git tag marks a specific point in your commit history—often used to mark a release version. For example:

| Tag     | Purpose                      |
| ------- | ---------------------------- |
| `v1.0`  | First stable release         |
| `v1.1`  | Minor update                 |
| `v2.0`  | Major changes/new structure  |

### Tags help users and teams reference or roll to a specific state of the repo-like a frozen snapshot of your documentation

---

## 🛠️ Step-by-Step: Create a Git Tag and Release

## 🏷️ 1. Create a Git Tag in Terminal or GitHub Desktop

In Terminal or VS Code terminal:

```bash
git tag v1.0
```

Or using GitHub Desktop:

- Go to **Repository > Tag**
- Type: `v1.0`
- Click Create Tag

## 🚀 2. Push the Tag to GitHub

In Terminal:

```bash
git push origin v1.0
```

Or in GitHub Desktop:

- Menu > Repository > Push

## 📦 3. Create a Release on GitHub

### 1. Go to your GitHub repo

### 2. Click "Releases" tab > **"Draft a new release"**

### 3. Select the tag: `v1.0`

### 4. Fill in

- Title: `v1.0 – First Public API Docs Release`

- Description: Summary of changes or features

### 5. Click Publish Release

## 📁 4. Managing Versioned Docs (Simple Strategy)

For now, use branches or folders to version your docs:

### Option A: Branching

- Create a branch: `version/v1.0`
- Freeze your docs there
- Continue new edits on `main`

### Option B: Folders (in `/docs`)

```bash
/docs/
├── v1.0/
│   └── overview.md
├── v1.1/
│   └── overview.md
```

Each version has its own doc set—great for user-facing projects or APIs with breaking changes

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 16 Notes

```bash
## Highlights

- Created `v1.0` Git tag and GitHub release
- Learned how to freeze documentation at a milestone
- Explored strategies for managing multiple doc versions
```

## 📋 Task Checklist

- [x] Create a Git tag (`v1.0`)
- [x] Pushed the tag to GitHub
- [x] Drafted and published a GitHub release
- [x] Created a strategy for managing versioned docs

---

## 🔁 Commit Log
