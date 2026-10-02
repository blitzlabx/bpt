# BPT: Blitz Portfolio Templates

**3,200 distinct portfolio website templates in one HTML file.**
Search them, filter them, preview them on phone, tablet and desktop widths, then copy or download any template as its own standalone page.

No frameworks. No build step. No dependencies. No external fonts, scripts or CDNs.

Built by [Blitz (@blitzlabx)](https://github.com/blitzlabx) · Portfolio: [blitz.devs.surf](https://blitz.devs.surf) · Telegram: [@blitzlabx](https://t.me/blitzlabx)

---

## Contents

1. [What it is](#what-it-is)
2. [Quick start](#quick-start)
3. [By the numbers](#by-the-numbers)
4. [Features](#features)
5. [Keyboard shortcuts](#keyboard-shortcuts)
6. [Using a template](#using-a-template)
7. [What is in this package](#what-is-in-this-package)
8. [Deploying](#deploying)
9. [Search engines and social previews](#search-engines-and-social-previews)
10. [Changing the domain](#changing-the-domain)
11. [Branding and logo](#branding-and-logo)
12. [Browser console API](#browser-console-api)
13. [How it works](#how-it-works)
14. [Customizing the catalog](#customizing-the-catalog)
15. [Saved data and privacy](#saved-data-and-privacy)
16. [Accessibility](#accessibility)
17. [Browser support](#browser-support)
18. [Troubleshooting](#troubleshooting)
19. [Known limitations](#known-limitations)
20. [Changelog](#changelog)
21. [License and credits](#license-and-credits)

---

## What it is

BPT is a specimen catalog. One file, `index.html`, contains a library interface and an engine that generates 3,200 portfolio templates on demand. Each one has its own layout, navigation, hero, footer, typography, palette and mix of sections. They are not 3,200 colour swaps of one design.

You can use it to:

- Find a portfolio design that fits a person, a profession or a mood.
- Preview it live at mobile, tablet and full width.
- Download the chosen template as a complete, standalone `.html` file and ship it.
- Use it as a reference library when designing your own.

## Quick start

**Option A: just open it.** Double-click `index.html`. It runs fully offline from your device.

**Option B: put it online.** Upload every file in this package to the same folder on any static host, with `index.html` at the root. See [Deploying](#deploying).

Then:

1. Tap **Browse the catalog**.
2. Search, or open **Filters** and pick what you like.
3. Tap a card to preview it.
4. Tap **Download** to save it as its own HTML file.

## By the numbers

| Item | Count |
| --- | --- |
| Templates | 3,200 |
| Design systems (families) | 80, with 40 templates each |
| Design groups | 10 (Editorial, Studio, Minimal, Dark & Tech, Brutalist, Swiss, Playful, Luxury, Photographic, Experimental), 320 templates each |
| Colour palettes | 232 |
| Type pairings | 79 |
| Navigation patterns | 12 |
| Hero layouts | 20 |
| Section types | 17 (about, skills, work, gallery, timeline, testimonials, services, stats, contact, clients, cta, notes, awards, process, faq, marquee, pricing) |
| Light / dark templates | 1,992 / 1,208 |
| External requests | 0 |

These counts come from the running file. You can confirm them yourself with [`BPT.selfTest()`](#browser-console-api).

## Features

### Browsing and finding

- **Search** across names, tags and styles. Words combine, so `dark serif split hero` narrows quickly. A number such as `100` jumps to exactly template #100.
- **Quick chips** under the toolbar for one-tap searches: Terminal, Serif, Dark, Split hero, Masonry, Mono, Editorial, Overlay nav.
- **Filters:** design group, mood (light or dark), structure (15 chips such as sidebar nav, overlay menu, split hero, big type, masonry, terminal) and type vibe (serif, sans, mono, display, mixed).
- **Active filter chips** above the grid. Tap one to remove it, or tap **Clear all**.
- **Sorting:** Curated, A to Z, Design system, Dark first, Light first.
- **Favorites:** tap the heart on any card, then use **Favorites only** in the filters to see your shortlist.
- **Surprise me:** opens a random template from whatever is currently visible.
- **Load more:** templates appear 36 at a time, and only the cards on screen exist in the page, so it stays fast with 3,200 entries.

### Previewing

- Full-screen live preview of the real template.
- **Device widths** on larger screens: Mobile (390), Tablet (834) and Full.
- **Previous and next** arrows (and arrow keys) to flip through results.
- **Open** in a new tab, **Copy** the HTML, **Download** it, or copy a **Link** that reopens that exact template.
- **Deep links:** `index.html#t-042` opens template 042 directly.

### Interface

- **Phone-first layout:** bottom navigation dock (Home, Browse, Search, Filters, Surprise) that tucks away as you scroll down and returns when you scroll up.
- **Filters as a bottom sheet** on phones and tablets, with a drag handle, swipe down to dismiss, and a live **Show N templates** button.
- **1 or 2 column** switch for phones. Desktop offers 2, 3 or 4 columns.
- **Light and dark themes.** The first visit follows your device setting, and your own choice is remembered afterwards.
- Scroll progress bar, back-to-top button, toasts, and motion that switches off for people who prefer reduced motion.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `/` | Focus search |
| `Esc` | Close the preview or panel |
| `←` `→` | Previous or next template while previewing |
| `Enter` | Open the focused card |
| `?` | Show or hide the shortcuts panel |

## Using a template

When you tap **Download**, you get a file named `bpt-<template-slug>.html`. It is a complete standalone page:

- All CSS and JavaScript are inline, in that one file.
- It uses system font stacks, so nothing is fetched from the internet.
- It contains placeholder person, project, client and testimonial content for you to replace.
- It carries a `generator` meta tag crediting BPT.

To make it yours:

1. Open the downloaded file in any text or code editor.
2. Replace the placeholder name, role, text, project names and links with your real details.
3. Rename it to `index.html` and upload it to your host.

**Copy** puts the same HTML on your clipboard instead, if you would rather paste it into your own project.

## What is in this package

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: interface, engine and all 3,200 templates |
| `README.md` | This document |
| `og-image.png` | 1200 × 630 preview image shown when the link is shared |
| `favicon.ico` | Classic browser tab icon (48, 32 and 16 px) |
| `favicon.svg` | Sharp, scalable tab icon for modern browsers |
| `favicon-16.png`, `favicon-32.png` | PNG tab icons |
| `apple-touch-icon.png` | Home-screen icon on iPhone and iPad (180 px) |
| `icon-192.png`, `icon-512.png` | Android and install icons |
| `icon-maskable-512.png` | Full-bleed icon that adapts to any Android icon shape |
| `site.webmanifest` | Lets people add BPT to their home screen as an app |
| `sitemap.xml` | Tells search engines which page to index |
| `robots.txt` | Allows crawling and points to the sitemap |
| `logo.svg` | Horizontal logo for light backgrounds |
| `logo-light.svg` | Horizontal logo for dark backgrounds |
| `logo-mark.svg`, `logo-mark.png` | The icon on its own |

`index.html` works alone for everyday use. The other files exist for icons, link previews and search engines, and they need to sit **next to `index.html`**.

## Deploying

BPT is a static site, so any static host works. There is nothing to build or install.

| Host | How |
| --- | --- |
| **Vercel** | Add the files to a GitHub repo, import it, set Framework Preset to **Other**, leave the build command empty, and keep the output directory as the root. |
| **Render** | New **Static Site**, connect the repo, leave the build command empty, set Publish Directory to `.` |
| **GitHub Pages** | Repo **Settings > Pages**, deploy from your branch, root folder. |
| **Netlify** | Drag the unzipped folder onto Netlify Drop, or connect the repo with no build command. |
| **Cloudflare Pages** | Direct upload of the folder, or connect the repo with no build command. |

Always upload the **whole set of files**, not only `index.html`. Without the others the link preview image, tab icon and sitemap will be missing.

## Search engines and social previews

The page ships with everything search engines and chat apps look for:

- A 56-character title and a 151-character description written for search results.
- A canonical link, plus robots directives that allow full snippets and large image previews.
- **Open Graph** tags (Facebook, WhatsApp, Telegram, LinkedIn, Discord, iMessage) and **Twitter/X card** tags using `og-image.png`.
- **Structured data (JSON-LD)** describing the site, the web app and the author.
- `sitemap.xml` and `robots.txt`.
- A plain-text fallback for crawlers that do not run JavaScript.
- Favicons, an Apple touch icon, and a web app manifest.

### After you go live

1. Open your site in a browser and confirm the tab icon appears.
2. Add the site to **Google Search Console** and **Bing Webmaster Tools**, verify ownership, and submit `sitemap.xml`.
3. Refresh the cached link preview, because chat apps and social sites remember the first version they saw:
   - Facebook: the Sharing Debugger.
   - LinkedIn: the Post Inspector.
   - Telegram: send the link to the `@WebpageBot` bot.
4. Share the link somewhere private first to check how it looks.

Indexing can take days to weeks. Nobody can promise a ranking position, but this setup removes the technical reasons a page gets overlooked. Links from other sites (your portfolio, GitHub profile, social bios) help most.

## Changing the domain

The package is set up for **`https://blitz.devs.surf/`**. If the catalog will live somewhere else, such as `https://example.com/bpt/`:

1. Open `index.html`, `sitemap.xml` and `robots.txt` in a text editor.
2. Search for `blitz.devs.surf`.
3. Replace every match with your real address, keeping `https://` and the trailing slash where it was.
4. Re-upload, then refresh the link previews as described above.

This matters. The canonical tag tells search engines which address is the real one, so a wrong domain can keep the page out of search results.

To use a different share image, replace `og-image.png` with any 1200 × 630 PNG of the same name, ideally under 300 KB.

## Branding and logo

The logo is a bold geometric **B** with a lightning bolt, drawn entirely with vector shapes. It needs no font and stays sharp at any size.

- Orange gradient tile: `#FF7A2E` to `#FF4D00` to `#D93A00`
- Letter: warm cream `#FFF7EE`
- Bolt: `#FFD166`
- Library dark background: `#131109`, light background: `#F2EFE8`

Use `logo.svg` on light backgrounds, `logo-light.svg` on dark ones, and `logo-mark.svg` or `logo-mark.png` when you only have room for the icon. The small tab icon is a simplified version with a heavier letter and no bolt so it stays readable at 16 px.

## Browser console API

Open your browser's developer console on the page to use `window.BPT`:

| Member | What it does |
| --- | --- |
| `BPT.version` | Current version string |
| `BPT.ALL` | Array of all 3,200 template records |
| `BPT.state` | Current filter and sort state |
| `BPT.applyFilters()` | Re-run the filters after changing `BPT.state` |
| `BPT.openPreview(g)` | Open the preview for a template record |
| `BPT.compose(g)` | Return the full standalone HTML string for a template |
| `BPT.poster(g)` | Return the miniature preview markup used on cards |
| `BPT.selfTest()` | Run the built-in integrity check and return a report |

Examples:

```js
// Open template 042
BPT.openPreview(BPT.ALL.find(g => g.serial === '042'));

// Get the HTML of a template as text
const html = BPT.compose(BPT.ALL[0]);

// Check the whole catalog
BPT.selfTest();
```

Adding `?selftest=1` to the address runs the self-test automatically on load. It composes a sample of templates and reports duplicate names or slugs, leaked `undefined` or `NaN` text, and missing style rules. A passing run shows a confirmation toast. At the time of writing it reports 3,200 templates, 80 families, 232 palettes, 79 type pairings and 0 errors.

Setting `BPT.state.q` changes the search used by the filters but does not update the search box text. Use the box itself for normal searching.

## How it works

`index.html` is organised in clear layers:

1. **Library interface styles** (`<style id="bpt-ui">`): the catalog chrome around the templates, with design tokens, filters, cards, the preview modal, the mobile dock and the polish layer.
2. **Template engine styles** (`<style id="bpt-engine">`): the CSS that gives every generated template its look.
3. **Markup:** masthead, hero, family ticker, filters, grid, mobile dock, preview modal, footer.
4. **Engine script:** builds the catalog, runs search and filters, draws the virtual grid, and composes templates.
5. **Polish script** (`<script id="bpt-polish">`): active filter chips, drag-to-dismiss sheet, dock behaviour, scroll helpers and small interactions.

Every template is generated from a fixed numeric seed, so serial `042` is the same template every time, on every device. A template is assembled from a navigation pattern, a hero layout, a footer, a plan of sections, a palette, a type pairing and a generated person with projects, clients and copy.

The grid is **virtualised**: only the rows near the screen are in the page, and cards are recycled as you scroll. That is why 3,200 templates stay smooth on a phone.

## Customizing the catalog

You can change the content tables inside the engine script. Look for these names in `index.html`:

| Name | Controls |
| --- | --- |
| `GROUPS` | The 10 design groups shown in the filter |
| `FAMILIES` | The 80 design systems |
| `PALETTES` | Colour palettes |
| `FONTS` | Type pairings |
| `NAVS` | Navigation patterns |
| `HEROES` | Hero layouts |
| `SECTIONS` | Section types a template may include |

After any change:

1. Open the page with `?selftest=1` and check the report shows no errors.
2. Search the file for `3,200`. Some visible copy, the page title, the meta descriptions and the share image state the template count and will need updating by hand if the total changes.
3. Regenerate or replace `og-image.png` if the headline numbers changed.

Work on a copy and keep the original. The file is large, and a single stray character in the script can stop the catalog from loading.

## Saved data and privacy

BPT has no server, no accounts, no analytics and no tracking. Everything stays in your browser. It stores three small items in `localStorage`:

| Key | Holds |
| --- | --- |
| `BPT_THEME` | Your light or dark choice (only once you toggle it yourself) |
| `BPT_MDENS` | Your phone grid choice, 1 or 2 columns |
| `BPT_FAVS` | The serial numbers of your favorite templates |

Clearing your browser's site data removes them. Private windows usually discard them on close.

The only outside links are ones you tap: GitHub, Telegram and the portfolio.

## Accessibility

- Skip link to jump straight to the templates.
- Cards are keyboard operable (focus, then `Enter` or `Space`).
- Buttons carry accessible labels, the result count is announced to screen readers, and the grid-layout toggles report which option is selected.
- Visible focus outlines.
- Animations are removed for people who set reduced motion in their system.
- Touch targets are enlarged on touch screens.

Full screen reader testing across devices has not been done, so treat this as a solid base rather than a certified result.

## Browser support

Built for current evergreen browsers: recent Chrome, Edge, Safari (16.2 and later) and Firefox (113 and later) on desktop and phone. It relies on modern CSS such as `color-mix()` and `backdrop-filter`. Older browsers may show flatter colours or miss blur effects.

## Troubleshooting

| Problem | What to try |
| --- | --- |
| Link preview does not show on WhatsApp, Telegram or X | Confirm `og-image.png` is uploaded next to `index.html` and opens at `https://your-domain/og-image.png`. Then refresh the cached preview (see [After you go live](#after-you-go-live)). |
| Link preview works locally but not online | Preview tags need absolute `https://` addresses. Check [Changing the domain](#changing-the-domain). |
| Tab icon not updating | Browsers cache icons hard. Close the tab, clear site data, or open the page in a private window. |
| Favorites disappear | They live in your browser storage. Private mode, cleared data or a different browser or device will not have them. |
| **Copy** does nothing | Some browsers block clipboard access on pages that are not served over `https`. Use **Download**, or host the page securely. |
| Filters or grid look wrong after editing | Restore from your original copy, then reapply changes in small steps, running `?selftest=1` each time. |
| Blank page after editing | A syntax slip in the script. Open the browser console to see the error line, or restore your backup. |
| Device width buttons missing in preview | They are hidden on phones on purpose, because the preview already fills a phone screen. |

## Known limitations

- **JavaScript is required** to browse the catalog. The no-JavaScript fallback gives crawlers and readers a description only.
- **One indexable page.** Search engines ignore the part of a link after `#`, so individual template deep links do not appear separately in search results. The sitemap lists one URL for that reason.
- **Placeholder content.** Downloaded templates contain sample names, text and projects. Replace them before publishing.
- **Large file.** `index.html` is about 1.2 MB. It loads once and then runs offline, but it is heavier than a typical landing page.
- **Rankings are not guaranteed.** The setup is technically complete, and visibility still depends on content, links and time.

## Changelog

### 2026-10-02 update

**Fixes**
- Page no longer scrolls sideways on phones. A hover tooltip was stretching the layout, which pushed the bottom dock and the preview's close button off screen.
- Rebuilt the phone **filter panel**. It was clipped and squashed with an oversized heart icon. It is now a bottom sheet with a sticky apply bar.
- Corrected the card grid math so cards no longer go missing in multi-column layouts.
- Card thumbnails now fill the whole card instead of only the top half.
- Favorite hearts are now visible on touch screens. Previously they appeared on hover only.
- Fixed hero badge numbers that disagreed with the stats beside them.
- Removed duplicated and conflicting legacy mobile drawer styles.

**Added**
- Active filter chips, 1 or 2 column phone switch, drag-to-dismiss filter sheet, sliding dock indicator and auto-hiding dock.
- Scroll progress bar, back-to-top button, staggered card reveals, heart animation, button ripple, empty-state illustration.
- Compact two-row preview header on phones.
- Icons on filter groups and sort control.
- New vector logo, favicon set, app icons, web manifest and 1200 × 630 share image.
- Open Graph and Twitter tags, JSON-LD structured data, canonical link, sitemap, robots file and no-JavaScript fallback.
- First visit now follows the device's light or dark setting, and the browser bar colour matches.
- Accessibility improvements (announced result count, pressed states on layout toggles).
- Footer link to the portfolio.

**Checked**
- Built-in self-test passes with 0 errors.
- No sideways overflow and no page errors in headless Chromium at 360, 390, 820 and 1280 px wide, in light and dark.

## License and credits

Designed and built by **Blitz**. All credits belong to Blitz.

No license file is included in this package yet. Before publishing the code publicly, add a `LICENSE` file that states what others may do with it. If you want it open, MIT is a common choice.

Need a portfolio, a template system or related work? Message [@blitzlabx on Telegram](https://t.me/blitzlabx).
