# Arora AI Landing Page

**Live URL: https://nikhilarora1219.github.io/aroraai-website/**

A clean, responsive landing page for Arora AI — an AI automation agency.

## Run Locally

Open `index.html` directly in a browser:

```bash
open index.html
```

Or serve with any static file server:

```bash
python3 -m http.server 8000
npx serve .
```

## Structure

```
landing-page/
├── index.html                          # Main landing page
├── styles.css                          # All styles (dark theme, responsive)
├── blog/
│   ├── index.html                      # Blog index page
│   ├── ai-automation-guide.html        # Pillar blog post
│   ├── ai-tasks-automation.html        # Supporting blog post
│   └── arora-ai-vs-agencies.html       # Competitor comparison post
├── .github/workflows/deploy.yml        # GitHub Pages deployment
└── README.md
```

## Features

- Dark theme with indigo (#6366f1) accent
- Responsive: 3 breakpoints (desktop, 768px, 480px)
- Sections: Hero, Services, Pricing, Blog, About, Contact/CTA
- 3-tier pricing (Starter $997, Growth $3,500, Enterprise Custom)
- 3 full blog posts with SEO meta tags + blog index page
- Fixed navbar with backdrop blur
- No JavaScript dependencies
- Deployed via GitHub Pages with Actions workflow

## Deployment

Deployed automatically on push to `main` via GitHub Actions. The workflow at `.github/workflows/deploy.yml` handles static site deployment to GitHub Pages.
