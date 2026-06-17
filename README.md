# Animated Content Landing Page

A single-page landing page concept for a content creation agency, built using **pure HTML and CSS** — no JavaScript, no animation libraries. The main feature is an infinite, multi-layered horizontal marquee effect created entirely with CSS keyframes.

🔗 **Live Demo:** https://khadija-faisal1.github.io/animated-landing-page/

---

## What This Project Does

The page displays a hero section with an image and headline, layered on top of three rows of continuously scrolling "Brand" text. Each row animates independently:

- **Row 1** — solid text, scrolling left to right
- **Row 2** — outlined (stroke-only) text, scrolling left to right, layered above Row 1 and the image for a depth effect
- **Row 3** — solid text, scrolling in the opposite direction (right to left)

All three animations run continuously and automatically on page load — they are not triggered by user scrolling, despite the name. They use CSS `@keyframes` and `transform: translateX()` only.

## Features

- Infinite CSS-only marquee animation across three independent, differently-styled layers
- Z-index layering so text, image, and headline overlap intentionally rather than just stacking
- Custom display font (Monument Extended Bold) for a bold, editorial look
- Color-coded micro-labels (Play / Video / About / Us) for quick visual hierarchy
- Responsive viewport meta setup as a base for mobile scaling

## Built With

- HTML5
- CSS3 (Flexbox, absolute positioning, keyframe animations)

## Running Locally

```bash
git clone https://github.com/yourusername/animated-content-landing-page.git
```

Then just open `index.html` in any browser. No build tools, no server, no dependencies.

## Notes

The custom font is loaded from a third-party CDN. If it fails to load, the layout and animations still work, only the typography falls back to the browser default.

## Preview

<img width="1920" height="843" alt="preview" src="https://github.com/user-attachments/assets/9aa10f85-2ec0-4930-b965-631fa5f3c669" />


---

Practice project from my self-paced full-stack development learning.
