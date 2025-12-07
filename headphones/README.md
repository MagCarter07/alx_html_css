📄 ALX HTML/CSS + JS Project – Headphones Webpage
📌 Overview

This project is part of the ALX Front-End Specialization, where the goal is to recreate a premium, responsive landing page for a fictional audio company using HTML and CSS, based strictly on a provided Figma design.

Although the original ALX brief allows only HTML and CSS, I implemented one extra enhancement using JavaScript:

✔️ A fully interactive hamburger menu

This enables opening/closing mobile navigation smoothly without relying on the checkbox hack — while keeping all original CSS styles intact.

All styling and structure faithfully follow the design specifications.

🎯 Project Goals

Rebuild the Figma layout with clean, semantic and accessible HTML.

Use modern CSS for layout, styling, animations, and responsive behavior.

Implement a mobile-first navigation experience.

Maintain a clean project structure with organized assets.

🗂 Project Structure
project/
│── 0-index.html
│── 0-styles.css
│── 1-index.html
│── 1-styles.css
│── 2-index.html
│── 2-styles.css
│── 3-index.html
│── 3-styles.css
│── 4-index.html
│── 4-styles.css
│── 6-index.html
│── 6-styles.css
│── 7-index.html
│── 7-styles.css
│── 8-index.html
│── 8-styles.css
│── menu.js
│── README.md
│
├── images/
│ ├── desktop_preview.png
│ ├── tablet_preview.png
│ ├── mobile_preview.png
│ ├── headphones_hero_1.jpg
│ ├── headphones_hero_2.jpg
│ └── logo_headphones.png
│
└── Spin-Cycle-OT/
├── spincycle_ot.otf
└── spincycle_3d_ot.otf

🧩 Features Implemented

1. Header & Navigation

Responsive nav bar with custom hamburger animation.

JS-controlled toggle for smaller screens.

Pixel-accurate spacing and alignment based on the Figma design.

2. Hero Section

Full-width background image.

Centered headline, supporting text, and CTA button.

Typography styled using the project’s custom fonts.

3. “What We Do” Section

Four service blocks with icons, headings, and descriptions.

Flexible layout that adapts from desktop → tablet → mobile.

4. Results Section

Custom “kite-shaped” graphic containers.

Overlaid percentage statistics.

Background image with centered layout.

5. Contact Section

Clean input fields with bottom-border style.

Fully responsive layout that scales across devices.

6. Footer

Social icons

Copyright

Brand logo

🎨 Styling Principles

Custom fonts integrated using @font-face.

CSS variables for color and theme consistency.

Flexbox-based layout for all major sections.

Mobile-first and tablet breakpoints using media queries.

Smooth transitions for interactive elements.

📱 Responsiveness

The entire page dynamically adapts based on viewport size:

🖥 Desktop (≥ 1000px)

Centered content with fixed max width

Multi-column layouts

📱 Mobile (≤ 600px)

Collapsed nav replaced by animated hamburger

Sections stack vertically

Images scale fluidly

📟 Tablet (600px – 999px)

Reduced margins

More compact grid arrangements

🖼 Final Page Previews
Desktop View

Tablet View

Mobile View

🛠 Tools & Resources Used

Figma — layout and spacing references

VS Code — coding environment

Chrome DevTools — testing and responsive preview

Spin Cycle OT & Source Sans Pro — typography

📦 JavaScript Enhancement (Optional Feature)

Although the original project restricts JavaScript, a small, optional enhancement was added:

✔️ Hamburger Menu Script (menu.js)

Opens/closes nav menu on mobile

Animates hamburger → X → hamburger

Fully replaces checkbox hack

Doesn’t modify existing CSS structure

📋 Final Checklist
Requirement Status
Pixel-accurate match to Figma ✔️
Fully responsive (desktop/tablet/mobile) ✔️
Semantic HTML structure ✔️
CSS variables + clean selectors ✔️
Custom fonts implemented ✔️
Animated hamburger menu ✔️ (JS-based)
No external frameworks ✔️

This project is part of the ALX Front-End Web Development Curriculum.
Design by Nicolas Philippot.
Implementation by Magnus Afiawo (2025).

👤 Author

Magnus Afiawo
Front-End Developer & UI Implementation Specialist
ALX Africa – Front-End Web Developmentg Cohort
