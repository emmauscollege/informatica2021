---
layout: default
title: gitpod
parent: Tools
nav_order: 4
---

# Gitpod
## Wat is gitpod?
Gitpod is een online editor die werkt met een dockerimage.
Dat wil zeggen dat je een dockerimage kunt draaient in de cloud. Dit image draait tijdelijk, zodra je gitpod sluit wordt de status van het dockerimage bewaard.
De editor heeft de look and feel van visual studio code
Enkele functies van gitpod:
- editor
- syntax checks door middel van kleuren van code
- preview venster voor bestanden, waaronder .html, .md enzovoort
- code uitvoeren in een dockerimage
- shell access op het dockerimage
- poorten van het dockerimage tijdelijk open zetten voor de buitenwereld
- koppeling met github om je code op github te bewaren

## Documentatie
[https://www.gitpod.io/docs/](https://www.gitpod.io/docs/)

## Account aanmaken
1. Ga naar [https://www.gitpod.io/](https://www.gitpod.io/).
2. Gebruik je github account om in te loggen

We gebruiken een gratis account, daarmee kun je public repo's uit github bewerken maximaal 50 uur per maand.

## Startcode van github naar gitpod kopieren (eenmalig)
1. Ga naar de https://github.com/
2. Kies de repo met startcode
3. Type in de browser voor de link: https://gitpod.io/#... \
... is https://github.com/jouw-organisatie-jouw-repo/

## Werken aan je project:
1. **Start** : ga naar https://gitpod.io/ en start je workspace
2. **Pull** : Haal alle updates van GitHub binnen in gitpod.
3. **Codeer** : Maak / verander je programmeercode.
4. **Save (all)** : Sla je veranderingen op.
5. **Probeer** : Test uit of het werkt.
6. **Stage** : Zet de bestanden klaar voor de commit.
7. **Message** : Typ een korte maar begrijpelijke commitboodschap.
8. **Commit** : Maak een nieuw punt in je tijdlijn.
9. **Push** : Duw je commit van gitpod naar GitHub.

## How-to
### nog geen how-to's toegevoegd

## Q&A
### Ik krijg een foutmelding dat ik geen schrijfrechten op de repo heb
De meest voorkomende reden voor deze fout is dat gitpod geen schrijftoegang heeft tot github. Dit kun je als volgt aanpassen.\
Klik rechtsboven op je account-icoontje, kies vervolgens "Access Control" in het menuutje dat verschijnt, 
zet alle vinkjes onder "Github" aan, klik update, geef toestemming in github als github daarom vraagt (groene knop).
### Hoe kan ik zien hoeveel gitpod gebruik ik deze maand nog over heb?
Klik rechtsboven op je account-icoontje, kies vervolgens "Account" in het menuutje dat verschijnt.
### Mijn 50 uur gratis gitpod gebruik zijn op
Bijna alle leerlingen hebben genoeg aan 50 uur per maand. Als dit bij jouw een keer niet zo is, dan kun je dit als volgt oplossen.\
Bewaar al je werk op gitpod vlak voordat je tijd op is. Maak met een ander e-email adres een nieuwe gitpod account aan, 
maak een workspace met je github code erin (https://gitpod.io/#https/github.com/jouw-oragnisatie/jouw-repo/). Je hebt nu weer 50 uur.

