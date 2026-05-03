# ACDL Website

This repository contains the built/deployed version of the ACDL (Agentic Context Description Language) website.

## Source

The source files and build scripts are maintained in the main [ACDL repository](https://github.com/yourusername/ACDL).

## Deployment

This repo is automatically updated by running the deploy script from the main ACDL repository:

```bash
# From the ACDL repository
node scripts/deploy-website.js
```

## Local Preview

To preview locally, serve the files with any static server:

```bash
npx serve .
# or
python -m http.server 8000
```

Then open http://localhost:8000 (or the port shown).
