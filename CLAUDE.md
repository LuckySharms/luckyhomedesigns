# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Lucky Home Designs — a GitHub Pages site at `luckyhomedesigns.com`, hosted via GitHub Pages with a custom domain.

## Repository Structure

```
├── CNAME            # Custom domain config for GitHub Pages (luckyhomedesigns.com)
├── index.html       # Landing page — presents the app as a Pinterest content manager
├── privacy.html     # Privacy policy covering Pinterest API data usage
└── README.md
```

This is a static site with no build step. Files are served directly by GitHub Pages.

## Deployment

- Hosted on GitHub Pages (deploy from `main` branch, root folder)
- Custom domain: `luckyhomedesigns.com`
- DNS: 4 A records pointing to GitHub Pages IPs + CNAME `www` → `luckysharms.github.io.`
- HTTPS enforced via GitHub Pages

## Key Details

- Brand name: **Lucky Home Designs**
- Contact email: `hello@luckyhomedesigns.com`
- Privacy policy URL: `https://luckyhomedesigns.com/privacy`
- GitHub Pages serves `privacy.html` at both `/privacy.html` and `/privacy`
- The CNAME file must contain exactly `luckyhomedesigns.com` with no protocol prefix
