# CLAUDE.md

## Project Overview
Research dashboard for designing a privatized individualized educational academy (grades 6-12). This is a living research tool, not a production app.

## Architecture
- Single-page HTML dashboard at `src/index.html`
- Chart.js loaded via CDN for data visualization
- No build system — static files only (for now)
- Fonts: DM Serif Display, DM Sans, JetBrains Mono via Google Fonts

## Design System
- Dark theme with amber (#e8a838) as primary accent
- School color coding: Alpha=blue, Acton=teal, HTH=rose, Khan=violet, Micro=amber
- Typography: DM Serif Display for headings, DM Sans for body, JetBrains Mono for labels
- Cards with subtle borders (rgba(255,255,255,0.06)) and 16px border-radius

## Conventions
- Keep all dashboard code in a single HTML file unless complexity demands splitting
- Chart.js is the charting library — do not introduce additional chart libraries
- Data should be easy to update (stored as JS objects/arrays, not hardcoded in chart configs)
- Maintain the 5-tab navigation structure (Overview, Comparison, Pros & Cons, Features, Blueprint)

## Content Context
- Five school models: Alpha School, Acton Academy, High Tech High, Khan Lab School, Microschool
- Three curriculum pillars: Academic Core, Applied Studios, Human Development
- Seven educational methodologies: Mastery-Based, Learner-Driven, PBL, Adaptive/AI, Socratic, Microschool, Hybrid
- Target: PA (Pennsylvania) regulatory environment
