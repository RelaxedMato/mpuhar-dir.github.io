---
layout: single
title: "Kontakt"
permalink: /contact/
---
<form action="">

  <label for="name">Name</label>
  <input
    type="text"
    id="name"
    name="name"
    required
  >

  <label for="email">E-Mail</label>
  <input
    type="email"
    id="email"
    name="email"
    required
  >

<label for="title">Betreff</label>
  <input
    type="text"
    id="title"
    name="title"
    required
  >

  <label for="message">Nachricht</label>
  <textarea
    id="message"
    name="message"
    rows="6"
    required
  ></textarea>

  <button class="btn btn--primary">
    Nachricht senden
  </button>

</form>