---
layout: home
title: "Home"
---

<style>

/* --- PALETA GENERAL --- */
:root {
  --bg-deep: #111827;               /* más elegante y un poquito más claro */
  --bg-panel: rgba(45, 53, 78, 0.82); 
  --text-main: #eaeaff;
  --text-soft: #cfd3ff;
  --link: #a9cafe;
  --link-hover: #d2b7ff;
  --accent: #c5a3ff;
  --shadow-orbit: rgba(197,163,255,0.28);
}

/* --- FONDO GENERAL Y TIPOGRAFÍA --- */
body {
  background: var(--bg-deep);
  color: var(--text-main);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
               Helvetica, Arial, sans-serif;
}

/* --- LINKS --- */
a {
  color: var(--link);
  text-decoration: none;
}
a:hover {
  color: var(--link-hover);
}

/* --- HEADER --- */
.site-header {
  background: rgba(17, 24, 39, 0.55);
  backdrop-filter: blur(8px);
  border-bottom: 1px solid rgba(197,163,255,0.12);
  box-shadow: 0 4px 16px rgba(0,0,0,0.3);
}

.site-title, .site-title a {
  color: var(--text-main) !important;
  letter-spacing: 0.6px;
}

/* --- PANEL PRINCIPAL --- */
.page-content {
  background: var(--bg-panel);
  padding: 3rem 2.4rem;
  border-radius: 26px;
  max-width: 980px;
  margin: 3rem auto;
  box-shadow: 0 18px 50px var(--shadow-orbit);
  border: 1px solid rgba(255,255,255,0.05);
}

/* --- TÍTULOS --- */  
h1, h2, h3 {
  color: var(--text-main);
  text-shadow: 0 0 10px rgba(197,163,255,0.30);
}

/* --- LOGO: halo etéreo --- */
img[src*="logo"] {
  display: block;
  margin: 2.6rem auto 3rem;
  width: 230px;
  filter:
    drop-shadow(0 0 14px rgba(197,163,255,0.45))
    brightness(1.1);
  opacity: 0.98;
}

/* Separadores tipo nebulosa */
hr {
  border: none;
  height: 1px;
  background: linear-gradient(
    90deg,
    transparent,
    rgba(197,163,255,0.35),
    transparent
  );
  margin: 2.1rem 0;
}


/* Footer astral */
.site-footer {
  text-align: center;
  padding: 1.4rem 0 1.8rem;
  background: transparent;
  border-top: 1px solid rgba(255,255,255,0.08);
  color: var(--text-soft);
  font-size: 0.9rem;
  opacity: 0.9;
}


/* Mejora de espaciados superiores */
.page-content h1:first-of-type {
  margin-top: 1.2rem;
  text-align: center;
}

/* Más aire alrededor del logo */
img[src*="logo"] {
  margin-top: 1.8rem;
  margin-bottom: 2.2rem;
}

/* Títulos de sección con acento mandálico */
h2 {
  position: relative;
  padding-bottom: 0.4rem;
  margin-top: 2.2rem;
  margin-bottom: 1.2rem;
}

h2::after {
  content: "";
  display: block;
  width: 70px;
  height: 2px;
  background: linear-gradient(
    90deg,
    transparent,
    var(--accent),
    transparent
  );
  margin: 0.4rem auto 0;
  opacity: 0.6;
}

  
</style>

<!-- ✨ Bloque superior: Mandala + Foto personal -->
<div style="display: flex; justify-content: center; gap: 2rem; align-items: flex-start; flex-wrap: wrap;">

  <!-- Mandala izquierda -->
  <img src="logo.png"
       style="width: 230px; border-radius: 12px;">

  <!-- Foto tuya derecha -->
  <img src="mecagoengemini.jpg"
       style="width: 230px; border-radius: 12px;">

</div>

<br>

<!-- 🌌 JWST centrado abajo -->
<p align="center">
  <img src="webb_glimpses_the_distant_past_pillars.jpg"
       style="max-width: 700px; width: 100%; border-radius: 10px;">
</p>

# Susana Pedrosa

Astrophysicist · Galaxy Formation & Evolution · Numerical Simulations & HPC  

---

- [About](#about-me)
- [Research](#research)
- [Publications](#publications)
- [Software & Tools](#software--tools)
- [Aerospace & Industry](#aerospace--industry)
- [Contact](#contact)

---

## About Me

I am an astrophysicist based at IAFE (UBA–CONICET) in Buenos Aires, Argentina.  
My research focuses on galaxy formation and evolution across cosmic time, with particular interest in:

- Angular momentum and galaxy structure
- The physics of the Cosmic Dawn and Reionization
- Cosmic Web and galaxy properties, Planes of Satellites 
- Low-surface-brightness galaxies (LSBGs)    

I work mainly with cosmological hydrodynamical simulations and numerical analysis.

---

## Research

My current and recent topics include:

- **Galaxy formation and evolution** in cosmological hydrodynamical simulations  
- **Feedback at Cosmic Dawn** (HMXBs and their impact on the ISM/IGM)  
- **Bulge/disk decomposition** and inner galaxy components
- **Chemo-dynamical analysis** of galaxies in the CIELO simulations  
- **Low-surface-brightness galaxies (LSBGs)** and angular-momentum–dark-matter coupling  

---

## Publications

A curated selection will appear here soon.  

For a complete and updated list, visit:  
👉 https://orcid.org/0000-0002-0144-8545

---

## Software & Tools

I regularly work with:

- Python, Jupyter, NumPy, pandas, Matplotlib  
- Cosmological simulations: EAGLE, TNG, FirstLight, CIELO, SWIFT  
- High-performance computing (HPC)  

---

## Exploring Industry & Aerospace Opportunities

I am actively working to bring my expertise in simulations, numerical modeling, and HPC into industry-oriented environments, particularly in aerospace. I have experience leading student teams and collaborative research efforts, coordinating technical workflows and ensuring results under demanding conditions. I am interested in opportunities where complex-system modeling, performance optimization, and scientific computing can contribute directly to technology development and mission-driven projects.

---

## Contact

- Institute: IAFE (UBA–CONICET), Buenos Aires  
- GitHub: https://github.com/su9000
- LinkedIn: https://www.linkedin.com/in/susana-pedrosa-2a876118/
- Email: susana.pedrosa@gmail.com

---

*This site is built with GitHub Pages (theme: minima).*

*This site is built with GitHub Pages.*
