# Sarayu Marri — My Sorceress's Grimoire

> **Status:** this is still a work in progress! I plan to keep tweaking it after submitting — see Future Improvements below for what's next.

## Project Description
A single-page responsive landing page built to match the dark-academia "grimoire" design language of my real portfolio (sarayu.dev) — leather-bound frame, torn parchment pages, tarot card skills deck, quest-style project cards, and wax-seal contact section.

## Intended User or Player
A recruiter, professor, or fellow student browsing my portfolio who wants a fast, memorable overview of who I am, what I've built, and how to reach me — while feeling the same design identity as my full site.

## User / Player Goal
Get oriented on my background, see real project and experience details without embellishment, and know how to get in touch or visit the full site.

## Inspiration Interfaces
- **My own sarayu.dev** — this page reuses the exact color tokens, typefaces, and component patterns (torn edges, tarot cards, quest cards, wax seals, tickets) from my real site so the two feel like the same product.
- **Persona 5 UI** — sharp diagonal cuts and bold accent color blocking, referenced in the CTA button shapes (clipped parallelogram edges).
- **Physical scrapbooks / tarot decks** — washi tape, polaroid corners, and the flip-card mechanic for the skills section.

## Design Choices
- **Layout:** A vertical single-page scroll through leather-framed "pages" (intro, Chronicle, Experience, Spells/Projects, Arcana, Achievements, Summon/Contact), each with stitched borders, corner rivets, and torn top/bottom edges to read as physical journal pages.
- **Color:** Leather browns (`#2A1508`, `#3D2010`, `#1A0C04`), parchment (`#F0E2C4`, `#E8D5A8`), gold accents (`#C9A84C`, `#8B6914`), and purple as the "magic" accent (`#7F77DD`, `#534AB7`) — pulled directly from my site's token system.
- **Typography:** Cinzel for headings and labels (formal, engraved feel), Cormorant Garamond for body copy, Caveat for handwritten annotations and tags.
- **Visual hierarchy:** Section eyebrows in Caveat, all-caps Cinzel section titles, and italic Cormorant Garamond subtitles establish a consistent three-tier heading rhythm across every section.
- **Feedback states:** Nav tabs highlight on hover/focus, tarot cards flip on hover (desktop) and on tap/click (touch — via a checkbox toggle so it works without JavaScript), project/contact links change color and background on hover/focus, all interactive elements have a visible focus ring for keyboard navigation.
- **Responsive design:** Below 720px, the experience and project grids collapse to a single column, the nav wraps, and the hero stacks the photo above the text.

## Technologies Used
- HTML
- CSS
- GitHub Pages

## Credits
- Fonts: Cinzel, Cormorant Garamond, Caveat — all via Google Fonts.
- Portrait photo: personal photo by the author, cropped for the polaroid frame.
- Design language (colors, torn-edge/tarot-card/quest-card/wax-seal patterns): adapted from the author's own sarayu.dev.
- No other tutorials, templates, or third-party code were used.

## Future Improvements
- **Hand-draw the scrapbook illustrations.** The tarot card symbols in the Arcana section are emoji placeholders right now (marked with `TODO (illustration swap)` comments in `index.html`) — I want to replace them with my own hand-drawn icons, along with the pressed-flower doodle on the photo and the leaf/gem hero background.
- Wire up the "Download Resume" button to an actual PDF (marked with a `TODO (swap link)` comment).
- Drop in real screenshots for each project card instead of the solid-color placeholders (also marked with `TODO` comments).
- Add the dark/light mode toggle from the full site.
