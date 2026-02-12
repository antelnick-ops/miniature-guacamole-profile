# Nicholas Antel — Portfolio Website

Personal portfolio website for Nicholas Antel — Tech Visionary, AI Builder, Blockchain Strategist & Patent Author.

## 🚀 Live Site

Deployed via GitHub Pages: `https://antelnick-ops.github.io/portfolio`

## 📁 Structure

```
/
└── index.html      # Single-file portfolio (all CSS & JS inline)
```

## ✏️ How to Update

All content lives in `index.html`. Key sections to customize:

### Blog Posts
Find the `#blog` section and update each `.blog-card` with your real Publish0x post titles, dates, excerpts, and direct post URLs:
```html
<div class="blog-title">Your Post Title</div>
<div class="blog-date">Month DD, YYYY</div>
<div class="blog-excerpt">Your excerpt...</div>
<a href="https://www.publish0x.com/@YourUsername/your-post-slug" ...>
```

### Publish0x Username
Replace `@NicholasAntel` with your actual Publish0x handle (3 occurrences in the blog section).

### Projects
Update the `.project-card` blocks in `#projects` with new projects, live demo links, and GitHub URLs.

## 🌐 Deploying to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set Source to `main` branch, `/ (root)` folder
4. Site will be live at `https://<your-username>.github.io/<repo-name>`

## 🛠 Tech Stack

- Pure HTML5 / CSS3 / Vanilla JS
- No frameworks, no dependencies, no build step
- Single file — deploy anywhere instantly

## 📄 License

All rights reserved © Nicholas Antel 2026
