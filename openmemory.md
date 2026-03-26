# CreatorVerse (creatorverse) — OpenMemory guide

## Overview

Static marketing playbook: single-page HTML slide deck (`index.html`) with stylesheet `creatorverse-playbook.css`. No bundler or server-side code.

## Architecture

- **Entry:** `index.html` (slides in `#slides`, keyboard navigation in-page script).
- **Styles:** `creatorverse-playbook.css` (Google Fonts `@import`, CSS variables, Syne / Space Mono / Unbounded).
- **Deploy:** Vercel static hosting; root = project root; see `vercel.json` and `README.md`.

## User defined namespaces

- (none yet)

## Components

- **Slide deck** — `index.html` + embedded behavior for progress and slide changes.

## Patterns

- Asset paths are relative (`creatorverse-playbook.css`) for local and Vercel parity.
