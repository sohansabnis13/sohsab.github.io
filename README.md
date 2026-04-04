# Portfolio – Product & Delivery Leadership

A clean, editorial-style personal portfolio showcasing enterprise platform delivery work in financial services.

## 🚀 Live Site

Hosted on GitHub Pages: `https://<your-username>.github.io/<repo-name>/`

## 📁 Project Structure

```
/
├── index.html        ← Main portfolio page (single-file, no dependencies)
└── README.md         ← This file
```

## ✏️ How to Customize

### 1. Update your name / headline
In `index.html`, find:
```html
<h1 class="hero-name">
  Building<br/><em>systems that</em><br/>move.
</h1>
```
Replace with your preferred headline.

### 2. Update contact links
Find the `#contact` section and replace:
- `https://linkedin.com` → your LinkedIn URL
- `your@email.com` → your email
- `resume.pdf` → add your resume file and update the path

### 3. Add your name to the footer
Find:
```html
<p>© 2025 — Product &amp; Delivery Portfolio</p>
```

### 4. Add a resume PDF (optional)
Drop a `resume.pdf` file in the root of the repo. The "Download Résumé" button will automatically link to it.

## 🌐 Deploying to GitHub Pages

1. Create a new GitHub repository (e.g., `portfolio`)
2. Upload `index.html` and `README.md` to the repo
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch and `/ (root)` folder
6. Click **Save**

Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

> **Tip:** If you name the repo `<your-username>.github.io`, the site will be at `https://<your-username>.github.io/` (no subfolder).

## 🎨 Design Notes

- **Fonts**: Syne (display), Cormorant Garamond (body), DM Mono (labels) — loaded from Google Fonts
- **Colors**: Warm paper `#f4f0e8`, ink `#0d0d0d`, terracotta accent `#c8533a`
- **Interactions**: Click any project row to expand full details
- **No build step** — pure HTML/CSS/JS, zero dependencies beyond Google Fonts
