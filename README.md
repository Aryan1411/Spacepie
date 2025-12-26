# Spacepie — Mining the Future Beyond Earth

Overview
- Spacepie is a cinematic, documentary-style single-page website for a space mining company focused on safe, sustainable extraction of non-hazardous materials from asteroids and the Moon.
- The experience combines a dark, futuristic UI with smooth scroll storytelling, micro-animations (rockets, asteroids, robotic arms, data flows), and parallax starfields.
- 100% responsive with mobile-first navigation and performant animations that respect reduced-motion preferences.

Key Features
- Hero: Animated orbital scene with rocket/asteroid and parallax starfield background.
- The Problem: Minimal copy with animated data bars highlighting resource depletion and environmental impact.
- Our Solution: Cards explaining asteroid selection, lunar processing, robotic extraction, and AI safety.
- How It Works: Interactive stepper showcasing the journey from space → Moon → Earth with subtle animated diagrams.
- Technology: Four tech pillars with animated iconography.
- Sustainability & Safety: Clear, trust-building commitments with a live radar motif.
- Contact: Indore headquarters, phone, embedded OpenStreetMap, and a functional contact form (client-side validation + local persistence).

Tech Stack
- HTML5, CSS3, vanilla JavaScript (no external dependencies for fast loads).
- SVG and Canvas for lightweight, performant visuals and animations.

Performance
- No heavy images or frameworks. Uses vector art and canvas.
- Pauses background animation on hidden tab to save resources.
- Respects prefers-reduced-motion.
- Loads quickly on low-end devices.

Accessibility
- Semantic sections and clear headings.
- aria-live for form status, focusable stepper with keyboard arrows.
- High contrast, large touch targets and responsive typography.

Setup
- No build step required.

Run locally
1. Save the repository files.
2. Open index.html in any modern browser.
3. Optional: serve via a local server for best results:
   - Python: python3 -m http.server 8080
   - Node: npx serve

Usage
- Navigate using the header or mobile menu (☰).
- Scroll through the story: Problem → Solution → Journey → Technology → Safety → Contact.
- Try the How It Works stepper: scroll horizontally on desktop or swipe on mobile; use Arrow keys when focused.
- Contact: Fill in name, valid email, and message. On submit, the app validates, simulates sending, and stores messages in localStorage under spacepie_messages. A mailto link is provided as an alternative.

Notes
- Map uses an OpenStreetMap embed. Internet is required for the embed to load; otherwise, the rest of the site works offline.
- Form submission is client-side only; integrate with your backend or services like Formspree to send emails server-side.

License
MIT License

Copyright (c) 2025 Spacepie

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.