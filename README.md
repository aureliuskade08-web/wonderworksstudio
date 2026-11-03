# Wonderworks Studio

Single-page site for Wonderworks Studio (voiceover and event DJ).

- `index.html` is the whole site: HTML, CSS and JS in one file. Three.js loads from a CDN.
- `images/` holds the gallery photos referenced by the page.
- `audio/demo-reel.mp3` (optional): add a voiceover demo to enable the play button in the Voiceover section.
- `fonts/Mokoto.woff2` (optional): add the licensed Mokoto font; Michroma is the fallback.

The background lofi track is synthesized in the browser with the Web Audio API, so there is no audio file to host. It starts when the visitor clicks the entry button; drums and bass come in once they scroll.

Before launch: set `BOOKING_EMAIL` near the top of the script in `index.html` and replace the placeholder social links in the footer.

Deploy: any static host works (GitHub Pages, Vercel, Netlify). No build step.
