---
title: Contatti
layout: default
permalink: /contatti/
css: /assets/css/contatti.css # carica il foglio di stile dedicato
---


<div class="contenitore">
  <div class="form-container">
    <h2>Contattaci</h2>
    Compila il form per contattarmi.
    <form action="https://formspree.io/f/mzzdgbdb" method="POST">
      <label>Nome: <input type="text" name="name" required></label>
      <label>Email: <input type="email" name="email" required></label>
      <label>Telefono: <input type="tel" name="phone"></label>
      <label>Messaggio: <textarea name="message" required></textarea></label>
      <button type="submit">Invia</button>
    </form>
  </div>
  <div class="image-container">
    <img src="/assets/images/placeholder_contatti.jpg" alt="Immagine contatti">
  </div>
</div>
