# CSS WDD
Alles wat ik heb gemaakt voor het vak CSS bij de minor Web Design and Development

## Project keuze
### Welk project?
Tijdens het vak CSS, wil ik de **'Control panel'** opdracht gaan doen. Dit lijkt mij een leuke en uitdagende oefening, en past goed bij mijn idee om beter te worden in het daadwerkelijk visuele en interactieve deel van CSS. 

### Welke CSS technieken kan/ga ik gebruiken?
- Een belangrijke techniek is natuurlijk de ```:checked``` en hidden inputs. Hiermee kan ik knoppen laten aan/uit gaan, lampjes laten branden, animaties starten, panels laten verschuiven ect.
- ```:target``` is nog een handige techniek, omdat je op die manier verschillende 'modes' kan maken, en ook tab-achtige interfaces kan maken
- ```:has``` is ook een krachtige manier voor styling van bijvoorbeeld de parent. Daarmee kan ik bijvoorbeeld het hele control panel laten reageren op een enkele toggle
- Uiteraard kan ik CSS animations gebruiken voor feedback voor de gebruiker.
- ```transform``` en ```rotate``` voor bijvoorbeeld knoppen en draaiknoppen. 

Er zijn er natuurlijk veel meer, maar dit is in elk geval een goed begin.


### Waar ligt mijn grootste uitdaging?
Het niet gebruiken van JS om dingen uit/aan te zetten, standen te onthouden logica toe te passen ect, maar dit doen met alleen CSS is moeilijk omdat dit ook helemaal nieuw is voor mij. De HTML heeft hier dus ook invloed op en moet goed gestructureerd zijn.

Het maken van realistische controls is ook lastig en je moet aan alles denken zoals: klikbaar gevoel, feedback geven, schaduw ect... 


### Eerste sketches en idee
Ik wil het controlpanel van een DJ panel namaken. Ik wil dit doen door een aantal verschillende knoppen te maken zoals toggle, draaiknop, sliders. Maar ook de grote ronde jogwheel. Dit wil ik ook visueel laten zien door animaties te maken, maar ook dat er elementen reageren op de inputs, zoals een volumebalk met lichtjes die groter en kleiner wordt. Of een track die ik dan terug of door kan spoelen (alleen visueel). Ook wil ik hierin eventueel wat eastereggs verstoppen, maar ook bijvoorbeeld de twee themes., door bijvoorbeeld het hele paneel van kleur te veranderen, of om bijvoorbeeld de kleur van de trackviewer veranderen.

![IMG_2204](https://github.com/user-attachments/assets/78a8d05e-b83d-48a5-8c39-410a4b05638e)

![IMG_2205](https://github.com/user-attachments/assets/6b888da3-6d24-4587-82c2-d549214f5fe3)



## Eeste checkout (18-02)
### Wat heb ik vandaag gedaan?
Ik heb vandaag samen met mijn groepje onderzoek gedaan naar carousels. We hebben veel CSS code bestudeerd en ook toegepast in onze eigen ontwerpen. 

We hebben verschillende Codepen's gemaakt die de verschillende niveau's tonen van soorten carousels. Zo hebben we een absolute basis, maar ook een wat meer advanced versie gemaakt die we kunnen laten zien aan de klas. Alles in de codepens word ook ondersteund door comments die ervoor zorgen dat alles net wat duidelijker is.

Link naar Codepen
https://codepen.io/MATS-the-typescripter/pen/VYjJYjV


Ook hebben we een presentatie gemaakt waarin alles staat wat wij morgen tijdens de presentatie willen laten zien.
<img width="1396" height="788" alt="Screenshot 2026-02-19 at 15 35 00" src="https://github.com/user-attachments/assets/99f5166d-10e3-428a-a16c-556902e3cc3d" />

En als laatste hebben we een kleine checkout gehad met Sanne :)


### Hoe lang duurde het?
We hebben in totaal zeker ruimt 5 uur gewerkt aan deze opdracht. Hiervan was een klein uurtje het lezen en doornemen van verschillende artikelen, en de rest van de tijd hebben we besteed aan het oefenen en het maken van carousels.


###  Wat heb ik geleerd?
Ik heb nog nooit een carousel gemaakt, waardoor vrijwel alles wat ik vandaag heb geleerd, daadwerkelijk nieuw was voor mij. 

Ik heb vandaag veel verschillende dingen geleerd, namelijk: 

- ::scroll-button()
- ::scroll-marker()
- scroll-snap-type()
- scroll-state
- scroll-snap-align
- :target-current
- overscroll-behavior-x

Dit zijn de verschillende dingen die ik heb geleerd bij het maken van een carousel.

### Wat ga ik morgen doen?
Morgen gaan we in de ochtend presenteren wat we vandaag hebben gedaan. Daarna krijgen we eindelijk te horen wat onze daadwerkelijke eindopdracht gaat worden. Ik ben benieuwd :) 





