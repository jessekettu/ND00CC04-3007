# OnlyFoxes 🦊

A static multi-page website built as a parody of subscription content platforms — but exclusively for fox creators and their devoted fans. Built with vanilla HTML, CSS, and JavaScript; no frameworks or build tools required.

## Pages

| File | Description |
|---|---|
| `index.html` | Homepage — hero, featured creator cards, trending mosaic, feature grid |
| `profile.html` | Creator profile page with tabbed posts/tiers/about sections |
| `gallery.html` | Image gallery with slideshow, filter bar, masonry grid, and lightbox |
| `subscribe.html` | Sign-up page with plan selector and form validation |
| `login.html` | Login page with form validation and Enter-key support |
| `about.html` | About page with company stats and mission statement |
| `contact.html` | Contact page with working message form |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |

## Tech Stack

- **HTML5** — semantic markup, no frameworks
- **CSS3** — custom properties, grid, flexbox, masonry columns, scroll-reveal animations
- **Vanilla JavaScript** — hamburger menu, tab switching, slideshow, gallery filters, lightbox, form validation
- **Google Fonts** — Playfair Display (headings) + DM Sans (body)
- **Unsplash** — fox photography (free to use under the [Unsplash License](https://unsplash.com/license))

## Running Locally

No build step needed. Open any HTML file directly in a browser, or serve the folder with any static server:

```bash
# Python
python3 -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Project Structure

```
OnlyFox/
├── index.html
├── profile.html
├── gallery.html
├── subscribe.html
├── login.html
├── about.html
├── contact.html
├── privacy.html
├── terms.html
├── styles.css
└── kettu.jpg        # Local fox photo used as lightbox fallback
```

## Image License

All photographs are sourced from [Unsplash](https://unsplash.com/s/photos/fox) and are free to use for commercial and non-commercial purposes without attribution under the [Unsplash License](https://unsplash.com/license). Redistribution or reselling of the photos as stock images is not permitted.
