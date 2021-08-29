---
layout: default
title: Toetsenbord
nav_order: 5
parent: Game
grand_parent: Opdrachten
---

# Toetsenbord gebruiken

Je kunt spelers laten bewegen met de toetsen op het toetsenbord. Veel gebruikte toetsen zijn de pijltjes toetsen of de toetsen W,A,S en D voor omhoog, links, omlaag en rechts. Voor springen of schieten wordt vaak de spatiebalk gebruikt.

# Het toetsenbord gebruiken in games
De p5js library biedt meerdere mogelijkheden om het toetsenbord te gebruiken. Voor games is de functie KeyIsDown(nummerVanDeToets) het meest geschikt. 
Het resultaat van deze functie is TRUE als de toets met het opgegeven nummer op het moment dat de functie wordt aangeroepen ingedrukt is. Je kunt zien of meerdere toetsen tegelijk zijn ingedrukt door deze functie meerdere keren te gebruiken met steeds een ander nummer voor de toets. Dit kun je gebruiken om de speler tegelijk te laten springen en lopen, of om de speler schuin te laten lopen.

# Voorbeeld
Voorbeeld in repl.it:
<iframe height="400px" width="100%" src="https://repl.it/@emmauscollege/HowtoToetsenbord?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

# Meer informatie
- Meer informatie over KeyIsDown()\
[https://p5js.org/reference/#/p5/keyIsDown](https://p5js.org/reference/#/p5/keyIsDown)
- Opzoeken van nummers van toetsen\
[http://keycode.info](http://keycode.info)
