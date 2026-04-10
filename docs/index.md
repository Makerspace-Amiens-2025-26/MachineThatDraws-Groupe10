---
layout: default
title: Accueil
nav_order: 1
---

<style>
  :root {
    --main-bg: #0d1117;
    --side-bg: #0d1117;
    --accent-blue: #58a6ff;
    --neon-blue: #00d4ff;
    --text-white: #e6edf3;
    --border-color: #30363d;
    /* Définition de la couleur du bouton Onshape pour réutilisation */
    --btn-primary-bg: #5d3fd3;
  }

  body,
  .side-bar,
  .main-content-wrap,
  .main-content,
  .site-header {
    background-color: var(--main-bg) !important;
    color: var(--text-white) !important;
  }

  .nav-list-link,
  .site-title,
  .nav-list-expander,
  .site-button {
    color: var(--text-white) !important;
  }

  .nav-list-link:hover {
    background-color: #161b22 !important;
    color: var(--neon-blue) !important;
  }

  h1, h2, h3 {
    color: var(--neon-blue) !important;
    border-bottom: 1px solid var(--border-color) !important;
    text-shadow: 0 0 8px rgba(0, 212, 255, 0.2);
  }

  /* Style pour le bouton Onshape (et maintenant GitHub) */
  .btn-primary {
    background-color: var(--btn-primary-bg) !important;
    border-color: var(--btn-primary-bg) !important;
    color: white !important;
    transition: background-color 0.3s ease;
  }
  
  .btn-primary:hover {
    background-color: #4c32ab !important; /* Un peu plus sombre au survol */
    border-color: #4c32ab !important;
  }

  /* MODIFICATION DU BOUTON REPO GITHUB POUR ÉGALER ONSHAPE */
  .btn-repo {
    /* On applique les mêmes couleurs que .btn-primary */
    background-color: var(--btn-primary-bg) !important;
    border-color: var(--btn-primary-bg) !important;
    color: white !important;
    transition: background-color 0.3s ease;
  }

  .btn-repo:hover {
    background-color: #4c32ab !important; /* Même effet de survol */
    border-color: #4c32ab !important;
  }

  /* Écrase TOUS les styles hr de Just the Docs */
  hr,
  .divider,
  .main-content hr {
    background: none !important;
    background-color: transparent !important;
    border: none !important;
    border-top: 1px solid #30363d !important;
    height: 1px !important;
    margin: 32px 0 !important;
  }
</style>

<div style="text-align: center; padding: 40px 0;">
  <h1 style="font-size: 2.5em; text-transform: uppercase; letter-spacing: 3px; margin-bottom: 10px;">
    Machine That Draws <span style="color: white;">- Groupe 10</span>
  </h1>
  <p style="color: var(--accent-blue); font-family: monospace;">> Le projet "Machine that draws" coniste en la création d'une machine qui va dessier de manière automatisé avec du matériel fournie de base et de nos compétences !</p>

  <div style="margin-top: 20px;">
    <a href="https://cad.onshape.com/documents/8b8c43a593a6e22dfd5bf280/w/f337884a351008c809d7df22/e/a178174cd77496a5cd270f55?renderMode=0&uiState=69d8e3a393e9b9c5b111a1c9" class="btn btn-primary fs-5 mb-4 mb-md-0 mr-2">Notre projet sur Onshape</a>
    <a href="https://github.com/Makerspace-Amiens-2025-26/MachineThatDraws-Groupe10" class="btn btn-repo fs-5 mb-4 mb-md-0">Notre repo GitHub</a>
  </div>
</div>

<hr class="divider">

## 🛰️ EXPLORATION 3D DU PROTOTYPE
*Manipulez le modèle ci-dessous pour découvrir la structure interne de la machine.*

<div style="border: 2px solid #30363d; border-radius: 12px; overflow: hidden; background: #000; box-shadow: 0 0 25px rgba(0, 212, 255, 0.15);">
  <iframe height="600" width="100%" src="https://modelembedder.net/embed?did=8b8c43a593a6e22dfd5bf280&wvm=v&wvmid=01f7cd1fe38b59d1cf645123&eid=a178174cd77496a5cd270f55&elementType=ASSEMBLY" frameborder="0"></iframe>
</div>

<hr class="divider">

## 👥 Notre équipe (le groupe 10)

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px;">
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">Louis BOURBON</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Mécanique & CAO</p>
  </div>
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">Soren Crëpin</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Électronique & Firmware</p>
  </div>
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">Célian DAIX</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Interface & Algorithmes</p>
  </div>
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">Mathis FRANCOIS</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Interface & Algorithmes</p>
  </div>
  <div style="padding: 20px; background: #161b22; border-radius: 10px; border-top: 3px solid var(--neon-blue); box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
    <h3 style="margin: 0; font-size: 1.1em; border:none !important;">Alexandre BOUREL</h3>
    <p style="font-size: 0.9em; opacity: 0.8; margin-top: 5px;">Spécialité : Interface & Algorithmes</p>
  </div>
</div>

<hr class="divider">

## 📺 TRANSMISSION VIDÉO

<div style="text-align: center; margin-top: 20px;">
  <video width="100%" controls style="max-width: 850px; border-radius: 10px; border: 1px solid #30363d; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
    <source src="./images/intro_amiens.mp4" type="video/mp4">
  </video>
</div>

<hr class="divider">

## 🖼️ POSTER TECHNIQUE

<div style="text-align: center; padding-bottom: 50px;">
  <img src="./images/poster.jpg" alt="Poster" style="max-width: 100%; border-radius: 8px; border: 1px solid #30363d;">
</div>
