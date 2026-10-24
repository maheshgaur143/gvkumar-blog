# G.V. Kumar Blog

A professional blog dedicated to meteorology, climate science, and environmental issues.

## 🚀 Project Overview

This repository contains the source files for the G.V. Kumar blog. The site is a static HTML/CSS project deployed via Netlify and hosted on GitHub.

- **Live Site**: [https://gvkumar-blog.netlify.app](https://gvkumar-blog.netlify.app)
- **GitHub Repository**: [https://github.com/maheshgaur143/gvkumar-blog](https://github.com/maheshgaur143/gvkumar-blog)

## 🛠 Deployment & Maintenance

This guide provides three methods for adding new articles and deploying updates.

### Method 1: GitHub Web Interface (Easiest)
1. Navigate to the [GitHub Repository](https://github.com/maheshgaur143/gvkumar-blog).
2. Click **Add file** $\rightarrow$ **Create new file**.
3. Name the file (e.g., `new-article.html`).
4. Use `delhi-smog.html` as a template for the structure and content.
5. **Commit changes**.
6. Redeploy using the Netlify command (see below).

### Method 2: Using Claude Code (Recommended)
Simply request the update in Claude Code:
> *"Add a new article titled '[Your Title]' to gvkumar blog"*

Claude will handle the HTML creation, update the `articles.html` listing, push to GitHub, and redeploy to Netlify automatically.

### Method 3: Local Development (Full Control)
1. **Create Article**: Add a new `.html` file in the blog folder.
2. **Update Listing**: Add the new article link and summary to `articles.html`.
3. **Push to GitHub**:
   ```bash
   git add -A
   git commit -m "Add new article: [Article Title]"
   git push origin master
   ```
4. **Deploy to Netlify**:
   ```bash
   npx netlify-cli deploy --prod --dir . --site 904fdc0b-971c-4280-90ad-3ad8bcca003c
   ```

## 📋 Quick Reference Card

| Item | Value |
| :--- | :--- |
| **Blog URL** | [https://gvkumar-blog.netlify.app](https://gvkumar-blog.netlify.app) |
| **GitHub Repo** | [https://github.com/maheshgaur143/gvkumar-blog](https://github.com/maheshgaur143/gvkumar-blog) |
| **Netlify Site ID** | `904fdc0b-971c-4280-90ad-3ad8bcca003c` |
| **Deploy Command** | `npx netlify-cli deploy --prod --dir . --site 904fdc0b-971c-4280-90ad-3ad8bcca003c` |
