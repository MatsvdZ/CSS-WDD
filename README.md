# CSS WDD

Alles wat ik heb gemaakt voor het vak CSS bij de minor Web Design and Development

## Project keuze

### Welk project?

Tijdens het vak CSS, wil ik de **'Control panel'** opdracht gaan doen. Dit lijkt mij een leuke en uitdagende oefening, en past goed bij mijn idee om beter te worden in het daadwerkelijk visuele en interactieve deel van CSS.

### Welke CSS technieken kan/ga ik gebruiken?

- Een belangrijke techniek is natuurlijk de `:checked` en hidden inputs. Hiermee kan ik knoppen laten aan/uit gaan, lampjes laten branden, animaties starten, panels laten verschuiven ect.
- `:target` is nog een handige techniek, omdat je op die manier verschillende 'modes' kan maken, en ook tab-achtige interfaces kan maken
- `:has` is ook een krachtige manier voor styling van bijvoorbeeld de parent. Daarmee kan ik bijvoorbeeld het hele control panel laten reageren op een enkele toggle
- Uiteraard kan ik CSS animations gebruiken voor feedback voor de gebruiker.
- `transform` en `rotate` voor bijvoorbeeld knoppen en draaiknoppen.

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

### Wat heb ik geleerd?

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

### Wat heb ik geleerd?

Uit de presentaties heb ik veel verschillende dingen geleerd, namelijk alle onderwerpen die we hebben gehad. Uiteraard betekent dit niet dat ik hier nu alls over weet, maar ik heb er in ieder geval een beter idee van gekregen.

### Wat ga ik morgen doen?

Morgen hebben we gesprekjes in groepjes en gaan we het hebben over onze eerste ideëen die we hebben voor onze projecten van beide vakken.
Daarna ga ik bedenken waar ik nog even aan wil werken na de gesprekjes, en dan is het vakantie!

## Weekly geek 2 Peter-Paul Koch (19-02)

### Browsers & support detection

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

### Rendering engine:

Verantwoordelijk voor HTML en CSS parsing en rendering, constructie van de DOM en AOM trees. Dus NIET interface of JavaScript engine.

### Core vs DOM

Core: wat JavaScript een programmeertaal maakt.

DOM: de manier waarop JavaScript delen van de HTML-pagina's kan aanspreken en wijzigen.

**Render blocking**

- CSS
- JavaScript, tenzij async of defer

#### Defer vs async

Do it now:
`<script src>`

Do it later:
`<script defer src>`

I don't care when you do it, just not now:
`<script async src>`

### Backward compatibility

- Alles wat de browser ooit heeft ondersteund, moet de browser voor altijd blijven ondersteunen.

voorbeelden:

`[form object].elements`
`<body bgcolor="abdaca">` heel oud, maar werkt wel nog.
`<frameset>` een soort voorganger van de `<iframe>`

### Browser als platform

"Browsers are the most hostile development platforms in the world" - Douglas Crockford

### Korte geschiedenis van browsers

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

## Voortgang week 1 (20-02)

Ik heb deze week het begin gemaakt aan het vak CSS. Ik heb onderzoek gedaan en een presentatie gegeven over carrousels in CSS en hoe dit precies in elkaar zit. Daarnaast heb ik ook geluisterd naar andere mensen hun presentaties over de onderwerpen die zij hebben behandeld. Verder hebben we te horen gekregen wat precies de eindopdracht is, waarin ik mijn keuze heb gemaakt om een control panel te maken, in de vorm van een DJ paneel.

Ik heb snel een kleine basis neergezet met drie vormpjes, om zo in ieder geval alvast even wat te hebben staan.

### Volgende week

Volgende week ga ik echt aan de slag met het ontwerpen en maken van mijn DJ paneel. Ik hoop een of meerdere soorten controls te maken en al te ontwerpen zodat deze er in ieder geval goed uitzien.

## Weekly Nerd: Nils Binder

### CSS to the rescue

Nils werkt bij 9Elements in Duitsland.

https://9elements.com/

Hier gebruiken ze 3 units:

- Communication Design
- Product Development
- Web Development

Nils heeft een UX design gemaakt voor Schalke04 hun native app voor zowel iOS als Android. Het was voor Nils zijn grootste opdracht die hij heeft gedaan

### Project OECD

Bij dit project moet hij opzoek naar de juiste kleuren voor accessibility voor OECD, een bedrijf dat chart maakt.

