# Aniras Hub — Home Page

Responsive HTML/CSS/JavaScript homepage based on the supplied Aniras Hub design reference.

## Files

```text
aniras-hub-homepage/
├── index.html
├── style.css
├── script.js
└── README.md
```

## GitHub Pages

1. Create a GitHub repository.
2. Upload the four files to the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save. GitHub will provide the live website URL.

## Important: hero image

The current hero photo is an external Unsplash image so the page works immediately. For the final site, replace it with an image you own or are licensed to use.

In `index.html`, replace the current `<img>` `src` with something like:

```html
src="assets/students.jpg"
```

and upload the image to an `assets` folder.

## Important: logo

The current logo mark is a lightweight CSS approximation so the homepage works with only four files. If you have the official Aniras Hub logo as PNG or SVG, replace the CSS mark with your official logo for a closer match.

## Navigation pages

The navigation is prepared for these pages:

```text
services.html
reviews.html
faqs.html
about.html
```

They are not included in this homepage-only package. Once created, place them in the same repository root.

## Current public information

The page currently displays:

- 44/45 in IBDP
- 55/56 in MYP
- First session is free
- AnirasHub@gmail.com
- Instagram: Aniras_Hub

Check these details before publishing.

## Enrolment

The free-session button currently opens an email to `AnirasHub@gmail.com`. Replace the `mailto:` link with your future booking form or scheduling system when ready.

## Main brand colours

The colours are defined at the top of `style.css`:

```css
--navy: #07347a;
--teal: #55c4c1;
--yellow: #f9bf2f;
```

## Suggested final project structure

```text
aniras-hub/
├── index.html
├── services.html
├── reviews.html
├── faqs.html
├── about.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── logo.svg
    ├── hero.jpg
    └── ...
```
