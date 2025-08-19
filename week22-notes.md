# 📘 Week 22: Analyze Public API Docs Repo Structures

## 🎯 Objectives

- Explore how established tech companies organize their API docs
- Identify best practices for file/folder structure, naming, and navigation
- Take notes on patterns you’d like to adopt
- Begin refining your own repo accordingly
  
---

## 🧠 Why This Matters

Great API doc repos aren’t just about good writing—they’re well-structured, navigable, and easy to maintain. By studying public examples, you’ll:

- Learn scalable patterns for future projects
- Avoid structural mistakes
- Level up your “Docs-as-Code” thinking

---

## 🔍 Suggested Repos to Study

Here are some real or high-quality open-source API documentation projects to analyze:

| Repo                                                                    | What to Look For                                               |
| ----------------------------------------------------------------------- | -------------------------------------------------------------- |
| [stripe/stripe-api-docs](https://github.com/stripe/stripe-api-docs)     | Structured endpoints, `_data`, and custom Jekyll layouts       |
| [Redocly/redoc](https://github.com/Redocly/redoc)                       | OpenAPI integrations and examples                              |
| [MicrosoftDocs/azure-docs](https://github.com/MicrosoftDocs/azure-docs) | Massive scale—search for smaller subfolders                    |
| [postmanlabs/postman-docs](https://github.com/postmanlabs/postman-docs) | Good use of `/src/pages/` with Markdown and YAML               |
| [mdn/content](https://github.com/mdn/content)                           | Mozilla’s content-first approach (see `/files/en-us/web/api/`) |

## 📋 What to Look For

Create a mini analysis checklist like:

- 📁 Folder Structure: Are topics grouped by domain or function?
- 🧾 File Naming: Are filenames clear, lowercase, hyphenated?
- 🔗 Linking: Internal navigation between docs?
- 📄 README.md Content: High-level or overly technical?
- 🧱 Metadata: Use of front matter or _config.yml?
- 📚 Navigation/TOC: Manually curated or auto-generated?
- ⚙️ Automation: Are Actions or CI tools being used?

---

## 🧪 Commands or Techniques Practiced

```bash
# Add your Git or CLI commands here
```

---

## 📝 Week 22 Notes

```bash
### Highlights

### Repo Analyzed: stripe/stripe-api-docs

- Folders grouped by product (`payments`, `connect`)
- Heavy use of `_data` and `_includes` for layout logic
- All content stored in Markdown with front matter
- GitHub Actions used to lint and test builds
- Clean README and `CONTRIBUTING.md`

### Repo Analyzed: postmanlabs/postman-docs

- Docs live in `src/pages`
- OpenAPI specs integrated via Redoc
- Code samples stored separately

### Takeaways for My Project

- Use consistent hyphenated filenames
- Add `_data.yml` if building sidebar nav later
- Possibly separate reference and guide content
```

## 📋 Task Checklist

- [x] Reviewed at least 2 public API doc repos
- [x] Took notes on structure, automation, metadata, etc.
- [x] Identified 3+ best practices to use in your own work
- [x] (Optional) Applied one change to your current repo

---

## 🔁 Commit Log
