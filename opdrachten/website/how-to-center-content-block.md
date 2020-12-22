---
layout: default
title: Block centreren
nav_order: 1
parent: Website
grand_parent: Opdrachten
---

# Block centreren

Hoe centreer ik een block-element, bijvoorbeeld een `<div>` midden in de pagina, of alle inhoud van een webpagina?

Een stukje HTML:

```html
<body>
  <div id="bedenk-je-eigen-id">Dit block moet gecentreerd worden</div>
</body>
```

Een stukje CSS:

```css
#bedenk-je-eigen-id {
  width: 200px;
  margin: auto;
}
```  

Voorbeeld in repl.it:
<iframe height="400px" width="100%" src="https://repl.it/@cammeraat/HTMLcenter?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>