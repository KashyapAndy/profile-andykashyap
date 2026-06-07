# profile-andykashyap

Single-file portfolio. All CSS + HTML + JS in `index.html`. No build step.

## Stack
- Vanilla HTML/CSS/JS
- Fonts: Satoshi (Fontshare CDN) — display, body, mono all unified
- Icons: Font Awesome
- Map: Leaflet.js
- Hosting: GitHub Pages

## Key files
- `index.html` — entire site
- `AnirudhKashyap_Resume.pdf` — linked as Download CV
- `img/` — profile photo, project screenshots, talk photos
- `.agents/skills/` — taste-skill, impeccable, and other design skills

## Branches
- `master` — live/production
- `typography-refresh` — DM Mono variant (archived, not merged)
- `typography-satoshi` — merged into master

## CSS tokens (top of `<style>`)
```
--font-display / --font-body / --font-mono: all 'Satoshi'
--text-xs: 0.72rem  --text-sm: 0.85rem  --text-base: 1rem
--text-md: 1.1rem   --text-lg: 1.3rem
```

## Design rules (taste-skill Section 9 — all applied)
- No em-dashes or en-dashes in visible content. Use : , . or -
- Max 3 section eyebrows (kept: My Journey, Career Timeline, AI Learning Log)
- Middle-dots: commas in prose, / in toggle hints, | in footer
- Chapter pills: `01/02/03` prefix, monochrome outline style
- Scroll events: IntersectionObserver only
- Beyond Work grid: 6-col asymmetric (not equal 3-col)
- Bold: timeline bullet metrics only, not prose

## Beyond Work grid layout
```
Row 1: Soundburst (span 4) | Conference Talks (span 2)
Row 2: BMW HUD (span 2)   | TWE Whisky (span 2) | Lifelong Learner (span 2)
Row 3: Global Footprint map (span 6)
```
Natural Polyglot card removed — languages folded into Lifelong Learner copy.

## Conventions
- Commit directly to master for fixes; use feature branches for experiments
- Always push after committing
- No framework, no npm, no build — just edit index.html
