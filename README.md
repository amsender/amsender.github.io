# Amarjeet Kushwaha — Portfolio

A single self-contained static site. No build step, no dependencies — just upload the folder.

## Files
```
portfolio/
├── index.html      # the page
├── style.css       # all styling (light + dark themes)
├── script.js       # theme toggle, mobile menu, scroll animations
├── README.md       # this file
└── assets/
    ├── Amarjeet_Kushwaha_CV.pdf   # linked by the "Download CV" buttons
    ├── profile.jpg                # ← ADD YOUR PHOTO HERE (see below)
    └── img/                       # project result images
```

## 1. Add your photo
Drop a square-ish photo into `assets/` named exactly **`profile.jpg`**.
Until you do, the hero shows a styled **"AK"** monogram automatically — nothing breaks.

## 2. Swap in exact GitHub repo links (optional, later)
Every **"View code"** button currently points to `https://github.com/amsender`.
When you push individual repos, find & replace each `https://github.com/amsender`
in `index.html` with the exact repo URL. There is one per project (7 total).

## 3. Update the CV
The "Download CV" buttons link to `assets/Amarjeet_Kushwaha_CV.pdf`.
Replace that file (keep the same name) whenever you update your CV.

## 4. Deploy to your host
Upload the **entire `portfolio/` contents** to your web root (e.g. `public_html/`)
via your host's File Manager or FTP. Open `index.html` in a browser to preview locally first.

## Notes
- Theme follows the visitor's system setting and has a manual ☀/☾ toggle (remembered per browser).
- Fully responsive — mobile menu included.
- Fonts load from Google Fonts; the page still looks clean if they're blocked.
