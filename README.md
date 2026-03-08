# Arora AI Landing Page

A clean, responsive landing page for Arora AI — an AI automation agency.

## Run Locally

Open `index.html` directly in a browser:

```bash
open index.html
```

Or serve with any static file server:

```bash
# Python
python3 -m http.server 8000

# Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Structure

```
landing-page/
├── index.html    # Single-page HTML
├── styles.css    # All styles (dark theme, responsive)
└── README.md     # This file
```

## Features

- Dark theme with indigo (#6366f1) accent
- Responsive: tested at 375px (mobile) and 1024px (tablet/desktop)
- Sections: Hero, Services, About, Contact/CTA
- Fixed navbar with backdrop blur
- No JavaScript dependencies
- No build step required
