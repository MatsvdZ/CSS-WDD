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
```<script src>```

Do it later:
```<script defer src>```

I don't care when you do it, just not now:
```<script async src>```

### Backward compatibility
- Alles wat de browser ooit heeft ondersteund, moet de browser voor altijd blijven ondersteunen.

voorbeelden: 

```[form object].elements```
```<body bgcolor="abdaca">``` heel oud, maar werkt wel nog.
```<frameset>``` een soort voorganger van de ```<iframe>```

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

###  Wat heb ik geleerd?
Ik heb erg veel geleerd over grid en hoe ik op verschillende manieren alles kan positioneren. Daarnaast heb ik veel geleerd over de ```input="range"``` waarmee ik mijn slider en draaiknop heb gemaakt.

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


###  Wat heb ik geleerd?
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


###  Wat heb ik geleerd?
Ik heb vandaag veel geleerd over style querys. Dit heeft mij ook veel meer de kans gegeven om functionaliteit toe te voegen. Ook heb ik vandaag veel geleerd over gradients, waarmee ik mijn discs heb kunnen maken naar hoe ik ze wil.

<img width="347" height="486" alt="Screenshot 2026-03-11 at 16 17 11" src="https://github.com/user-attachments/assets/64106bf0-b445-459d-b78f-9c292f90dc8d" />



### Wat ga ik de volgende keer doen?
Ik ga de volgende keer door met het perfect maken van mijn style querys, en kijken wat ik nog verder kan doen om er wat meer flare aan te geven.





## Weekly geek (12-03)
Robbert Boersma

**Ff formulieren maken met NL design system richtijnen**

### Opbouw van een formulier:

    - Introductietekst
    - Informatie vragen die nodig is
    - Gebruiker kan voor inzending de ingevoerde waardes controleren, wijzigen of ongedaan maken
    - Na “volgende” of “verzenden” verschijnt een samenvatting van alle fouten
    - Na verzenden verschijnt een duidelijke bevestiging 

    - Het is erg fijn als het lukt om een formulier op te slaan en later verder te gaan.

    - Verplichte velden goed aangeven
    - Uitleggen waarom je specifieke informatie nodig hebt
    - Gebruiker dezelfde informatie niet twee keer vragen
    - Geen jargon of gekke afkorting(en)


### Design van componenten:

	- Check het kleurcontrast van componenten. De randen moeten voldoende contrast hebben met de achtergrondkleur
	- Check de kleurcontrasten van subtielere tekst. De tekst van de beschrijvingen en van de placeholder moet voldoende contrast hebben met de achtergrondkleur.
	- Zijn de componenten groot genoeg? 44x44px is je vriend.


### Design van het formulier:

	- Staan er buttons aan het eind van de regel, zoals “volgende”? Plaats de buttons aan het begin van de regel, waar iedereen ze kan vinden.
	- De voortgang wordt getoond boven het formulier in tekst, bijvoorbeeld “stap 2 van 4”
	- De navigatie (volgende, vorige, annuleren) is consistent in elke stap.
	- Het is duidelijk in welke stap het formulier daadwerkelijk wordt verzonden.
	- Elk invoerveld heeft een zichtbaar label dat boven het invoerveld staat. Alleen bij de zoekfunctie is de label eventueel vervangen door alleen een placeholder
	- Er staat ‘verplicht’ of ‘niet verplicht’ in tekst, niet alleen met het asterix teken.


### Flow van het formulier:

	- Staan de formuliervelden in logische volgorde?
	- Zijn er meerdere contactmogelijkheden om hulp te krijgen? Zorg voor meerdere manieren zodat het voor iedereen mogelijk is contact op te nemen, bijvoorbeeld email, chat en 		telefoon.
	- Wordt hulp op meerdere plekke aangeboden?
	- De voortgang wordt getoond boven het formulier in tekst.


### Labels:
	- Gebruik een <label for="input-id”> voor het formulierveld, en zorg dat alles een gekoppeld label heeft.
	- Andere code voor een label, zoals aria-label=“” of title="" moeten in elk geval de zichtbare labeltekst bevatten, anders werkt het niet met spraakbesturing.
	- “Voorna(a)m(en)” Nope! Voornaam (1 of meerdere) Yep!


### Makkelijker invullen

	- Als de gebruiker is ingelogd, dan worden bekende gegevens vooral ingevuld.
	- Knippen en plakken is overal toegestaan
	- Controleer of de browser autocomplete aanbiedt om velden vooraf in te vullen, waar je dat verwacht.


### Beschrijvingen bij een veld

	- Belangrijke uitleg is altijd zichtbaar. Essientiële informatie staat in een description of in de labeltekst, niet alleen in een placeholder tooltip.
	- Extra teksten bij een formulierveld zijn gekoppeld met aria-describedby op het formulier-element, zoals <input> of <select>
 	   - Beschrijving, foutmeldingen
 	   - Feedback zoals ’42 van de 100 tekens’ of ‘je wachtwoord voldoet aan de eisen’
	- De beschrijving en foutmeldingen van Checkbox Group en Radio Group zijn gekoppeld aan de <fieldset> niet aria-describedby


