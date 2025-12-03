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

/* --- SEPARADORES --- */
hr {
  border: none;
  border-top: 1px solid rgba(197,163,255,0.25);
  margin: 2rem 0;
}

/* --- FOOTER --- */
.site-footer {
  background: transparent;
  border-top: 1px solid rgba(255,255,255,0.08);
  color: var(--text-soft);
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
  
</style>


<p align="center">
  <img src="/logo.png" width="200" style="border-radius: 50%;">
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
- Low-surface-brightness galaxies (LSBGs)  
- Feedback from compact-object stellar systems (e.g. X-ray binaries)  
- The physics of the Cosmic Dawn and Reionization  

I work mainly with cosmological hydrodynamical simulations and numerical analysis.

---

## Research

My current and recent topics include:

- **Galaxy formation and evolution** in cosmological hydrodynamical simulations  
- **Chemo-dynamical analysis** of galaxies in the CIELO simulations  
- **Feedback at Cosmic Dawn** (HMXBs and their impact on the ISM/IGM)  
- **Bulge/disk decomposition** and inner galaxy components  
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

## Aerospace & Industry

I am actively interested in:

- Applying numerical modeling and HPC to data-intensive scientific and technological environments  
- Exploring collaborations with **space** and **aerospace** companies  
- Translating expertise in **simulations and complex systems** to industry-impact projects  

---

## Contact

- Institute: IAFE (UBA–CONICET), Buenos Aires  
- GitHub: https://github.com/su9000  
- Email: susana.pedrosa@gmail.com

---

*This site is built with GitHub Pages (theme: minima).*

*This site is built with GitHub Pages.*
