# MOSAIC prototype source

This archive contains the complete source for the current MOSAIC browser prototype.

## Run it

Open `index.html` in a modern browser. No package install or build step is required.

## What is included

- Onboarding and editable personal profile
- Opportunity discovery and explainable matching using the prototype's included sample records
- A personal growth roadmap with progress tracking
- Profile, identity/portfolio, resume-draft and student-application support
- Export and reset controls for profile data

The prototype is a self-contained front end. Profile state is stored in that browser's `localStorage`; it does not currently include a server, shared database, authentication, or live opportunity-feed integrations. The optional Google Fonts import falls back to system fonts if network access is unavailable.

## Files

- `index.html` — app markup, styles, and JavaScript source
