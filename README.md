<p align="center">
  <img src="images/WE_icon.svg" alt="Wake Espresso" width="160">
</p>

# Wake Espresso

Marketing and menu website for **Wake Espresso**, a drive-thru and walk-up
coffee shop in Canyon Lake, TX. Live at **https://wakeespresso.com**.

## About Wake Espresso

Wake Espresso was founded by Canyon Lake natives and is all about great coffee
and lake vibes — *"Locally Brewed, Lake Approved."* Whether you're heading out
on the water or just passing through, you can grab a handcrafted coffee, tea, or
espresso drink from the convenient drive-thru or walk-up window (pup cups for the
dogs, too).

- **Location:** 8392 FM2673, Canyon Lake, TX 78133
- **Phone:** (830) 310-1101
- **Hours:** 5:30 AM daily; closes 7:00 PM Sun–Thu, 8:00 PM Fri–Sat
- **Instagram:** [@wakeespresso](https://www.instagram.com/wakeespresso)

The site presents the full menu — signature lattes, signature energy drinks,
classic coffee, non-coffee drinks, teas, kolaches, muffins, flavors, milk
alternatives, and extras — alongside an About section with an Instagram feed and
customer reviews, and a Contact section with an interactive map, directions,
hours, and phone.

## How it's built

It's a static, single-page site with no build step or framework — just vanilla
HTML, CSS, and JavaScript.

- **Single page:** everything lives in `index.html`, with the styles and scripts
  inline. Tabbed navigation (About / Menu / Contact) swaps content client-side.
- **Design tokens:** brand colors and scale are defined as CSS custom properties
  in `css/tokens.css` and documented in `design-system.md`. Reference tokens
  rather than hardcoding values.
- **Fonts:** [Montserrat](https://fonts.google.com/specimen/Montserrat) for body
  text and [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P)
  for the retro arcade touches, loaded from Google Fonts.
- **Map:** the Contact tab uses [Leaflet](https://leafletjs.com/) with CARTO
  basemap tiles, loaded lazily the first time the tab is opened.
- **SEO & social:** Schema.org `CafeOrCoffeeShop` structured data (JSON-LD),
  Open Graph and Twitter Card meta tags, plus `sitemap.xml` and `robots.txt`.
- **PWA / mobile:** web app manifest, Apple touch icons, an iOS splash-screen
  script (`js/ios-pwa-splash.js`), and theme-color metadata.

### Easter egg

There's a little something hidden in the site for the curious. Poke around — you
might just wake the lake. 🚤
