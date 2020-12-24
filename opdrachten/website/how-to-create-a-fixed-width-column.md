---
layout: default
title: Kolom links
nav_order: 2
parent: Website
grand_parent: Opdrachten
---

# Kolom links met vaste breedte

Hoe maak ik een kolom links met een vaste breedte?

Dit kun je bijvoorbeeld gebruiken als je links een menu wilt neerzetten.

Een stukje HTML:

```html
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

Een stukje CSS:

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

Denk eraan dat de marge, border en padding tussen de twee kolommen ook plaats innemen. 
En vergeet niet om de clear na de kolommen op te nemen. De html die na de clear komt gebruikt weer de volle breedte.

Voorbeeld in repl.it:
<iframe height="400px" width="100%" src="https://repl.it/@emmauscollege/kolomVasteBreedte?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
