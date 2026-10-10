# Labo 3 - reflecties

Jolien Wouters

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af? 
Antwoord: De inspringing (padding/margin aan de linkerkant) en de bolletjes (list-style-type).

- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet? De hoogte van de banden verandert mee, de breedte verandert niet.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?
text-align: center voor de tekst en margin: 0 auto (gecombineerd met een vaste max-width) voor de kolom.
- Waarom werkte de padding op de knop pas na `display: inline-block`?
Omdat een knop (een <a>-element) standaard een inline-element is.

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border? Exact 15rem door border box

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet? 
Omdat de ouder van de cirkel (het oranje buitenste vierkant) een expliciete hoogte heeft meegekregen (90vh)

- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?

Tegen de breedte van de ouder.

## 5. Landingspagina


- Gaf je `main` een `height` of een `min-height`, en waarom? Een min-height.   Uitleg: Als je een vaste height gebruikt en de inhoud is groter dan het scherm, dan loopt de tekst uit de box (overflow). Met min-height zorg je ervoor dat het element minstens de gevraagde hoogte heeft, maar kan uitbreiden als er meer inhoud is.   
- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`? er onstata witruimte

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
