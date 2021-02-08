---
layout: default
title: Kolom links
nav_order: 2
parent: Website
grand_parent: Opdrachten
---

# Kolom links met vaste breedte

![plaatje van kolom met vaste breedte](../../.gitbook/assets/how-to-create-a-fixed-width-column-figure-1.png)

Hoe maak ik een kolom links met een vaste breedte?

Dit kun je bijvoorbeeld gebruiken als je links een menu wilt neerzetten.

Een stukje HTML en CSS:

{% tabs %}
{% tab title="HTML" %}
{% code title="index.html" %}
```markup
<body>
  <p class="kolomLinks">
    Links een kolom met een vaste breedte.
  </p>
  <p class="kolomRechts">
    Rechts een kolom met een variabele breedte. 
  </p>
  <div class="floatClear"></div>
  <p>
    Tekst over de volle breedte.
  </p>
</body>
```
{% endcode %}
{% endtab %}

{% tab title="CSS" %}
{% code title="style.css" %}
```css
.kolomLinks {
  float: left;
  width: 100px;
}

.kolomRechts {
  float: left;
  width: calc(100% - 100px - 40px); 
}

.floatClear {
  clear: both;
}
```
{% endcode %}
{% endtab %}
{% endtabs %}

Denk eraan dat de marge, border en padding tussen de twee kolommen ook plaats innemen. En vergeet niet om de clear na de kolommen op te nemen. De html die na de clear komt gebruikt weer de volle breedte.

Voorbeeld in repl.it:

