# PRPO Project Page

Official project website for:

**Chart Deep Research in LVLMs via Parallel Relative Policy Optimization (PRPO)**

- Venue: ICLR 2026 (Accepted)
- Project page: https://prpo.github.io
- Paper (arXiv): https://arxiv.org/abs/2603.06677v1

## Repository Overview

This repository contains the static website files used for GitHub Pages deployment.

- `index.html`: main content and section structure
- `styles.css`: page styling and responsive layout
- `script.js`: reveal animation behavior
- `assets/`: figures, logos, and favicon

## Local Preview

Run a simple static server from this folder:

```bash
python3 -m http.server 8080
```

Then open: http://localhost:8080

## Deployment

This repository is deployed via GitHub Pages with custom domain:

- `prpo.github.io`

Any push to the default branch updates the live site after GitHub Pages finishes deployment.

## Coming Soon

- Training/inference code
- MCDR-Bench release and evaluation toolkit