### CSS day 2023

**Hieronder staan een aantal talks die er zijn gegeven op CSS day**

Tinker by night - door Sanne ’t Hooft

Creative coding - Jhey Topkins

Personal website - Sophie Koonin

Building components Stephanie Eckles

Structuring & Restructuring - Manuel Matuzoviç

Selector Performance - Patrick Brosset

Vroeger gebruikte iedereen Photoshop om websites te designen. Nu gebruiken ze daar natuurlijk Figma voor. De interface van Figma is veel gemakkelijker om te gebruiken dan die van Photoshop, en is redelijk gelijk aan hoe het moet in CSS.
Zo zit er in Figma ook flex, gap, padding, justify content ect. Ook zijn er variabelen in Figma, wat je natuurlijk ook gebruikt in CSS.

In 2016 was er een tweet die eigenlijk zei dat we veel dezelfde soort sites maken, maar toen kwam Figma waardoor je veel sneller kunt designen.

Er zijn ook veel frameworks zoals Tailwind, wat ook het proces van designen sneller maakt. Maar nu ook AI gebruikt wordt, is de web development omgeving lichtelijk ‘saai.’

Kijk niet naar pixels, maar kijk naar de ratio en de relatie tussen verschillende objecten en hun positie. Hierbij kan je CSS grids gebruiken. Je kunt dus grid gebruiken in CSS met de 1fr/2fr met grid-templatecolumns.

```
.fancy-text {
	display: grid;
	grid-template-columns: 2fr 3fr auto 1fr;
}

h1 {
	grid-column: 2/4}
	p {grid-column: 3/4}
```

Het past zich dus aan op basis van het scherm en een max-width aan de paragraaf geven. Dit is dus mooier op een groot scherm, en niet op mobiel want je hebt te weinig ruimte

### Animatie

Je kan animaties als het ware als een soort stop motion maken door meerdere foto’s achter elkaar te plakken en deze te animeren. De animatie is eigenlijk een lange strip van images die als het ware achter elkaar worden getoond.

Animation: stop-motion 3s steps(31, end) infinite

### Subgrid

Dit is het laten groeien van een soot blokken t.o.v. andere blokken voor bijvoorbeeld een tijdschema.

Je gebruikt dit om de items te displayen, als een rij groeit, groeien de andere rijen ook mee.

### First line selector

Er is een first line selector die je kunt gebruiken om de eerste line van tekst anders te stijlen dan de rest van de tekst.

### View transitions

Je kunt transities hebben tussen verschillende pagina’s, zo kan je bijvoorbeeld mooi een taal switch toevoegen aan je website, inclusief animaties.

## Derde checkout (04-03)

### Wat heb ik vandaag gedaan?

We begonnen de dag met een weekly nerd van Nils Binder over wie hij is en wat hij doet. Ik heb vandaag gewerkt aan de layout van mijn project en het maken van verschillende sliders. Zo heb ik een slider gemaakt die lijkt op een slider op een DJ paneel. Daarnaast heb ik ook een soort knob gemaakt met een slider die langs verschillende stappen gaan.

<img width="560" height="355" alt="Screenshot 2026-03-04 at 15 30 45" src="https://github.com/user-attachments/assets/e6937873-41bb-4b1d-89b5-bd452da8bd08" />

### Hoe lang duurde het?

Ik heb in totaal zo'n 4 uur echt aan mijn eigen project kunnen werken, waarin ik dus vooral aan de sliders en layout heb gezeten.

### Wat heb ik geleerd?

Ik heb erg veel geleerd over grid en hoe ik op verschillende manieren alles kan positioneren. Daarnaast heb ik veel geleerd over de `input="range"` waarmee ik mijn slider en draaiknop heb gemaakt.

### Wat ga ik morgen doen?

Ik ga morgen verder met het perfectioneren van mijn grid, en ik wil het mijn sliders en knop daadwerkelijk iets laten doen.

## Vierde checkout (05-03)

### Wat heb ik vandaag gedaan?

Ik heb vandaag redelijk wat voortgang geboekt. Ik ben aan de slag gegaan met de soundwaves en het animeren hiervan.

<img width="304" height="886" alt="Screenshot 2026-03-05 at 15 15 23" src="https://github.com/user-attachments/assets/dbbcddac-0f30-445e-9b45-66587a4c66d0" />

