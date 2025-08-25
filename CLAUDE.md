# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal portfolio website for "Only Humans Group" - a single-page HTML website showcasing data science work, projects, and professional experience. The site is designed for GitHub Pages deployment.

## Architecture

- **Single-file architecture**: The entire website is contained in `index.html`
- **Self-contained styling**: All CSS is embedded in a `<style>` tag within the HTML
- **Vanilla JavaScript**: Minimal JavaScript for year updates and accessibility features
- **Static site**: No build process or dependencies required

## Key Features

- Responsive design with CSS Grid and Flexbox
- Dark/light mode support using CSS `prefers-color-scheme`
- Sticky navigation with backdrop blur
- Structured data (JSON-LD) for SEO
- Accessibility features (skip links, focus management, semantic HTML)

## Development Approach

- **Direct editing**: Make changes directly to `index.html`
- **Testing**: Open the file in a browser to preview changes
- **Deployment**: Push changes to GitHub - the site is served via GitHub Pages

## Content Sections

The website includes:
- Hero section with introduction
- About section
- Projects showcase (3-column grid)
- Writing/blog posts (2-column grid) 
- Experience timeline
- Education cards
- Contact information

## Styling System

- CSS custom properties for theming
- Utility classes: `.container`, `.card`, `.btn`, `.grid`, `.pill`, `.chip`
- Responsive breakpoints at 900px
- Design system with consistent spacing and colors