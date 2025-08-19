# 📘 Week 18: Customizing GitHub Pages with YAML & Front Matter

## 🎯 Objectives

- EUnderstand YAML front matter and how it affects page rendering
- Customize `_config.yml` to control theme and metadata
- Add titles and descriptions to each page
- Build a polished, navigable docs site
  
---

## 🧠 What Is YAML Front Matter?

YAML front matter is metadata at the top of your `.md` files, enclosed in `---`. It tells Jekyll (the engine behind GitHub Pages) how to render the page.

## 🔧 Example

```bash
---
title: Getting Started
description: Learn how to connect to the To-Do API and make your first request.
---

# Getting Started

This API helps users manage tasks using REST endpoints...
```

### 📌 Without front matter, your Markdown still works, but won’t integrate well with themes or layouts

---

## 🛠️ Step-by-Step Customization

## ✅ 1. Add Front Matter to All Docs Pages

In each file inside `/docs/`:

`overview.md`

```bash
---
title: API Overview
description: A summary of the To-Do API's purpose and key endpoints.
---
```

`faq.md`

```bash
---
title: Frequently Asked Questions
description: Answers to common API usage questions.
---
```

## 🧾 2. Create or Edit `_config.yml`

Located at the root of your repo (or create one if missing):

```bash
title: To-Do API Documentation
description: Official API documentation for the sample To-Do REST service.
theme: jekyll-theme-cayman
markdown: kramdown
```

You can also add optional settings

```bash
show_downloads: false
google_analytics: UA-XXXXXXXXX-X
```

## 🔁 3. Commit & Push Changes

- Save all updated .md files with front matter
- Save or create _config.yml
- Use GitHub Desktop to commit

```bash
docs: add front matter and update _config.yml for GitHub Pages
```

- Push to GitHub

## 🌐 4. Visit Your GitHub Pages Site

Go to your GitHub Pages URL (from Week 17) and refresh—your titles and descriptions should now appear properly in the browser and theme layout

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 18 Notes

```bash
## Highlights

- Used YAML front matter to title and describe each docs page
- Customized the site's look and feel via _config.yml
- Improved navigability and metadata for my published docs
```

## 📋 Task Checklist

- [x]  Added YAML front matter to all `.md` pages
- [x]  Created or updated `_config.yml` file
- [x]  Structured docs for easy navigation
- [x]  Customized site title, theme, and description
- [x]  Verified updates on GitHub Pages site

---

## 🔁 Commit Log
