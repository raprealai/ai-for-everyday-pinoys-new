# AI for Everyday Pinoys

Welcome to the **AI for Everyday Pinoys** landing page project!

This is a modern, responsive landing page designed to offer accessible AI tools, kits, and prompts specifically tailored for Filipinos. It features a clean, premium visual design and an integrated 3D holographic background.

## Features

* **Premium "AI format" Aesthetic:** Designed with striking colors (Navy, Gold, Red), noise texture overlays, and modern typography (Outfit & Plus Jakarta Sans).
* **3D Hero Background:** Features a highly optimized, interactive "Breathing Holographic Orb" built using pure WebGL and Three.js running within a custom Fragment/Vertex Shader.
* **Fully Responsive:** Adapts seamlessly across desktop, tablet, and mobile devices.
* **Performance Focused:**
    * Zero heavy dependencies (Three.js loaded via CDN).
    * `devicePixelRatio` capped for battery optimization.
    * Uses `IntersectionObserver` to halt 3D processing when scrolled out of view.
    * Animations pause when the browser tab is hidden.

## Tech Stack

* **HTML5:** Semantic architecture.
* **Vanilla CSS3:** Custom styling, variables, keyframe animations, and responsive flexbox/grid layouts.
* **JavaScript (Vanilla):** Light DOM manipulation.
* **Three.js (r128):** 3D WebGL rendering, Custom ShaderMaterials (GLSL), Mouse mapping.

## Setup & Deployment

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/your-username/ai-for-everyday-pinoys-new.git
   \`\`\`
2. **Open locally:** Include `index.html` in your favorite local server (like VSCode Live Server) or simply open it in your browser.
3. **Deploy:** This repository consists of a static `index.html` file and can be hosted seamlessly through GitHub Pages, Vercel, Netlify, or any standard web host.

## Author

* **Ralph Angelo Real** - AI Strategist, Bicol Region
