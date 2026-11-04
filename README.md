# Wonderworks Studio

Single-page site for Wonderworks Studio (voiceover and event DJ).

- `index.html` is the whole site: HTML, CSS and JS in one file. Three.js loads from a CDN.
- `images/` holds the gallery photos referenced by the page.
- `audio/demo-reel.mp3` (optional): add a voiceover demo to enable the play button in the Voiceover section.
- `fonts/Mokoto.woff2` (optional): add the licensed Mokoto font; Michroma is the fallback.

The hero plays `video/wonderworks-promo.mp4` on click, with sound. The site has no background music.

Before launch: set `BOOKING_EMAIL` near the top of the script in `index.html` and replace the placeholder social links in the footer.

Deploy: any static host works (GitHub Pages, Vercel, Netlify). No build step.
