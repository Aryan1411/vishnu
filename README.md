# Vishnu — Civil Aviation Pilot Portfolio

## Overview
A single-page, offline-friendly portfolio for Vishnu, a professional civil aviation pilot with 4+ years of flying experience. The page features an aesthetic animated sky background with drifting clouds by day, stars and moon by night, and tasteful planes flying across the horizon. It is responsive, fast, and accessible, with a built-in light/dark theme toggle.

Key features:
- Animated sky background:
  - Day: gradient sky, sun, drifting clouds
  - Night: deep sky gradient, moon, twinkling stars
  - Subtle planes cruising with contrails in the background
- Responsive layout for desktop and mobile
- Accessible navigation with keyboard and screen-reader-friendly markup
- Theme toggle with local preference storage
- No external dependencies; loads quickly and works offline

## Setup
No build tools or external assets are required.

- Option 1: Double-click index.html to open in any modern browser.
- Option 2: Serve locally for best results:
  - Python 3: python -m http.server 8080
  - Node: npx serve
  - Then visit http://localhost:8080

Everything is inline; there are no network requests.

## Usage
- Navigate via the header links to About, Experience, Skills, Certifications, and Contact.
- Theme toggle:
  - Click “Theme” to switch between light and dark modes; your choice is saved.
  - The sky adapts automatically (sun/clouds by day, moon/stars by night).
- Contact:
  - Email: Replace vishnu@example.com in two places (About and Contact sections) and in the footer, and optionally in the JSON-LD script.
  - Replace the placeholder links (LinkedIn/Resume) with real URLs.
- CV: Update the “Download CV/Resume” buttons to point to a valid file (e.g., ./Vishnu_CV.pdf).

Performance tips:
- Keep the app inline as provided for best load times.
- If you add images, compress them (WebP/SVG recommended).
- Animations honor reduced motion: users with prefers-reduced-motion will see fewer/simpler animations.

## Improvements in Round 2
From the previous version, the background has been significantly enhanced to better reflect a living sky scene:
- New animated sky with layered gradient, sun by day and moon by night
- Procedurally generated twinkling stars at night
- Soft, drifting clouds with parallax-like motion
- Animated airplanes cruising across the background with subtle contrails
- Performance-conscious spawning and automatic pausing when tab is hidden
- Respects prefers-reduced-motion to reduce visual movement when requested

All prior features remain: responsive layout, accessible navigation, theme toggle with saved preference, no external dependencies, and fast load times.

## License
MIT License

Copyright (c) 2025 Vishnu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.