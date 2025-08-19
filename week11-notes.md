# 📘 Week 11 Notes - Commit Best Practices & `.gitignore` Usage

## 🎯 Objectives

- Write meaningful, consistent commit messages
- Use atomic commits (one purpose per commit)
- Set up a `.gitignore` file to exclude unnecessary files from your repo

---

## 🧠 Why Commit Quality Matters

Good commit messages:

- Help teams understand what changed and why
- Make rollbacks and reviews easier
- Let project history serve as documentation

---

## ✅ Bad vs. Good Commit Messages

```bash
| ❌ Bad       | ✅ Good                                               |
| ----------- | ---------------------------------------------------- |
| `fix stuff` | `Fix typo in getting-started authentication section` |
| `docs`      | `Add internal links between overview and FAQ`        |
| `update`    | `Update code sample in tasks tutorial`               |
```

## ✍️ Commit Message Format (Optional Standard)

```bash
<type>: <short summary>

<body> (optional if needed for detail)

Examples:
docs: add overview.md to /docs
fix: correct typo in FAQ answer
enhancement: restructure getting-started.md
```

## 🛠️ Step-by-Step: Add a `.gitignore`

### 1. Create `.gitignore`

In the root of your repo:

- Right-click > New File > name it `.gitignore` (no file extension)

### 2. Add common exclusions

```bash
# macOS
.DS_Store

# VS Code
.vscode/
*.code-workspace

# Logs & system files
*.log
*.tmp

# Build artifacts (future use)
dist/
node_modules/
```

💡 You can customize this as you add tools to your project.

## 🔄 Practice Activity

### 1. Edit one of your `/docs` files—make a small content improvement

### 2. Stage it in GitHub Desktop

### 3. Write a descriptive commit message

### 4. Push the commit to GitHub

### 5. Add a `.gitignore` file to your repo

### 6. Commit that separately: `chore: add .gitignore for VS Code and system files`

---

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 11 Notes

```bash
## Highlights

- Practiced writing clear, purpose-driven commit messages
- Learned the value of atomic commits
- Created a `.gitignore` to keep clutter out of the repo
```

## 📋 Task List

- [x] Followed best practices for commit messages
- [x] Made at least one new atomic commit with a clear summary
- [x] Created and configured `.gitignore`
- [x] Pushed all changes to GitHub

---

## 🔁 Commit Log
