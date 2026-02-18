# Shea Curran Portfolio Website

## Overview
Personal portfolio website for Shea Curran (sheacurran.xyz). A static HTML site showcasing projects, experience, photography, and contact information. Built at the intersection of AI, Web3, and consumer platforms.

## Project Architecture
- **Type**: Static HTML website (single page)
- **Structure**:
  - `index.html` - Main (and only) page with embedded CSS and JavaScript
  - `assets/photos/` - Image assets (avatar, photography gallery, etc.)
- **No build step required** - Pure HTML/CSS/JS
- **No backend** - Entirely client-side

## Running Locally
Served via Python's built-in HTTP server on port 5000:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a static site deployment with the root directory (`.`) as the public directory.