<img width="340" height="945" alt="Screenshot 2026-03-05 at 15 15 47" src="https://github.com/user-attachments/assets/ebc8be66-7d96-4d82-a115-9e838a7a15cc" />

Ook ben ik vandaag aan de slag gegaan me thet werkend maken van mijn draaiknop.

<img width="603" height="418" alt="Screenshot 2026-03-05 at 15 17 41" src="https://github.com/user-attachments/assets/42eaae6d-4e6e-471b-8516-8f4d79c08c94" />

Deze knop zorgt er nu voor dat ik op elke stand van de knop een andere achtergrond kleur heb.

Daarnaast heb ik ook nog een klein beetje gedaan aan het ordenen van mijn code en het verbeteren van mijn responsiveness.

En tot slot heb ik vandaag mijn CSS opgeschoond en CSS nesting gebruikt waar dit kon.

### Hoe lang duurde het?

Ik heb er vandaag zo'n 4 uur aan gezeten, en heb hier veel mee kunnen doen.

### Wat heb ik geleerd?

Ik heb verder geoefend met het werkend maken van inputs. Daarnaast heb ik ook geoefend met het maken van lijnen en deze animeren op een manier dat het precies moet zijn zoals ik dat wil.

Ook het nesten van CSS is iets wat ik niet echt eerder heb gebruikt en waar ik vandaag dus ook lekker mee aan de slag ben gegaan.

### Wat ga ik de volgende keer doen?

De volgende keer wil ik de styling van mijn discs daadwerkelijk laten lijken op echte dj discs. Ook wil ik nog een extra input toevoegen die werkt als een soort aan/uit knop voor de hele dj set.

## Voortgang week 2 (06-03)

Ik heb vandaag de feedback gehad van Sanne tijdens het voortgangsgesprek. Hierin heb ik mijn code laten zien waarop ik de feedback kreeg om meer om feedback/hulp te vragen. Dit is wat ik volgende week dan ook meteen ga doen, om zo mijn CSS te verbeteren.

Verder was Sanne positief over de vordering van mijn control panel.

### Volgende week

Volgende week wil ik graag samen met Sanne aan het begin alvast samen zitten om zo mijn code even te reviewen en eventueel aan te passen naar een nettere structuur.

Daarna wil ik verder met de styling van mijn werk, en nog de eis over de typografie verwerken in mijn project.

## Vijfde checkout (11-03)

### Wat heb ik vandaag gedaan?

We begonnen de dag met de intro van Sanne waarin we een uitebreide uitleg kregen over kleuren en het gebruik hiervan.

Na deze intro heb ik een workshop gevolgd over container style queries. Ik vond dit een hele interessante workshop en wil hierdoor ook graag iets met deze style queries gaan doen.

Ik ben begonnen met het bedenken met wat ik met de style querys wou doen. Dus ik heb er voor gekozen om een soort 'eyebleed' modus te maken, deze verandert het paneel van kleur met een gradient en deze gaat ook heen en weer. Ook veranderen de discs van kleur en worden ook een gradient. Ik Wil met deze modus het eigenlijk zo extreem lelijk maken dat je er niet lang naar kan en wilt kijken. Daarnaast heb ik ook een 'Off' state gemaakt. Deze zorgt dat alle animaties op de dj set stoppen, en gedimd worden. Eigenlijk een compleet tegenover gestelde van de eyebleed modus.

Ik heb ook de standaard discs zelf aangepakt, door deze eindelijk een fatsoenlijke stijling te geven, waardoor deze daadwerkelijk voelen als discs. Ik heb ze ook een soort retro touch gegeven, wat ervoor zorgt dat ze een beetje op vinyl platen lijken.

**Basic styling**

<img width="1728" height="962" alt="Screenshot 2026-03-11 at 16 11 45" src="https://github.com/user-attachments/assets/3a5d8a83-78f5-46dc-9cfb-591e05e762f6" />

**Eyebleed modus styling**
Dit animeert ook!

<img width="1728" height="962" alt="Screenshot 2026-03-11 at 16 12 18" src="https://github.com/user-attachments/assets/955051ac-ffbe-4e7a-88c5-3105baae5c1e" />

**Off modus styling**

<img width="1728" height="962" alt="Screenshot 2026-03-11 at 16 13 08" src="https://github.com/user-attachments/assets/cd66060f-1b08-41ac-8467-bc7f0102788e" />

