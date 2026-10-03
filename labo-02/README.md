# Labo 2 - reflecties

Naam: (jouw naam)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`:  Alle links die in een lijst item staan , die in een lijst staat , die in een navigatie staat, die dan in de header staan.
- b. `article > p`:  alle paragraven die rechstreeks in een artikel staan
- c. `.uren li:nth-child(3)`: Het derde lijs item in de class genaamd 'uren'
- d. `h2 ~ p`:  alle paragraven die na h2 staan , met ook dezelfde houder hebbben.
- e. `.rassen li:first-child`:  het eerste lijst item in de class genaamd 'rassen'

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | | | | |Groen wint omdat er maar één CSS-regel is die dit element aanspreekt.
| 2 | | | | | Blauw wint omdat beide selectors even sterk zijn. Daarom wint de regel die als laatste in de CSS staat.
| 3 | | | | | Rood wint omdat een class (.opvallend) sterker/specifieker is dan een element (em).
| 4 | | | | | Groen wint omdat .v4 > a specifieker is dan .v4 a.
| 5 | | | | | Blauw wint omdat een ID (#v5-tekst) sterker is dan een class (.een.twee.drie).
| 6 | | | | | Blauw wint omdat beide selectors even sterk zijn en de blauwe regel als laatste staat.
| 7 | | | | | Rood wint omdat er maar één CSS-regel is die de kleur bepaalt.
| 8 | | | | | Rood wint omdat er maar één CSS-regel is die de kleur bepaalt.
| 9 | | | | | Rood wint omdat !important sterker is dan een gewone CSS-regel.
| 10 | | | | | Groen wint omdat de andere kleurcode niet geldig is . Er is gene ; gezet waardoor deze niet geldig is .

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?) Alles juist , ik twijfelde over vraag 10 omdat ik dacht dat ik miss per ongeluk die ; weg had gedaan.

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?  
`--color-accent`: deze gebruik ik voor de kleur van mijn navigatielinks.
- `--color-text`: deze gebruik ik voor de gewone tekst op mijn website.
- `--font-body`: deze gebruik ik als lettertype voor de tekst op mijn website.
- Wat verandert er in je site als je één token wijzigt? Als ik één token wijzig, verandert de waarde op alle plaatsen waar dat token gebruikt wordt. Als ik bijvoorbeeld `--color-accent` verander, krijgen mijn navigatielinks automatisch een andere kleur.

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. **Pixel-soep:** de AI gebruikt veel `px`, bijvoorbeeld `padding: 40px 20px`, `max-width: 800px` en `margin: 40px auto`. Volgens **2.8 / F2.9** moet `px` niet gebruikt worden voor tekst en zijn `rem` en andere geschikte eenheden bedoeld voor relatieve afmetingen.

2. **Overspecifieke selectors:** in deze output komt bijvoorbeeld `.kaart li:nth-child(even)` voor. De cursus waarschuwt bij **R2.3** voor overspecifieke selectors. Volgens **2.5** kun je met de structuur van de HTML selecteren zonder overal extra classes te gebruiken.

3. **`!important`:** de AI gebruikt in deze output geen `!important`. Dit is dus juist **geen fout** in deze output. Volgens **F2.5/F2.6** en de AI-slide is `!important` iets dat je moet herkennen als het voorkomt.

4. **Verweesde waarden:** de AI gebruikt `font-family: Georgia, serif;` rechtstreeks in `body`, terwijl de cursus bij **2.9** zegt dat je met design tokens werkt en waarden via `var()` uitleest. Een font is juist een voorbeeld van een waarde die als token kan worden benoemd.

5. **Geneste spelling:** de AI gebruikt in deze output geen geneste CSS-spelling. Dit is dus ook **geen fout** in deze specifieke output. De cursus zegt bij **2.5** dat je geneste spelling moet kunnen lezen en naar de platte vorm moet kunnen vertalen.

