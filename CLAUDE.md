# CLAUDE.md — Portfolio Site

## Project
Personal portfolio/resume site. Static output only (Astro → GitHub Pages).
No backend, no databases, no secrets. Priority #1: personalization —
this site must feel handmade by Dante, never templated.

## Stack
- Astro, static build, deployed via GitHub Actions to GitHub Pages
- All site content lives in `src/data/site.ts` — components render from it.
  New project = data edit only, no redesign.

## Aesthetic — "Sunset Builder" (do not deviate)
- Palette: Sunbleached #FBF0E2 · Haze #EFE0C9 · Driftwood #2A2320 ·
  Sunset #F2683C · Surf #2F8F86 · Wine #7A2E43
- Fonts: Bricolage Grotesque (display) · DM Sans (body) · Space Mono (utility)
- Warm skin, tight hierarchy, generous space, restrained motion

## Component naming
PascalCase, universal names: HeroSection, ProjectCard, TickerDivider, etc.

## Git rules
- Commit format: `type: description` (feat/style/content/fix/chore)
- Commit + push automatically per completed working component
- Never push a broken build
