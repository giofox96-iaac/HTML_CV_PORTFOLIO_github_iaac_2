# Architecture

This document describes the architecture and structure of the Giovanni Carlo Volpe Portfolio project, based on the current codebase.

## Overview
The project is a static website built with HTML, CSS, and JavaScript. It follows a semantic HTML structure for better SEO and accessibility, with responsive design via CSS and basic interactivity via JS.

## File Structure
```
portfolio/
├── [`index.html`](index.html )          # Main HTML file with semantic structure
├── [`style.css`](style.css )           # CSS for layout, styling, and responsiveness
├── [`script.js`](script.js )           # JS for smooth scrolling and event handling
├── .gitattributes      # Git configuration for line endings
├── [`1.py`](1.py )                # Unrelated Python file (possibly test)
├── [`1.txt`](1.txt )               # Unrelated text file
├── Pictures/           # Directory for image assets
│   ├── COVER.jpeg
│   ├── GCV_PROFILE PIC.jpg
│   ├── South bronx.jpg
│   ├── the sh-rooms.jpg
│   ├── paris bercy.jpg
│   └── mubi.jpg
└── Documents/          # Documentation files
    ├── [`Documents/README.md`](Documents/README.md )
    ├── [`Documents/prompt.md`](Documents/prompt.md )
    ├── [`Documents/log.md`](Documents/log.md )
    ├── [`Documents/features.md`](Documents/features.md )
    └── [`Documents/architecture.md`](Documents/architecture.md )
```

## Technologies
- **HTML5**: Semantic markup (header, nav, main, aside, section, footer) for structure.
- **CSS3**: Flexbox for hero and main layout, Grid for project cards, media queries for responsiveness, transitions for hover effects.
- **JavaScript (ES6+)**: Event listeners for smooth scrolling and placeholders.

## Components and Interactions
- **Header**: Contains cover image (background) and hero (flex layout with profile pic and name).
- **Nav**: Flex list with links; JS adds smooth scroll to target sections.
- **Main**: Flex container with aside (left: contacts/skills) and section (right: education/work).
- **Projects**: Grid container; cards have hover scale; links trigger JS alerts.
- **Footer**: Simple text.
- **CSS Interactions**: Hover on nav links (underline), project cards (scale), and section links (underline).
- **JS Interactions**: Smooth scroll on nav clicks; alert on project link clicks.
- **Responsiveness**: Media query stacks layouts on mobile, adjusts image sizes.

## Design Principles
- Mobile-first responsive design.
- Clean, professional aesthetic with blue accents (#4a90e2).
- Modular code: Separate files for HTML, CSS, JS.
- Separation of concerns: HTML for content, CSS for presentation, JS for behavior.
- Accessibility: Alt text on images, semantic elements.