# Ember & Oak — one-page coffee shop website

A single-file, dependency-free landing page for a neighbourhood coffee bar.
Open `index.html` in any browser — nothing to install, no build step.

## What's in it

- **Hero** with an animated steam/cup illustration and floating info badges
- **Scrolling marquee** strip
- **Menu** — three grouped cards (Espresso Bar, Slow & Cold, From the Kitchen) with prices
- **Our Roast** story section with stat tiles
- **Visit** — opening hours (today's row highlights itself) and contact details
- **Order ahead** call-to-action button with a toast confirmation
- Sticky blurred header, mobile hamburger nav, scroll-reveal animations

## Design notes

- Warm palette: cream `#FBF4EC`, espresso `#241610`, caramel `#C2763A`, clay `#8C4A2F`
- Type pairing: *Fraunces* (display) + *Inter* (text), loaded from Google Fonts with
  system fallbacks, so the page still looks right offline
- Fully responsive from 320px up; respects `prefers-reduced-motion`
- No frameworks, no build tooling — one HTML file, ~28 KB

## Customising

Everything themeable lives in the `:root` block at the top of the `<style>` tag.
Menu items are plain `<li>` rows in the `#menu` section — edit the name, the
`<small>` description and the `.price` span.
