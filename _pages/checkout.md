---
layout: single
title: "Checkout"
permalink: /checkout/
classes: wide
---

<div class="checkout">
<div>
<form class="checkout-form">

## Kundeninformationen

<label for="vName">Vorname*</label>
<input
  type="text"
  id="vName"
  name="vName"
  required>

<label for="nName">Nachname*</label>
<input
  type="text"
  id="nName"
  name="nName"
  required>

<label for="email">E-Mail*</label>
<input
  type="email"
  id="email"
  name="email"
  required>

<label for="company">Unternehmen</label>
<input
  type="text"
  id="company"
  name="company">

<label for="address">Adresse*</label>
<input
  type="text"
  id="address"
  name="address"
  required>

## Zahlungsinformationen

<label for="card">Karteninhaber*</label>
<input
  type="text"
  id="cName"
  name="cName"
  required>

<label for="card">Kartennummer*</label>
<input
  type="text"
  id="card"
  name="card"
  required>

<label for="expiry">Ablaufdatum*</label>
<input
  type="text"
  id="expiry"
  name="expiry"
  placeholder="MM/JJ"
  required>

<label for="cvc">CVC*</label>
<input
  type="text"
  id="cvc"
  name="cvc"
  required>

<label class="checkbox">
  <input type="checkbox" required>
  <span>Ich akzeptiere die <a href="/agb/">AGB und Lizenzrechte</a>.*</span>
</label>

<button
  type="submit"
  class="btn btn--primary">
  Kostenpflichtig bestellen
</button>

</form>
</div>
<div>

## Bestellübersicht

| Produkt | Preis |
|---|---:|
| Pro Tarif | € 600,- |
| 0 Zusatzmodule | € 0,- |
| OCR-Addon | € 20,- |
| **Gesamt** | **€ 620,-** |

<span class="license"> <small>Zusätzliche Module kosten € 200 / Monat. </small></span>

</div>

</div>