### Hoe lang duurde het?

Ik heb er vandaag ruim 4 uur aan kunnen zitten. Maar daarnaast heb ik ook zeker een 1,5 uur aan workshops en intro gehad.

### Wat heb ik geleerd?

Ik heb vandaag veel geleerd over style querys. Dit heeft mij ook veel meer de kans gegeven om functionaliteit toe te voegen. Ook heb ik vandaag veel geleerd over gradients, waarmee ik mijn discs heb kunnen maken naar hoe ik ze wil.

<img width="347" height="486" alt="Screenshot 2026-03-11 at 16 17 11" src="https://github.com/user-attachments/assets/64106bf0-b445-459d-b78f-9c292f90dc8d" />

### Wat ga ik de volgende keer doen?

Ik ga de volgende keer door met het perfect maken van mijn style querys, en kijken wat ik nog verder kan doen om er wat meer flare aan te geven.


## Zesde checkout (12-03)

### Wat heb ik vandaag gedaan?

We begonnen de dag vandaag met een ruime intro over wiskunde in CSS, en hoe krachtig dit eigenlijk is.

Daarna ben ik aan de slag gegaan met nog een leuk iets toevoegen, namelijk een volume meter. Deze is ook te besturen met mijn fader slider. De slider bepaalt hoe 'hoog' het geluid staat. De meter zelf loopt van groen naar rood. En als kers op de taart heb ik het zo gemaakt dat wanneer de fader op 100% staat, het laatste rode lampje begint te knipperen, wat ongeveer lijkt op 'clipping' op een echte DJ set. (Clipping is een vorm van audiovervorming dat voorkomt wanneer een audiosignaal de maximale capaciteit van de audio apparatuur overschrijdt).

Ik heb nog een workshopje gevolgd van Vasilis over typografie, en heb hierbij een aantal linkjes gekregen die denk ik wel handig kunnen zijn in de zoektocht naar een leuke font.

Ik heb vandaag ook weer een feedback gesprekje gehad met mijn groepje. Daarbij kreeg ik van Sanne te horen dat ik nu qua eisen alleen nog de typografie moet doen. Verder zijn er natuurlijk ook nog andere kleine dingen die nog verbeterd kunnen worden, maar de functionaliteit is er in iedergeval wel.

Op het einde van de dag hadden we nog een weekly nerd.

### Hoe lang duurde het?

Ik heb in totaal zo'n 4 uur gewerkt aan mijn eigen project. Daarnaast heb ik nog iets minder dan een uurtje de workshop van Vasilis gevolgd. Daarna hebben we nog de weekly nerd gehad.

### Wat heb ik geleerd?

Ik heb vandaag geleerd hoe sterk wiskunde kan zijn als je dit gebruikt in CSS. Ik heb met behulp van calc dan ook de thresholds berekent voor mijn volume lampjes.

Verder heb ik vandaag nog kleine tweaks aan de off mode gedaan.

### Wat ga ik de volgende keer doen?

Volgende keer ga ik aan de slag met de typografie eis van de opdracht. Hiervoor ga ik eerst onderzoek doen en een juist etypografie uitzoeken, daarna ga ik hier mee spelen.




## Zevende checkout (17-03)

### Wat heb ik vandaag gedaan?
Ik heb vandaag dus gewerkt aan mijn typografie. Ik heb een variabele font gevonden die ik ga gebruiken voor mijn project. Dit is de font 'Sixtyfour Convergence' geworden. Deze font gebruik ik op de baseplate van mijn DJ set, en voor de tekst bij de checkboxes. Ik heb hiervoor gekozen omdat deze ook is opgebouwd uit lijnen, en dat vond ik wel mooi passen bij mijn geluidsgolven die ik heb gemaakt. 

<img width="1219" height="451" alt="Screenshot 2026-03-17 at 15 41 51" src="https://github.com/user-attachments/assets/34a9177f-056d-4c02-af59-0f28d888c86b" />

Hierna ben ik gaan spelen met de mogelijkheden van het animeren en aanpassen van de font. Ik heb het nu zo gemaakt dat de font animeert wanneer de eyebleed modus aan staat en van kleuren verandert dankzij een filter die ik erover heen gooi. Het moet natuurlijk ook een fitting title zijn dus heb ik gekozen voor "Music for the eyes" omdat er natuurlijk geen geluid uit mijn DJ set komt, maar er wel veel te zien is. Ook heb k er uiteraard voor gezorgd dat er een 'off' state is.

