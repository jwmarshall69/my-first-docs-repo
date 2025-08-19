# 📘 Week 19: Automating Docs Tasks with GitHub Actions

## 🎯 Objectives

- Understand what GitHub Actions are
- Set up a simple workflow to lint Markdown or check spelling
- Automate quality checks every time you push
- Build a foundation for CI/CD in documentation
  
---

## 🧠 What Is GitHub Actions?

GitHub Actions let you create workflows that run when events happen in your repo (e.g., push, PR). It's like setting up your own little robot that checks your work every time you update your docs.

These workflows are written in YAML and stored in   `.github/workflows/`.

## 🛠️ Step-by-Step: Add a Markdown Linter Workflow

## ✅ 1. Create a Workflow Directory

In your repo

```bash
.github/workflows/
```

## ✅ 2. Add a Linter Workflow

Create a new file

```bash
.github/workflows/markdown-lint.yml
```

Paste this

```bash
name: Markdown Lint

on:
  push:
    paths:
      - '**.md'
  pull_request:

jobs:
  markdownlint:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v3

      - name: Run Markdown Linter
        uses: DavidAnson/markdownlint-cli2-action@v13
```

### ✅ This runs a Markdown linter every time you push or open a PR

## 🧪 Optional: Add a Spell Checker Workflow

Create

```bash
.github/workflows/spell-check.yml
```

Paste

```bash
name: Spell Check

on: [push, pull_request]

jobs:
  spellcheck:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: rojopolis/spellcheck-github-actions@0.33.1
        with:
          config_path: .spellcheck.yml
```

Then add a basic .spellcheck.yml in the root of your repo

```bash
files:
  - docs/**/*.md
output: ./spellcheck-results.txt
```

---

## ✅ 3. Commit & Push

In GitHub Desktop:

- Stage both YAML files
- Commit message: `chore: add GitHub Actions for linting and spell check`
- Push to GitHub

GitHub will automatically run the workflows under the Actions tab of your repo.

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 19 Notes

```bash
## Highlights

- Set up GitHub Actions for Markdown linting and spell checks
- Learned how to write YAML-based workflow automation
- Now every push checks my docs for issues automatically
```

## 📋 Task Checklist

- [x]  Created `.github/workflows` directory
- [x]  Added `markdown-lint.yml`
- [x]  (Optional) Added `spell-check.yml` and config
- [x]  Committed and pushed changes
- [x]  Verified automation in the Actions tab

---

## 🔁 Commit Log
