# 📘 Week 10 Notes - Setting Up a Documentation Project Structure

## 🎯 Objectives

- Create a `/docs` directory in your repo
- Add modular Markdown files: overview, getting started, FAQ
- Follow a logical, scalable folder structure
- Use internal links to connect your docs

---

## 🧠 Why `/docs`?

GitHub uses the /docs folder automatically with GitHub Pages. Structuring your content inside it:

- Prepares you for publishing
- Helps dev teams locate all documentation
- Makes modular content easier to maintain

---

## 🛠️ Step-by-Step Instructions

## 📁 1. Create `/docs` Folder

In your repo root (via VS Code or File Explorer):

Create a folder named: `docs`

Inside that folder, add the following files:

| File Name            | Purpose                       |
| -------------------- | ----------------------------- |
| `overview.md`        | What the API/service does     |
| `getting-started.md` | Setup or authentication steps |
| `faq.md`             | Common user questions/issues  |

## 📝 2. Starter Content Templates

`overview.md`

```bash
# API Overview

This API allows users to manage to-do tasks via a REST interface.

## Key Features
- Add, retrieve, and delete tasks
- Query by user ID
```

`getting-started.md`

```bash
# Getting Started

## Base URL
```

`https://example.com/api/tasks`

```bash

## Authentication
Currently no authentication is required. Future versions will use API keys.
```

`faq.md`

```bash
# FAQ

**Q: Can I retrieve tasks by user ID?**  
A: Yes, use the `GET /tasks?user_id=123` endpoint.

**Q: What format are dates returned in?**  
A: ISO 8601 format.
```

## 🔗 3. Add Internal Links

In each file, add a section like:

```bash
📄 [Return to Overview](./overview.md)
📄 [See Getting Started](./getting-started.md)
```

🔄 4. Commit & Push

In GitHub Desktop:

- Add all three files
- Commit message: `Add docs structure with overview, getting-started, and faq`
- Push to GitHub
  
---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 10 Notes

```bash
## Highlights

- Structured my docs into a `/docs` folder
- Created modular files for overview, setup, and FAQs
- Linked files together for easy navigation
```

## 📋 Task List

- [x] Created a `/docs` folder in my repo
- [x] Added `overview.md`, `getting-started.md`, and `faq.md`
- [x] Used internal links to connect files
- [x] Committed and pushed changes

---

## 🔁 Commit Log
