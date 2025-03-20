<h1>De Opdracht</h1>

Op 4 maart kregen we de opdracht te horen. We konden kiezen uit drie verschillende onderwerpen: een control panel, een film tijdlijn en een Rubik’s Cube. Ik heb gekozen voor het control panel, omdat ik daar meteen een leuk idee had: een paneel waarmee je de verschillende seizoenen kunt veranderen.

Ik kwam met het idee dat de gebruiker door de vier seizoenen heen kon, dit kan doormiddel van een slider of een knop (hier was ik nog niet helemaal over uit in het begin).

<h2>Week 1 – Concept en Schetsen</h2>

In de eerste week ben ik begonnen met het schetsen van het idee en nadenken over hoe ik de vier seizoenen het liefst wou weergeven. Ik tekende een standaard lay-out die als basis zou dienen voor elk seizoen. Daarna ben ik gaan nadenken over hoe ik het verschil tussen de vier seizoenen kon laten zien.

Om elk seizoen anders te maken, wilde ik verschillende elementen aanpassen:

<h3>Lente </h3>
<li>Een roze boom die kersenbloesem moet nabootsen.
<li>Een roze gloed.

<h3>Zomer</h3>
<li>Een groene boom.
<li>Felle kleuren.
<li>Heldere kleuren.

<h3>Herfst </h3>
<li>Bladeren krijgen een oranje gloed.
<li>De grond krijgt ook een oranje tint om gevallen bladeren weer te geven.
<li>Een oranje gloed over de site.

<h3>Winter</h3>
<li>De grond wordt wit, om sneeuw te simuleren.
<li>De boom word wat kaler.
<li>De lucht wordt grijs.

<h2>Responsief Design</h2>
Omdat een goede UI op alle apparaten goed moet werken, wilde ik vanaf het begin een responsive layout maken. Ik zorgde ervoor dat:
<li>De zon altijd zichtbaar is.
<li>De knoppen of slider goed werken op mobiele apparaten en volledig zichtbaar is.

<h3>Extra Ideeën</h3>
Mijn docent gaf aan dat de basis misschien te eenvoudig was en dat ik extra elementen kon toevoegen. Daarom heb ik bedacht om een extra functionaliteit toe te voegen met knoppen waarmee je:
<li>Vogels aan en uit kunt zetten.
<li>Een dark mode kunt activeren, waarmee het landschap verandert naar een nachtmodus.

Dit ga ik alleen toevoegen als ik de rest allemaal af heb.


<h2>Week 2 – Begin met programmeren</h2>

In week twee ben ik begonnen met de implementatie van mijn idee.

Ik startte met het programmeren van de standaard lay-out, en om het makkelijker te maken koos ik ervoor om eerst de zomer te bouwen. Dit seizoen bevat namelijk de meeste elementen (zoals een volle boom en een heldere lucht), en vanuit daar kon ik de andere seizoenen opbouwen.

<h3>Stap 1: Achtergrond en Grond</h3>

De eerste stap was het maken van de grond en de lucht.

<li>De lucht kreeg een blauwe kleur, met een gradient.

<li>De grond had ik eerst een vlak gemaakt, door alleen en balk onder te plaatsen, maar dat vond ik saai. Daarom heb ik het aangepast naar twee overlappende driehoeken om meer diepte te creëren. Met een gradiënt heb ik een soort schaduw effect gecreëerd.

<h3>Stap 2: De Boom </h3>

De boom was een uitdaging, omdat ik geen classes wilde gebruiken, maar alles puur in HTML en CSS wilde doen. Ik wist niet goed hoe ik dit moest aanpakken, dus ik vroeg Sanne om hulp. Uiteindelijk hebben we samen een structuur bedacht:

<li>De stam is een clip-path.

<li>De bladeren bestaan uit **meerdere cirkels **die elkaar overlappen.

<li>Voor de andere seizoenen kan ik simpelweg de kleur van de bladeren aanpassen.
<br>

Ik was erg blij met het eindresultaat en leerde veel over hoe je elementen in CSS kunt structureren zonder extra HTML-elementen te gebruiken, en hoe je css-nesting kan toepassen.

<h2>Week 3 – Seizoenen Wisselen & has Statement<h2>

In de derde week heb ik mij vooral gefocust op het veranderen van seizoenen.

Sybren heeft zich helemaal verdiept in has statements, en hij vertelde me dat dit een makkelijke manier was om mijn code te structureren.

<h3>Hoe werkt het?</h3>

<li>Elke knop is een label dat gekoppeld is aan een radio-button.

<li>Wanneer een gebruiker een seizoen selecteert, kijkt de CSS via has of dat label actief is.

<li>Op basis daarvan wordt de juiste CSS-styling toegepast.

Dit zorgde ervoor dat ik **het runnend kreeg zonder javaschript **nodig te hebben, en alles puur met HTML en CSS kon doen!

<h3>Probleem: Code Structureren</h3>

Ik probeerde alle code bij elkaar te zetten, maar ik moest voor elk seizoen een aparte has statement maken. Dit maakte de CSS erg lang. Daarom heb ik geprobeerd de has statements bij elkaar te doen, maar dat lukte helaas niet.

Ik heb ook gewerkt aan de kleuraanpassingen van de verschillende seizoenen, zoals:

<li>Lente: lichtere kleuren, zachte overgangen.

<li>Zomer: felle kleuren, scherpe contrasten.

<li>Herfst: warme oranje en bruine tinten.

<li>Winter: koude blauwtinten en een witte achtergrond.


<h2>Week 4 – Finetuning & Extra Features</h2>

In de vierde week ben ik verder gegaan met de laatste details en extra functionaliteiten.

<h3>Extra functionaliteiten toegevoegd:</h3>

Ik kwam er in deze week achter dat ik nog geen titel had, nu kwam ik met het idee om een vliegtuig door het scherm te laten vliegen, met een banner er achter.

Dit het ik dus ook toegevoegd, maar het was lastiger dan ik dacht. Het vliegtuig zelf is een afbeelding, maar de banner is volledig met css gemaakt. Ik ben tot 6 uur op school gebleven en heb lopen brainstormen met Nils en Sanne. Uiteindelijk hadden we het voor elkaar gekregen om de letters over het scherm te laten "dansen", en toen ben ik naar huis gegaan om de volgende dag door te gaan. Toen ik op school kwam hadden Sanne en Nils allebei een heel ontwerp voor me gemaakt. Ik ben uiteindelijk met die van Nils gegaan omdat de andere er meer als een vlag uitzag, en minder als een banner. Deze code heb ik wel moeten aanpassen, omdat ik er een andere font in wou hebben, maar dit is uiteindelijk gelukt.

Responsiviteit Verbeterd

<li>Getest op verschillende schermformaten (desktop, tablet, mobiel).

<li>Knoppen correct gepositioneerd.

<li>Seizoenswisselingen werken goed op touchscreens.

<h2>Conclusie</h2>
Ik ben heel tevreden over mijn eindproduct, heb ook veel vwerschillende dingen geleerd, zoals:
<li>Hoe CSS-nesting werkt.
<li>Dat je niet voor alles een aparte class voor hoeft te maken.
<li> Hoe ik verschillende vormpjes kan maken.

Als ik dit project opnieuw zou moeten doen zou ik eigenlijk niest anders doen, ik ben heel tevreden.
