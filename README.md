🚀 James Smite – Digital Marketing Portfolio

A modern, visually dynamic digital marketing portfolio showcasing projects, certifications, experience, and contact information.
Built with HTML, CSS, JavaScript, enhanced with 3D tilt hover effects, gradient lighting, and smooth UI transitions.

🌐 Live Demo

(Insert your deployed GitHub Pages or Netlify link here)
Example:
https://yourusername.github.io/portfolio-site/

✨ Features
🎨 Modern UI & Animations

Soft shadow depth + neon gradient highlights

Smooth hover transforms across projects, certifications, and experience sections

3D tilt hover effects powered by VanillaTilt.js

Responsive layouts for all screen sizes

ScrollReveal-friendly structure

🧩 Sections Included

Hero Section – Intro & CTA

About Section – Bio, skills, and profile image

Certificates Section – Hover-enhanced cards

Projects Section – Case studies with interactive thumbnails

Experience Section – Modern card layouts with animated images

Contact Section – Quick access to email

Footer – Social links & back-to-top button

🛠️ Tech Stack
Area	Technologies
Frontend	HTML5, CSS3, JavaScript
Animation	CSS transitions, keyframes, VanillaTilt.js
UI Enhancements	Gradients, lighting overlays, 3D hover effects
Icons	Font Awesome
Deployment	GitHub Pages / Netlify
📁 Project Structure
portfolio-site/
│
├── docs/                # Build folder for GitHub Pages deployment
│   ├── index.html
│   ├── styles.css
│   └── index.js
│
├── src/                 # Original development files (optional)
│
├── README.md
└── package.json         # Optional if using npm

🔧 How to Run Locally

Clone the repository:

git clone https://github.com/yourusername/portfolio-site.git


Navigate into the project:

cd portfolio-site


Open the site manually:

Double-click index.html OR

Use VS Code Live Server for auto-reload:

npx live-server .

🔥 Adding 3D Hover Effects (VanillaTilt)

Your project uses:

<div class="thumbnail tilt-hover" data-tilt data-tilt-max="4" data-tilt-glare="true" data-tilt-max-glare="0.5">


To enable tilt:

<script src="https://cdnjs.cloudflare.com/ajax/libs/vanilla-tilt/1.7.2/vanilla-tilt.min.js"></script>


Or inside index.js:

VanillaTilt.init(document.querySelectorAll("[data-tilt]"));

🎨 Editing Styles

All custom hover effects live at the bottom of styles.css under:

/* ============================
   MODERN HOVER EFFECTS
   ============================ */


You can customize:

Shadow intensity

Gradient colors

Hover transforms

Card layout

🚀 Deployment (GitHub Pages)

Push your final code to the docs/ folder

Go to Repository Settings → Pages

Select docs/ as the deploy source

Save → website becomes live!
