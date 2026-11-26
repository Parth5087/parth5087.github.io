# Parth Patel – Portfolio

Static portfolio site for **Parth Patel** (Mobile Application Developer — Android, Android TV & Flutter), hosted on GitHub Pages.

## Files
- `index.html` — self-contained portfolio (HTML, CSS, JS, inline SVG icons, and embedded portrait images)
- `og.jpg` — Open Graph social preview card (`1200×630`) for WhatsApp / LinkedIn / Twitter shares
- `Parth_Patel_Resume.pdf` — resume PDF linked from the header and contact section

## Features
- **Interactive Hero** — cursor-responsive 3D avatar zones, docked corner assistant on scroll, and typed role showcase
- **Pull-Cord Theme Switch** — animated light/dark mode switch (`localStorage` persisted, with zero-flash theme initialization and View Transitions radial reveal)
- **Six Apps, Three Platforms** — pinned horizontal showcase + filterable grid view (`Android`, `Android TV`, `Flutter`), interactive device mockups, and full case-study modal dialogs
- **Skills ↔ Projects Mapper** — filterable technical skills panel showing which projects used each technology
- **Quick Search (`Ctrl/Cmd + K`)** — keyboard-accessible command palette for sections, project case studies, theme toggle, resume, and links

## Deploy on GitHub Pages
1. Commit and push `index.html`, `og.jpg`, `Parth_Patel_Resume.pdf`, and `README.md` to `Parth5087/parth5087.github.io` (`main` branch).
2. Open https://parth5087.github.io/ and hard-refresh (`Cmd+Shift+R` / `Ctrl+Shift+R`).
3. To refresh social share preview caches, paste the URL into https://www.linkedin.com/post-inspector/.

## Editing Content
All portfolio copy, projects, skills, and experience entries live in the `PROFILE` object at the top of the `<script>` in `index.html`.
