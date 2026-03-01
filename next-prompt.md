---
page: library
---
The "My Flashcard Library" page for LinguaFlash. This page displays a list of all the user's flashcard sets with options to search, filter, and manage them.

**DESIGN SYSTEM (REQUIRED):**
- **Visual Theme:** Clean, Trustworthy, and Educational. Modern Academic vibe.
- **Primary Color:** Deep Academic Blue (#1e1eae) for CTAs, icons, highlights.
- **Hover Color:** Deep Night Indigo (#16168a) for hover states.
- **Background:** Soft Cloud Gray (#f6f6f8) for light mode.
- **Surface:** Pure White (#ffffff) for cards, sidebars, containers.
- **Text Main:** Onyx Text (#121217) for headlines and body.
- **Text Muted:** Slate Muted Purple (#656586) for descriptions and labels.
- **Font:** Lexend (sans-serif), bold for headers, regular for body.
- **Corners:** Generously rounded (0.75rem / rounded-2xl).
- **Shadows:** Whisper-soft diffused (shadow-sm) with subtle ring borders.
- **Buttons:** Pill-shaped or rounded, scale-up on hover, blue background with white text.
- **Primary Tailwind color:** #2020ee
- **Primary dark Tailwind color:** #1e1eae

**Page Structure:**
1. Same sticky navigation bar as index.html with "LinguaFlash" logo and links (Explore → index.html, Study Modes → study.html, Library → library.html)
2. Page header with title "My Library" and a "Create New Set" button (links to create.html)
3. A search bar and filter options (All, Recent, Favorites)
4. A grid of flashcard set cards, each showing:
   - Set title (e.g., "Academic Writing", "Business English", "TOEFL Prep")
   - Number of cards in the set
   - Last studied date
   - Progress bar showing completion percentage
   - A "Study Now" button linking to study.html
   - A "View Words" button linking to wordlist.html
5. Each card should have hover effects (slight lift, shadow increase)
6. Footer matching index.html

**Navigation links:**
- Explore → index.html
- Study Modes → study.html
- Library → library.html (current, should be highlighted)
- Create New Set → create.html
- Study Now → study.html
- View Words → wordlist.html
