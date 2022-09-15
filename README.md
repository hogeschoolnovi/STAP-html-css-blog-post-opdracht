# Opdrachtomschrijving
Als kersverse junior developer wil jij een toffe blogpagina gaan maken. Daar bestaan inmiddels allemaal fraaie tools
zoals bijvoorbeeld Wordpress of Wix voor, maar het is natuurlijk véél toffer om zelf een website te bouwen 🤩 (En bovendien een stuk goedkoper en efficienter!)

Je gaat de blogpagina opbouwen met verschillende `HTML elementen`. Benieuwd welke er allemaal zijn?
Je vindt [hier een overzicht van alle elementen.](https://www.w3schools.com/TAgs/default.asp)
Let op! Je gebruikt **geen CSS**.

Geen zin om te typen? Onderaan in `README` vind je alle dummytekst voor de opdracht.

## Inhoudsopgave
1. Eindresultaat
2. Randvoorwaarden
3. Stappenplan
4. Dummytekst

## Eindresultaat

![Het eindresultaat op desktop](assets/examples/voorbeeld-pagina-desktop-met-css.png)

![Het eindresultaat op mobiel](assets/examples/voorbeeld-pagina-mobiel-met-css.png)

## Randvoorwaarden
* Je gebruikt alleen HTML (geen CSS!);
* De CSS zal niet werken, als je niet de juiste `HTML-tag` gebruikt.
* Je mag de bestanden (`.css` & `.html`) niet verplaatsen;
* Je gebruikt de afbeeldingen uit de `assets` map.

## Stappenplan
Vind je het lastig om te beginnen? Volg dan het stappenplan.

_TIP_: Kom je er niet helemaal uit? Spiek dan soms in het CSS bestand. Maar doe dat niet te vaak 😉

De opdracht kan opgesplitst worden in drie onderdelen: een `header`
een `main` en een `footer`. We beginnen met het maken van de `header`.

### Deel 1: Header
- [ ] Open de `index.html`. Voeg een element toe met daarin een geneste `icon`, `H1 heading` en een stuk tekst.
- [ ] Voeg de blog `afbeelding` toe, let op: deze `afbeelding`-tag is een child-element van de `header`.
- [ ] Maak een element voor de auteursinformatie: met daarin een geneste `avatar`, een stuk tekst en `link`-tag.
- [ ] Benieuwd of je het goed hebt gedaan? Schakel dan de `link`-tag aan in de `head` van de `index.html`.

Ziet het er niet zo uit als op de pagina? Loop dan nog even de mogelijke tags en instructies af.

### Deel 2: Main
Bekijk de schermontwerpen, je kan de `main` onderverdelen in vier stukken: een social box, artikelen, een formulier
en gerelateerde artikelen.

#### 2.1 Social box
- [ ] De social box staat los aan de **zijkant** van de pagina. Kijk [weer eens naar het overzicht.](https://www.w3schools.com/TAgs/default.asp) Welke tag kan je gebruiken?
- [ ] Voeg het `gekozen element` toe met daar in een geneste `tijd` (Let op! Gebruik **niet** `<data>`!) en plaats daarin een `span` element voor het getal
- 
- [ ] Voeg in hetzelfde `gekozen element` waar de `tijd` in is genest voor elke afbeelding een nieuw child element toe, met klikbare `icons` die naar externe pagina's linken.
- [ ] Ben je benieuwd of je het goed hebt gedaan? Schakel dan de `link`-tag aan.

#### 2.2 Artikelen
- [ ] Voor de drie artikelen gebruik je een `article`-tag met daarin drie geneste `section`-tags.
  Binnen deze `section`-tags komt content te staan.
- [ ] Plaats in de eerste `section`-tag een `H2 heading`, drie `paragrafen` met daartussen een `quote` en de `afbeelding`.
- [ ] Plaats in de tweede `section`-tag een `H2 heading`, twee `paragrafen` met daartussen een `niet-georderede list` en de `afbeelding`.
- [ ] Plaats in de derde `section`-tag een `H2 heading`, drie `paragrafen` en een `georderde lijst`.
- [ ] Ben je benieuwd of je het goed hebt gedaan? Schakel dan de `link`-tag aan.

#### 2.3 Formulier
- [ ] Welke [tag hebben we nodig voor het formulier?](https://www.w3schools.com/TAgs/default.asp) Heb je een `gekozen tag`?
- [ ] Plaats in jouw`gekozen tag` een `H2 heading` en een `paragraaf` met de dummytekst.
- [ ] Plaats nu `invoervelden` voor de naam en emailadres. Vergeet deze niet te omwikkelen met een`label`.
- [ ] Bij iedere `invoerveld` en `label` combinatie kan je tekst toevoegen. Je hoeft dus geen extra tekst tag te plaatsen. Zie:
  `<label> Een titel <invoerveld/> </label>`
- [ ] Voeg een `drop down list` met `opties` (vergeet hierbij niet een `label`!)
- [ ] Maak een `tekstvlak` element, geef deze de twee attributen `cols="30"` en `rows="5"` mee.
- [ ] Maak twee `invoervelden` die een`type` hebben van `radio` en de tekst Public of Private.
- [ ] Maak een `invoerveld` met een `type` van `checkbox` en de terms and conditions tekst.
- [ ] Als laatste stap voor het formulier voeg je een `button` toe met een `type` attribuut van `submit`.
- [ ] Ben je benieuwd of je het goed hebt gedaan? Schakel dan de `link`-tag aan.

#### 2.4 Gerelateerde artikelen
Bij **2.2 Artikelen** hebben we een opbouw gemaakt van een buitenste `article`-tag met daarin drie `section`-tags.
Voor de **gerelateerde artikelen** pakken we dit net wat anders aan.
- [ ] Plaats een `section`-tag en plaats daar je titel in.
- [ ] Plaats in deze `section` een `div`-tag met daarin drie geneste `article`-tags.
- [ ] Plaats in iedere `article`-tag een `afbeelding`.
- [ ] Voeg onder de `afbeelding` (nog steeds in de `article`!) een lege `div` met een stukje tekst en `tijd`.
- [ ] Plaats hieronder een nieuwe lege `div` met een `H3 heading`, `paragraaf` en een `link`.
- [ ] Ben je benieuwd of je het goed hebt gedaan? Schakel dan de `link`-tag aan.

### Deel 3: Footer
- [ ] Welke [tag hebben we nodig voor de footer?](https://www.w3schools.com/TAgs/default.asp) Heb je een `gekozen tag`?
- [ ] Voeg jouw `gekozen tag` toe en plaats hiertussen een `paragraaf` met de tekst: Copyright &copy; 2022, all rights reserved.
- [ ] Ben je benieuwd of je het goed hebt gedaan? Schakel dan de `link`-tag aan.

## Dummytekst
> ## De onmisbare gids voor Amsterdam
> Stedentrip | 5 min 

> Jane Doe | Markering Manager @Jane_Doe
-------------------------------------------------------------------------
> 21 jul 22
> ## Amsterdam is echt een van de mooiste steden ter wereld. We hebben een complete gids voor Amsterdam voor je gemaakt als first-timer.
> Amsterdam is de hoofdstad van Nederland - een enorme stad met meer dan een miljoen inwoners, vol met ongelooflijke architectuur, musea, eten en cultuur. Het wordt vaak het Venetië van het Noorden genoemd, vanwege de vele kanalen die de stad doorkruisen en de 1.281 bruggen die langs die kanalen te vinden zijn.
>
> Als je denkt aan een reis naar Amsterdam, bekijk dan onze essentiële reisgids voor Amsterdam voor de beste hotels, buurten, dingen om te doen en plekken om te eten en drinken in Amsterdam, Nederland.
> 
>Amsterdam was een grote verrassing voor mij. Ik had Venetië altijd gezien als de stad van de grachten; het was nooit in me opgekomen dat ik soortgelijke omstandigheden in een Nederlandse stad zou vinden.
> 
>Of je nu de voorkeur geeft aan cultuur en geschiedenis, rondneuzen in musea, serieus feesten of gewoon genieten van de ontspannen charme van een oude Europese stad, er zijn veel verschillende buurten (of wijken) om te verkennen in Amsterdam.

> ### Beste periode om naar Amsterdam te gaan
> Elk moment van het jaar is goed om naar Amsterdam te reizen, hoewel het raadzaam is om regenkleding mee te nemen omdat het elk moment kan regenen. Juli tot augustus wordt beschouwd als het hoogseizoen voor reizen. Zo vind je de beste tarieven voor hotels en vluchten buiten die tijden. Om gekke drukte te vermijden en toch te genieten van mooi weer, raden we aan om Amsterdam te bezoeken in:
> - April
> - Mei
> - September
> - Oktober
> 
> Wat het weer betreft, het wordt in Amsterdam nooit echt te warm of te koud. Wolken en wat regen zijn echt de omvang van de weerpatronen.

> ### Wat te doen in Amsterdam
> Amsterdam, de hoofdstad van Nederland, is een van de meest populaire toeristische bestemmingen in Europa. Met zijn universiteiten, academies en onderzoeksinstituten, samen met meer dan 40 musea, talrijke theaters en uitgaansgelegenheden, is Amsterdam ook het belangrijkste culturele centrum van het land.
>
> Daarnaast staat de stad bekend om zijn vele goed bewaarde historische huizen. Deze goed bewaarde monumentale gebouwen, opgesteld in een patroon van concentrische segmenten in de vorm van een waaier, zijn gebouwd op palen die door een bovenste laag modder in de stevige zandbodem worden gedreven tot 18 meter lager.
>
>Ontdek de beste plaatsen om te bezoeken in deze dynamische stad met onze lijst met topattracties en leuke dingen om te doen in Amsterdam:
> - Bekijk de kunstcollecties in het Rijksmuseum
> - Bezoek het Anne Frank Huis
> - Beleef geweldige kunst in het Van Gogh Museum
> - Verken de Jordaan
> - Ontspan in het schitterende Vondelpark
> - Mensen kijken op de Dam
> - Ga shoppen in de Kalverstraat en Bloemenmarkt
> - Word slim in het NEMO Science Museum
> - Ontdek de Wallen
-------------------------------------------------------------------------
> ### Laat een reactie achter
> Ben je in Amsterdam geweest en wil je bijdragen aan deze blog? Laat een reactie achter en laat ons weten wat we moeten toevoegen aan onze lijst.
> - Naam
> - Email
> - Type
> - Reactie
> - Publiek
> - Prive
> - Ik ga akkoord met de voorwaarden
> - Reageer
-------------------------------------------------------------------------
> ### Gerelateerde artikelen
> #### Studeren en leven in Amsterdam
> - Reizen
> 
> Dat er zoveel studenten in de hoofdstad zijn, is niet gek. Op het gebied van onderwijs is er in Amsterdam namelijk heel veel mogelijk!
> 
>Lees artikel

> #### Topactiviteiten in Nederland
> - Lifestyle
> 
> Leer Nederland echt kennen met de beste activiteiten die het te bieden heeft. Wij hebben de beste activiteiten voor jou op een rij gezet.
> 
> Lees artikel

> #### Beste historische locaties in Amsterdam
> - Stedentrip
>
> Amsterdam is een stad met een rijke geschiedenis, die weerspiegeld wordt in de vele duizenden
monumenten. De monumenten van Amsterdam vertellen de meest prachtige verhalen.
> 
> Lees artikel