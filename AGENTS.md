# PixelForge

Single-page landing site for PixelForge, a retro gaming review site. Plain HTML and CSS only: [index.html](index.html) and [styles.css](styles.css).

## Conventions

- No build step, frameworks or third-party libraries (CSS or JS). The Google Fonts `@import` at the top of `styles.css` is the only external resource; do not add more.
- HTML: clean, semantic tags (`header`, `nav`, `main`, `section`, `article`, `footer`, etc.). Prefer element selectors; add classes sparingly and name them by meaning (`.review-card`), never by appearance (`.red-box`).
- CSS: all colours must come from the `--color-*` variables in `:root` of `styles.css`. Do not hardcode hex values elsewhere; add a new variable first if a colour is missing.
- Design direction: retro/pixel-game inspired on a dark theme (red, orange, purple and grey accents).

## Dev environment

- Served with the Five Server VS Code extension (live reload). `index.html` links the stylesheet with the root-relative path `/styles.css`, which relies on that server.
