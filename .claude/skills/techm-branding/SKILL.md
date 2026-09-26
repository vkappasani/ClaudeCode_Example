---
name: techm-branding
description: Apply the Tech Mahindra brand system (colors, Aptos typography, logo rules, layout, verbal identity) to any generated PowerPoint deck, Word document, PDF, proposal, HTML page, prototype, dashboard, or data visualization. Read this BEFORE writing the first line of markup, CSS, python-pptx/python-docx code, or choosing any color or font. Triggers on: pptx, powerpoint, deck, slide, docx, word document, proposal, report, html page, landing page, prototype, dashboard, chart, brand review, branding, Tech Mahindra, TechM. Skip only when the user explicitly asks for different or client branding.
version: 1.2.0
source_version: "Tech Mahindra Basic Brand Guidelines V.02 (January 2026); TechM PowerPoint Template & Guidelines (23-Oct-2025); TechM Word Proposal Template"
---

# Tech Mahindra Branding

## Purpose

This skill ensures that **every artifact generated in any project in this Claude Code environment**—PowerPoint presentations, Word documents, PDFs, or HTML web pages—complies with Tech Mahindra's official brand guidelines. Read it before creating or reviewing any branded content.

**Primary Reference:** https://www.techmahindra.com/

**Until explicitly instructed otherwise, all generated artifacts MUST follow this branding.**

---

## Quick Brand Reference

### Brand Promise
**Scale at Speed™**

### Core Values
- Integrity
- Quality  
- Care

### Brand Voice
**Ascending Force** — Conveys pride, momentum, empathy, mastery, drive, agility, partnership, and willingness to contend to win. Human and credible, never boastful.

**Tone:** Consciously Clear — Fresh, purposeful, evidence-based, with a clear point of view.

---

## Color Palette (Use as CSS Custom Properties)

```css
:root {
  /* Primary Brand Color */
  --techm-mahindra-rising-red: #E31837;
  
  /* Secondary Reds */
  --techm-impact-red: #5F0229;
  --techm-clarity-red: #F8B4A3;
  
  /* Dark Accents */
  --techm-blueprint-navy: #0A0838;
  
  /* Neutrals */
  --techm-clarity-grey-1: #F6F2EA;
  --techm-clarity-grey-2: #E5DFDD;
  --techm-steel-grey: #4D4D4F;
  --techm-anchor-grey-1: #4A453D;
  --techm-anchor-grey-2: #29251D;
  
  /* Base Colors */
  --techm-ink-black: #000000;
  --techm-white: #FFFFFF;
}
```

