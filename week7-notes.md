# 📘 Week 7: Resolving Merge Conflicts

## 🎯 Objectives

- Understand what a merge conflict is and why it happens
- Simulate a simple merge conflict
- Resolve the conflict using Visual Studio Code and GitHub Desktop
- Commit and complete the merge

---

## 🧠 What is a Merge Conflict?

A merge conflict occurs when two branches change the same line(s) in the same file, and Git doesn’t know which version to keep. You'll have to manually choose which changes to keep, combine, or discard.

---

## 🧪 Simulate a Merge Conflict (Safe Practice)

### 📝 Step 1: Prepare the File

### 1. In your `main` branch, open or create a file called `merge-practice.md`

### 2. Add this content

```bash
# Merge Conflict Practice

This is the original content from the main branch.
```

### 3. Commit and push this to `main`

### 🌱 Step 2: Create Two Branches

### 1, Branch A

- From `main`, create `branch/alpha-edit`
- Edit `merge-practice.md`

```bash
This line was added from branch Alpha.
```

- Commit and push the change

### 🔀 Step 3: Merge Alpha into Main

- Open a PR from   `branch/alpha-edit` into `main`
- Merge it cleanly—should succeed

### ❌ Step 4: Merge Beta into Main

- Open a PR from `branch/beta-edit` into `main`
- GitHub will block the merge and say: ⚠️ “This branch has conflicts”

### 🛠️ Step 5: Resolve the Conflict in VS Code

### 1. Pull the conflicting branch to your local machine

### 2. Open the file (`merge-practice.md`) in VS Code

### 3. You'll see something like

```bash
<<<<<<< HEAD
This line was added from branch Alpha.
=======
This line was added from branch Beta.
>>>>>>> branch/beta-edit
```

### 4. Pick one, combine both, or write your own resolution. Example

```bash
This line includes edits from both Alpha and Beta.
```

### 5. Save the file, go to GitHub Desktop, and commit the resolution

### 6. Push the resolved branch

### 7. Merge the PR—now it will succeed

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 7 Notes

```bash
## Highlights
- Experienced a merge conflict for the first time
- Learned how to identify conflict markers
- Resolved the issue using VS Code and GitHub Desktop
- Now confident in handling real-world Git hiccups
```

## 📋 Task List

- [x] Simulated a merge conflict between two branches
- [x] Identified the conflicting lines
- [x] Used VS Code to resolve the conflict
- [x] Committed and pushed the resolved version
- [x] Merged the PR

---

## 🔁 Commit Log