Ik heb ook nog snel een favicon toegevoegd, daar worden de docenten altijd zo blij van :) 

Tot slot heb ik nog even gewerkt aan mijn bronnen/bronnenlijst en deze ook netjes in de code verwerkt.

### Hoe lang duurde het?
Ik heb vandaag ongeveer 3 tot 4 uur aan mijn project gezeten. Dit komt omdat ik vandaag eigenlijk vooral de puntjes op de i wil zetten, om daarna verder te kunnen met de laatste dingen voor browser technologies.

### Wat heb ik geleerd?
Ik heb vandaag geleerd over variable fonts en hoe ik deze kan gebruiken. Ik heb daar een beetje mee lopen spelen en ook animaties gemaakt.


### Wat ga ik de volgende keer doen?
Waarschijnlijk is de volgende keer de evaluatie :)




## Week 4 - Completion
### Final result!

<img width="1728" height="961" alt="Screenshot 2026-03-18 at 09 52 42" src="https://github.com/user-attachments/assets/a50e702e-7d17-4d24-a110-995b950b316f" />

<img width="1728" height="962" alt="Screenshot 2026-03-18 at 09 53 00" src="https://github.com/user-attachments/assets/4d9fc5ef-d2cc-4a98-96fc-aea45714c81e" />

<img width="1728" height="961" alt="Screenshot 2026-03-18 at 09 53 15" src="https://github.com/user-attachments/assets/802dc753-54b1-4d1f-a12e-859607671b94" />

<img width="654" height="962" alt="Screenshot 2026-03-18 at 09 54 34" src="https://github.com/user-attachments/assets/21f04eb6-cee0-492c-93a8-f65ceac12002" />

Dit is hem dan, mijn DJ paneel gemaakt in alleen HTML en CSS (en een klein beetje toegestaande JavaScript :) )

Ik heb deze paar weken gewerkt aan een DJ paneel die op verschillende inputs reageert, en ook andere functies hebben. Ik heb namelijk de volgende funtionaliteiten toegevoegd:



#### LED Geluidsmeter
Sound meter met 'LED' lampjes om zo het geluidsniveau na te bootsen. Deze reageert op de input van de fader die ik heb gemaakt, en zodra de fader op standje 100 staat, speelt de 'blink' animatie af om zo dus dat clippen na te maken.

<img width="58" height="275" alt="Screenshot 2026-03-18 at 10 07 45" src="https://github.com/user-attachments/assets/d1f89605-af82-4ceb-bf0d-c5afc5b5dcdd" />

<img width="356" height="807" alt="Screenshot 2026-03-18 at 10 09 13" src="https://github.com/user-attachments/assets/c289ab5b-1b96-4c08-9cc8-3a70ef208090" />

<img width="603" height="959" alt="Screenshot 2026-03-18 at 10 09 37" src="https://github.com/user-attachments/assets/f2ca376c-0fc0-49b7-812d-d3ff1ab8a8aa" />


#### Geluidsgolven

Geluidsgolven die op een random timing lopen, met verschillende animaties om het zo random mogelijk te maken, je kunt hier de 'brightness' van aanpassen door de fader te gebruiken.

<img width="857" height="329" alt="Screenshot 2026-03-18 at 10 11 31" src="https://github.com/user-attachments/assets/c5edf131-6d58-4333-8fc5-2e5edb5bfceb" />


Hier style ik de waves die je ziet, en maak ik drie animatie soorten aan, voor randomness.

<img width="578" height="966" alt="Screenshot 2026-03-18 at 10 12 35" src="https://github.com/user-attachments/assets/41d48d83-9a15-4511-b83b-144f08c93763" />


Hier geef ik de bars delays om de randomness toe te voegen zodat deze nooit hetzelfde lijken.

<img width="183" height="449" alt="Screenshot 2026-03-18 at 10 13 00" src="https://github.com/user-attachments/assets/5c2fbcba-3f1a-486e-b523-8bd7f260b8cd" />


#### Slider / Fader
De slider lijkt echt op een slider van een DJ paneel. Deze bestuurt dus de brightness van de geluidsgolven, maar ook de ronddraai snelheid van de discs, en de hoogte van de geluidsLEDjes.

