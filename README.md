# Model

Het staat model voor digitale tuintjes welke bij 'Het web is voor iedereen' door studenten worden gemaakt.

## Learning Log

### [...]

[...]

### 2 sept - Deep dives

Ik heb gekozen om vandaag de volgende deep dives te volgen:

- HTML & CSS Basics
- Interactie: MMD, micro-interacties, forms

Voor de eerste deepdive HTML & CSS Basics heb ik de artikelen gelezen die we als huiswerk hadden gekregen, hier heb ik aantekeningen bij gemaakt. Tijdens het lezen van deze artikelen kwamen de volgende vragen bij mij op:

- Wat is het verschil tussen <b> en <strong>?
  Beide taggs zorgen ervoor dat de tekst visueel hetzelfde eruit zien, maar ze betekenen iets anders. <strong> geeft aan dat de tekst inhoudelijk belangrijk, dringend of ernstig is. Zoekmachines zorgen er dan meestal automatisch voor dat deze tekst vetgedrukt wordt. Daarnaast wordt deze tekst door een schermlezen anders voorgelezen omdat <stong> extra waarde aan de tekst geeft. De <b>-tagg is enkel visueel en zorgt ervoor dat een tekst vet gedrukt worden en hierdoor aandacht trekt. Maar het geeft niet aan dat de tekst inhoudelijk belangrijk is, hier zullen zoekmachines of schermlezer geen speciale beteknis aan geven. <a href="https://www.freecodecamp.org/news/difference-between-b-and-strong-in-html/">Dit is de bron van deze tekst</a>
- Hoe kunnen meerdere CSS-regels met elkaar botsen, en hoe bepaalt de browser welke regel voorrang krijgt?
  Dit komt doordat twee of meer CSS-regels zich richting op hetzelfde HTML-element, maar verschillende eigenschappen hebben. Hierbij zal een van de klassedefinities de andere overrschrijven. Dit kan leiden tot inconsistentei of onverwachte resultaten. CSS lost conflicten op door middel van een systeem van specificiteit, overerving en de cascade, vaak aangeduid als het "Cascading Style Sheets" systeem. Dit werkt als volgt: 1. Specificiteit. Specificiteit verwijst naar het gewicht van een CSS-selector. Hoe specifieker een selector is, hoe hoger de prioriteit. 2. De Cascade. De cascade verwijst naar hoe de volgorde van stijlen hun toepassing beïnvloedt. Wanneer twee regels dezelfde specificiteit hebben, heeft degene die later wordt geschreven voorrang. 3. Ervenis. Overerving verwijst naar hoe stijlen die worden toegepast op bovenliggende elementen kunnen cascaderen naar hun onderliggende elementen. Sommige eigenschappen, zoals lettertypefamilie of kleur, zijn erfelijk, terwijl andere, zoals marges of randen, dat niet zijn. 4. Belangrijkste. De `!...` verklaring is een andere factor die de normale specificiteitsregels overschrijft. Wanneer een eigenschap is gemarkeerd als `!...`, het heeft voorrang op andere verklaringen, zelfs als die andere verklaringen een hogere specificiteit hebben. <a href="https://medium.com/@kinzaeman69/conflicting-css-classes-20e7b6776f0d">Dit is de bron van deze tekst</a>

Ook zijn er een paar zaken die mij verwonderen:

- Een "<h1>"-tag vertelt hoe belangrijk een titel is niet hoe groot hij moet zijn.
  Ik dacht altijd dat <h1> ervoor zorgde dat een titel groter werd. Maar nu blijft dat dit helemaal niet de belangrijkste functie van <h1> is. Met <h1> geef je namelijk aan dat een tekst de belangrijkste titel van een pagina is. De grootte van de tekst wordt vervolgens door CSS bepaald. <h1> gaat dus niet zozeer over hoe groot iets is, maar over hoe belangrijk iets is.
- De tekst achter een afbeelding is net zo belangrijker, misschien nog wel belangrijker dan de afbeelding zelf.
  Ik dacht altijd dat een afbeelding op een website gewoon een afbeelding was die je met een `<img>`-tag toevoegt. Nu begrijp ik dat de tekst die je bij `alt` toevoegt minstens zo belangrijk is. Deze tekst beschrijft namelijk wat er op de afbeelding staat voor mensen die de afbeelding niet kunnen zien, bijvoorbeeld wanneer ze een screenreader gebruiken. Ik vind het bijzonder dat je bij het maken van een website dus niet alleen moet nadenken over wat je zelf ziet, maar ook echt rekening moet houden met mensen die niet goed kunnen zien.

Ook ben ik naar de deep dive Interactie: MMD, micro-interacties, forms. Tijdens deze deepdive hebben we een opfrissing gekregen van interacties, hier kwam ik er achter dat ik dit eigenlijk nog super goed weet. En vond ik dat er weinig nieuwe dingen vertelt zijn. We hebben tijdens de les een begin gemaakt aan een ontwerp voor een take-away menu voor een noodleshop. Ik ben hier zelf niet heel ver mee gekomen, maar wil dit wel nog een keer afmaken als ik hier de tijd voor heb. Maar wil momenteel meer de focus leggen op html/css dan op figma.

### 31 aug - Kickoff

Een fork van de model repository gemaakt en gepubliceerd via mijn eigen Github omgeving.

1. Leg uit wat een source hosting platform is en voor welke jij gekozen hebt.

- Een Source hosting platform is een plek waar je de gegevens, code, van je site kunt opslaan. Ik heb zelf gekozen voor Github, omdat ik dit al vaker gebruikt heb.

2. Vertel welke domeinnaam jij gekozen hebt en hoe je die hebt gekoppeld aan jouw pagina.

- Mijn domeinnaam is tuintjevanleonie. Ik heb deze naam gekoppeld via TransIp en heb hiernin DNS instellingen gemaakt. Vervolgens heb ik in Github mijn domeinnaam naar de IP-adressen van de Github server verwezen. En maakt het systeem automatisch een CNAME bestand. Na het activeren van de Enforce HTTPS is mijn eigen dommeinnaam geactiveerd.

3. Beschrijf hoe je aanpassingen aan jouw pagina kunt maken en hoe je er voor zorgt dat die op het web gepubliceerd worden.

- Door in Source Control bij changes aanpassingen een naam te geven en op commit te drukken herkent het systeem een wijziging. Door vervolgens op 'Sync Changes' te klikken worden je aanpassingen geupdated. Als je vervolgens je webpagina opnieuwe laad, zijn de aanpassingen zichtbaar.
