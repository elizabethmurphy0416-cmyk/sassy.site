# sassy.site

The single-page website for **Sassy & Structured** (@sassynspirit): a home for digital products, content, and the brand itself.

> *Structure for the woman who refuses to be boring about it.*

## What this is

The whole site is **one HTML file**. The CSS (styling) and JavaScript (interactivity) sit inside that file, so there's no build step, no framework, and nothing to install. Open the file in a browser and you're looking at the site.

| Piece | Where it lives |
|---|---|
| Page structure and content | HTML in the single page file |
| Styling (colors, fonts, layout) | Inline `<style>` block in the same file |
| Interactivity | Inline `<script>` block in the same file |
| Fonts | Google Fonts, loaded by link |

## Why one file

- **Easy to host.** Drop it on GitHub Pages or any static host and it works.
- **Easy to edit.** Everything is in one place, with no tooling to learn.
- **Easy to back up.** One file is the whole site.

## Brand tokens

The site uses the Sassy & Structured brand system exactly.

**Colors**

| Token | Hex | Use |
|---|---|---|
| Lipstick Red | `#E63950` | Primary / "SASSY" |
| Hot Raspberry | `#FF3D7F` | "STRUCTURED" on dark |
| Electric Coral | `#FB5A3C` | "STRUCTURED" on light |
| Gold | `#D4A537` | The ampersand and accents |
| Navy | `#1B2A4A` | Tiny accents only, never a background |
| Bone | `#F4EDE4` | Light background |
| Ink | `#241019` | Dark background and text |

**Type**

| Role | Font |
|---|---|
| Display / big hooks | Chunky script or fat display, ALL CAPS only |
| The ampersand | EB Garamond Italic, oversized, tilted ~15°, gold |
| Headers | League Gothic, tall and condensed, letter-spacing 2–4 |
| Body | Poppins (Light–Medium) |

**Rules:** The loud element is the loudest thing on the page. Lots of bone or ink breathing room. Two or three accent icons max. No body text in script. Never all four brights in one design. No drop shadows or outlines on the logo.

## Accessibility

Accessibility is a requirement here, not a nice-to-have. The page should always have:

- Semantic HTML: headings in order, real buttons, real lists
- Alt text on meaningful images, `alt=""` on decorative ones
- Contrast of at least 4.5:1 for body text and 3:1 for large text and UI components
- Full keyboard navigation with visible focus states
- Meaning that never depends on color alone
- Labeled form inputs (placeholder text is not a label)

## Viewing it locally

1. Download or clone this repository.
2. Double-click the HTML file to open it in your browser.

That's it. No server needed.
