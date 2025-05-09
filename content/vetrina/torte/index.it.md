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
    <img src="img/torta1.jpg" alt="Torta 1">
    <p>Cioccolato · Compleanno</p>
  </div>
  <div class="torta-item">
    <img src="img/torta2.jpg" alt="Torta 2">
    <p>Pistacchio · Battesimo</p>
  </div>
  <div class="torta-item">
    <img src="img/torta3.jpg" alt="Torta 3">
    <p>Frutti di bosco · Laurea</p>
  </div>
  <div class="torta-item">
    <img src="img/torta4.jpg" alt="Torta 4">
    <p>Nutella · Anniversario</p>
  </div>
</div>
<p style="margin-top: 30px; font-size: 1rem;">
  Hai in mente una torta speciale? La realizziamo su misura per te! Scrivici o chiamaci, trovi tutto nella sezione <strong>Contatti</strong>.
</p>