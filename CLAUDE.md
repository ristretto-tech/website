# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Ristretto Technologies, a financial technology company specializing in high-frequency market making and advanced trading strategies. The website is designed as a simple, single-page landing page.

## Architecture

- **Static HTML Site**: Single-page website with embedded CSS styling
- **Deployment**: GitHub Pages (configured via CNAME file pointing to ristretto.tech)
- **Structure**: Minimal structure with only `index.html` and `CNAME` files

## Key Files

- `index.html`: Main landing page with embedded styles
- `CNAME`: GitHub Pages domain configuration for ristretto.tech

## Development Approach

This is a static website with no build process, package.json, or development dependencies. Changes are made directly to the HTML file and deployed via git commits to the master branch.

## Styling Architecture

- Embedded CSS within `index.html`
- Uses Google Fonts (Roboto)
- Dark theme with gradient backgrounds
- Responsive design with mobile breakpoints at 600px
- Flexbox layout for vertical centering and footer positioning

## Contact Information

- Business email: info@ristretto.tech (configured in footer)