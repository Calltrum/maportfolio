# Chidera Omeje — Portfolio Site

A dark, terminal-themed portfolio built with plain HTML/CSS/JS — showcasing automation engineering work (n8n).

## File structure

```
portfolio/
├── index.html          # Main page (all content lives here)
├── css/
│   └── style.css       # All styling
├── js/
│   └── script.js       # Interactivity (currently minimal)
└── assets/
    ├── README.txt       # This file
    └── profile.jpg       # ← your photo goes here
```

## Adding your profile photo

Drop a square image (440x440px or larger) into this `assets/` folder and name it exactly:

```
profile.jpg
```

The hero section is already wired to look for it — no code changes needed. Until it's added, the site shows a placeholder pattern in its place.

## Running it locally

No build step required. Just open `index.html` in a browser, or for live-reload while editing, run a local server from the `portfolio/` folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Still to finish

- [ ] Add `profile.jpg`
- [ ] Replace placeholder email in the contact section (`index.html`)
- [ ] Add real Upwork/Fiverr profile links (`index.html`)

## Deploying

Any static host works — GitHub Pages, Netlify, Vercel, or Cloudflare Pages. Just upload the whole `portfolio/` folder; no server-side code involved.
