---
title: "Torte"
description: "Le nostre colazioni artigianali"
date: 2025-04-14
menu:
  vetrina:
    weight: 1
---
<style>
  .torta-catalogo {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 20px;
  }

  .torta-item {
    flex: 1 1 calc(25% - 20px);
    text-align: center;
  }

  .torta-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
  }

  .torta-item p {
    margin-top: 8px;
    font-weight: 500;
  }

  @media (max-width: 768px) {
    .torta-item {
      flex: 1 1 calc(50% - 20px);
    }
  }

  @media (max-width: 480px) {
    .torta-item {
      flex: 1 1 100%;
    }
  }
</style>

<div class="torta-catalogo">
  <div class="torta-item">
    <img src="torta1.png" alt="Torta 1">
    <p>Cioccolato Compleanno</p>
  </div>
  <div class="torta-item">
    <img src="torta2.png" alt="Torta 2">
    <p>Tartufone</p>
  </div>
  <div class="torta-item">
    <img src="torta3.png" alt="Torta 3">
    <p>Compleanno</p>
  </div>
  <div class="torta-item">
    <img src="torta4.png" alt="Torta 4">
    <p>Tronchetto gelato</p>
  </div>
</div>

<div class="torta-catalogo">
  <div class="torta-item">
    <img src="torta5.png" alt="Torta 1">
    <p>Torta Montagna</p>
  </div>
  <div class="torta-item">
    <img src="torta6.png" alt="Torta 2">
    <p>Torta Mimosa</p>
  </div>
  <div class="torta-item">
    <img src="torta7.png" alt="Torta 3">
    <p>Compleanno</p>
  </div>
  <div class="torta-item">
    <img src="torta8.png" alt="Torta 4">
    <p>San Valentino</p>
  </div>
</div>

<p style="margin-top: 30px; font-size: 1rem;">
  Hai in mente una torta speciale? La realizziamo su misura per te! Scrivici o chiamaci, trovi tutto nella sezione <strong>Contatti</strong>.
</p>