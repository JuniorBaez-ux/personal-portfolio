# Junior Baez — Portfolio

Personal portfolio site for Junior Baez, Full-Stack .NET Developer & QA Specialist.

🔗 Live site: _add your Vercel URL here once deployed_

## About

A single-page, recruiter-facing portfolio highlighting full-stack development and QA/testing work — spanning backend architecture, frontend delivery, QA automation, and mobile development.

## Tech

- Plain HTML, CSS, and JavaScript — no build step, no dependencies
- CSS custom properties for theming
- Light/dark mode, following system preference by default with a manual toggle
- Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter), and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

## Structure

Everything lives in `index.html`, organized into clearly commented sections:

```
<!-- ===== NAV ===== -->
<!-- ===== HERO ===== -->
<!-- ===== ABOUT + STACK ===== -->
<!-- ===== PROJECTS — edit/add project cards here ===== -->
<!-- ===== EXPERIENCE TIMELINE — edit/add jobs here ===== -->
<!-- ===== CERTIFICATIONS — edit/add certs here ===== -->
<!-- ===== CONTACT ===== -->
```

To update content (a new project, a new job, a new cert), find the matching section comment and edit the markup directly — no build tools required.

## Running locally

No install needed. Just open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

## Deploying

Deployed via [Vercel](https://vercel.com):

1. Push this repo to GitHub
2. Import the repo in Vercel
3. No build settings needed — it's a static file, deploy as-is

## License

Personal project — all rights reserved.
