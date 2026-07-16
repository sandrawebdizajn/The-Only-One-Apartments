# The Only One Apartments — website

Premium redesign for The Only One Apartments (Niš). Dark, gold-accented, bilingual (SR/EN), mobile-first.

## Structure
```
index.html        → home page
Galerija.html     → full gallery page
support.js        → runtime (required, keep next to the HTML files)
assets/           → logo
images/           → all photos (edit / replace here)
```

## Editing photos
Replace any file in `images/` with your own (keep the same filename), or add a new file and update the reference in `index.html` / `Galerija.html`. No build step needed.

## Deploy

### GitHub Pages
1. Upload the whole folder contents (index.html, Galerija.html, support.js, assets/, images/) to the repo root.
2. Settings → Pages → Source: `main` branch, `/root`.
3. Live at `https://<username>.github.io/<repo>/`.

### Any static host
Upload all files/folders preserving the structure. `index.html` is the entry point.

> Note: because files load `support.js` and the images by relative path, open the site through a web server (or GitHub Pages) rather than double-clicking the file — some browsers block relative script loading from `file://`.

## Notes
- Booking links point to `booking.com/hotel/rs/the-only-one-apartment.html`.
- The Booking rating (8.6) and guest reviews are editable in `index.html`.
