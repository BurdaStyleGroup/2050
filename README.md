# 2050 Legal Pages Recovery

## Project Purpose

This project restores two legally required pages that were removed from the original 2050 website:

- `Impressum`
- `Datenschutz`

The pages were initially recovered from the Wayback Machine. The archived output contained injected replay scripts, toolbar code, and rewritten URLs that caused CORS and runtime issues when hosted statically.  
This repository provides cleaned, deployable static versions for Cloudflare Pages.

## What Is Included

- `impressum.html`  
  Clean static Impressum page with restored content and navigation.

- `datenschutz.html`  
  Clean static Datenschutz page with restored content and navigation.

- `images/2050-logo.svg`  
  Logo asset used in the navbar.

- `_next/static/css/dce953b3f607c812.css`  
  Existing stylesheet artifact from the previous site export.

## Deployment Target

The project is intended for static hosting on **Cloudflare Pages**.  
After deployment, legal pages are accessible at:

- `/impressum.html`
- `/datenschutz.html`

