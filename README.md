# Anuj Sarode – Personal Portfolio

A multi-page portfolio website for Anuj Sarode (Electrical and Electronics Engineering, semiconductor and advanced packaging). Built from static HTML, shared CSS, and minimal JavaScript.

## Structure

- **index.html** – Home: hero, summary, and Explore cards (Education, Skills, Experience, Leadership, Interests)
- **education.html** – Education (ASU MS, IIST BTech) and certifications (CFA, Coursera)
- **skills.html** – Technical skills with clickable items that show related experience in a popup
- **experience.html** – Professional experience at ISRO (SE, SD, SC)
- **leadership.html** – Leadership and volunteer work
- **interests.html** – Other interests: Astrophotography, Finance, Adventure Sports, DIY
- **astrophotography.html** – Deep-sky image gallery
- **finance.html** – Finance interest and certifications
- **adventure-sports.html** – Adventure sports + links to Scuba Diving and Skydiving
- **scuba-diving.html** – Scuba certifications timeline with certificate images and lightbox
- **diy.html** – DIY interest
- **portfolio.html** – One-page resume (light theme, in-page sections)

## Assets

Place images in the `assets/` folder. Referenced files include:

- **Certifications:** `cfa-level1.png`
- **Scuba:** `open-water.png`, `advanced-open-water.png`, `enriched-air-diver.png`, `deep.png`, `sidemount.png`, `advanced-nitrox.png`, `decompression-procedures.png`
- **Astrophotography:** `orion-horsehead.png`, `trifid.png`, `heart-nebula.png`, `sadr-region.png`, `rosette.png`, `pacman.png`

Copy these from your existing Portfolio project or add your own.

## Running locally

Open `index.html` in a browser, or serve the folder with any static server (e.g. `npx serve .` or Python `http.server`).

## Tech

- HTML5, CSS3 (shared `styles.css`, page-specific styles where needed)
- Vanilla JS: `main.js` (menu, scroll animations, header), plus inline scripts for skills popup and scuba lightbox
- No build step; works with file:// or any static host