# MH14 Ventures Ltd website

A local static website for MH14 Ventures Ltd.

## How to run locally

Option 1: open directly
- Open `index.html` in your browser.

Option 2: run a local server
```bash
cd mh14-ventures-site
python -m http.server 8080
```
Then visit `http://localhost:8080`.

## Project structure

```text
mh14-ventures-site/
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── mh14-mark.svg
│   └── favicon.svg
└── README.md
```

## Notes

- The old MH14 plate-style hero image/card has been removed.
- The design now uses a text-led premium editorial layout with no remote images.
- Replace `hello@mh14ventures.com` in `index.html` with the final company email address before deployment.
- For Cloudflare Pages, no build command is required because this is a static HTML/CSS/JS site.
