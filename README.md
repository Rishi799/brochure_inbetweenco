# in-Between Co — The Festive Edit 2026 · Online Brochure

An **online version of the Festive Edit 2026 brochure**. Instead of sending the PDF
(which the recipient has to download and open in a PDF app), you send **one link** and
they flip through the real brochure pages right in the browser — on any phone or laptop.

## What it is
- A single-page viewer that shows the six designed brochure pages.
- Dark gallery backdrop, page counter (`01 / 06`), tap-to-zoom, arrow-key / on-screen
  navigation, and a WhatsApp enquiry button throughout.
- Loads fast (~1.6 MB total, images are optimised and lazy-loaded).
- Sharing the link on WhatsApp shows the cover as the preview image.
- The original PDF is still available via the **PDF** button for anyone who wants to
  download or print it.

## View it online (GitHub Pages)
Once GitHub Pages is enabled for this repository (Settings → Pages → Deploy from a
branch → `main` / root), the brochure is live at:

```
https://rishi799.github.io/brochure_inbetweenco/
```

That is the link to share.

## Structure
```
index.html                         The viewer
styles.css                         Styling (brand: Manrope + Instrument Serif,
                                    cream / Midnight Indigo / Burnt Saffron)
assets/
  logo.png, logo-light.png         Brand marks
  pages/page1.jpg … page6.jpg      The six brochure pages (optimised)
  in-Between-Festive-Edit-2026.pdf The original PDF (download button)
```

## Updating the brochure
When a new edition of the brochure is designed, export each page as an image, replace
the files in `assets/pages/` (keep the same names), swap in the new PDF, and push.
No other changes are needed.

## The collection (for reference)
- **The in-Between Signature** — ₹999 · 3 × 350 ml jars
- **The in-Between Prestige** — ₹1,499 · 4 × 350 ml jars
- **The Dry Fruit Quartet** — ₹599 · 200 g

Orders & corporate enquiries: **WhatsApp +91 99104 93207** ·
between@eatinbetween.com · Jaipur & Bengaluru, delivering pan India.
