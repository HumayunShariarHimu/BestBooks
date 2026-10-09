# BestBooks — Premium GitHub Pages Refresh

## Implementation
- Preserve the complete existing `BOOKS` dataset exactly; no story or book title is removed.
- Keep the project dependency-free and GitHub Pages compatible with a single static `index.html`.
- Add client-side search, language filtering, author filtering, sorting, favorites stored in `localStorage`, theme preference, random pick, copy/share actions, and Google/PDF quick links.
- Add semantic layout, responsive behavior, accessible controls, keyboard shortcuts, empty states, and a mobile-friendly bottom action bar.
- Maintain a route manifest at `public/manus-routes.json` for the root GitHub Pages route.

## Design
- **Design movement:** editorial digital library / dark luxury reading room.
- **Core principles:** quiet hierarchy, tactile surfaces, purposeful motion, generous breathing room.
- **Color philosophy:** ink navy and warm ivory create a calm reading environment; saffron is the ownable highlight for discovery and bookmarks.
- **Layout paradigm:** asymmetric editorial hero followed by a focused library workspace, rather than a generic centered grid.
- **Signature elements:** saffron bookmark mark, oversized Bengali editorial headline, glass-like stat rail.
- **Interaction philosophy:** every action gives immediate visual feedback; saved books persist locally and are easy to recover.
- **Animation:** subtle entrance fade/slide, hover lift, and reduced-motion fallback; no distracting loops.
- **Typography:** Noto Serif Bengali for editorial display and Hind Siliguri/Inter for interface text.
- **Brand essence:** a thoughtful, searchable Bengali-first reading shelf for curious readers. Personality: curated, warm, quietly premium.
- **Brand voice:** clear, literary, useful. Example: “আজ কোন পাতায় যাবেন?” and “আপনার নিজের পাঠের তাক।”
- **Wordmark:** a bookmark-shaped amber glyph paired with the BestBooks wordmark.
- **Signature brand color:** amber saffron `#E5A84B`.

## Project structure
- `index.html`: complete static application and preserved book catalog.
- `public/manus-routes.json`: GitHub Pages route declaration.
- `README.md`: project overview, feature list, usage and publishing notes.
