# Quality Cueing™

Placeholder marketing site for qualitycueing.com — the teacher-training arm of the [yogaudio](https://www.yogaudio.com) ecosystem, built around Megan Rader's QualityCueing™ method.

Static HTML/CSS, no build step. Pages:

- `index.html` — homepage, explains what QualityCueing™ is
- `about.html` — Megan Rader and Danae
- `courses.html` — training modules (TBD, placeholder cards)
- `contact.html` — mailto contact
- `style.css` — shared styles (white base, mustard-gold accent, Inter font)

## Local preview

Just open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deploy

Static files — works as-is on GitHub Pages, Netlify, Vercel, or any static host. No dependencies, no build process.
