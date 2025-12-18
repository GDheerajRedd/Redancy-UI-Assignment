# Redancy-UI-Assignment

**Files**
- **Index:** [index.html](index.html) — main entry file for the static site.
- **Compiled CSS:** [styles/main.css](styles/main.css) — compiled stylesheet included by `index.html`.
- **SCSS Source:** [styles/main.scss](styles/main.scss) — source SCSS with variables and mixins (breakpoints at 768px and 480px).
- **Assets:** [images/](images/) — image assets used by the page.

**How to view locally**
1. Open `index.html` directly in your browser by double-clicking it.
2. Or install Live Server Extension in VS Code:

**Build / Work with SCSS**
If you modify `styles/main.scss` you'll need to compile it to `styles/main.css`. option:

```bash
npx sass --watch styles/main.scss:styles/main.css
```

Notes:
- The SCSS includes variables for primary colors and breakpoints: tablet at 768px and mobile at 480px.
- The compiled `styles/main.css` already exists in the repo; rebuilding is only required if you edit the SCSS.

**Development notes**
- Responsive layout uses flexbox and CSS grid for the testimonials and advantages sections.
- Main layout containers and brand assets are in `index.html` and `images/`.
- If you want a faster dev experience, use the VS Code Live Server extension to auto-reload.