<img width="448" height="83" alt="Screenshot 2026-03-18 at 10 19 52" src="https://github.com/user-attachments/assets/469bd554-25ef-43ed-adc9-356580298808" />

<img width="561" height="974" alt="Screenshot 2026-03-18 at 10 15 14" src="https://github.com/user-attachments/assets/a0b3e3f8-d67e-46e1-97d1-e178c7e07f91" />


#### Knob
Ik heb ook nog een knob gemaakt (slider die lijkt op een draaiknop). Deze bestuurt de achtergrond kleur.

<img width="114" height="109" alt="Screenshot 2026-03-18 at 10 20 35" src="https://github.com/user-attachments/assets/a3baf2a5-55bc-4aed-8dab-69e812c5cd34" />


Hier maak ik de achtergrond kleur door middel van calc aan de hand van variabelen op een radial gradient.

<img width="528" height="381" alt="Screenshot 2026-03-18 at 10 21 46" src="https://github.com/user-attachments/assets/201f751a-9e41-4db6-b4d3-f6d79f2367a0" />

Dit is de algemene styling voor de knob, ook zie je hoe ik de knob positie aanpas door calc te gebruiken om de positie te bepalen.

<img width="582" height="850" alt="Screenshot 2026-03-18 at 10 23 20" src="https://github.com/user-attachments/assets/2c5f3fa1-4659-4173-997d-14624742f2b7" />


#### Style querys
Daarnaast heb ik met style querys nog twee soorten 'states' gemaakt voor mijn paneel. Zo heb ik een 'crazy' mode, en een 'off' mode. De naam van de 'off' mode zegt het al. Deze modus dimt alle lichtjes en stopt alle animaties, zodat deze dus echt uit staat. De 'crazy' mode is eigenlijk een soort gimmick waarin ik zoveel mogelijk random kleuren, patronen en animaties heb toegevoegd. Mensen op feestjes houden vaak van specifieke substanties, dit is hoe ik me voorstel hoe dat er dan ongeveer uitziet :).

Hier zie je hoe ik de achtergrond van de 'crazy' mode gemaakt en geanimeerd heb.

<img width="573" height="957" alt="Screenshot 2026-03-18 at 10 25 23" src="https://github.com/user-attachments/assets/6877363c-505b-4236-83c0-155990b8664b" />

En hier zie je dat ik ook mijn variable font een animatie heb gegeven, die dus alleen afspeelt wanneer de mode aan staat

<img width="172" height="382" alt="Screenshot 2026-03-18 at 10 26 21" src="https://github.com/user-attachments/assets/352b0ab3-20a5-489c-897f-5616981066d9" />

Hieronder staat dan ook hoe ik de 'off' modus heb gemaakt. Eigenlijk zet ik gewoon voornamelijk de animaties en lichtgevende effecten uit.

<img width="493" height="698" alt="Screenshot 2026-03-18 at 10 27 11" src="https://github.com/user-attachments/assets/070799db-0b14-4f56-b98b-09e4312ac13f" />

#### Responsiveness
Verder heb ik mijn paneel mooi responsive gemaakt, door wanneer de container kleiner wordt dan 900px het paneel om wordt gegooid naar een paneel met een enkele disc, en andere layout. De foto hiervan staat boven.

Dit heb ik gedaan met grid layouts, om zo het grote en het kleine scherm op andere manieren te ordenen

<img width="481" height="495" alt="Screenshot 2026-03-18 at 10 30 43" src="https://github.com/user-attachments/assets/dc017ed2-36ef-4635-8afc-0f984e78e341" />

Daarna heb ik een container query gebruikt om zo bij een breedte van 900px de grote variant te maken door deze in te delen met grid layout.

<img width="387" height="1016" alt="Screenshot 2026-03-18 at 10 31 37" src="https://github.com/user-attachments/assets/c2711e9d-f2da-44fd-bed8-5fb2ba3d037c" />


### Wat ging goed, wat was lastig, en waar ben ik het meest trots op?
Ik heb in de afgelopen jaren altijd voor het vak met coderen gekozen, maar ik heb de laatste tijd vooral veel gewerkt aan de backend kant van het coderen met JavaScript. Ik had me dus nog niet zo zeer goed verdiept in CSS voordat we dit vak hadden. Het was daarom aan het begin wel weer even inkomen met CSS. het is uiteindelijk wel weer gelukt om er lekker in te komen, maar sommige van de nieuwe technieken was nog steeds even wennen, zoals het gebruik van nesten in CSS, wel ben ik erachter gekomen dat dit echt heel handig is om te gebruiken. Ook style querys waren nieuw, maar ook hier heb ik de kracht van gebruikt.

