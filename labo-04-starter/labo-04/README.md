# Labo 4 - reflecties

Naam: (jouw naam)

## 1. Drie kolommen

- Op welk element staat `display: flex`, en op welke elementen staat `flex`?
Display flex staat op main div' en flex staat bij main div:nth-child
- Waarom staan die twee niet op hetzelfde element?
display: flex maakt van main een flex-container. De property flex bepaalt hoeveel ruimte de kolommen krijgen. Daarom staan ze op verschillende elementen.

## 2. Navigatiebalk

- Welke property verdeelt de ruimte langs de hoofdas, en welke lijnt uit op de kruisas?
justify-content verdeelt de ruimte langs de hoofdas. align-items lijnt de elementen uit op de kruisas.
- Wat gebeurt er met de links als je `gap` vervangt door `margin-right` op elke `li`?
Er komt ook ruimte tussen de links, maar met margin-right krijgt elk li-element een rechtermarge. Daardoor kan er ook onnodige ruimte achter het laatste element ontstaan. Met gap regel je alleen de ruimte tussen de elementen.

## 3. Mondriaan

- Welke twee vlakken moest je expliciet plaatsen, en waarom volstond de impliciete vulling voor de andere vier?
De twee brede vlakken moesten expliciet geplaatst worden met grid-column, omdat ze meerdere kolommen innemen. De andere vier vlakken konden automatisch in de overgebleven cellen geplaatst worden door Grid.
- Waarom is `gap` hier beter dan een border op elk vlak?
Met gap zie je de blauwe achtergrond tussen de vlakken en aan de buitenrand. Met borders zouden de randen van de vlakken zelf gekleurd zijn en zouden ze tegen elkaar kunnen dubbele lijnen vormen.

## 4. Trap

- Wat zie je als je de `grid-row`-declaraties weghaalt, en waarom?
De treden komen naast elkaar op de eerste rij te staan, omdat Grid ze automatisch plaatst wanneer je niet aangeeft op welke rij ze moeten staan.
- Wat betekent `grid-column: 4 / -1` voor de laatste trede, en waarom werkt het hier ook?
De laatste trede begint bij kolomlijn 4 en loopt tot de laatste kolomlijn. -1 verwijst naar de laatste lijn van het raster. Het werkt omdat het raster hier vier kolommen heeft.


## 5. Dierenasiel Zonnehoek


- Hoeveel layoutcontainers telt deze pagina, en welk gereedschap koos je voor elk?
Er zijn minstens vijf belangrijke layoutcontainers: body gebruikt Grid voor de pagina-indeling, header gebruikt Flexbox voor de navigatiebalk, .kaarten gebruikt Grid voor de kaarten, elke .kaart gebruikt Flexbox in de richting van een kolom en .beschrijving gebruikt flex: 1 om de knop onderaan te houden.

- Verklein het venster tot de helft: wat breekt er, en in welk hoofdstuk wordt dat opgelost?

De kolommen en kaarten kunnen te smal worden en de inhoud kan minder goed passen. Dit wordt opgelost met responsive design, waarbij je de layout aanpast aan de schermgrootte. De opdracht verwijst hiervoor naar hoofdstuk 5.1 tot en met 5.3.



## Thuis: B4.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
