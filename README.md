StaticPWA
=========

A tiny static website with three pages (Home, About, Contact) using Bootstrap via CDN.

How to use
---------

Open `index.html` directly in a browser, or serve the folder with a simple local server for correct behaviour of relative links and service workers:

For example (Python 3):

```bash
# from the repository root
cd staticpwa
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Files
-----

- `index.html` — Home page
- `about.html` — About page
- `contact.html` — Contact page (demo form)

Notes
-----

This is intentionally minimal. You can extend it with a service worker, manifest, or additional styling.