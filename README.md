# Dibs Shop Static Website

Single-page static site for Dibs Shop, a vintage and new home goods / gift shop in Park Slope, Brooklyn. All business facts and copy details come from `files/info.md`.

## Files

- `index.html` - Semantic one-page site with hero, story, product categories, visit, press, and footer sections.
- `styles.css` - Local font loading, responsive layout, colors, and visual styling.
- `public/images/` - Local image assets. No decorative external image URLs are used.
- `public/fonts/` - Local copies of the Google font files used by the site.
- `files/info.md` - Source research document.

## Images

Real downloaded assets:

- `public/images/storefront-exterior.jpg` - Yelp/MapQuest storefront image.
- `public/images/shop-interior.png` - Original Park Slope Pulse / Cool Hand Movers Dibs image.
- `public/images/shop-interior-1600.jpg` - Optimized local derivative used on the site for faster loading.
- `public/images/dibs-yellow-tableware.jpg` - Dibs-specific image found in the Cool Hand Movers gift guide page.

Placeholder images:

- None. All displayed images are real local files.

Skipped media:

- The Park Slope Pulse cover image was a Cool Hand Movers promo image, not a Dibs Shop image.
- Other Cool Hand Movers gift guide image candidates belonged to unrelated businesses and were not saved into `public/images/`.

## Owner Still Needs To Provide

- Confirmed hours.
- Phone number, if they want one published.
- Email address, if they want one published.
- Official logo or wordmark.
- More high-resolution interior, exterior, product, and owner photos.
- Any official online shop URL, if one exists.
- Confirmation on whether prints should be listed separately from art.

## Running Locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

The Google Maps iframe in the Visit section is the only external embed, used as a functional map rather than decorative media.
