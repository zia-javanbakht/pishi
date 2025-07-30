# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static website for Pishi (www.pishiapp.com) - currently serving as a temporary landing page with a "coming soon" message. The site is hosted via GitHub Pages.

## Architecture

- **Static HTML Site**: Single-page website with no build process or dependencies
- **Assets**: PNG images stored in `./pishi/` directory
- **Deployment**: GitHub Pages (configured via CNAME file pointing to www.pishiapp.com)

## Key Files

- `index.html`: Main landing page with centered image and coming soon text
- `CNAME`: GitHub Pages custom domain configuration
- `pishi/`: Directory containing image assets (numbered PNG files)

## Development

This is a static site with no build tools, package managers, or testing frameworks. Changes can be made directly to HTML/CSS and committed to deploy via GitHub Pages.

The current design uses:
- Black background
- Centered image display
- Pink (#FF93AF) "coming soon" text with Average font family
- Responsive design with flexbox layout