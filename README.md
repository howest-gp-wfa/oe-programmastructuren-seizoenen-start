# oe-programmastructuren-seizoenen-start
In deze opdrachten laten we het verschillende seizoenen 'regenen'.
Wanneer een seizoen aangetikt wordt met één van de buttons, dan programmeer je welke afbeeldingen er getoond moeten worden voor dat seizoen.

## Beginsituatie
Bekijk voor je begint de HTML-pagina en de CSS-pagina.
Op de index-pagina werd reeds het script gekoppeld alsook de CSS.

### Reeds aanwezig in HTML
Op de index-pagina vind je een twee `div`-elementen:
|div id|functie|
|------|-------|
|imagecontainer|deze doet dienst al container voor de afbeeldingen in je programma|
|buttoncontainer|deze doet dienst al container voor de knoppen op de pagina|

### Reeds aanwezig in CSS
In CSS staan reeds een aantal regels en animaties beschreven. Hier hoeft je **niets mee te doen**, maar weet dat ze instaan voor het animeren van de afbeeldingen die terecht komen in `#imagecontainer`.

## Opdrachten
Voeg telkens aan `#imagecontainer` een aantal `img`-elementen toe. De afbeeldingen die gekoppeld moet worden vind je in de map `images`.

### 1. Maximum aantal afbeeldingen
Voorzie een variabele die bij houdt dat het maximale aantal afbeeldingen `5` is. Je zal deze variabele straks doorheen je volledige script gebruiken.

### 2. Clear Images
Maak een functie die de inhoud van het HTML-element `#imagecontainer` wist. Deze zal je nodig hebben wanneer je straks switcht tussen verschillende knoppen.

### 3. Summer
Schrijf een  `for`-lus die het maximale aantal zomerblaadjes toevoegt aan `#imagecontainer`.
De zomerblaadjes vind je in `/images/summer`.

### 4. Winter
Schrijf een  `do ... while`-lus die het maximale aantal sneeuwvlokjes toevoegt aan `#imagecontainer`.
De sneeuwvlokjes vind je in `/images/winter`.

### 5. Spring
Schrijf een  `for`-lus die het maximale aantal lente-afbeeldingen toevoegt aan `#imagecontainer`.
De lente-afbeeldingen vind je in `/images/spring`.

Echter:
* indien het getal van je teller deelbaar is door 2, dan toon je de afbeelding met het bloemetje.
* is het niet deelbaar door 2, dan toon de de afbeelding van de bijtjes.

### 6. Autumn
Schrijf een  `for`-lus die het maximale aantal herfst-afbeeldingen toevoegt aan `#imagecontainer`.
De herfst-afbeeldingen vind je in `/images/autumn`.

Gebruik een `switch` om het volgende te bereiken:
* Indien de teller gelijk is aan 0, dan toon je het bruine blad
* Indien de teller gelijk is aan 2, dan toon je het geel blad
* Indien de teller gelijk is aan 4, dan toon je het groen blad
* In alle andere gevallen toon je de afbeelding van de eikel.





