# Saurabh — Personal Portfolio

Next.js (App Router) + TypeScript + SCSS Modules portfolio for Saurabh,
Content Creator & Storyteller — AI Builder · Creator · Entrepreneur.

## Content source of truth

All copy comes from Saurabh's personal brand profile (provided 2026-10-25).
Facts live in one place: `data/content.ts`. Rules baked into the content:

- No invented clients, achievements, metrics, employment, years, or email.
- Sparkos is presented as a creative studio **in development** (not launched,
  working solo), tagline "Turn Ideas Into Intelligent Systems".
- The Motivational Text Reel is **reference material only**, labelled as such.
- Tools are listed neutrally under "Tools I work with" — no proficiency claims.
- KeepIt (Habit Tracker) is described only by its verified live headline,
  "Build Habits. Keep Promises."

## Design

Bold, typography-driven, editorial layout inspired by the section hierarchy
verified from the reference portfolio (oversized repeated name → "Hi!" intro →
"Things I'm good at" skills → "crafted with love." works). The reference's
motion specifics were not verifiable from research, so the animations are
Saurabh's explicitly requested effects: scroll-linked paragraph fade-out
(Framer Motion `useScroll`/`useTransform`), a CSS name marquee, heading
entrances, clip-path hero reveal, and project hover transitions — all
respecting `prefers-reduced-motion`.

## Develop

```bash
npm install
npm run dev
npm run build
npm run lint
```
