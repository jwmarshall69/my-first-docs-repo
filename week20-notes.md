# 📘 Week 20: Build a Mini API Documentation Project

## 🎯 Objectives

- Create a new repo and docs project from scratch
- Structure documentation for a fictional or real API
- Use GitHub Pages, Actions, and versioning
- Practice clean commits, branching, and PRs
  
---

### 🛠️ Step-by-Step: Your Project Plan

### 🗂️ 1. Create a New Repo

Name it something like:

```bash
to-do-api-docs
```

Initialize it with a `README.md`.

## 🧱 2. Project Structure

Use this file layout:

```bash
📁 to-do-api-docs/
├── 📁 docs/
│   ├── index.md
│   ├── overview.md
│   ├── authentication.md
│   ├── endpoints.md
│   ├── faq.md
├── .github/
│   └── workflows/
│       ├── markdown-lint.yml
│       └── spell-check.yml
├── CONTRIBUTING.md
├── LICENSE
├── .gitignore
├── _config.yml
```

## ✍️ 3. Fill Out Content

`overview.md`

```bash
# API Overview

The To-Do API allows users to manage tasks, mark them complete, and organize by category.
```

`authentication.md`

```bash
# Authentication

This API uses token-based authentication via headers.

`Authorization: Bearer <your-token>`
```

`endpoints.md`

```bash
# Endpoints

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | /tasks           | List tasks               |
| POST   | /tasks           | Add a new task           |
| DELETE | /tasks/{id}      | Delete a task            |
```

## 🎨 4. Pages + YAML

Add front matter (`---`) to all pages

Update`_config.yml`

```bash
title: To-Do API Docs
theme: jekyll-theme-slate
description: Developer documentation for a sample REST API
```

## 🔁 5. Automation & Versioning

- Enable GitHub Pages (`/docs` folder)
- Add GitHub Actions for:
- - Markdown Lint
- - Spell Check
- Create and push a tag: `v1.0`
- Draft a GitHub Release

## ✅ 6. Deliverables Checklist

| Item                             | Status |
| -------------------------------- | ------ |
| 📁 Structured repo with `/docs`  | ✅      |
| ✍️ Filled out all Markdown files | ✅      |
| 🎨 Configured GitHub Pages       | ✅      |
| ⚙️ Added GitHub Actions          | ✅      |
| 🏷️ Created tag and release       | ✅      |
| 🌐 Live documentation site       | ✅      |

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 20 Notes

```bash
## Highlights

- Built my first end-to-end API documentation project
- Used versioning, GitHub Pages, Actions, and front matter
- Project is live and ready for collaboration or portfolio use
```

## 📋 Task Checklist

- [x]  Structured repo with /docs
- [x]  Filled out all Markdown files
- [x]  Configured GitHub Pages
- [x]  Added GitHub Actions
- [x]  Created tag and release
- [x]  Live documentation site

---

## 🔁 Commit Log
