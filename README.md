# gustavofnovoa.com

Personal research website. Plain HTML/CSS — no build step, no framework.
GitHub Pages serves these files directly.

## Files

| File | What it is |
|------|-----------|
| `index.html` | Home page (bio, photo, contact links) |
| `research.html` | Publications, working papers, works in progress |
| `assets/css/style.css` | All styling (colors, fonts, layout) |
| `assets/img/profile.svg` | Placeholder photo — replace with your own |
| `assets/cv.pdf` | Your CV (the "CV" nav link opens this) |
| `CNAME` | Custom domain (`www.gustavofnovoa.com`) |

## How to edit

- **Bio / contact:** edit the text in `index.html`.
- **Add a paper:** in `research.html`, copy a `<li>...</li>` line inside the
  relevant section (Publications / Working Papers / Works in Progress) and edit it.
- **Add your photo:** save it as `assets/img/profile.jpg`, then change the
  `src` in `index.html` from `assets/img/profile.svg` to `assets/img/profile.jpg`.
- **Add your CV:** put the PDF at `assets/cv.pdf`.
- **Change colors/fonts:** edit the variables at the top of `assets/css/style.css`.

## Preview locally

Just open `index.html` in a browser. (Or run `python3 -m http.server` in this
folder and visit http://localhost:8000.)

## Publish

Commit and push to the `main` branch. GitHub Pages redeploys automatically.
