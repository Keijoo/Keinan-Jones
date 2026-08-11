# Keinan Jones - Personal Portfolio

> *"built by trial, error, and a bit of stubbornness"*

Live at **[keijoo.github.io/Keinan-Jones](https://keijoo.github.io/Keinan-Jones/)**

---

## About

A single-page personal portfolio and timeline - part professional showcase, part personal archive. It follows a road/path metaphor inspired by Twenty One Pilots, tracing the journey from Ebbw Vale, Wales to Lohja, Finland, through university, a cross-country move, and an ongoing career in software development.

Built entirely as one HTML file. No frameworks, no build tools, no dependencies beyond a Google Fonts import and Formspree for the contact form.

---

## Features

- **Scroll-driven timeline** - waypoint cards marking life and career milestones, with a road line and animated marker dot that tracks progress down the page
- **Skills constellation** - canvas-based animated star map showing tech stack, with twinkling nodes and connecting lines
- **Finland photo gallery** - three photos with staggered fade-in on scroll, hover colour reveal, and 3D tilt on mouse movement
- **Ambient background** - Sagittarius constellation SVG (my sign) with a glow filter, slow-drifting radial gradients, and a cursor particle trail
- **Contact form** - inline Formspree form at the bottom of the page, plus a modal triggered by pressing `K`
- **Ambient audio** - optional background music with smooth fade-in/out toggle
- **Animated stats** - live counters for days in Finland, years coding, degree, and Finnish level
- **Honest skills breakdown** - animated fill bars across three columns: comfortable, learning, exploring

### Easter Eggs

- **Konami code** (↑↑↓↓←→←→BA) - triggers a visual glitch spectacle followed by a 15-second star-catching mini game. On mobile, tap the ♪ button 7 times quickly instead
- **Sagittarius constellation** - click 5 stars to trigger a brief acknowledgment
- **Idle doodle** - leave the page alone for 10 seconds and it starts drawing on its own
- **Console messages** - open devtools and see what's waiting

---

## Structure

```
Keinan-Jones/
├── index.html          # Everything - HTML, CSS, and JS in one file
├── Photos/
│   ├── hero.jpg        # Profile photo
│   ├── photo-1.jpg     # Finland gallery
│   ├── photo-2.jpg
│   └── photo-3.jpg
└── I Will Go To You 4.mp3   # Ambient audio
```

---

## Tech

- Vanilla HTML, CSS, JavaScript - no frameworks
- Canvas API for the cursor trail, idle doodle, and skills constellation
- IntersectionObserver for scroll-triggered reveals
- SVG filters for constellation glow effects
- Formspree for contact form handling
- Google Fonts (JetBrains Mono, Inter)
- GitHub Pages for hosting

---

## Running Locally

Just open `index.html` with a local server - the audio and photos won't load from `file://` due to browser security restrictions.

If you use VS Code, the easiest way is the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer):

1. Open the project folder in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. Visit `http://127.0.0.1:5500`

---

## Notes

This site is intentionally personal. The copy is honest, the timeline is real, and the easter eggs are there for the kind of person who looks for them. If you found one - nice work.

---

*Welsh in Finland. Still figuring it out.*# Keinan Jones - Personal Portfolio

> *"built by trial, error, and a bit of stubbornness"*

Live at **[keijoo.github.io/Keinan-Jones](https://keijoo.github.io/Keinan-Jones/)**
