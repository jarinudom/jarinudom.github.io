# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a simple static personal website for Jarin Udom hosted on GitHub Pages. The repository contains a single HTML file that serves as a personal homepage showcasing professional background and links to social media and business.

## Repository Structure

```
jarinudom.com/
├── index.html          # Main homepage file with embedded CSS
├── .claude/            # Claude Code configuration
│   └── settings.local.json
└── .git/              # Git repository metadata
```

## Architecture

This is a minimal static website with:
- **Single HTML file**: Contains all HTML structure, CSS styling, and content
- **Embedded CSS**: All styles are contained within `<style>` tags in the HTML head
- **Static deployment**: Designed for direct hosting on GitHub Pages
- **Responsive design**: Uses flexbox layout with mobile-friendly viewport meta tag

## Development Workflow

### Local Development
- No build process required - directly edit `index.html`
- Open `index.html` in browser to preview changes
- No dependencies or package management needed

### Deployment
- Repository is connected to GitHub Pages via `jarinudom.github.io` repository
- Changes pushed to main branch are automatically deployed
- Remote: `git@github.com:jarinudom/jarinudom.github.io.git`

### Common Git Commands
```bash
git add index.html
git commit -m "Update homepage content"
git push origin main
```

## Code Structure

### Content Sections
- **Header**: Name and welcome message
- **Background**: Professional history (Software Development → Cybersecurity Sales → Game Shop Owner)
- **Links**: Social media and business connections (LinkedIn, Twitter, Bards & Cards)

### CSS Architecture
- Single stylesheet embedded in HTML head
- Uses CSS Grid/Flexbox for centering and layout
- Color scheme: Blue (#0056b3, #007bff) on white/light gray background
- Responsive design with max-width container

## File Permissions
The `.claude/settings.local.json` file contains specific permissions for Claude Code operations, allowing bash commands for file finding and listing.