Daarnaast was het vaak ook gewoon veel opzoeken om relatief 'kleine' dingen aan te passen/te fixen, maarja dat is nou eenmaal hoe het is met coderen.

Maar wat nou echt het lastigste was, en wat eigenlijk vooral veel tijd in beslag nam, was het niet gebruik kunnen maken van classes en ID's. Het was soms erg lastig om ergens de juiste selector voor te vinden en ook netjes te kunnen gebruiken. 

Ik ben het meest trots op eigenlijk alles wat met nieuwe code te maken heeft. Ik ben vaak iemand die houdt van het vasthouden bij dingen die ik al weet/ken. Dus door deze verschillende nieuwe methodes te gebruiken moet ik eigenlijk een beetje uit mijn comfort zone kruipen, en dat is natuurlijk goed! 

Maar project gewijs ben ik het meest trots op de volume meter en op de style querys. De volume meter is in dat opzicht niet eens hele ingewikkelde code, maar het was wel leuk om alle verschillende componenten op elkaar af te stemmen en dit er goed uit te laten zien. De style querys vond ik gewoon grappig om te doen, maar kwamen toch ook soms nog wel wat probleempjes naar boven met het gebruik van variabelen maar deze heb ik wel op kunnen lossen. 



### Welke experimenten heb ik geprobeerd die mislukt zijn?
Waar ik het meeste mee heb geëxperimenteerd is eigenlijk de algemene vormgeving en de vibe die ik wil afgeven. Ook de layout heb ik meerdere keren omgegooid om zo tot een fijne en bruikbare layout te komen die ook goed te schalen is. 


### Heb ik nieuwe inzichten over het gebruik en de kracht van CSS?
Absoluut! Ik wist aan het begin totaal niet dat je zoveel kon doen met enkel CSS, ik had verwacht dat er bij dit soort dingen véél meer JavaScript zou komen kijken. Bijvoorbeeld calc. Ik had geen idee dat je dit voor zo veel verschillende dingen kon gebruiken. Ook de style querys hebben mij verbaasd over wat je daar allemaal mee kan. 

Ook is het gebruik van variabelen erg handig en heel sterk om te gebruiken.



### Wat wil ik verder ontdekken?
Ik wil in de volgende projecten en vooral voor mijn eigen site veel meer doen met CSS, al ga ik dan wel iets meer gebruik maken van classen en ID's ;). Als ik hieraan begin wil ik eigenlijk nog verder onderzoek doen naar nieuwe technieken die ik nog niet heb gebruikt tijdens dit vak, want ik heb er in vergelijking met het aantal nieuwe technieken natuurlijk niet zo veel gebruikt. Er zijn dus vast nog veel meer manieren om dingen te doen en misschien zelfs om dingen te doen waarvan ik niet eens weet dat het kan in CSS.





## Bronnen:
https://www.algoriddim.com/hardware

https://css-tricks.com/the-shapes-of-css/

https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/input#step

https://css-tricks.com/complete-guide-css-grid-layout/

https://codepen.io/shooft/pen/LYaexbj

https://codepen.io/yomateo/pen/ypbNrJ

https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Containment/Container_queries

https://codepen.io/MATS-the-typescripter/pen/XJjNzXG?editors=1100

https://cssgradient.io/

https://www.w3schools.com/howto/howto_css_custom_checkbox.asp

https://ishadeed.com/article/css-container-style-queries/

https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Fonts/Variable_fonts

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/filter

https://w7.pngwing.com/pngs/97/954/png-transparent-macbook-pro-djay-disc-jockey-macos-computer-icons-dj-fruit-nut-macos-mac-app-store.png

https://chatgpt.com/share/69b956fd-3d54-800a-9459-4a560ea3bbb9

https://fonts.google.com/specimen/Sixtyfour+Convergence

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/background-size

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/var

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/box-shadow

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/::-moz-range-thumb

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/::-webkit-slider-thumb

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/background-size

https://developer.mozilla.org/en-US/docs/Web/CSS/clamp

https://developer.mozilla.org/en-US/docs/Web/CSS/calc

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/color_value#currentcolor_keyword
