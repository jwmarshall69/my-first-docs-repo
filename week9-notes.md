# 📘 Week 9: Markdown Mastery for API Docs

## 🎯 Objectives

- Deepen my understanding of Markdown syntax
- Practice formatting real-world API documentation
- Learn internal linking and table formatting
- Preview and Lint Markdown in VS Code
  
---

## 🛠️ Essential Markdown Syntax for API Writers

### Here’s a quick reference cheat sheet

| Feature        | Syntax Example                     |
| -------------- | ---------------------------------- |
| Heading        | `#`, `##`, `###`, etc.             |
| Link           | `[OpenAI](https://openai.com)`     |
| Image          | `![Alt Text](image.png)`           |
| Code block     | ` ```python\nprint("Hello")\n``` ` |
| Inline code    | ``Use `curl` to test``             |
| List (bullets) | `- Item` or `* Item`               |
| Ordered list   | `1. First`                         |
| Table          | See below                          |
| Quote          | `> This is a blockquote`           |

## 🧪 Table Example

| Method | Endpoint        | Description             |
|--------|------------------|-------------------------|
| GET    | /tasks           | Retrieve task list      |
| POST   | /tasks           | Add new task            |
| DELETE | /tasks/{id}      | Delete a specific task  |

---

## 🔗 Internal Links for Navigation

```bash
[Go to API Overview](./api-overview.md)
```

### 🧩 Hands-On Practice

### 1. Create a file: markdown-practice.md

### 2. Include

- Headings
- A blockquote
- A list of API endpoints
- One table
- A code block using curl
- A link to another file in your repo

Example

```bash
# Markdown Practice

## API Methods

> The following endpoints are currently supported.

- GET `/tasks`
- POST `/tasks`
- DELETE `/tasks/{id}`

```bash
curl -X GET https://example.com/api/tasks
```

Return to Overview

```bash

---

### 🔍 VS Code Pro Tips

- **Preview:** Right-click the file > **Open Preview**
- **Shortcuts:**
  - Bold: `Ctrl+B`
  - Italics: `Ctrl+I`
  - Preview: `Ctrl+K V`
- **Linting:** Use `markdownlint` to spot style issues (e.g., missing blank lines)
```

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 9 Notes

```bash
## Highlights

- Practiced advanced Markdown for API documentation
- Used tables, code blocks, and internal linking
- Improved formatting for developer usability
```

---

## 📋 Task List

- [x] Practiced using headers, links, code, tables, and quotes
- [x] Created a full `markdown-practice.md` file
- [x] Previewed it in VS Code
- [x] Committed and pushed changes to GitHub

## 🔁 Commit Log