## Tweede checkout (19-02)
### Wat heb ik vandaag gedaan?
We begonnen vandaag met onze presentaties. We hebben veel presentaties aangehoord over allerlei verschillende onderwerpen.

**Dat waren de volgende onderwerpen:**
- :has
- containers
- carousels
- Makeup
- Scroll-animations
- Anchors

Na de presentaties hebben we te horen gekregen wat de eindopdracht is, en dat we hierin kunnen kiezen. Ik heb gekozen voor de control panel opdracht, met hierbij het idee om een DJ panel te maken. Ik hierbij ook al twee kleine schetjes gemaakt.


### Hoe lang duurde het?
Vandaag hebben de presentaties ongeveer 1,5 tot 2 uur gekost, daarna hebben we een tijdje pauze gehad en zijn we door gegaan met de eindopdracht en hieraan werken. Dit heeft zo'n 2,5 uur geduurd.


###  Wat heb ik geleerd?
Uit de presentaties heb ik veel verschillende dingen geleerd, namelijk alle onderwerpen die we hebben gehad. Uiteraard betekent dit niet dat ik hier nu alls over weet, maar ik heb er in ieder geval een beter idee van gekregen.


### Wat ga ik morgen doen?
Morgen hebben we gesprekjes in groepjes en gaan we het hebben over onze eerste ideëen die we hebben voor onze projecten van beide vakken.
Daarna ga ik bedenken waar ik nog even aan wil werken na de gesprekjes, en dan is het vakantie!




### Weekly geek 2 Peter-Paul Koch (19-02)
#### Browsers & support detection

**Wat is een browser?: **
- HTML
- CSS
- DOM (een soort kopie voor je HMTL maar voor je JavaScript.)
- AOM (Accesiblity object model)
- interface
- JavaScript engine (als aparte component)

In theorie is het mogelijk dezelfde browser te houden, met een andere JavaScript engine.

![IMG_2207](https://github.com/user-attachments/assets/6afd4a1e-302e-4448-a990-3b8c4067bdb3)

Een parser is een programma wat een screen neemt (HTML) en kijkt wat er eigenlijk in zit.
Er is ook een JS en CSS parser.

Layout is erg zwaar voor de browser, zorg dat dit van te voren is berekend, en niet plots gedaan wordt. (Keep it stupid simple)

#### Rendering engine:

Verantwoordelijk voor HTML en CSS parsing en rendering, constructie van de DOM en AOM trees. Dus NIET interface of JavaScript engine.

#### Core vs DOM

Core: wat JavaScript een programmeertaal maakt.

DOM: de manier waarop JavaScript delen van de HTML-pagina's kan aanspreken en wijzigen.

**Render blocking**
- CSS
- JavaScript, tenzij async of defer

#### Defer vs async

Do it now:
```<script src>```

Do it later:
```<script defer src>```

I don't care when you do it, just not now:
```<script async src>```

#### Backward compatibility
- Alles wat de browser ooit heeft ondersteund, moet de browser voor altijd blijven ondersteunen.

voorbeelden: 

```[form object].elements```
```<body bgcolor="abdaca">``` heel oud, maar werkt wel nog.
```<frameset>``` een soort voorganger van de ```<iframe>```

#### Browser als platform
"Browsers are the most hostile development platforms in the world" - Douglas Crockford


#### Korte geschiedenis van browsers
**WWW Browser (1990)**

Allereerste browser, gebouwd te Cern door Tim Berners-Lee en consorten.

Herbouwd in 2019: https://worldwideweb.cern.ch/

**Mosaic (1993)** 

De eerste browser die plaatjes had

**Netscape (1994)** 

De eerste ECHTE browser

**Internet Explorer (1995)** 

De eerste gratis browser en van Microsoft.

**Opera (1995)**

**IE 5 Mac (2000)**

**Konqueror (2000)**

**Safari (2003)**

De eerste eigen browser van Apple

**Firefox (2004)**

Van Mozilla

**Safari iOS (2007)**

**Chrome (2008)**

**Flow (2020)**

Eigen rendering engine, onvoorspelbaar hoe het met CSS omgaat. 

**Ladybird (2024)**

Ook een eigen rendering engine. Begonnen als hobbyproject om van zijn drugsverslaving af te komen.

**Igalia**

Geen browser maker, maar weten er veel vanaf. Spaans open source bedrijf, richten zich op het maken van delen van rendering engines.




### Bronnen:

https://css-tricks.com/the-shapes-of-css/

https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/input/radio

https://css-tricks.com/complete-guide-css-grid-layout/



