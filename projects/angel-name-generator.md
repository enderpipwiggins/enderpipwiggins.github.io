---
layout: default
title: Angel Name Generator
---

# Angel Name Generator

[View on GitHub](https://github.com/enderpipwiggins/angel-name-generator) &nbsp;|&nbsp; [Back to Portfolio](/)

---

## Overview

A full Angular single-page application that procedurally generates angel names drawn from **Hebrew**, **Christian**, **Islamic**, and **Enochian** traditions. Each result surfaces the root word, its meaning, domain classification, and the suffix's tradition of origin — making it useful for worldbuilding, creative writing, or just exploration.

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Angular 21 |
| Language | TypeScript |
| Build | Angular CLI / npm |
| Testing | Karma / Jasmine |

## Features

- **Tradition selector** — filter by a specific tradition or generate across all four
- **Domain filter** — narrow results to a thematic category (celestial, nature, divine, concepts, geography, time, hidden, war, healing)
- **Suffix lock** — pin a suffix while randomizing roots
- **Batch generation** — produce 1–48 names in a single action
- **Rich result cards** — each name shows root word + meaning, domain, and suffix origin

## Tradition Suffixes

| Tradition | Suffixes |
|---|---|
| Hebrew | `-el`, `-iel`, `-on` |
| Christian | `-el`, `-iel`, `-on`, `-us` |
| Islamic | `-il`, `-ail`, bare forms |
| Enochian | `-el`, `-iel`, `-eel`, `-qiel` |

## Running Locally

```bash
# Requires Node.js 18 or 20 (LTS) and npm 9+
npm install
npm start        # dev server at localhost:4200
npm run build    # production build → dist/
npm test         # run test suite
```

The core name-generation service is framework-agnostic and can be used independently outside of Angular.
