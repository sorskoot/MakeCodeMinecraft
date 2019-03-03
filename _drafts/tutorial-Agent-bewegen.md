---
layout: post
title:  "De agent laten bewegen"
date:   2019-03-03 10:35:00am
excerpt:  Hoe kun je de agent commando's geven om te bewegen?
---
# Agent

Het wordt tijd dat we de agent wat aan het werk zetten. Daarvoor is het handig als we de agent kunnen besturen. We gaan vandaag 3 chatopdrachten maken om de agent te besturen.

{% include image.html src="/assets/post_img/agent-bewegen/de-agent.png" title="De Agent." %}

## Chatopdracht 1

Soms staat de agent best wel een eind weg. Het zou erg makkelijk zijn als we hem kunnen roepen. De eerste chatopdracht die we gaan maken doet precies dat. Als we een nieuw project beginnen krijgen we weer de 2 standaard gebeurtenissen, we kunnen de _Bij Opstarten_ gebeurtenis verwijderen. Bij de andere gebeurtenis veranderen we de tekst in "_kom_". Dit zorgt ervoor dat als we "kom" typen in de chat in Minecraft dan wordt de code binnen de gebeurtenis uitgevoerd. De opdracht de we gaan geven heet _Agent Teleporteer naar Speler_ en je kunt hem vinden in de _Agent_-categorie. Sleep de opdracht naar de _Bij Chatopdracht_-gebeurtenis. Ga nu naar Minecraft en typ "kom" in de chat. Als het goed is komt de agent nu naar je toe.

{% include image.html src="/assets/post_img/agent-bewegen/BijChatopdracht-Kom.png" title="Bij Chatopdracht - Kom" %}

## Chatopdracht 2

De agent kijkt nu nog altijd dezelfde kant uit. Meestal is het nodig de agent in een andere richting te laten kijken. We kunnen de agent een opdracht geven om te draaien, naar links of naar rechts.
Om dit te kunnen doen hebben een nieuwe chatopdracht nodig. Sleep er eentje naar je werkblad vanuit de _Speler_-categorie en verander de tekst in "_draai_".
De opdracht die we moeten uitvoeren heet _Agent Draai_ en die kun je vinden in de _Agent_-categorie. Sleep dezen naar de nieuwe chatopdracht.
Als je nu naar Minecraft gaat kun je je nieuwe commando uitvoeren in de chat. Als het agent moet nu gaan draaien.
{% include image.html src="/assets/post_img/agent-bewegen/BijChatopdracht-Draai.png" title="Bij Chatopdracht - Draai" %}

## Chatopdracht 3

De laatste opdracht die we agent gaan laten uitvoeren is naar voren bewegen. Om dit te kunnen doen hebben we nog een _Bij Chatopdracht_-gebeurtenis nodig. Sleep er eentje vanuit de _Speler_-categorie naar je werkblad en verander de tekst naar "_vooruit_".
De opdracht die we moeten uitvoeren heet _Agent Beweeg_ en staat in de _Agent_-categorie. Deze opdracht heeft 2 argumenten. In de eerste staat de richting waarin de agent moet gaan bewegen. In de lijst kun je alle richtingen kiezen.
In het tweede argument staat het aantal blokken dat de agent moet bewegen. Stanaard staat deze op 1 blok, maar je kunt heb veranderen in wat je wilt.

{% include image.html src="/assets/post_img/agent-bewegen/BijChatopdracht-Vooruit1.png" title="Bij Chatopdracht - Draai" %}

Je wilt de agent natuurlijk niet altijd hetzelfde aantal blokken vooruit bewegeen. Soms is het 1 blok, maar soms misschien wel 25. Het zou mooi zijn als we een argument kunnen maken waar we het aantal blokken kunnen meegeven in de chat.
Dit kan door op de **+** te klikken naast de tekst in de chatopdracht. Er komt nu een argument bij met de naam _num1_. Je kunt je voorstellen dat dit niet de meest handige naam is. Nu kun je misschien nog wel onthouden dat "num1" het aantal blokken is, maar als je programma groter wordt en je veel verschillende argument hebt is het handiger het argument een duidelijke naam te geven. Dit kan door op het argument te klikken. Er komt nu een menu tevoorschijn en als je op "Naam van variable wijzigen" klikt kun het argument een nieuwe naam geven. Ik heb de variable "_Aantal_" genoemd, omdat er het 'aantal' blokken in staat dat de agent moet gaan beweegen.

{% include image.html src="/assets/post_img/agent-bewegen/BijChatopdracht-Vooruit-VariablenaamWijzigen.png" title="Bij Chatopdracht - Draai" %}

De plaats waar de waarde bewaard wordt heet "Variable". De waarde van een variable kun je instellen in een argument, maar ook op elke andere plaats in je programma. In een latere tutorial komen we hier op terug.
Nu moeten we de variable gaan gebruiken. Variablen die je aangemaakt hebt staan in de _Variablen_-categorie.

{% include image.html src="/assets/post_img/agent-bewegen/BijChatopdracht-Vooruit-VariableAantal.png" title="Bij Chatopdracht - Draai" %}

Als je de variable sleept naar de plaats waar ' 1 ' staat in de _Agent Beweeg_-opdracht wordt de waarde van de variable daar gebruikt.

{% include image.html src="/assets/post_img/agent-bewegen/BijChatopdracht-Vooruit-VariableAantal-Plaatsen.png" title="Bij Chatopdracht - Draai" %}

Als het goed is ziet je chatopdracht er uit als hier onder en kun je hem gaan testen in je Minecraft door bijvoorbeeld "vooruit 5" in te typen in de chat om de agen 5 blokken vooruit te bewegen.

{% include image.html src="/assets/post_img/agent-bewegen/BijChatopdracht-Vooruit2.png" title="Bij Chatopdracht - Draai" %}

## Wat nog meer

Nu weet je hoe je de agent simple opdrachten kunt geven, nieuwe chatopdrachten kunt maken en eigen argumenten kunt gebruiken. Kun je zelf een chatopdract bedeken om de agent naar rechts te laten draaien?

Als je dat gelukt is, zou je het voor elkaar kunnen krijgen om de agent een blok te laten plaatsen? **hint**: deze opdracht staat in de _Agent_-categorie bij de acties. 