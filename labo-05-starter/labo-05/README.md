# Labo 5 - reflecties

Naam: (Jolien WOuters)

## 1. Letterraster

- Wat gebeurt er als je in de template één gebied een L-vorm geeft, en waarom?

CSS Grid werkt met rechthoeken. Als je een vlak een rare L-vorm geeft, weet het rooster niet meer hoe het de cellen moet opdelen en crasht je layout.

- Hoeveel declaraties zou dezelfde plaatsing met `grid-column` en `grid-row` vragen?

Met grid-template-areas teken je in één oogopslag de hele plattegrond. Als je dat met losse lijnnummers (grid-column/row) zou moeten doen, moet je voor elk vlak apart gaan typen bij welke lijn het begint en eindigt, wat veel meer werk is.

## 2. Citaten

- Waarom lijnt de tweede rij bij 1280 px niet uit met de eerste zoals een grid dat zou doen?
  We gebruikten hier geen Grid, maar Flexbox (flex-wrap: wrap). Flexbox vult een rij op en springt door naar de volgende. Als een tekst bovenaan per toeval iets langer is, blijft een element daaronder daaraan hangen.

- Wat verandert er als je de basis van 18rem naar 30rem zet, en waarom?

rem is een maat. Als je de basisbreedte veel groter zet (30rem), past een citaat simpelweg niet meer met z'n vieren naast elkaar, waardoor er minder op een rij komen te staan

## 3. Fotolijst

- Waar belanden de vlakjes als je `position: relative` van de lijst weghaalt, en waarom?

Een element met position: absolute zoekt altijd naar een voorouder met een positie (zoals relative) om zich aan vast te hechten. Haal je dat weg bij de lijst, dan schieten de blokjes naar de rand van het hele scherm.

- Waarom ligt roze zonder `z-index` onder groen?
  Omdat het groene vlak eerder in je HTML-code staat dan het roze vlak. In webdesign is "wie het laatst komt, maalt het eerst" (komt iets later in de code, dan ligt het erbovenop).

## 4. Toonzaal

- Wat gebeurt er als je `top: 0` weghaalt, en waarom?

position: sticky betekent "blijf plakken". Maar je moet wel vertellen waar hij moet plakken. top: 0 zegt: plak vast zodra de bovenkant van het scherm de balk raakt. Zonder top: 0 weet de browser niet wanneer hij moet plakken.

- Wat is het verschil met `position: fixed` voor de rest van de pagina, en welke extra declaratie zou fixed nodig hebben?

position: fixed plakt een balk vast aan het venster en haalt hem uit de normale paginaflow. Gevolg: je tekst eronder schuift er blind achter en verdwijnt, tenzij je extra ruimte (padding) toevoegt.

## 5. Koffiebar Kaai 12

- Welke drie vragen van deze week (container, item, plaatsing) beantwoordde je waar in deze pagina?

1. Container regel je bij de body (het grote grid).
2. Item regel je bij de .kaart en .tekst (flexbox zodat alles netjes onder elkaar staat).
3. badge (position: absolute) en de prijs (margin-top: auto).

- Haal `aspect-ratio` weg bij de foto's: wat gebeurt er met het rooster, en waarom?

## Thuis: B5.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1.
2.
3.
