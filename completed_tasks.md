# Review: Portfolio Revamp

## Summary

Redesigned the portfolio site with an editorial minimalist aesthetic. The site now uses distinctive typography, a warm monochrome color palette, and a centered single-column layout.

## Changes Made

### Design System
- **Typography**: Replaced Noto Sans with Instrument Serif (headings) + DM Sans (body) via Google Fonts CDN
- **Color palette**: Shifted from gray/blue to warm near-monochrome with terracotta accent (#C45D3E)
- **Layout**: Moved from fixed two-column sidebar to centered single-column (640px max-width)
- **Animation**: Added a single subtle fade-up on page load

### Files Changed

| File | Change |
|------|--------|
| `_config.yml` | Updated title to "Mona Khalil", uncommented and updated description tagline |
| `_layouts/default.html` | Complete rewrite: single-column layout, top nav (Home/Portfolio/Consulting), hero section with photo + name on homepage only, proper footer |
| `_sass/jekyll-theme-minimal.scss` | Complete rewrite: new typography, colors, spacing, nav styles, hero styles, list styles, responsive breakpoints, fade-in animation |
| `assets/css/style.scss` | Added rouge-github import for syntax highlighting |
| `index.md` | Restructured: intro paragraph, then Book/Selected Talks/Courses sections, then links at bottom |
| `portfolio.md` | Restructured: cleaner section formatting, renamed "Articles" to "Writing", removed redundant [Home] link (now in nav) |
| `consulting.md` | Tightened copy, cleaner structure, removed redundant [Home] link |

### Design Decisions
- Serif headings create editorial authority; sans-serif body maintains readability
- Terracotta accent is warm and distinctive vs. generic corporate blue
- List items use subtle bottom borders instead of bullet points for a cleaner look
- Navigation is minimal uppercase text links -- no underlines, no icons
- Profile photo gets a slight desaturation filter to match the muted palette
- Footer uses a short 40px line as a subtle section divider
