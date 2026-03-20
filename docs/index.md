---
layout: default
title: Accueil
nav_order: 1
---

<style>
  /* CONFIGURATION DU MODE SOMBRE TOTAL (Menu + Contenu) */
  :root {
    --main-bg: #0d1117;
    --side-bg: #0d1117; 
    --accent-blue: #58a6ff;
    --neon-blue: #00d4ff;
    --text-white: #e6edf3;
    --border-color: #30363d;
  }

  /* 1. Fond global du site et de la barre latérale */
  body, 
  .side-bar, 
  .main-content-wrap, 
  .main-content,
  .site-header {
    background-color: var(--main-bg) !important;
    color: var(--text-white) !important;
  }

  /* 2. Texte du menu latéral en blanc */
  .nav-list-link, 
  .site-title, 
  .nav-list-expander,
  .site-button {
    color: var(--text-white) !important;
  }

  /* 3. Effet au survol des liens du menu */
  .nav-list-link:hover {
    background-color: #161b22 !important;
    color: var(--neon-blue) !important;
  }

  /* 4. Titres stylés avec lueur */
  h1, h2, h3 { 
    color: var(--neon-blue) !important; 
    border-bottom: 1px solid var(--border-color) !important;
    text-shadow: 0 0 8px rgba(0, 212, 255, 0.2);
  }

  /* 5. Boutons personnalisés */
  .btn-primary { 
    background-color: #5d3fd3 !important; /* Violet/Bleu Onshape */
    border-color: #5d3fd3 !important;
    color: white !important;
  }
  
  .btn-repo {
    border: 1px solid var(--text-white) !important;
    color: var(--text-white) !important;
  }
</style>

<div style="text-align: center; padding: 40px 0;">
  <h1 style="font-size: 2.5em; text-transform: uppercase; letter-spacing: 3px; margin-bottom: 10px;">
    Machine That Draws <span style="color: white;">- Groupe 10</span>
  </h1>
  <p style="color: var(--accent-blue); font-family: monospace;">> SYSTÈME DE TRAÇAGE AUTOMATISÉ GÉNÉRATION 2026</p>
  
  <div style="margin-top: 20px;">
    <a href="URL_DE_TON_ONSHAPE" class="btn btn-primary fs-5 mb-4 mb-md-0 mr-2">Notre projet sur Onshape</a>
    <a href="https://github.com/Makerspace-Amiens-2025-26/MachineThatDraws-Groupe10" class="btn btn-repo fs-5 mb-4 mb-md-0">Notre repo GitHub</a>
  </div>
</div>

---

## 🛰️ EXPLORATION 3D DU PROTOTYPE
*Manipulez le modèle ci-dessous pour découvrir la structure interne de la machine.*

<div style="border: 2px solid #30363d; border-radius: 12px; overflow: hidden; background: #000; box-shadow: 0 0 25px rgba(0, 212, 255, 0.15);">
  <iframe height="600" width="100%" src="https://modelembedder.net/embed?did=8b8c43a593a6e22dfd5bf280&wvm=v&wvmid=a17a5659704397e41d2346cb&eid=a178174cd77496a5cd270f55&elementType=ASSEMBLY" frameborder="0"></iframe>
</div>

---

## 👥 L'UNITÉ DE DÉVELOPPEMENT
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px;">
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">MEMBRE 1</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Mécanique & CAO</p>
  </div>
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">MEMBRE 2</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Électronique & Firmware</p>
  </div>
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">MEMBRE 3</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Interface & Algorithmes</p>
  </div>
</div>

---

## 📺 TRANSMISSION VIDÉO
<div style="text-align: center; margin-top: 20px;">
  <video width="100%" controls style="max-width: 850px; border-radius: 10px; border: 1px solid #30363d; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
    <source src="./images/intro_amiens.mp4" type="video/mp4">
  </video>
</div>

---

## 🖼️ POSTER TECHNIQUE
<div style="text-align: center; padding-bottom: 50px;">
  <img src="./images/poster.jpg" alt="Poster" style="max-width: 100%; border-radius: 8px; border: 1px solid #30363d;">
</div>
