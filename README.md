# Oren Pipano — Portfolio

Personal engineering & coding portfolio. Hosted via GitHub Pages.

## 🚀 Live Site
> [https://YOUR-GITHUB-USERNAME.github.io](https://YOUR-GITHUB-USERNAME.github.io)

---

## 📁 Structure

```
index.html   ← entire portfolio (single file, no dependencies)
README.md    ← this file
```

Everything is in one self-contained `index.html` file — no build tools, no frameworks, no npm. Just open it in a browser or push to GitHub Pages.

---

## ✏️ How to Update

### Add a New Project

1. Open `index.html`
2. Find the `Projects` section (search for `<!-- PROJECT 1`)
3. Copy any existing `<div class="project-card">` block
4. Paste it **before** the `<!-- ADD NEW PROJECT PLACEHOLDER -->` div
5. Update the fields:
   - `project-title` → Project name
   - `project-year` → Year / context
   - `project-badge` class → choose one:
     - `badge-award` (orange — for competition wins)
     - `badge-research` (blue — for published/academic)
     - `badge-design` (purple — for design/creative)
     - `badge-engineering` (green — for active builds)
   - Badge text → label inside the span
   - `project-desc` → description paragraph
   - `project-tags` → add/remove `<span class="tag">` items
   - Optionally add a `<a class="project-link">` for external links

### Add a Publication

1. Find `<!-- ════════ TO ADD A PUBLICATION`
2. Copy a `<div class="pub-card">` block
3. Update the number `[N]`, title, meta info, and href

### Update Contact/Social Links

Search for `Update with your username` in the file and replace with your actual GitHub URL.

---

## 🌐 Hosting on GitHub Pages

1. Create a repo named `YOUR-GITHUB-USERNAME.github.io`
2. Push `index.html` and `README.md` to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your site will be live at `https://YOUR-GITHUB-USERNAME.github.io`

---

## 🎨 Design Notes

- Font: DM Serif Display (headings) + DM Sans (body) + DM Mono (labels)
- Color: Warm off-white `#F7F5F2` background, accent blue `#1A4D8F`
- No external JS dependencies — pure HTML/CSS
- Fully responsive (mobile-friendly)
