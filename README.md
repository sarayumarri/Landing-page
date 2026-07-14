# Sarayu Marri — My Sorceress's Grimoire

> **Heads up:** this is still a work in progress! I'm planning to keep tweaking it after I submit, so check out Future Improvements below for what's next on my list.

## Project Description
A single-page landing page styled after the dark-academia "grimoire" look of my real portfolio (sarayu.dev). Think leather-bound frame, torn parchment pages, a flippable tarot card skills deck, quest-style project cards, and a wax-seal contact section.

## Intended User or Player
A recruiter, professor, or fellow student who's checking out my portfolio and wants a quick, memorable sense of who I am, what I've built, and how to reach me, without it feeling like a totally different site from my main one.

## User / Player Goal
Get a feel for my background, see real project and experience details (no fluff or exaggeration), and know how to get in touch or click through to the full site.

## Inspiration Interfaces
- **My own sarayu.dev**: I pulled the exact colors, fonts, and components (torn edges, tarot cards, quest cards, wax seals, tickets) straight from my real site so this page feels like part of the same world instead of a knockoff.
- **Persona 5's UI**: I borrowed the sharp diagonal cuts and bold color blocking for the CTA button shapes (the clipped parallelogram edges).
- **Physical scrapbooks and tarot decks**: washi tape, polaroid corners, and the flip-card mechanic in the skills section all came from wanting it to feel handmade rather than templated.

## Design Choices
- **Layout:** One long scroll through leather-framed "pages": Hero, Origins, Quests, Archive, Arcana, and Summon, each with torn top and bottom edges so it reads like turning pages in a journal.
- **Color:** Leather browns (`#2A1508`, `#3D2010`, `#1A0C04`), parchment (`#F0E2C4`, `#E8D5A8`), gold accents (`#C9A84C`, `#8B6914`), and purple as the "magic" color (`#7F77DD`, `#534AB7`), all taken directly from my site's color system.
- **Typography:** Cinzel for headings (it has that formal, engraved look), Cormorant Garamond for body text, and Caveat for the handwritten-style tags and notes.
- **Visual hierarchy:** Every section follows the same rhythm: a small Caveat eyebrow line, an all-caps Cinzel title, and an italic Cormorant Garamond subtitle, so the page feels consistent even though there's a lot going on.
- **Feedback states:** Nav links highlight on hover/focus, tarot cards flip on hover on desktop and on tap on mobile (done with a hidden checkbox trick, so no JavaScript needed), and every link and card has a visible focus outline for keyboard users.
- **Responsive design:** Below 720px, the experience and project grids drop from two columns to one, the nav wraps, and the hero stacks the photo above the text instead of side by side.

## Technologies Used
- HTML
- CSS
- GitHub Pages

## Credits
- Fonts: Cinzel, Cormorant Garamond, and Caveat, all from Google Fonts.
- The portrait photo is my own.
- The color palette and the torn-edge/tarot-card/quest-card/wax-seal look are adapted from my own sarayu.dev, not copied from anyone else.
- Everything else (layout, icons, code) is original. No templates or tutorials used.

## Future Improvements
- **Hand-draw the scrapbook illustrations.** Right now the tarot card icons in the Arcana section are simple line-art SVGs standing in for the real thing (look for `TODO (illustration swap)` comments in `index.html`). I want to go back and hand-draw those, plus the pressed-flower doodle on the photo and the leaf/gem hero background.
- Hook up the "Download Resume" button to an actual PDF (there's a `TODO (swap link)` comment marking where).
- Swap in real screenshots for each project card instead of the solid-color placeholders (also marked with `TODO` comments).
- Maybe bring over the dark/light mode toggle from the full site.
