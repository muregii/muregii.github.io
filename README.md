# raydonmuregi.net

Personal website for **Raydon Muregi** — software engineer, product manager, and founder.
Computer Science at Duke University.

Live at **https://muregii.github.io**

## Structure

Single self-contained page — `index.html` holds the markup, styles and scripts,
with everything else under `assets/`.

```
index.html          markup + inline CSS/JS
favicon.svg
assets/
  hero.jpg          hero portrait (WebGL fluid-reveal canvas)
  about.jpg
  contact.jpg
  projects/         full-bleed layers for the Selected Work scroll
  ventures/         founder-project imagery
  speaking/         talks & conferences
```

External runtime dependencies are loaded from CDNs: GSAP (+ ScrollTrigger, Flip),
Splitting, threejs-components, and Google Fonts.

## Local preview

```bash
python3 -m http.server 8899
# http://localhost:8899
```

## History

The previous (2024) version of this site is preserved on the
[`old-site-2024`](https://github.com/muregii/muregii.github.io/tree/old-site-2024) branch.
