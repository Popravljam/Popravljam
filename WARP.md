# WARP.md

This file provides guidance when working with code in this repository.

## Repository Overview

This is a GitHub profile README repository (username: Popravljam). The README.md file serves as the profile page displayed on the GitHub profile at https://github.com/Popravljam.

## Structure

- **README.md**: Bilingual profile page (English/Serbian) showcasing:
  - Professional background (Journalist & Trainer, OSINT & Data Exploration)
  - Featured projects (browser extensions, OSINT tools, data exploration tools)
  - Tech stack and GitHub statistics
  - Links to external projects and website

## Common Commands

### Preview Changes Locally
Since this is a profile README, changes can be previewed by:
1. Viewing the rendered markdown in your editor
2. Pushing to GitHub and viewing at https://github.com/Popravljam

### Version Control
```bash
# Stage and commit changes
git add README.md
git commit -m "Update profile: <description>"

# Push to GitHub
git push origin main
```

### Check for Markdown Issues
```bash
# Check for broken links (requires npm)
npx markdown-link-check README.md

# Validate markdown syntax
npx markdownlint-cli README.md
```

## Content Guidelines

### Profile Structure
The README maintains a bilingual format (English first, Serbian second) with consistent sections:
1. Header with name, role, and location
2. About section
3. Featured projects organized by category
4. Tech stack with badges
5. GitHub statistics

### Project Categories
- **Browser Extensions**: ORCID Chrome Extension, Publishing Date Finder
- **Data & Exploration Tools**: Jugofilm.online, Telegram Bill Tracker, Serbian Word Explorer
- **OSINT Tools**: Investigato.rs Toolbox

### Badge Format
Tech stack badges use shields.io format:
```
![Name](https://img.shields.io/badge/-Name-HEX?style=flat&logo=name&logoColor=color)
```

### Links Format
- Project links point to GitHub repositories under Popravljam organization
- Personal website: lazarcovs.com
- GitHub stats widget uses vercel app

## Key Considerations

- **Bilingual Content**: All content updates should be reflected in both English and Serbian sections
- **Link Integrity**: Ensure all project links point to valid repositories
- **Professional Tone**: Content focuses on OSINT, journalism, and research tools
- **GitHub Display**: README.md is automatically displayed on the GitHub profile page
