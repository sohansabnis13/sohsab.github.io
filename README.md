# Sohan Sabnis – Portfolio

Personal portfolio hosted on GitHub Pages. Dark, modern design built with plain HTML, CSS, and JavaScript — no frameworks, no build step, zero dependencies beyond Google Fonts.

## 🌐 Live Site

`https://<your-username>.github.io/<repo-name>/`

---

## 📁 Files

```
/
├── index.html    ← Complete portfolio (single file)
├── resume.pdf    ← Add your resume here
└── README.md
```

---

## ✏️ Things to Update Before Publishing

Open `index.html` and search for these placeholders:

| Placeholder | Section | Replace with |
|---|---|---|
| `[Your Company]` | Hero / intro | Your current company name |
| `your@email.com` | Hero + Contact (×2) | Your actual email address |
| `https://github.com` | Contact section | Your GitHub profile URL |

### Optional tweaks
- **Skills proficiency labels** — Update Expert / Advanced / Intermediate to match your actual level
- **Summary bio** — Personalise the intro paragraph in the hero section
- **Résumé** — Drop a `resume.pdf` file in the root folder; the "Download Résumé" button links to it automatically

---

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `portfolio`)
2. Upload `index.html` and optionally `resume.pdf`
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose `main` branch, `/ (root)` folder, and click **Save**
6. Your site goes live in ~1 minute at the URL shown

> **Tip:** Name the repo `<your-username>.github.io` and your site will be at `https://<your-username>.github.io` with no subfolder path.

---

## 🎨 Design

- **Theme:** Dark — background `#0f1117`, surfaces `#181c27`
- **Accent:** Blue `#4f8ef7` with green `#34d399` for impact chips
- **Fonts:** Syne (headings) + Inter (body) via Google Fonts
- **Other Projects:** Compact table/row format — scannable at a glance
- **Skills:** Grid layout with proficiency levels per skill
- **Animations:** Subtle fade-in on scroll only
- **Projects:** Click any card to expand Role / What Was Built / Impact
- **Mobile:** Fully responsive; nav collapses on small screens

---

## ➕ Adding More Projects

To add another row to the **Other Projects** table, copy this block inside `.other-table` in `index.html`:

```html
<div class="other-row">
  <div class="other-cell other-icon">🔧</div>
  <div class="other-cell">
    <div class="other-name">Project Name</div>
    <div class="other-client">Client / Company</div>
  </div>
  <div class="other-cell other-desc">
    Short description of what was built and your contribution.
  </div>
  <div class="other-cell">
    <div class="other-tags">
      <span class="otag">Tag 1</span>
      <span class="otag">Tag 2</span>
    </div>
  </div>
  <div class="other-cell">
    <span class="role-pill">Your Role</span>
  </div>
</div>
```
