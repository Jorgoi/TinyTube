# TinyTube
TinyTube trims any YouTube URL to its shortest possible format.
A clean, fast, and privacy-focused client-side web utility that strips tracking parameters
(`?si=...`), playlist clutter (`&list=...`), and excess parameters from YouTube URLs, reducing
them to their shortest valid `youtu.be` format.
## Live Demo
https://Jorgoi.github.io/TinyTube/
![TinyTube screenshot](Sreenshot.png)
## Why TinyTube?
Sharing links directly from YouTube often results in bloated URLs filled with personal tracking
tokens, playlist counters, and feature tags. **TinyTube** extracts the canonical 11-character
video ID in real time and provides a clean, clutter-free link ready for messaging, email, or social
media.
## Key Features
- **Instant URL Minimization:** Strips tracking tokens (`?si=...`), playlist IDs (`&list=...`,
`&index=...`), and referrer metadata down to clean `youtu.be/ID` links.
- **Single & Bulk Processing:** Paste an individual URL or an entire list of mixed YouTube links
at once.
- **In-Text Mode:** Paste whole messages or emails—TinyTube cleans the links in place while
leaving your text intact.
- **Customizable Output:** Toggle optional protocol prefix (`https://`), keep timestamps (`?t=`), or
remove duplicate links.
- **100% Client-Side:** No server, no backend tracking, no third-party analytics. Everything runs
locally in your browser.
## Tech Stack
- Single-file zero-dependency architecture (`index.html`)
- HTML5, modern vanilla JavaScript, Tailwind CSS (CDN)
- Hosted on GitHub Pages
## License
This project is licensed under the MIT Licence.
