# 📘 Week 5: Branching Strategy for API Technical Writers

## 🎯 Objectives

- Learn naming conventions and types of branches
- Understand how branching supports Docs-as-Code
- Create a branch for a specific documentation feature
- Practice making, committing, and pushing changes

---

## 🧠 Why a Branching Strategy Matters

In API documentation projects, especially when using GitHub collaboratively, branching ensures that:

- Changes are isolated and reviewable
- You can work on multiple topics without overwriting others
- Collaboration with developers stays organized

---

## 🔀 Common Branch Types & Naming Conventions

| Branch Type    | Naming Pattern       | Use Case                            |
| -------------- | -------------------- | ----------------------------------- |
| Feature        | `feature/topic-name` | New doc, guide, or section          |
| Fix            | `fix/typo-or-bug`    | Small corrections or grammar fixes  |
| Update/Enhance | `update/filename`    | Refinements to existing content     |
| Release        | `release/v1.0`       | Preparing for major publish/release |

### ✅ Pro Tip: Use kebab-case (lowercase with hyphens) for clarity

---

### 🛠️ Step-by-Step Practice

### 1. Create a Feature Branch

In GitHub Desktop:

- Go to Branch > New Branch
- Name it: `feature/api-overview`
- Base it on `main`
- Click Create Branch

### 2. Add a New File in VS Code

- File name: api-overview.md
- Paste this starter content:

```bash
# API Overview

This document provides a high-level summary of the API’s purpose, structure, and capabilities.

## Goals
- Help developers understand what the API does
- Summarize key endpoints and responses
- Link to detailed topics

*Created in feature/api-overview branch*
```

### 3. Commit and Push Changes

In GitHub Desktop:

- Review your new file
- Commit message: `Add API Overview starter file`
- Click Commit to feature/api-overview
- Click Push origin

### 4. Open a Pull Request

- Visit your repo on GitHub
- Click “Compare & Pull Request”
- Title: `Add API Overview`
- Description: “Initial structure for API overview section.”
- Click Create Pull Request

## 📋 Task List

- [x] Learned branch types and naming conventions
- [x] Created a `feature/api-overview`
- [x] Wrote a new topic file
- [x] Committed and pushed to GitHub
- [x] Opened a PR for it

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

## 📝 Week 5 Notes

- [x] Learned branch types and naming conventions
- [x] Created a `feature/api-overview branch`
- [x] Wrote a new topic file
- [x] Opened a PR for it

---

## 🔁 Commit Log
