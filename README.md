# Alos Floral Arrangements — editable concept demo

This is an **unofficial website concept**, not a commissioned or live store. No actual business photos are included yet.

## Preview
Open `index.html` in a browser. The navigation, English/Spanish toggle, image enlargement, and Instagram links work without a server.

## Instagram and ordering
All ordering calls-to-action currently link to **https://www.instagram.com/alosarrangements/** and open a new tab. Instagram decides whether the user sees the website or app; an Instagram login may be required. These links open the profile, not a guaranteed prefilled DM. TikTok links to https://www.tiktok.com/@alosarrangements.

## Replace the picture placeholders
Put approved client photographs into `assets/photos/` (create that folder). Then edit the `src` of the following `<img>` elements in `index.html`.

| Placeholder file | Intended placement | Suggested real file |
|---|---|---|
| `hero.svg` | Homepage hero | `assets/photos/hero.webp` |
| `gallery-01.svg` | Gallery red roses | `assets/photos/red-roses.webp` |
| `gallery-02.svg` | White/gold bouquet | `assets/photos/white-gold.webp` |
| `gallery-03.svg` | Statement bouquet | `assets/photos/statement.webp` |
| `gallery-04.svg` | Pastel bouquet | `assets/photos/pastel.webp` |
| `gallery-05.svg` | Anniversary arrangement | `assets/photos/anniversary.webp` |
| `gallery-06.svg` | Pink bouquet | `assets/photos/pink.webp` |
| `about.svg` | About-section photograph | `assets/photos/about.webp` |
| `feature.svg` | Feature-panel photograph | `assets/photos/feature.webp` |

You can quickly search in `index.html` for `assets/placeholders/` and swap each image path. Change `alt` text so it accurately describes the actual image. `gallery-01.svg` is also used for the hidden lightbox's initial source. The gallery lightbox automatically enlarges whichever image is displayed in the gallery.

**Important:** Do not remove the temporary preview notice or unofficial demo disclaimer before the owner approves the concept. Remove the preview notice when actual images are in place; replace the disclaimer only with the owner's approval.

## Launch
Upload the folder to Cloudflare Pages, GitHub Pages, or another static host. No public deployment was done. Test mobile layouts and external links after publishing.
