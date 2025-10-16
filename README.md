# Yutori Natsuband — Personal Website

This repository contains a lightweight, static personal website for Yutori Natsu/Arc Foxylotl. It showcases a profile, featured projects, skills, and contact information. The site is built with plain HTML and CSS and is intended to be served as a static site (for example via GitHub Pages).

## Features

- Responsive single-page layout
- Profile card with avatar, bio, and contact details
- Projects grid and simple scroll animations
- Lightweight: no build step, plain HTML/CSS/JS

## Project structure

- `index.html` — main page
- `styles.css` — global styles (if present)
- `fonts/` — local font files
- `tests/` — experimental or test pages

## Preview locally

Easiest: open `index.html` in your browser by double-clicking it.

Or serve a local HTTP server (recommended) — in PowerShell:

```powershell
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

Or with Node (if you have http-server installed):

```powershell
npx http-server -p 8000
# then open http://localhost:8000
```

## Contributing

Small fixes and improvements are welcome. Suggested workflow:

1. Fork the repository
2. Create a feature branch
3. Make changes and open a pull request

If you'd like help polishing content or adding new sections (blog, projects pages, i18n, etc.), open an issue describing what you'd like.

## Notes

- This repository currently has no license specified. Add a `LICENSE` file if you want to make reuse explicit.
- The site is intentionally simple so it's easy to host on GitHub Pages or any static hosting provider.

---

Contact: arcfoxylotl@gmail.com