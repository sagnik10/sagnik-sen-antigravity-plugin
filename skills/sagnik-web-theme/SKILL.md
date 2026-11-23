---
name: sagnik-web-theme
description: Apply Sagnik Sen's editorial-scientific CSS design tokens and GitHub Pages hosting conventions to web and frontend projects.
---

# Sagnik Sen Editorial-Scientific Web Theme

All web projects under `github.com/sagnik10` share a cohesive visual identity anchored on `SagnikSenPortfolio`.

## Design Tokens

```css
:root {
  --bg: #f6f9fd;
  --surface: #ffffff;
  --ink: #192a43;
  --muted: #54647a;
  --accent: #275cce;
  --accent-hover: #1949ae;
  --tint: #eaf1ff;
  --line: #dce4ee;
  --status: #258066;
}
```

## Typography

- **Display & Headings:** `Newsreader`, Georgia, serif
- **Body & UI:** `IBM Plex Sans`, system-ui, sans-serif
- **Eyebrows, Badges & Code:** `IBM Plex Mono`, monospace

## GitHub Pages Checklist

- Include `.nojekyll` at the repository root for static HTML/JS sites.
- Set the repository `homepage` to `https://sagnik10.github.io/<repo-name>/`.
- Include a `Live Demo` badge in `README.md` pointing to the GitHub Pages URL.
