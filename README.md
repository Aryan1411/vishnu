# Vishnu — Civil Aviation Pilot Portfolio

## Overview
A lightweight, aesthetic, single-page portfolio website for Vishnu, a professional pilot in civil aviation with more than 4 years of flying experience. The site highlights experience, operational proficiency, certifications, and provides quick contact options.

Key features:
- Elegant aviation-themed design (animated clouds by day, stars by night)
- Responsive layout that works across desktop and mobile
- Accessible and keyboard-friendly UI
- Dark/light theme toggle with local preference storage
- No external dependencies for fast loads and offline-friendly usage

## Setup
No build tools are required.

- Option 1: Double-click index.html to open in any modern browser.
- Option 2: Serve locally for best results:
  - Python 3: python -m http.server 8080
  - Node: npx serve
  - Then visit http://localhost:8080

All assets are inline; there are no external network requests, ensuring the page loads quickly.

## Usage
- Navigate via the header links to About, Experience, Skills, Certifications, and Contact.
- Theme toggle: Click “Theme” to switch between light and dark modes; your preference is saved.
- Contact:
  - The “Email Vishnu” button uses a mailto link. Replace vishnu@example.com with the correct address in index.html (two places: Contact section and footer) and in the JSON-LD script if you wish.
  - Update the social links (LinkedIn/Resume) in the Contact section by replacing the placeholder href="#" values.
- CV download: The “Download CV” button is a placeholder. Replace its href="#" with a valid file path (e.g., ./assets/Vishnu_CV.pdf) and ensure the file exists.
- Content customization: All text is within index.html. Search for sections by their IDs (#about, #experience, #skills, #certs, #contact) and update as needed.

Performance tips:
- Keep everything inline as provided for optimal load time.
- If adding images, compress them and consider using modern formats (WebP/SVG).

## License
MIT License

Copyright (c) 2025 Vishnu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.