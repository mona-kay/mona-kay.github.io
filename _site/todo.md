# Portfolio Revamp Plan

## Design Direction
**Aesthetic**: Extreme minimalism, editorial. Think: a well-designed book interior or a Swiss design poster. Restrained, precise, confident. The kind of design where every pixel of whitespace is intentional.

**Key Differentiator**: The site should feel like opening a beautifully typeset book -- quiet authority, nothing wasted. Typography does all the heavy lifting. No decorative elements, no gradients, no icons. Just type, space, and structure.

**Typography**: Replace Noto Sans with a distinctive serif/sans pairing:
- Display/headings: **Instrument Serif** (Google Fonts) -- elegant, editorial, distinctive
- Body: **DM Sans** (Google Fonts) -- clean geometric sans, excellent readability, more character than generic sans-serifs

**Color palette**: Near-monochrome with one warm accent
- Background: `#FAFAF8` (warm off-white)
- Primary text: `#1A1A1A` (near-black)
- Secondary text: `#6B6B6B` (warm gray)
- Accent: `#C45D3E` (muted terracotta -- warm, sophisticated, not corporate blue)
- Dividers: `#E8E6E2` (warm light gray)

## Tasks

- [x] **1. Update `_config.yml`** -- Add a description tagline, update title formatting
- [x] **2. Rewrite `_layouts/default.html`** -- Restructure layout for a single-column, editorial feel with refined navigation. Add Google Fonts links. Add subtle page-load animation.
- [x] **3. Rewrite `_sass/jekyll-theme-minimal.scss`** -- Complete CSS overhaul: new typography, new color palette, refined spacing, editorial layout. Minimal animations (fade-in on load). Responsive design.
- [x] **4. Rewrite `index.md`** -- Restructure homepage content to better convey expertise. Surface key credentials (book, talks, courses) on the homepage.
- [x] **5. Rewrite `portfolio.md`** -- Better structure and visual hierarchy for portfolio items. Clean section formatting.
- [x] **6. Rewrite `consulting.md`** -- Sharpen consulting page copy and structure.
- [x] **7. Update `assets/css/style.scss`** -- Added rouge-github import to the chain.
- [x] **8. Add review to `completed_tasks.md`** -- Summary of all changes made.
