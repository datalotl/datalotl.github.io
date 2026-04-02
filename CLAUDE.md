# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static single-page website for **Datalotl LLC** (datalotl.com / datalotl.ai) — a consulting, education, and entertainment company. No build system, framework, or package manager.

## Architecture

- `index.html` — the entire site: markup, inline `<style>`, and inline `<script>`. No external CSS/JS files.
- `artwork/` — logo images (PNG). The site references `artwork/datalotl_trans.png`.
- The contact form composes a `mailto:info@datalotl.com` link client-side (no backend).

## Development

Open `index.html` directly in a browser; no build or serve step is needed. To preview with a local server:

```
python3 -m http.server 8000
```

## Key Details

- Brand color: `#5b6abf` (primary purple), `#1a1a2e` (dark headings).
- All styles and scripts are inline in `index.html` — there are no separate asset files to keep in sync.
