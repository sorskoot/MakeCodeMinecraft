---
layout: post
title:  "Kippenregen!"
date:   2019-02-27 9:45:00am
excerpt:  Tutorial. Laten we wat aan het weer doen.
---

# Regen

Bah, wat een weer! Het lijkt wel of het _altijd_ regent in Minecraft. Misschien kunnen we MakeCode gebruiken om het iets anders te laten regen? Kippen bijvoorbeeld!

{% include image.html src="/assets/post_img/kippenregen/banner.png" title="kippenregen" %}

## Nieuwe chatopdracht

Laten we beginnen met een nieuw project. Als je in MakeCode een nieuw project maakt begin je met de 2 meest gebruikte _gebeurtenissen_ (of 'events' in het engels). Gebeurtenissen worden automatisch uitgevoerd als er iets gebeurt in je Minecraft wereld of als er iets gebeurt in je programma. De gebeurtenis _Bij Opstarten_ wordt altijd uitgevoerd als je programma wordt geladen. Deze gaan we vandaag niet gebruiken en kun je verwijderen door erop te klikken (het blok krijgt een geel randje) en op de _delete_-toets op je toetsenbord de drukken. Je kunt een blok ook verwijderen door er met de rechter muisknop op te klikken en _Blok Verwijderen_ te selecteren. In deze tutorial gebruiken we alleen de _Bij Chatopdracht_ gebeurtenis.

{% include image.html src="/assets/post_img/kippenregen/gebeurtenissen.png" title="gebeurtenissen" %}

De _Bij Chatopdracht_-gebeurtenis wordt uitvoerd als de opgegeven tekst wordt ingetypt in de chat van Minecraft. De tekst staat nu nog op "run", maar dat gaan we veranderen. Je kunt op "run" klikken op de tekst aan te passen. Laten we te tekst veranderen in "_kip_". Om te testen of het werkt zetten we een _Zeg_-blok in de _Bij Chatopdracht_-gebeurtenis zetten. Je kunt het _Zeg_-blok vinden in de _Speler_ categorie in het menu. Sleep dit blok binnen het _Bij Chatopdracht_-blok zodat ze allebei blauw zijn. Als je nu naar Minecraft gaat en in de chat "_kip_" typt, zou je "Hi!" terug moeten krijgen.

{% include image.html src="/assets/post_img/kippenregen/chatopdracht-hoi.png" title="chatopdracht" %}

## Kip in de lucht

Om een kip te spawnen in de Minecraftwereld gebruiken we het _spawn_ commando (of 'statement' in het engels). Deze kun je vinden in de mobs categorie. Sleep hem naar je _bij chatopdracht_-gebeurtenis. Je kunt _zeg_-commando verwijderen als je wilt. Je kunt in het _spawn_-commando twee dingen instellen. Deze instellingen worden argumenten genoemd. Het eerste argument is het dier dat je wilt spawnen. Deze staat als eeste op 'kip'. Experimenteer gerust met andere dieren.
Het tweede argument is de positie waar de kip moet gaan verschijnen. De positie bestaat uit 3 getallen: X, Y en Z. Dit zijn 3 richtingen waarop je kunt bewegen in de Minecraftwereld. De ' ~ ' wil zeggen dat de positie relatief is ten opzichte van de speler.

{% include image.html src="/assets/post_img/kippenregen/coordinaten.png" title="coordinaten" %}

We willen de kip spawnen in de lucht, boven de speler. Daarvoor moeten we het tweede getal, het Y coördinaat, aanpassen. Als we deze een waarde van _10_ geven, betekend dit dat de kip 10 blokken boven de speler verschijnt. Als je het blok hebt staan kun je het in Minecraft proberen. Ga naar de chat en type 'kip'. Zie je de kip boven je hoofd?

{% include image.html src="/assets/post_img/kippenregen/spawn-kip.png" title="spawn-kip" %}

## Kippenregen

Maar één kip is nog geen kippen regen. We willen natuurlijk veel meer kippen. We zouden nog 100 keer een spawn-kip-opdracht kunnen maken, maar dat is niet echt efficiënt. Gelukkig is daar een oplossing voor: Een _Lus_. Lussen worden bij het programmeren veel gebruikt en zorgen ervoor dat je stukje van je programma kunt herhalen totdat aan een bepaalde voorwaarde is voldaan.
Als we een stuk code een aantal keer willen herhalen kunnen we hiervoor de _doe_-lus gebruiken. Deze kun je vinden in de _lussen_-categorie. Sleep deze naar het _bij chatopdracht_-blok en zorg ervoor dat deze om het _span_-commando komt te staan. De _doe_-lus heeft 1 argument, het aantal keer dat de code moet worden herhaalt. Zet deze op 100 om 100 kippen te spawnen.

{% include image.html src="/assets/post_img/kippenregen/programma.png" title="Eind resultaat" %}

Daarmee is het kippenregen-programma af. Als je nu naar minecraft en weer het 'kip'-command in de chat typt zul je heel veel kippen boven je hoofd zien verschijnen.

## Wat nog meer?

Kun je dit programma zelf veranderen? Zou het bijvoorbeeld ook koeien kunnen regenen? Zou je iets met de positie van het _spawn_-commando kunnen doen? Kijk maar eens of je het _kies willekeurige positie_-blok erin kunt krijgen.
