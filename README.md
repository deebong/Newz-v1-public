# Newz.in — Public Demo

Live demo: open `index.html` (the tool) or `demo.html` (a sample news page).

## What is this?

This repository contains **only generated static files** — plain HTML, CSS and
JavaScript. It is published automatically by a CI pipeline from a private
source repository. Nothing here is edited by hand; every file is regenerated
and smoke-tested on each release.

- `index.html` — the Newz.in tool as one self-contained file. Pick news
  sources, choose a template, preview live, export your own static site.
- `demo.html` — a sample news page showing what the tool produces.
- `version.json` — build stamp for this release.

Build: `b245eaf` · `2026-10-25T22:07:20.178Z`

## How it works (no backend)

Browsers block direct cross-origin feed fetching (CORS), so headlines load
through a configurable proxy. This demo uses a public relay proxy that needs
no signup. Inside the tool (Design → Advanced) you can point it at your own
free Cloudflare Worker instead — the Worker source ships with every export.

## Rights & responsibilities

Headlines, summaries and articles belong to the **respective publishers**.
These pages show them with attribution and links back to the originals, for
**personal, non-commercial reading**. Check each source's terms before wider
redistribution, and always keep attribution and source links intact. Feeds can
change or disappear without notice; if one section errors, the rest keeps
working.