### Controleren

	- De laatste stap toont een samenvatting van alle ingevoerde gegevens.
	- Het formulier biedt de mogelijkheid om een inzending te controleren, te wijzigen of ongedaan te maken.
	- Voorkom met <bdi translate="no”> dat wat de gebruiker zelf heeft ingevoerd, wordt vertaald. Dit is met name op de controle-pagina en de bevestigingspagina.


### Bevestiging

	- Is er een duidelijke bevestiging? Een goede bevestiging vermeldt welke informatie is verstuurd.


### Validatie

	- De regels voor een invoerveld zijn vooraf duidelijk, bijvoorbeeld: welke tekens, of hoe lang de tekst mag zijn.
	- Boven het formulier staat uitleg over hoe de verplichte of niet verplichte velden zijn aangemerkt.


### Design van foutmeldingen

	- Foutmeldingen staan bij het betreffende veld


### Toetsenbord

	- Doorloop het formulier volledig met alleen het toetsenbord. De volgende dingen moeten goed werken:
   	 - Elk invoerveld, elke button en elke link is bereikbaar met de tab toets.
   	 - Tabvolgorde is logisch
    	- De focus indicator is goed zichtbaar
    	- Sommige componenten werken met andere toetsen dan tab.


### Screenreader - invullen

	- Het label van elk veld wordt voorgelezen als het veld focus krijgt.
	- De beschrijving van een veld wordt voorgelezen als het veld focus krijgt.
	- Verplichte velden worden verplicht aangeduid bij het voorlezen.
	- Foutmeldingen en feedback onderbreken de gebruiker niet bij het invullen.
	- Feedback over invoer (bijvoorbeeld: of ‘je wachtwoord voldoet aan de eisen’) worden automatisch voorgelezen, zonder dat de gebruiker er naartoe hoeft te navigeren 


### Screenreader - Navigatie

	- De voortgang is hoorbaar voor screenreadergebruikers: “stop 2 van 4” of vergelijkbaar.
	- Na verzenden verschijnt een duidelijke bevestiging dat het formulier succesvol is verzonden.
	- Positieve statusberichten na het versturen (zoals “formulier verzonden”)



## Zesde checkout (12-03)
### Wat heb ik vandaag gedaan?
We begonnen de dag vandaag met een ruime intro over wiskunde in CSS, en hoe krachtig dit eigenlijk is. 

Daarna ben ik aan de slag gegaan met nog een leuk iets toevoegen, namelijk een volume meter. Deze is ook te besturen met mijn fader slider. De slider bepaalt hoe 'hoog' het geluid staat. De meter zelf loopt van groen naar rood. En als kers op de taart heb ik het zo gemaakt dat wanneer de fader op 100% staat, het laatste rode lampje begint te knipperen, wat ongeveer lijkt op 'clipping' op een echte DJ set. (Clipping is een vorm van audiovervorming dat voorkomt wanneer een audiosignaal de maximale capaciteit van de audio apparatuur overschrijdt).

Ik heb nog een workshopje gevolgd van Vasilis over typografie, en heb hierbij een aantal linkjes gekregen die denk ik wel handig kunnen zijn in de zoektocht naar een leuke font.

Ik heb vandaag ook weer een feedback gesprekje gehad met mijn groepje. Daarbij kreeg ik van Sanne te horen dat ik nu qua eisen alleen nog de typografie moet doen. Verder zijn er natuurlijk ook nog andere kleine dingen die nog verbeterd kunnen worden, maar de functionaliteit is er in iedergeval wel.

Op het einde van de dag hadden we nog een weekly nerd.



### Hoe lang duurde het?
Ik heb in totaal zo'n 4 uur gewerkt aan mijn eigen project. Daarnaast heb ik nog iets minder dan een uurtje de workshop van Vasilis gevolgd. Daarna hebben we nog de weekly nerd gehad.



###  Wat heb ik geleerd?
Ik heb vandaag geleerd hoe sterk wiskunde kan zijn als je dit gebruikt in CSS. Ik heb met behulp van calc dan ook de thresholds berekent voor mijn volume lampjes.

Verder heb ik vandaag nog kleine tweaks aan de off mode gedaan.

### Wat ga ik de volgende keer doen?
Volgende keer ga ik aan de slag met de typografie eis van de opdracht. Hiervoor ga ik eerst onderzoek doen en een juist etypografie uitzoeken, daarna ga ik hier mee spelen.





## Bronnen:

https://css-tricks.com/the-shapes-of-css/

https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/input/radio

https://css-tricks.com/complete-guide-css-grid-layout/

https://codepen.io/shooft/pen/LYaexbj

https://codepen.io/yomateo/pen/ypbNrJ

https://fonts.adobe.com/fonts/basset

https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Containment/Container_queries

https://codepen.io/MATS-the-typescripter/pen/XJjNzXG?editors=1100

https://cssgradient.io/

https://www.w3schools.com/howto/howto_css_custom_checkbox.asp

https://ishadeed.com/article/css-container-style-queries/

https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Fonts/Variable_fonts

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/filter

https://w7.pngwing.com/pngs/97/954/png-transparent-macbook-pro-djay-disc-jockey-macos-computer-icons-dj-fruit-nut-macos-mac-app-store.png
