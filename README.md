# prjct-trckr · RaFund / RafeTech

> A project showcase and investor-facing web presence for **RaFund** — the climate finance vehicle founded by Chrispine Sibale, Blantyre, Malawi. Built and maintained by **RafeTech**.

---

## What This Is

This is a single-page HTML/CSS website that serves as:
- The **public face of RaFund** — showcasing funded projects, investment thesis, and market data
- A **contact gateway** for investors, InsurTech partners, NGOs, and development finance institutions
- A **reusable template** for future RaFund and RafeTech project pages

The site is intentionally minimal, data-forward, and institutional in tone — it is not a startup landing page. Every design decision reflects the seriousness of climate finance infrastructure in Sub-Saharan Africa.

---

## File Structure

```
prjct-trckr/
├── index.html          # Single-page site — all sections live here
├── assets/
│   ├── css/
│   │   └── style.css   # All styles — do not inline or split
│   └── media/
│       └── background.PNG
```

---

## Sections (in order — do not reorder)

| # | Section ID | Purpose |
|---|---|---|
| 1 | `#hero` | Founder intro, key stats, active build badge |
| 2 | `#about` | Mission, background, four technology pillars |
| 3 | `#market` | Market context with sourced data points |
| 4 | `#projects` | Cards for each RaFund-funded project |
| 5 | `#thesis` | Five-point investment thesis |
| 6 | `#contact` | Contact form + direct channels |

---

## 🤖 LLM Instructions — Read Before Editing

If you are an AI assistant helping to edit, extend, or clone this project, follow these rules without exception:

### ✅ Always Preserve

**Visual Style**
- Dark background aesthetic — `#0a0a0a` base, never switch to light mode
- Muted, high-contrast typography — white/off-white on dark
- Minimal UI — no gradients, no drop shadows, no rounded cards unless already present
- Subtle `reveal` scroll animations (intersection observer, already implemented)

**Typography — Do Not Change These Fonts**
- Headings: `Cormorant Garamond` (serif, italic for emphasis words)
- Body / UI: `DM Sans` (clean, modern sans)
- Code / data labels: `DM Mono`
- All three are loaded via Google Fonts in `<head>` — keep the import link intact

**Brand Tone**
- Institutional and data-driven — cite sources on all statistics
- No hype language ("revolutionary", "game-changing", "disrupting")
- Africa-specific context — always name the country, region, or partner when relevant
- Founder: Chrispine Sibale · Entity: RaFund (fund) / RafeTech (software studio)

**Color Palette — Do Not Alter**
- Background: `#0a0a0a`
- Surface/cards: `#111111` or `#141414`
- Accent (green): `#4ade80` (used sparingly — active badge, CTA hover states only)
- Text primary: `#f5f5f5`
- Text muted: `#888888` or `#666666`
- Borders: `1px solid rgba(255,255,255,0.08)`

### ❌ Never Do

- Do not change fonts or import new typefaces
- Do not introduce a light mode or white background sections
- Do not add carousels, sliders, or heavy JS libraries
- Do not remove source citations from market statistics
- Do not use placeholder copy — all text must be real, accurate content
- Do not break the single-file HTML structure (keep all content in `index.html`)

---

## Adapting This Template for a New RaFund Project

When cloning this site for a new project page:

1. Keep `style.css` as-is — only add new rules, never overwrite existing ones
2. Replace hero stats with project-specific data points (keep 3 stat cards)
3. Update the `#projects` section cards with new project details
4. Keep the `#thesis` section or replace with project-specific rationale (same 5-point format)
5. Update contact channels but keep the form structure identical
6. Change `<title>` and `nav-logo` text only — do not restructure nav

---

## Tech Stack

- **HTML5** — semantic, no framework
- **CSS3** — custom properties, grid, flexbox (no Tailwind, no Bootstrap)
- **Vanilla JS** — scroll reveal only (IntersectionObserver)
- **Google Fonts** — Cormorant Garamond, DM Sans, DM Mono
- No build tools, no bundler, no dependencies

---

## Contact / Ownership

**Chrispine Sibale** — Founder, RaFund · CEO, RafeTech  
📍 Blantyre, Malawi  
📞 +265 981 167 823  
🐙 [github.com/Raf3-Tech](https://github.com/Raf3-Tech)

© 2025–2026 Chrispine Sibale. All rights reserved.