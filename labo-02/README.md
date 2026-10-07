# Labo 2 - reflecties

Naam: Denys Moroz

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: elke link die in lijsten die binnen nav die binnen header 
- b. `article > p`:  elke paragraf die een direct (buitenste) kind van article
- c. `.uren li:nth-child(3)`: ergens binnen class "uren" het derde kind van zijn ouder dat  "li" moet zijn
- d. `h2 ~ p`: kijkt na h2, maar altijd binnen dezelfde ouder
- e. `.rassen li:first-child`: ergens binnen class "rassen" het eerste kind van zijn ouder dat "li" moet zijn

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |groen |mijn regel |groen |juist |
| 2 |blauw |laatste in het bestand |blauw |juist |
| 3 |rood class blauw em|class>element |rood+em |fout |
| 4 | rood a ergens binnen| laatste in het bestand |rood |juist |
| 5 | blauw|id's winnen altijd |blauw |juist |
| 6 |blauw en "vraag 6" rood|eigen regels en de laatste overwrites de eerste |blauw en "vraag 6" rood|juist |
| 7 |alles rood |class instelling |rood |juist |
| 8 |rood |een style-attribuut in html verslaat selectors |blauw |fout |
| 9 | rood h3|!important red |rood |juist |
| 10 | groen maar geen 1.5 rem vanwege de foutieve declaratie|foutieve declaratie |groen |juist |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
Vragen 8 en 10 waren de moeilijkste vanwege interessante regels en foutieve declaraties. Om een of andere reden was vraag 7 ook moeilijk voor mij.
## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
Vanwege  gebrek aan ervaring en abstract begrip van meerdere concepten, kostte bijna alles wat tijd en daarna nog meerdere aanpassingen om de code robuster te maken. In de navigatie koos ik nav a en footer a. Ik heb dat gedaan omdat het gewoon gemakkelijker is ,en ik geen nut van class zag.
## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
Er zijn meer dan drie, maar de voornamelijkste zijn de kleuren voor de tekst, de achtergrond en de font voor de tekst. Omdat sommige kleuren en lettertypen niet overduidelijk zijn en die ​​uit hexadecimale waarden bestaan. Om ze gemakkelijk meerdere keren te kunnen gebruiken, is het zeer handig.
- Wat verandert er in je site als je één token wijzigt?
Al de elementen waarop je de token toegapst heb, zullen ok van waarde veranderen.


## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
