# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal portfolio website for Michael T. Clare, hosted on GitHub Pages at mtclare.github.io. The site showcases data science and machine learning projects through a clean, responsive design.

## Architecture

The project follows a simple static website structure:

- **`index.html`** - Main landing page with personal portfolio layout, contact information, and navigation to project pages
- **Project pages** - Individual HTML files for each project showcase:
  - `thumbtack.html` - Thumbtack project details
  - `capgemini.html` - Capgemini project details  
  - `doordash.html` - DoorDash project details
  - `VideoAmp1.html` - VideoAmp project details

## Development

This is a static HTML/CSS website with no build process or dependencies. The project uses:

- Pure HTML5 with semantic markup
- CSS3 with custom properties (CSS variables) for theming
- Responsive design with mobile-first approach
- Google Fonts (Montserrat) for typography

### Design System

The site uses a consistent color scheme defined in CSS custom properties:
- Primary: `#1a5b80` (dark blue)
- Accent: `#00bfae` (teal)
- Background: `#f7f9fa` (light gray)
- Text: `#222` (dark gray)
- Muted: `#6c7a89` (medium gray)

### File Structure

All HTML files are self-contained with embedded CSS and follow the same basic structure:
- Header with name and title
- Navigation bar linking to project pages
- Main content container
- Footer with contact links

## Deployment

The site is deployed via GitHub Pages from the main branch. Any changes pushed to main will automatically deploy to the live site at mtclare.github.io.

## Project Files

The project HTML files appear to be Jupyter notebook exports converted to HTML format, containing data science project documentation and visualizations. These are large files (300KB-900KB) with embedded Bootstrap CSS and JavaScript dependencies.