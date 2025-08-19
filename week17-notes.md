# 📘 Week 17: Publishing Documentation with GitHub Pages

## 🎯 Objectives

- Enable GitHub Pages in your repo
- Publish Markdown files as a website
- Understand how Jekyll powers GitHub Pages
- Customize basic Pages settings

---

## 🧠 What Is GitHub Pages?

GitHub Pages lets you turn your repo into a live, public website using:

- Static Markdown files
- Optional themes via Jekyll
- Auto-generated navigation based on your structure
  
---

## 🛠️ Step-by-Step: Publish with GitHub Pages

## ✅ 1. Enable GitHub Pages

### 1. Go to your *GitHub repo

### 2. Click Settings > Pages (in the left sidebar)

### 3. Under "Source", select

- Branch: `main`
- Folder: `/docs`

### 4. Click **Save**

✅ GitHub will assign you a URL like:
`https://your-username.github.io/my-first-docs-repo`

### ⚠️ It may take a minute or two for the site to become active

## 📁 2. Structure Your `/docs` Folder

Make sure it contains:

```bash
/docs/
├── index.md         ← homepage
├── overview.md
├── getting-started.md
├── faq.md
```

## 📌 Rename one of your existing `.md` files to `index.md`, or create a new one like

```bash
# Welcome to the To-Do API Docs

Use this site to get started with the API, explore features, and find answers to FAQs.

- [Overview](./overview.md)
- [Getting Started](./getting-started.md)
- [FAQ](./faq.md)
```

## 🎨 3. Optional: Use a GitHub Pages Theme

### 1. In Settings > Pages > Theme Chooser

### 2. Pick a built-in Jekyll theme (like Minimal, Cayman, or Slate)

### 3. GitHub will automatically create `_config.yml` for you

### 4. You can edit `_config.yml` to customize

```bash
title: To-Do API Docs
theme: jekyll-theme-cayman
```

### 🔁 4. Commit & Push

In GitHub Desktop:

- Commit any new `index.md` or `_config.yml`
- Push to GitHub
- Refresh your GitHub Pages URL to see the live site

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 17 Notes

```bash
## Highlights

- Published my documentation live using GitHub Pages
- Created a homepage and linked internal topics
- Chose a Jekyll theme to style the docs
- Now have a professional URL to share
```

## 📋 Task Checklist

- [x]  Enabled GitHub Pages from `/docs` folder
- [x]  Created or renamed `index.md` as homepage
- [x]  Structured docs for easy navigation
- [x]  Customized theme using `_config.yml`
- [x]  Pushed changes and verified live site

---

## 🔁 Commit Log
