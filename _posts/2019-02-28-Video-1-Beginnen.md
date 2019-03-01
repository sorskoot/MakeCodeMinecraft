---
layout: video
title:  "Kippenregen!"
date:   2019-03-01 9:45:00am
excerpt:  YouTube Video - Kippenregen!
video: qkY6e94Fz5Y
---

In deze nieuwe tutorial laat ik je zien hoe je een mod voor Minecraft kunt programmeren om het kippen te laten regen.

Mocht je er niet helemaal uitgekomen zijn kun je het eindresultaat [hier](/assets/downloads/mkcd/minecraft-Kippenregen.mkcd) downloaden.

# Extra

Aan het einde van de video sprak ik over het op een willekeurige positie spawnen van de kippen. Zoals we het programma nu geschreven hebben spawnen de kippen altijd direct boven je hoofd. Leuker is het als de kippen verschijnen ergens boven je hoofd en om je heen. Makecode heeft hier een speciaal blok voor: _Kies Willekeurige Positie_. Je kunt dit blok vinden in de _Posities_-categorie. Je moet dit blok op de plek van de relative positie zetten in het _Spawn_-blok. In plaats van 1 positie, moet je bij het _kies willekeurige positie_-blok 2 coördinaten meegeven. Hiertussen wordt een willekeurig positie gekozen die elke keer anders is. Als je bijvoorbeeld een gebied boven je hoofd wilt hebben kun je een gebied aangeven van -10, 10, -10 naar 10, 10, 10. Dit betekend dat de kippen nog steeds 10 blokken boven je hoofd verschijnen, maar mogelijk 10 blokken naar links, naar rechts, naar voor of naar achter. Het programma ziet er dan zo uit:

{% include image.html src="/assets/post_img/kippenregen/kippenregen-willekeurig.png" title="kippenregen" %}