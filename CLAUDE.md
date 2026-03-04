# Claude Code Mastery Guide — Project Context

## Project
A multi-page HTML guide teaching Claude Code mastery from zero to autonomous agent teams.
Target audience: A single reader with zero formal coding background who has used Claude Code to build small projects (Resy sniper, apartment dashboard, daily newsletter).

## File Structure
- index.html → Table of Contents / landing page
- level-01.html through level-XX.html → One page per level
- styles.css → Shared stylesheet (single source of truth for all styling)

## HTML & Design Rules
- Every page must link styles.css (never inline full stylesheets)
- Color scheme: tan/beige backgrounds (#FAF6F1), dark brown text (#3B2F2F), warm orange accents (#D4793A)
- Font: Inter (import from Google Fonts)
- Force light mode: include color-scheme: light only meta tag
- Include @media (prefers-color-scheme: dark) block with !important overrides
- Mobile-responsive: readable on phone screens (max-width breakpoints at 600px)
- Navigation: every level page has "← Previous | TOC | Next →" nav at top and bottom

## Content Rules
- NEVER show a code block without an explanation before AND after it
- Code blocks must have syntax highlighting via inline styles or a lightweight approach
- Highlight "high-impact" concepts with a distinct visual callout (orange left-border box)
- Each level ends with a clearly defined checkpoint project including:
  - What to build
  - Success criteria (how you know you passed)
  - Estimated time to complete
- Use analogies and mental models before technical definitions
- Cover both macOS and Windows where commands or setup differ (use tabbed or side-by-side format)
- When introducing a concept, follow this structure:
  1. Why this matters (motivation)
  2. Mental model / analogy
  3. Technical explanation
  4. Concrete example with walkthrough
  5. Common mistakes / gotchas

## Tone
- Direct, no fluff, slightly informal
- Speak to the reader as "you"
- OK to reference that the reader has already built things in Claude Code
- Don't condescend — the reader is smart but not formally trained