---
name: project-website-redesign
description: Personal website v2 redesign — branch, design system, and projects content
metadata:
  type: project
---

Redesign launched on branch `redesign/v2-animated` (May 2026).

**Why:** User wanted a cutting-edge, animated, professional redesign using the ui-ux-pro-max skill. Same content, new visual layer.

**Design system:**
- Style: Dark glassmorphism + particle mesh background
- Colors: Deep navy `#080b14`, electric blue `#3b82f6`, emerald `#10b981`
- Typography: Montserrat (display) + Inter (body)
- Tailwind CDN (no build step)

**Key animations added:**
- Canvas particle network with mouse repulsion in hero
- Magnetic custom cursor (dot + ring)
- Split-text character animation on H1
- Scroll reveal (Y, X, scale variants with stagger delays)
- 3D card tilt on project cards (mouse tracking)
- Animated gradient text on hero headline
- Skill bar fill animations (IntersectionObserver)
- Counter animation on stats
- Mouse parallax on hero floating code snippets
- Conic gradient rotating photo ring

**New section — Projects:**
- Kitchen Manager App (iOS, React Native) — pending App Store review, ready to deploy
- Web Application Vol. 1 — In Progress (React, Tailwind, JS)
- Web Application Vol. 2 — In Progress (Next.js, TypeScript)
  - Cards are placeholders; user to update names/descriptions when ready

**Files:**
- `personalWebsite.html` — development source (image paths: `./docs/Images/`)
- `docs/index.html` — GitHub Pages deployment (image paths: `./Images/`)

**How to apply:** When updating projects, add real project names/descriptions/links to the three project cards in the Projects section. Kitchen app card should get App Store link once live.
