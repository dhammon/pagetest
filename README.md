# pagetest

This is a "Hello World" MkDocs project for an ebook.

## How to Update and Deploy

### 1. Update Content

Edit the Markdown files in the `docs/` directory.
To add new chapters or sections, create new Markdown files and update the `nav` section in `mkdocs.yml`.

### 2. Serve Locally (for testing)

To view your changes locally with a live-reloading server:

```bash
mkdocs serve
```

Open your browser to `http://127.0.0.1:8000` (or the address shown in your terminal). Press `Ctrl+C` to stop the server.

### 3. Deploy to GitHub Pages

Once you are happy with your changes, commit them to your `main` branch and then deploy to GitHub Pages:

```bash
# Stage all changes (new files, modified files)
git add .

# Commit your changes
git commit -m "feat: Your descriptive commit message"

# Push your changes to the main branch on GitHub
git push origin main

# Deploy the site to GitHub Pages (this pushes to the 'gh-pages' branch)
mkdocs gh-deploy
```

Your site will be available at `https://dhammon.github.io/pagetest/` after a few minutes.