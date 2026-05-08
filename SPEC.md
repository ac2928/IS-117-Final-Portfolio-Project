# SPEC.md — Aspirational Portfolio Site
## Project Summary
Build a single-page aspirational professional portfolio for Aarav Chopra, an NJIT BIS student targeting AI Product Engineer roles. This is a full redesign from the previous Swiss Minimal portfolio into a dark editorial design system that communicates a forward-looking professional identity.

This is not a refinement project — it is a purposeful redesign driven by a new professional direction.

## Pages
- Single-page site (index.html) hosted under /docs for GitHub Pages

## Sections
1. Hero
2. About
3. Projects
4. AI Workflow
5. Contact / Footer

## Design System — Dark Editorial
### Layout
- Full-width sections with 48px horizontal padding
- Max-width containers where needed (1200px for grids, 900px for text)
- Vertical rhythm based on 8px scale
- CSS custom properties for all design tokens

### Typography
- Primary: Syne (headings, nav, UI labels)
- Secondary: Instrument Serif (italic accent in headings)
- Mono: DM Mono (tags, labels, code-style text)
- Max 3 font weights per family

### Color Palette
- Background: #0a0a0b
- Surface: #1e1e24
- Text: #f0ede8
- Muted: #7a7880
- Accent: #e8622a
- Accent 2: #f0a05a
- Green: #4ade99
- Blue: #60a5fa

### Components
- Buttons: rectangular, no radius, filled (primary) or ghost (secondary)
- Project cards: surface background, 1px border, accent top-bar on hover
- Skill rows: full-width bordered rows with tag chips
- Tags: monospaced, color-coded by category (orange/blue/green)
- Scroll-reveal animations on all major content blocks

## Deployment Requirements
- Static HTML/CSS/JS only
- Hosted on GitHub Pages via /docs folder
- No build system
- No frameworks

## Acceptance Criteria
### Visual
- Consistent dark color palette throughout
- All sections use design token variables
- Hover states on all interactive elements
- Smooth scroll-reveal on content as it enters viewport

### Structural
- Single-page layout
- All 5 sections present
- Code organized and readable

### Functional
- Nav links scroll to correct sections
- All project links open correct live sites in new tab
- Email hover reveal shows ac2928@njit.edu
- GitHub links point to https://github.com/ac2928
- Site loads without console errors

### Deployment
- Deploys via GitHub Pages from /docs
- README.md includes live site URL
- README.md includes project reflection

## Non-Goals
- No multi-page conversion
- No backend or database
- No framework migration
- No fake or placeholder projects

## Definition of Done
The portfolio:
- Presents a believable and intentional AI Product Engineer identity
- Showcases only real, shipped projects with working links
- Clearly communicates AI workflow and tool usage
- Is deployed, accessible, and submission-ready
