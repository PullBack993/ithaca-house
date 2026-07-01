# Thalassa House · Ithaca

A single-page site for a two-bedroom sea-view holiday home on the island of
Ithaca (Ithaki), in the Ionian Islands, Greece. Sleeps four, with a fully
equipped kitchen and a terrace facing the sunset.

## View it
It's a static page — no build step. Just open the file:

```bash
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Photos
The house-specific images (hero, kitchen, both bedrooms, terrace) are the
owner's own photos. The area/scenery shots (coves, village, olive groves) are
Unsplash placeholders. See [`images/CREDITS.md`](images/CREDITS.md) — to change
any image, drop a file with the same name into `images/`.

## Editing
- **Property name / location:** the placeholder name "Thalassa House" and the
  approximate distances in the location section are easy to find in `index.html`.
- **Contact:** the enquiry form opens a prefilled email via `mailto:`.

## Built with
Plain HTML + CSS + a little vanilla JavaScript (IntersectionObserver scroll
reveals). Fonts loaded from Google Fonts, with system-font fallbacks.
