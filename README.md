# Varun Mathur — Portfolio

A single-page portfolio site built to introduce me, showcase my experience in AI/ML engineering, and make it easy for recruiters to reach out.

**Live site:** `https://dudefr0mmars.github.io` *(once GitHub Pages is enabled — see below)*

## What's on it

- **Hero** — quick intro, plus one-click resume download and email
- **About** — summary of my work at Accenture with key impact metrics
- **Experience** — timeline of my roles at Accenture and my internship at Samsung R&D
- **Leadership** — highlights from mentoring and driving GenAI initiatives
- **Skills** — languages, AI/ML frameworks, backend & cloud, databases & engineering practices
- **Certifications** — Microsoft and Claude certifications
- **Education** — B.Tech from Vellore Institute of Technology
- **Contact** — direct links to email, phone, LinkedIn, and GitHub, plus another resume download

## Tech

Plain HTML, CSS, and vanilla JavaScript — no framework, no build step, no dependencies. Everything (styles, icons, scroll animations) lives in `index.html`. Icons are inline SVG so the page has zero external requests.

## Files

```
index.html                    the entire site
Varun-Mathur-Resume.pdf       resume, linked from the site's download buttons
```

## Running it locally

Just open `index.html` in a browser — no server required. For live-reload while editing, any static server works, e.g.:

```
python3 -m http.server
```

## Deploying (free, via GitHub Pages)

1. Push this repo to GitHub as a **public** repo (GitHub Pages on the free plan requires public repos). Name it `dudefr0mmars.github.io` to get the root URL `https://dudefr0mmars.github.io`, or use any other name to get `https://dudefr0mmars.github.io/repo-name`.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. The site goes live at the URL GitHub shows, and updates automatically a minute or two after every push.

## Updating content

All copy lives directly in `index.html`. Each section has an `id` (`about`, `experience`, `skills`, `certifications`, `education`, `contact`) — search for it to find the section you want to edit. To swap in a newer resume, replace `Varun-Mathur-Resume.pdf` with a file of the same name (or update the `href` in the download buttons if you rename it).