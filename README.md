# Collaborative Women's Care · Brand & Website Proposal

A private review site for the Collaborative Women's Care team. It holds:

| Page | What it is |
|---|---|
| `index.html` | Welcome screen: what's inside, how to review, the decisions we need, logo downloads |
| `brand-guide.html` | The 17-page brand guide (logo, palette, fonts, website elements, collateral examples) |
| `homepage-v2.html` | **Recommended** homepage: simpler, premium, journey-first. Interactive, desktop + mobile |
| `homepage-v1.html` | First-pass homepage, kept for comparison. Desktop + mobile |

**Access phrase:** `dale` (not case-sensitive). You're asked once per browser; the **Lock** button on the welcome screen clears it.

> The phrase is a courtesy lock for a private review, not security. Anyone who has these files can read them. Don't put patient information or anything confidential in this repository.

## View it

**On your computer (no setup):** download the ZIP (GitHub: *Code › Download ZIP*), unzip it, and double-click `index.html`. Fonts load from Google Fonts, so stay online for the full look.

**As a private link (GitHub Pages):**
1. Create a **private** repository and upload these files, keeping the folder structure.
2. *Settings › Pages › Build and deployment*: Source **Deploy from a branch**, branch **main**, folder **/ (root)**.
3. Open the address GitHub shows. (Pages on a private repository needs a paid GitHub plan; on a free plan the repository must be public, and then anyone with the link can reach the site. The phrase still gates it, but it isn't real protection.)

## Using the pages

- **Brand guide:** ← → keys (or swipe) to page, **G** for all pages, **Esc** to close. A page number in the address (`brand-guide.html#9`) opens that page directly.
- **Homepages:** the **Desktop / Mobile** switch is at the top. In Version 2, try the journey tabs, the **EN · ES · RU · FR** switcher (headline and buttons only for now) and the review arrows.
- Anything in **[brackets]** is a placeholder: photos, portraits, article images.

## Structure

```
index.html            welcome + access gate
brand-guide.html      17 slides, 1920×1080, scaled to fit
homepage-v1.html      mockup, desktop 1440 + mobile 390
homepage-v2.html      mockup, desktop 1440 + mobile 390, interactive
assets/
  css/site.css        brand tokens (8 colors, 3 fonts) + shared UI
  js/gate.js          access phrase check (SHA-256, stored as a hash)
  js/dc-lite.js       tiny renderer for the mockups ({{holes}}, loops, clicks)
  img/                logo: transparent PNG, white-background JPG
```

No build step, no dependencies. Every page is plain HTML, CSS and JavaScript.

## The brand in brief

- **Logo:** the circular seal, unchanged. On navy, always inside a cream circle.
- **Colors:** Navy #1B2E4A · Sky #8BBBDA (from the logo) · Blue #285A7C · Blush #E7C6BC · Cream #FAF7F2 · White · Pale Blue #E8F2F8 · Slate #4A5561.
- **Fonts (Google Fonts):** Cormorant Garamond (headlines) · Nunito Sans (body, buttons) · Josefin Sans (small spaced labels).

## Open items

- Dr. Bertha Campo: portrait, bio and exact title
- Photography of the doctors, team and office
- Vector logo (SVG / PDF / AI) from the original designer
- Native-speaker review of the Spanish, Russian and French text before any launch

*Confidential draft · September 2026*