**Color Usage:**
- Mahindra Rising Red (#E31837) = Primary brand color
- Use neutrals for hierarchy, space, and readability
- Preserve accessible contrast (WCAG AA minimum)
- **Never create gradients, tints, or unapproved colors**

---

## Typography

### For PowerPoint & Word (Aptos)
```
Cover/Divider Title:     Aptos Thin, 60pt
Page Title:              Aptos Thin, 40pt
Subtitle:                Aptos Thin, 18pt
Body Copy:               Aptos Regular, 16pt
Card Heading/Annotation: Aptos, ~23pt (usually Mahindra Rising Red)
Source Line:             Aptos Thin, 8pt
Footnote/Note:           Aptos, 6pt–12pt (depending on role)
```

### For Web/HTML Pages
```
Use: 'Aptos', 'Aptos Display', 'Segoe UI', Calibri, 'Helvetica Neue', Arial, sans-serif

Fallback font stack for HTML:
font-family: 'Aptos', 'Aptos Display', 'Segoe UI', Calibri, 'Helvetica Neue', Arial, sans-serif;

- Keep headlines short and specific
- Use restrained weight variation
- Maintain consistent line spacing
- Align text to grids; no right-aligned long-form text
- Avoid all-caps paragraphs
- Do not mix many sizes, fonts, or weights on one page
```

---

## Logo & Symbol

### Logo Usage
- Always use **official, approved artwork**
- Never distort, stretch, or change proportions
- Never add shadows, glows, bevels, or effects
- Never recolor, modify, or redraw
- Minimum digital width: **30px**
- Minimum print width: **10mm**
- **Clear space:** Width of lowercase 'm' in wordmark on all sides

### Symbol Usage (Use Only When Logo Unavailable)
- Use symbol **only** when full logo cannot remain legible due to space
- For avatars, favicons, app icons, or constrained layouts
- **Only approved colorways:** Mahindra Rising Red, Ink Black, or White
- Minimum digital: **16px**
- Minimum print: **10mm**
- Clear space: **½ symbol height (1/2 X)** on all sides
- **Never:** Use as bullet, illustration container, photography mask, or repeated pattern

---

## PowerPoint Guidelines

For any PowerPoint creation, redesign, or brand review, read
[`references/powerpoint-template.md`](references/powerpoint-template.md) before
selecting layouts, placing imagery, or modifying master elements. The official
PowerPoint master is authoritative for geometry and placeholder placement; this
skill supplies the decision rules for using it correctly.

### Clear Space & Workspace
- Content must fit within the **designated workspace** (see template master)
- Keep **top-right brand-flag zone unobstructed**
- Preserve footer: `© Tech Mahindra Limited. All Rights Reserved`
- Never move master elements to gain space; edit content instead

### Common Slide Patterns
Select the closest approved pattern rather than inventing new layouts:
- Hero cover
- Agenda
- Chapter divider
- Single-message page
- Two-column editorial page
- Three-card or three-column page
- Image-and-copy page
- Portrait grid
- KPI split
- Chart page
- Data table
- Comparison matrix
- Closing page

### Iconography
- Use **flat, monoline icons only** (Microsoft default icon set via Insert > Icons)
- Keep size, stroke, arrangement, and color consistent
- Use Ink Black or Mahindra Rising Red by default
- **Never:** Gradients, textures, shadows, bevels, 3D emoji-style, cartoons, or mixed icon families

### Photography
- Use **authentic, genuine, lifelike photography** of real people engaged in real activities
- Prefer **candid, context-rich scenes** over staged stock-photo gestures
- Do NOT reproduce conceptual examples from the brand guidelines (those may be third-party sources)

### Data Visualization
Use the approved red and neutral palette:
- Mahindra Rising Red (primary)
- Impact Red (secondary)
- Blueprint Navy (deep contrast)
- Clarity Red (light accent)
- Clarity Grey 1 & 2, Anchor Grey 1 & 2 (neutrals)

**Rules:**
- Use color to clarify categories, not decorate
- Reserve strongest red for most important series
- Ensure scales, totals, units, legends, baselines, source notes are accurate
- Avoid effects, gradients, 3D charts, shadows, unnecessary furniture

---

## Word Document Guidelines

### Proposal documents

For any TechM proposal (cover, confidentiality agreement, TOC, numbered
sections), read
[`references/word-proposal-template.md`](references/word-proposal-template.md)
before drafting. It captures the exact page order, the standard
confidentiality language and 120-day validity clause, heading color
hierarchy, and footer/pagination format from the official proposal master.

### Master Template
- Always use the official **Tech Mahindra Word master template** when supplied
- Preserve all clear areas and master elements
- Keep footer copyright notice intact
- Never place text, charts, images over protected clear areas

### Layout
- Use full-logo lockups only where the master designates (covers, dividers, closing)
- Use small red flag mark on standard content pages (when provided by master)
- Preserve page or section numbering
- Keep top-right brand-flag zone clear

### Content Structure
- **Confidentiality statements** use approved language
- **Section headings** in Mahindra Rising Red when appropriate
- **Body text** justified with proper spacing
- **Tables & charts** readable and accessible
- **Images** with proper captions and source attribution

---

## HTML/Web Page Guidelines

### Use the shared design system — do not hand-roll CSS

A complete implementation of everything in this section already exists at
`design-system/` (a symlink from this skill directory to the canonical copy in
OneDrive). **Link it instead of writing brand CSS from scratch.** Hand-rolled CSS
drifts from the brand and from every other project.

```
design-system/
  css/techm-tokens.css       load FIRST — every colour, type, spacing token
  css/techm-base.css         reset, type scale, layout, focus, print
  css/techm-components.css   buttons, cards, forms, tabs, modals, badges, stats
  js/techm-theme.js          light/dark switching, localStorage
  js/techm-ui.js             WAI-ARIA tabs, modal focus trap, theme toggles
  js/techm-charts.js         token-aware palettes + ECharts/Mermaid themes
  templates/html-starter.html  copy this as the starting point for a new page
  tools/audit.mjs            run before delivery — catches token/class/hex drift
  references/COLOR.md        measured contrast, ramp derivation, hard caps
```

**To set up a project:** run `design-system/setup.sh <project-dir>`. It symlinks
the system to `<project-dir>/.claude/design-system`. Pages then reference it with
a relative path, so they open from `file://` with no server and no network.

**Non-negotiables when consuming it:**
- Load order is tokens → base → components.
- Never hardcode a hex in page code. Every colour is a `var(--techm-*)`.
- Categorical chart colour is **capped at 4 series in light, 3 in dark** — the
  brand has one chromatic family. A 5th series folds into "Other" or becomes a
  facet. Never invent a hue. `TechMCharts.series(n)` enforces this.
- Never place Anchor Grey `#4A453D` and Steel Grey `#4D4D4F` in one chart; they
  are indistinguishable (ΔE 3.3).
- Colour is never the only carrier of meaning — pair status with an icon and a
  text label.
- **No CDNs, external fonts, or network calls.** Use the Aptos font stack defined
  in `techm-base.css`. For dataviz libraries (ECharts, Mermaid), download them
  once and vendor them into `design-system/vendor/` — they are shared across all
  projects and available offline. See `design-system/references/ARCHITECTURE.md`
  for library setup instructions.

The raw token values below are the source of truth the system is built from; read
them to understand *why*, but consume them via the stylesheets above.

### Color Implementation
```css
/* Define all colors as CSS custom properties in :root */
:root {
  --techm-mahindra-rising-red: #E31837;
  --techm-impact-red: #5F0229;
  --techm-blueprint-navy: #0A0838;
  --techm-clarity-red: #F8B4A3;
  --techm-clarity-grey-1: #F6F2EA;
  --techm-clarity-grey-2: #E5DFDD;
  --techm-steel-grey: #4D4D4F;
  --techm-anchor-grey-1: #4A453D;
  --techm-anchor-grey-2: #29251D;
  --techm-ink-black: #000000;
  --techm-white: #FFFFFF;
}

/* Use in styles */
background-color: var(--techm-mahindra-rising-red);
color: var(--techm-ink-black);
```

### Semantic HTML & Accessibility
- Use semantic HTML5 (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`)
- Proper heading hierarchy (`<h1>` → `<h6>`)
- WCAG 2.1 AA compliance minimum
- Visible keyboard focus states
- 44px minimum touch targets
- Proper `alt` text for images
- Color is never the only means of conveying information

### Typography in HTML
```css
font-family: 'Aptos', 'Aptos Display', 'Segoe UI', Calibri, 'Helvetica Neue', Arial, sans-serif;

/* Responsive title sizing with clamp() */
h1 {
  font-size: clamp(2rem, 5vw, 3.75rem); /* Preserves 60pt:40pt relationship */
}

h2 {
  font-size: clamp(1.5rem, 4vw, 2.5rem);
}
```

### Layout & Spacing
- Reserve ~5% viewport clear area on desktop, minimum 16px on mobile
- Keep **top-right flag zone clear** (logo/symbol placement)
- Use **fluid layouts without shadows, gradients, textures, ornamental effects**
- Flat design: clean, minimal, focused
- Maintain consistent gutters and alignment

### Logo & SVG Usage
- Use supplied official logo artwork (SVG preferred for web)
- **Never recreate the protected logo or symbol as improvised SVG**
- Use inline SVG only for:
  - Simple charts/data visualizations
  - Generic monoline icons (from Microsoft/approved sets)
- Never distort or modify supplied logo SVG

### Images & Photography
- Use authentic, genuine photography
- Optimize images for web (compressed, appropriately sized)
- Include proper alt text and captions
- Never use generic stock photos over authentic company/team photography

### Print Styles
- Include CSS for `@media print`
- Ensure readable contrast when printed
- Prevent horizontal scrolling on small screens
- Test responsive design across breakpoints

### External Resources
- **Do not use external fonts, analytics, CDNs, or network calls** unless explicitly approved
- Keep all assets local or use approved hosted resources
- No third-party tracking codes unless authorized

---

## Brand Quality Gate Checklist

Before delivery, verify every item:

### Strategy & Voice
- [ ] Purpose, promise, mission, values use approved wording
- [ ] Copy embodies "Ascending Force" tone
- [ ] Headlines are specific, concise, human
- [ ] Claims are evidence-based
- [ ] Tone is "Consciously Clear"

### Logo & Symbol
- [ ] Official artwork is used (no recreations)
- [ ] Correct colorway with maximum contrast
- [ ] Clear space and minimum size respected
- [ ] No distortion, recoloring, effects, masking, misuse
- [ ] Symbol not used as bullet, container, ad-hoc pattern, or illustration

### Color
- [ ] Every color matches an approved token
- [ ] No malformed or OCR-corrupted values
- [ ] Contrast is accessible (WCAG AA)
- [ ] No gradients or unapproved tints

### Typography
- [ ] Typeface matches the format (Aptos for Office, web stack for HTML)
- [ ] PowerPoint uses proper Aptos sizes from master
- [ ] Hierarchy, line spacing, alignment are consistent
- [ ] No excessive all-caps, weight extremes, or font mixing

### Imagery, Icons, Patterns
- [ ] Photography is authentic or explicitly approved
- [ ] Icons are flat and monoline
- [ ] Only supplied pattern assets used
- [ ] Visual elements do not harm legibility
- [ ] Conceptual examples from guidelines not reproduced

### Layout & Delivery
- [ ] Protected clear areas remain empty
- [ ] Master elements and footers preserved (for Office docs)
- [ ] Content fits without overflow, clipping, or tiny text
- [ ] Tables and charts remain readable
- [ ] Accessibility and print behavior checked (for digital deliverables)

---

## Format-Specific Corrections

### If Using PowerPoint:
1. Open the official Tech Mahindra PowerPoint master
2. Verify workspace boundaries on each slide
3. Use only approved color palette in fills and text
4. Check logo placement and clear space on covers
5. Ensure iconography is consistent and flat
6. Validate footer and page numbering

### If Using Word:
1. Apply the official Tech Mahindra Word template
2. Verify header/footer with copyright notice
3. Use Aptos for all body text at correct sizes
4. Check image placement and captions
5. Validate table formatting and colors
6. Ensure clear areas are preserved

### If Using HTML:
1. Define all colors as CSS custom properties from the approved palette
2. Apply semantic HTML structure
3. Use the Aptos font stack as fallback
4. Include print styles and mobile breakpoints
5. Optimize images and ensure alt text
6. Validate WCAG AA compliance with axe DevTools or similar
7. Test on multiple breakpoints and devices
8. Never embed third-party scripts without approval

---

## When to Apply This Skill

**Always use this skill before generating:**
- PowerPoint presentations
- Word proposals, reports, or documents
- HTML landing pages, prototypes, or web applications
- Email templates or marketing materials
- Dashboard or data visualization components

**Do NOT use this skill when:**
- Explicitly instructed to use different branding (e.g., "Use customer branding")
- Building internal developer tools or test environments
- Creating draft or exploration documents (mark as "DRAFT – NOT FOR EXTERNAL USE")

---

## Deviation & Exceptions

**This branding applies unless:**
1. The user explicitly requests different branding
2. A specific client engagement requires their branding
3. The artifact is clearly marked as "DRAFT" or "INTERNAL ONLY"
4. A future update to this skill supersedes these guidelines

**When deviating, document the reason and approved exception in the artifact.**

---

## Resources & References

- **Official Website:** https://www.techmahindra.com/
- **Brand Guidelines Source:** Tech Mahindra Basic Brand Guidelines V.02, January 2026
- **PowerPoint Master:** TechM PowerPoint Template & Guidelines (23-Oct-2025) — see [`references/powerpoint-template.md`](references/powerpoint-template.md)
- **Word Proposal Master:** TechM Word Proposal Template — see [`references/word-proposal-template.md`](references/word-proposal-template.md)
- **Logo & Symbol:** Use only official artwork supplied in brand kit
- **Questions:** Contact `brandmarketing@techmahindra.com`

---

## How to Use This Skill

This skill is registered globally at `~/.claude/skills/techm-branding/` and is available in every project. It is invoked automatically when a task involves generating or reviewing a deck, document, or web page. You can also invoke it explicitly:

```
/techm-branding
/techm-branding powerpoint
/techm-branding word
/techm-branding html
```

Read the matching format section, apply the tokens and rules, then run the Brand Quality Gate checklist before delivering.
