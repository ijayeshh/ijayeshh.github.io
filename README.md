# ijayeshh.github.io

Personal portfolio for Jayesh Ingale, Applied ML Engineer. It's a static site with plain HTML, CSS and JS, no build step, served by GitHub Pages.

```
index.html                    all content (sections, project cards, inline SVG diagrams)
assets/css/style.css          design tokens (dark + light), layout, components
assets/js/main.js             theme toggle, mobile menu, project tabs, scroll reveal
assets/Jayesh_Ingale_Resume.pdf   resume served by the "Resume" buttons
assets/img/og-image.png       1200×630 link-preview image (LinkedIn, Slack, X)
favicon.svg, assets/img/favicon-32.png, assets/img/apple-touch-icon.png
.nojekyll                     serve files as-is (skip Jekyll)
```

**Update the resume:** replace `assets/Jayesh_Ingale_Resume.pdf`, keeping the same filename.

**Preview locally:** `python -m http.server 8000`, then open http://localhost:8000.

**Add a project:** copy an `<article class="card">` block inside `#panel-llm` or `#panel-cv` in `index.html` and update the count in the matching tab button.
