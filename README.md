# Cursor Website Clone

A desktop-first recreation of the [cursor.com](https://cursor.com) landing page using pure HTML and CSS — no JavaScript, no frameworks, no Tailwind.

---

## Sections Recreated

| # | Section | Status |
|---|---------|--------|
| 1 | Top Navigation Bar | ✅ |
| 2 | Hero Section | ✅ |
| 3 | Trusted By / Logos | ✅ |
| 4 | Feature Sections (3 blocks, alternating) | ✅ |
| 5 | Feature Cards Grid | ✅ |
| 6 | Testimonials | ✅ |
| 7 | Use Cases / Stories | ✅ |
| 8 | Changelog / Updates | ✅ |
| 9 | Team / About | ✅ |
| 10 | Final CTA | ✅ |
| 11 | Footer (multi-column) | ✅ |

---

## Fonts Used

- **Primary Font:** [Geist](https://fonts.google.com/specimen/Geist) — loaded via Google Fonts
- **Monospace Font (IDE mockup):** SF Mono / Fira Code / Consolas (system fallbacks)
- **Fallback stack:** `-apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif`

Cursor's website uses Geist (designed by Vercel), which closely matches the original design.

---

## Color Palette

| Role | Value | Usage |
|------|-------|-------|
| Background | `#0a0a0a` | Page background |
| Surface | `#111111` / `#141414` | Cards, panels |
| Border | `#1f1f1f` / `#2a2a2a` | Dividers, card borders |
| Text Primary | `#ffffff` | Headings |
| Text Secondary | `#999` / `#aaa` | Body copy |
| Text Muted | `#666` / `#555` | Captions, footer links |
| Accent Primary | `#ffffff` | Primary CTA buttons |
| Accent Green | `#4ade80` | Checkmarks, "New" tags |
| Accent Blue | `#60a5fa` | Active states, "Improvement" tags |
| Code keyword | `#c586c0` | Purple — keywords |
| Code function | `#dcdcaa` | Yellow — function names |
| Code string | `#ce9178` | Orange — strings |
| Code variable | `#9cdcfe` | Blue — variables |
| Code comment | `#6a9955` | Green — comments |

---

## Key Design Decisions

- **Desktop-only:** Fixed `min-width: 1280px` on body, max container width `1200px`
- **Glassmorphism nav:** `backdrop-filter: blur(12px)` with semi-transparent background
- **IDE mockup:** Pure HTML/CSS — no images needed. Simulates VS Code dark theme
- **Gradient headings:** `background-clip: text` trick for the fade effect on hero and final CTA titles
- **No animations:** Static, per assignment constraints
- **Semantic HTML:** `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` used throughout

---

## File Structure

```
cursor-clone/
├── index.html    — all 11 sections
├── style.css     — all styles (~650 lines)
└── README.md     — this file
```

---

## How to Run

Simply open `index.html` in any modern browser. No build step required.

```bash
open index.html
# or
python3 -m http.server 8000
```

---

## Constraints Followed

- ✅ HTML + CSS only
- ✅ No JavaScript
- ✅ No Tailwind CSS
- ✅ No animations
- ✅ No responsiveness (desktop-only)
- ✅ Fonts and colors matched to original
- ✅ Semantic HTML structure
