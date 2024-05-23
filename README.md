# Victory
*Blessures bij lopers reduceren door middel van schokdetectie, die via een LED en trilling wordt waargenomen.* 

*Ian Maes*

24/05/2024

## Samenvatting
Heden ondervinden talrijke hardlopers belemmeringen in de vorm van **blessures**. Middels schokdetectie zal een waarschuwing aan de hardlopers worden verstrekt, waardoor de lopers gedurende de loopactiviteit de loopstijl kunnen moduleren ter voorkoming van blessures. Het is echter cruciaal om de lopers **tijdens het hardlopen effectief te waarschuwen**. In een initiële poging hiertoe werd gebruik gemaakt van auditieve interferentie, zoals ruis op muziek. Uit een aanvankelijk onderzoek bleek dat niet iedereen de voorkeur geeft aan hardlopen met muzikale begeleiding. Om die reden werd naar alternatieve benaderingen gezocht. Het doel is om de hardlopers te waarschuwen door middel van een **LED die de kleur rood aanneemt**. Deze waarschuwingsfunctie kan worden geïntegreerd als een toevoeging aan het horloge. Gezien het feit dat de overgrote meerderheid van hardlopers reeds een horloge draagt, is het gerbuik hiervan relatief eenvoudig.

Bovendien kan er een **disciplinaire sanctie** geassocieerd worden met deze waarschuwing, zodat hardlopers niet slechts worden geïnformeerd over het suboptimale loopgedrag, maar ook extra gemotiveerd worden om daadwerkelijk corrigerende acties te ondernemen. Deze disciplinaire maatregel neemt de vorm aan van een **vermindering van de loopsnelheid**, iets wat iedere hardloper vanzelfsprekend wenst te vermijden, aangezien niemand graag heeft dat de afnemende snelheid wordt waargenomen door vrienden of medelopers.

Tot slot is het van belang dat deze data tot bij de gebruikers geraakt. Hiervoor wordt gebruik gemaakt van een **applicatie**. Deze applicatie geeft de data op een overzichtelijke manier weer. Zo kan de loper duidelijk zien waar er ruimte is voor verbetering. Met hulp van deze applicatie zal ook het sociale contact met vrienden bevorderd worden.
<img src="images/heroshot_def.png"/>


## Introductie
Victoris[^1] heeft lang onderzoek gedaan naar dit onderwerp en bedacht het idee om met een sensorband signalen te sturen naar een koptelefoon die de loper waarschuwt. Uiteindelijk was het concept niet overtuigend genoeg. Daarom heeft het initiële concept een paar aanpassingen/toevoegingen nodig. Gedurende lange tijd vormde het obstakel zich in het onvermogen van technologie om hardlopers van blessures te ontnemen. Victoris heeft getracht deze situatie te verbeteren. De technologie voor schokdetectie tijdens het hardlopen is geëvalueerd en heeft zich als uitermate doeltreffend bewezen. Echter, er bestaat een wens om aanvullende inzichten te vergaren met betrekking tot het waarschuwen van hardlopers en mogelijke aanpassingen aan de sensorband. 
De ambitie is om het product succesvol op de markt te introduceren. 

Randvoorwaarden:
- gebruiksvriendelijkheid
- aanpasbaarheid
- visualisatie

## Methodologie
Het eerste deel van de opdracht werd opgedeeld in 2 grote fasen: discovery en definition. Dit is hieronder weergegeven in een quadruple diamond.

<img src="images/Methodologie.png"/>

### problem discovery 
In het eerste deel ging alle aandacht naar het onderzoeken van de opdracht. Het is belangrijk om elk detail van de opdracht te kennen. Dit alles om de verschillende deelaspecten van de opdrachten in kaart te brengen. 

### problem definition
Na het bespreken van alle problemen was er terug nood aan eenduidigheid. Aan de hand van *user interviews* werd geconvergeerd naar het idee om het auditieve interferentie aan te pakken. Ook het sociale contact zal geïntroduceerd worden.

### solution discovery
In de tweede fase werd opnieuw gedivergeerd met *ideation* en werd het sportlab in Gent bezocht. Dit was een heel interessant bezoek, aangezien er veel feedback en feedforward werd gegeven door experten. Ze waren enthousiast over het idee om te werken met leds. Daarna moesten ideeën gegenereerd worden. Het prototypen kon beginnen.

### solution shaping
Daarna moest opnieuw een keuze gemaakt worden tussen verschillende prototypes. Voor dit te verwezenlijken werden gerbuikerstesten gehouden. Via deze methode werden snelle en correcte beslissingen genomen. 

### iterative build cycles (ideate - prototype - test)
In deze fase werd 3 maal de cyclus 'ideate - prototype - test' doorlopen. Telkens uit een andere invalshoek: *Human Body*, *Human Mind* en *Human Senses*. Telkens na een cyclus werden design requirements opgesteld. Op die manier werd duidelijk wat er in het concept nodig was en wat niet.

### finalize, implement
Tot slot werden renders gegenereerd en een demo video opgemaakt. Zo is het concept duidelijk gevisualiseerd. 

## Discovery
### Doelstellingen
Het doel is om een duidelijk inzicht te krijgen in welke deelaspecten geïnoveerd moeten worden en hoe dit verwezenlijk kan worden.
### Materiaal & methoden
De volledige ruimte werd eerst onderzocht aan de hand van:
- *Innovatrix*
- WWWWWH-model
- *Problem Solution Matrix*
- *Root-cause analysis*

Om deze methodes toe te passen moest er eerst aan *benchmarking* en *user interviews* gedaan worden.

### Resultaten
#### Benchmarking (N=8)
Aangezien vele designkeuzes vaak al succesvol opgelost worden door anderen, werd gebruik gemaakt van *benchmarking*. Niet alles moet opnieuw onderzocht worden. Daarom worden bestaande oplossing grondig bestudeerd. Alle resultaten werden gestructureerd in een *problem-solution matrix* gegoten.

<img src="images/problem_solution_matrix_groen.png"/>

#### Sportlab Gent (30/11)
Dit werd zoals vermeld eigenlijk later pas gedaan, maar wat hieronder vermeld wordt past beter bij de *discovery* fase. Een inzicht dat daar gegeven werd, was dat ook de iets minder gedreven lopers zich moeten aangesproken voelen. Het zijn dan namelijk ook vaak deze lopers die te kampen krijgen met blessures [^2]. Ook sinds Corona zijn er veel mensen die ineens beginnen sporten. Deze groep is uiteraard niet zo fysiek in orde zoals echt sporters. Daarom moet zeker bekeken worden hoe deze groep kan aangezet worden tot het kopen van het product.

#### User interviews (N=4)
Om de probleemruimte grondig te analyseren kon een *user interview* uiteraard niet ontbreken. Op die manier wordt met de toekomstige gebruikers kort op de bal gespeeld. Vaak worden hier ook nieuwe inzichten gegeven of worden vermoedens bevestigd. Na de korte ondervraging werd snel duidelijk dat doorgaan met het audio-systeem niet zou werken.
> "In wedstrijden loop ik nooit met muziek."

Ook het idee van de waterrugzak, die afhankelijk van de schokdetectie wel of geen water doorliet, werd snel de kop ingedrukt. Dit was te bruut en ook moeilijk in gebruik. Zeker in vergelijking met het volgende idee. 
Dat was een eenvoudige LED strip die de loper waarschuwt tijdens het lopen. Als het rood is, is de schokdetectie te hoog. 

Er is ook een idee om met een straf te werken, aangezien de loper echt gedwongen moet worden om de loopstijl aan te passen. Dit zou een snelheidsvermindering zijn. Elke loper wil dit uiteraard vermijden. Dit werd wel genuanceerd tijdens een gesprek met andere studenten in Gent. Die kwamen met het inzicht dat mensen die het product kopen, sowieso iets willen veranderen aan de loopstijl. Daardoor zou de onnodig blijken. Dit wordt verder onderzocht. 

Alles is hieronder mooi weergeven in een tabel.

||1|2|3|4|  
|---:|:---:|:---:|:---:|:---:|
|Feedback: (muziek/waterrugzak/LED/trilling)|Trilling|LED|LED|LED en Trilling|
|Ondergrond|90% verhard|2x/week piste, anders verhard|meestal verhard|1x/week pist, anders verhard|
|Lopen met muziek|Soms|Nooit|Nooit|Altijd|

### Conclusies & implicaties
De conclusie hieruit is dat er 2 specifieke zaken moeten aangepakt worden:
    1. Het real-time feedbacksysteem
    2. De dataweergave
Dit zal verwezenlijkt worden door te werken met een LED en trilling. Dit om de loper te waarschuwen. Daarnaast wordt data schematisch weergegeven op een applicatie. Hoe en wat wordt onderzocht in de volgende fase: Definition.

## Definition
### Doelstellingen
Met de test in de eerste wave moet inzicht verworven worden in waar de loper de add-on (LED) zou willen bevestigen en waar het gemakkelijk waarneembaar is, zonder hinder voor de gebruiker tijdens het lopen.
Onderzoeksvraag 1: Hoe kan de loper gewaarschuwd worden via licht?
In deze tweede wave werd onderzocht hoe de data weergeven wordt voor de loper. De testpersonen maken elk een keuze en daaruit werden de juist beslissingen maken.
Onderzoeksvraag 2: Via welke applicatie en op welke manier wilt de gebruiker de data te zien krijgen? 

### Materiaal & methoden
Deze onderzoeksvragen werden ondervraagd met volgende materialen: 
- Led
- 3 verschillende applicaties
De Victory-applicatie is zelf ontworpen. Het is een zelfstandige applicatie waarop alle data kan verschijnen, in verband met een loopsessie en schokdetectie.

Als methode werd de *focus group* gebruikt.
Na de brainstorm fase werden er *user tests* en *user interviews* toegepast.

### Resultaten
#### Real-time feedbacksysteem (N=3)
Na een voorafgaand interview, waarin werd gepeild naar het gebruiksgemak met de verschillende gadgets, volgde de test. Deze test onderzocht de zichtbaarheid en het comfort van de LED. 
Er werd gevraagd om even een stukje te lopen. De loper kan op die manier inschatten of de LED op de juiste plaats bevestigd wordt. Verder kan de loper eventuele problemen/ongemakken ervaren.
Uit het voorafgaande interview uit wave 1 werd vooral vastgesteld dat 2 van de 3 testpersonen geen enkel probleem hadden met meer gadgets/technologie naast de gebruikelijke sporthorloge en hartslagmeter. De andere testpersoon vond het net iets te veel, maar de voordelen wogen alsnog meer door t.o.v. de nadelen. Over het algemeen waren de reacties op het concept positief en enthousiast. Uit de test bleek dat de in de regio van de pols de beste oplossing was, de andere posities waren moeilijk waar te nemen (bijvoorbeeld op de schoen). **De add-on op het horloge was hierbij dan de populairste positie**.

<p>
    <img src="images/licht_schoen.jpg" width="40%"/>
    <img src="images/licht_pols.jpg" width="40%"/>
</p>

#### Dataweergave (N=3)
De tweede test werd aan de hand van uitlegvideo's en taak interviews aan de gerbuikers voorgesteld.
Met 3 verschillende vragen en telkens 3 verschillende prototypes, werd aan de slag gegaan. 3 keuzes werden aan 3 verschillende testpersonen (lopers) voorgesteld en daaruit de beste genomen.

De testpersonen werden gevraagd om met het prototype aan de slag te gaan. Dit om te kijken hoe gebruiksvriendelijk de interface was opgesteld. Daarna werd uitgelegd hoe het concept met de applicatie in elkaar zit. Na deze stappen kunnen de testpersonen een keuze maken. Welke applicatie het vaakst werd gekozen, wordt verder uitgewerkt in dit ontwerp. 
De eerste keuze werd gemaakt op basis van waar de data terecht komt. De data wordt grafisch weergegeven in grafieken. Ook dit kan op verschillende manieren. De testpersonen mochten ook hier een voorkeur uitspreken. Tot slot werd in de discovery fase duidelijk dat de ondergrond belangrijk is voor de grote van de schokken. Daarom werd gepolst of een routebouwer, die een route maakt met de zachtste ondergrond, kan geïmplementeerd worden in de applicatie.

<p>
    <img src="images/voorbeeld_stravaapp.png" width="32%"/>
    <img src="images/voorbeeld_victory_stravaapp.png" width="32%"/>
    <img src="images/voorbeeld_victoryapp.png" width="32%"/>
</p>
<p>
    <img src="images/strava grafieken3.jpg" width="32%"/>
    <img src="images/victory_grafieken.jpg" width="32%"/>
    <img src="images/voorbeeld_victory_grafiek.png" width="32%"/>
</p>
<p>
    <img src="images/voorbeeld_victory_routebouwe.png" width="32%"/>
</p>

Bij deze eerste keuze kozen 3/3 testpersonen voor de Victory-applicatie. De meeste mensen houden liever de zaken uit elkaar en willen geen zaken verwarren met elkaar. Bij de tweede keuze koos opnieuw 3/3 voor de tweede optie, met de rode balken onder de grafiek. Deze grafiek vonden ze het duidelijkst. Tenslotte bij de derde keuze vond één iemand het niet per se nodig, maar mag wel. De andere twee vonden het wel een handige functie, die ze zouden gebruiken. 
> "Ik had vandaag de routebouwer kunnen gebruiken, want de weg lag er echt slecht bij."

**Resultaat= aparte (Victory) applicatie, rode balk onder de grafiek en een functie routebouwer.**

### Conclusies & implicaties
Om de loper te waarschuwen wordt gerbuik gemaakt van een add-on die licht uitstuurt. Ook is het feit dat de add-on nog verder moeten ontwikkelen en nog moet getest worden welk soort bandje, dikte, dichting... het best past.
Daarnaast wordt geconcludeerd dat de data weergegeven wordt op een aparte applicatie 'Victory'. De grafieken worden weergegeven met rode balken onder de grafiek en er zit een functie routebouwer in de applicatie. 


> [!IMPORTANT]
> #### Design requirements
>
> Er wordt een add-on, die licht uitstraalt, gebruikt om de loper te waarschuwen.
> De add-on bevindt zich op de pols. 
> Er is een aparte, zelfstandig applicatie voor de dataweergave.
> Er wordt een routebouwer geïplementeerd in de applicatie.

## Bill of materials
|Materialen|Prijs|Link|  
|---:|:---:|:---:|
|Add-on|€86,80|https://www.kickstarter.com/projects/1742184757/glance-worlds-first-smart-accessory-for-your-watch/comments|
|Sensor|€119,00|https://www.movesense.com/shop/|

## Develop 1: Human Body
### Doelstellingen
Het eindpunt voor deze opdracht is een geoptimaliseerd ontwerp, waarvan aan de hand van een anthropometrische analyse en *user tests* kan aangetoont wordeb welke optimalisaties moeten aangebracht worden op het vlak van de fysieke ergonomie.

### Materiaal en methoden
Voor deze opdracht werd verder gewerkt op de add-on en sensorband vanuit de definition. Daarvoor werd eerst een antropometrische analyse uitgevoerd. De add-on dient onder een horlogeband geplaats worden en waarschuwt de loper met rood licht en een trilling. De sensorband wordt georiënteerd op de enkel en meet de schokken van de gebruiker. Het zijn beiden onderdelen die op het lichaam worden gebruikt. Een antropometrische analyse om te onderzoeken of het ergonomische aangebracht kan worden is dus zeker niet overbodig. 
Na opzoekingswerk werden volgende afbeeldingen interessant bevonden. Uiteraard is het voor de meeste mensen wel logisch dat een rechthand tot bij een linkerpols geraakt of omgekeerd. Ook wordt het niet in vraag of de handen tot aan een enkel kunnen. Tot slot werd ook nog duidelijk dat de add-on absoluut niet groter mag zijn dan 18cm, omdat de vingers die anders niet kunnen vasthouden. Dit is duidelijk op de derde afbeelding.
[^4]

<p>
    <img src="images/antropometrie_sensor.png" width="40%"/>
    <img src="images/antropometrie_sensorband.png" width="18%"/>
    <img src="images/antropometrie.jpg" width="40%"/>
</p>

Hieronder worden de handelingen ook gesimuleerd in Siemens NX.
De add-on:
<p>
    <img src="images/Jack_1.png" width="40%"/>
    <img src="images/Jack_2.png" width="39%"/>
</p>

De sensorband:
<p>
    <img src="images/Jack_3.png" width="26%"/>
    <img src="images/Jack_4.png" width="40%"/>
    <img src="images/Jack_5.png" width="33%"/>
</p>

De percentielberekeningen hadden in dit concept geen extra waarde.
Ondertussen werden er wel ook andere zaken bevraagd en gemeten bij de sensorband. De omtrek was nog steeds onbepaald. Ook werd bevraagd of de sensorband een elastische band moet zijn of er beter met een kliksysteem gewerkt wordt. Dit is duidelijk te zien in onderstaande afbeeldingen.

### Resultaten
#### Antropometrische analyse (N=3)
Voor de add-on werd gebaseerd op een bestaand product, genaamd Glance[^3]. Dit is een stuk die perfect onder een horlogeband past. Aan beide zijden komt het er een beetje uit, voor de stabiliteit van het product. Langs de ene zijde komt er net een groter deel uit, omdat er daar een OLED display zit. Zo kan de gerbuiker snel een bericht lezen of dergelijke. Bij het ontwerp zou de display vervangen worden door een led. Op die manier wordt de loper gewaarschuwd. Zie onderstaande foto's ter verduidelijking.
<p>
    <img src="images/glance_product.png" width="36%"/>
    <img src="images/glance_oled.png" width="32%"/>
    <img src="images/nx_glance.png" width="26%"/>
</p>

Eerste prototype:
<p>
    <img src="images/prototype_tante.jpg" width="20%"/>
    <img src="images/nx_prototype.png" width="20%"/>
    <img src="images/prototype_rense.jpg" width="20%"/>
    <img src="images/gwin_add-on.png" width="18.5%"/>
</p>

Dit prototype werd iets breder gemaakt om de stabiliteit te vergroten (zie afbeelding rechts).
Voor deze opdracht werd zoals vermeld gebruikt gemaakt van *user tests*. Deze testpersonen werden gevraagde de add-on en sensorband te bevestigen. Uit die ondervindingen werd bepaald of het product al dan niet ergonomisch ontworpen is en of er eventuele aanpassingen nodig zijn.

<p>
    <img src="images/gwin_sens.png" width="34%"/>
    <img src="images/gwin_senso.png" width="29%"/>
    <img src="images/gwin_velcro.png" width="33%"/>
</p>

Uit het onderzoek dat een velcroband best was. Vooral als de schoenen al aan de voeten zijn, is het heel moeilijk om de elastische band nog over je voet te trekken. 
Om de omtrek van de sensorband te bepalen, werden er, vanuit een steekproef met een volledige klasgroep en de testpersonen, afmetingen genomen van de omtrek van de enkels. Hieronder zijn de resultaten. Deze werden gebruikt om de sensorband mee te maken.
De laagste score was 19,5 cm en de hoogste 27 cm. De sensorband werd dus gemaakt met als kleinste omtrek 19,5cm en als grootste omtrek 27 cm. [maten](https://docs.google.com/document/d/177shcS6c-XjRFj7ajuwbEiQrWMjYZvnB4AYkbZvYki0/edit)

<img src="images/oma_naaien.jpg" width="30%"/>

> [!IMPORTANT]
> #### Design requirements
> De ontwerpstrategie voor de add-on is *design for more types*. De add-on moet in verschillende maten beschikbaar zijn, want er zijn ook verschillende breedtes horlogebanden. Bij de sensorband moet *design for adjustability* toegepast worden. De maat voor de sensorband moet aanpasbaar zijn. Voor verschillende diktes benen. 
> <img src="images/design_for_am.png" width="70%"/>
> 
> Naast de ergonomische verbeteringen moet de add-on nog een beetje aangepast worden. Zoals vermeld moet de uitsparing iets dieper zodat het er niet onderdoor schuift en beter blijft zitten. Daarnaast zijn er verschillende breedtes van horlogebanden. Daarom moet de add-on in meerdere types beschikbaar zijn. Dit is mooi weergegeven in onderstaande afbeelding.
> 
> <img src="images/design_glance.png" width="40%"/>

## Develop 2: Human Mind
### Doelstellingen
Het eindpunt voor deze opdracht is een geoptimaliseerd ontwerp, waarvan aan de hand van een *expert review* en *usability tests* optimalisaties moeten worden aanbracht.

### Materiaal en methoden
Er werd ondertussen grondig verder gewerkt aan de add-on.
In bijlage zit een duidelijke video waarin de add-on wordt getoond en getest. Zoals daarin te zien, is er een  RGB LED (LED) vastgemaakt op de add-on. De LED kan veranderen van kleur en zal zo de lopers waarschuwen. Ook is er een trilmotor voorzien die de loper extra waarschuwd, wanneer er met de rode LED wordt gelopen. Deze twee componenten zijn verbonden met een arduino. Op die arduino zit een infraroodsensor. Voor te testen werd gebruik gemaakt van de *wizard of oz* methode. Op die manier kon de LED van op afstand bediend, terwijl de loper het prototype test. In de realiteit staat de add-on met Bluetooth in verbinding met de sensor. Onderstaand code werd in Arduino IDE geprogrameerd. Daaronder is ook nog een afbeelding weergegeven.


```py
#include <IRremote.h>
#include <TimerFreeTone.h>

#define buzPin 4

IRrecv IR(7);
int ledR = 10; // Rood
int ledG = 9; // Groen
int ledB = 11; // Blauw
bool ledKleur = false;
bool buzzerActive = false;

unsigned long previousMillis = 0;
unsigned long buzzerPreviousMillis = 0;
const unsigned long buzzerInterval = 20000; // Buzzer interval in milliseconds

void setup()
{
  IR.enableIRIn();
  pinMode(ledR, OUTPUT);
  pinMode(ledG, OUTPUT);
  pinMode(ledB, OUTPUT);
  pinMode(buzPin, OUTPUT);
  Serial.begin(9600);
}

void loop()
{
  unsigned long currentMillis = millis();
  
  // Check if it's time to activate the buzzer
  if (ledKleur && (currentMillis - buzzerPreviousMillis >= buzzerInterval))
  {
    for (int t = 0; t < 750; t += 10)
    {
      TimerFreeTone(buzPin, t, 10);
    }
    buzzerPreviousMillis = currentMillis; // Reset the buzzer timer
  }

  if (IR.decode())
  {
    Serial.println(IR.decodedIRData.decodedRawData, HEX);
    if (IR.decodedIRData.decodedRawData == 0xA15EFF00) // Knop 3 (Rood)

    {
      digitalWrite(ledR, HIGH);
      digitalWrite(ledG, LOW);
      digitalWrite(ledB, LOW); // ROOD
      ledKleur = true;
      buzzerPreviousMillis = currentMillis; // Reset the buzzer timer
      for (int t = 0; t < 750; t += 10)
      {
        TimerFreeTone(buzPin, t, 10);
      }
    }
    if (IR.decodedIRData.decodedRawData == 0xF30CFF00) // Knop 1 (Groen)
    {
      digitalWrite(ledR, LOW);
      digitalWrite(ledG, HIGH);
      digitalWrite(ledB, LOW);
      ledKleur = false;
    }
    if (IR.decodedIRData.decodedRawData == 0xE916FF00) // Knop 0 (Uit)
    {
      digitalWrite(ledR, LOW); 
      digitalWrite(ledG, LOW);
      digitalWrite(ledB, LOW);
      ledKleur = false;
    }
    if (IR.decodedIRData.decodedRawData == 0xE718FF00) // Knop 2 (Oranje) 
    {
      analogWrite(ledR, 255);
      analogWrite(ledG, 20);
      digitalWrite(ledB, LOW); 
      ledKleur = false;
    }
    if (IR.decodedIRData.decodedRawData == 0xF708FF00) // Knop 4 (Start 3 toggle)
    {
      digitalWrite(ledR, LOW);
      digitalWrite(ledB, LOW);
      digitalWrite(ledG, LOW);
      delay(1000);
      analogWrite(ledR, 255);
      delay(1000);
      digitalWrite(ledR, LOW);
      digitalWrite(ledB, LOW);
      digitalWrite(ledG, LOW);
      delay(1000);
      analogWrite(ledR, 255); 
      analogWrite(ledG, 20); 
      delay(1000);
      digitalWrite(ledR, LOW);
      digitalWrite(ledB, LOW);
      digitalWrite(ledG, LOW);
      delay(1000);
      analogWrite(ledG, 255);
      delay(1000);
      digitalWrite(ledR, LOW);
      digitalWrite(ledB, LOW);
      digitalWrite(ledG, LOW);
      ledKleur = false;
      buzzerPreviousMillis = currentMillis; // Reset the buzzer timer
      for (int t = 0; t < 750; t += 10)
      {
        TimerFreeTone(buzPin, t, 10);
      }
    }
    if (IR.decodedIRData.decodedRawData == 0xE31CFF00) // Knop 5 (Groen ademen)
    {
      for (int i = 0; i <= 255; i++) {
      analogWrite(ledG, i);
      delay(10);  // stel de snelheid van de fade in
      }
      // Geleidelijk weer uit
      for (int i = 255; i >= 0; i--) {
      analogWrite(ledG, i);
      delay(10);  // stel de snelheid van de fade in
      }
    }
    IR.resume();
  }
}
```
<p>
    <img src="images/stopwatch_arduino.jpg" width="20%"/>
    <img src="images/add-on_arduino.png" width="20%"/>
</p>


Deze opdracht werd opgesplitst in twee waves: de *expert review* en de *usability tests*. 

### Resultaten 
#### Expert review (N=2)
In de *expert review* werd met 2 medestudenten een test uitgevoerd. Deze testpersonen kennen de opdracht, dus worden als experts beschouwd. Op die manier werden gerichtere en specifiekere vragen gesteld.
Nadat de experts het prototype grondig bekeken en daarna uittesten, werden nog extra vragen en bedenkingen besproken. 

Er werden volgende dingen nog opgemerkt: het moet mogelijk zijn om de add-on op te laden, de tijdspanne tussen de trilling, tijdens de rode LED, was nog steeds onbepaald. Er werd vastgesteld dat de loper best zijn eigen tijdspanne instelt. De functionaliteit van de applicatie is goed, maar moet visueel veel beter. Dit laatste vertaald zich in: het lettertype, het kleurgebruik, animaties...

Er werden volgende zaken opgemerkt.:
- De eerste expert zei dat de LED niet eerst groen moet worden. Het zal de loper meest waarschuwen als de LED ineens op oranje springt. Daarop had de tweede expert wel een andere inkijk. Die vertelde dat als de groene LED niet brandt bij lage impact, de loper kan denken dat de add-on niet werkt. Om een middenweg te vinden moet worden getest of het eventueel beter is als de groene LED geleidelijk aan en uit gaat.
- De velcroband hapert te veel tijdens het aandoen.
- De experts plaatsten allebei de add-on, met de LED, naar het hoofd. 
- De sensor is quasi altijd gemakkelijk in te steken en uit te halen, maar af en toe komt er toch wat moeite bij kijken. 

Daarnaast werden ook een aantal goede zaken aangekaart.: 
- Dankzij de elasticiteit van de sensorband is het heel stevig aan te spannen en blijft het ten allen tijde op zijn plaats.

> "De belastingscurve is erg interessant, omdat die mooi weergeeft of de loper al dan niet progressie maakt."

<p>
    <img src="images/test_emile.jpg" width="32%"/>
    <img src="images/test_rense.png" width="48%"/>
</p>

#### Usability test (N=3)
Daaropvolgend werd de test nogmaals uitgevoerd. Nu met 3 testpersonen.

Er werden volgende zaken opgemerkt.:
- De straf is niet nodig. Wanneer een loper dit product aankoopt, wilt die al zijn loopstijl verbeteren en hoeft daarom niet extra gestimuleerd te worden.
- De testpersonen plaatsen ook hier alle drie de add-on, met de LED, naar het hoofd. 1 persoon omdat het logisch leek, maar de andere 2 merkten op dat de add-on anders in de plooi van de pols terecht komt. Om dus die richting duidelijk aan te geven, zal er een symbool geplaatst worden op de add-on.
- De sensorband kan misschien ook eens in het wit gemaakt worden en dan testen welk kleur beter is.
Daarnaast werden ook een aantal goede dingen opgemerkt.: 
- Het is goed dat de LED eerst nog op oranje springt en niet meteen op rood.

De eerste testpersoon vroeg hoe de routebouwer eigenlijk in elkaar zit. Daarop werd verder gebrainstormd. Toen werd op het idee gekomen om een functie in de applicatie te stoppen, die alle routes minder dan 15% impact verzameld. Dus de lopers maken eigenlijk mee de routebouwer te maken. Wanneer een locatie wordt ingegeven zal de routebouwer alle routes voorstellen die minder dan 15% schokken ondervonden. Daarna kan de gekozen route gestart en opgenomen worden. Dit werd getest met de testpersonen en als zeer nuttig ervaard.

> [!IMPORTANT]
> #### Design requirements:
>
> - Tijdspanne tussen trillingen, als loper, zelf kunnen instellen.
> - De LED moet voor de rode LED eerst oranje zijn.
> - De sensorband moet smaller, zodat die minder hapert.
> - De add-on moet oplaadbaar zijn.
> - De add-on wordt geplaatst met de LED richting het hoofd van de loper.
> - De functionaliteit van de applicatie zit goed.
> - De belastingscurve is erg interessant.
> - De interface moet aantrekkelijker.
> - De routebouwer leert welke routes goed zijn, door de gegevens van de lopers te bekijken en daaruit de beste terug voor te stellen.
> - De sensorband moet smaller, zodat die minder hapert.
> - De elasticiteit in de sensorband is zeer goed om aan te spannen.

## Develop 3: Human Senses
### Doelstellingen
Het eindpunt voor deze opdracht is een geoptimaliseerd ontwerp, waarvan aan de hand van een hiërarchische taakanalyse en gebruikerstesten kan worden aangetoont welke optimalisaties werden aangebracht op het vlak van de sensoriële ergonomie.

### Materiaal en methoden
Voor deze laatste deelopdracht werden er nog heel wat zaken getest. Sommige in verband met de sensorband en add-on. Andere dan weer met de applicatie. Deze applicatie kreeg een flinke opknapbeurt. Uit vorige deelopdracht bleek namelijk dat de functionaliteiten wel goed zaten, maar het uiterlijk nog veel beter kon. Ook is er nieuwe functie 'de rangschikking', die rangschikt alle vrienden van de loper en zichzelf volgens de schokken. De persoon met de minste schokken staat uiteraard bovenaan. De routebouwer zit ook in de applicatie. Daarop werden 3 gelijke applicaties gemaakt, maar telkens met subtiele verschillen om op die manier aan de testpersonen te vragen welke ze verkiezen. Uit al deze keuzes werd dan 1 finale applicatie gemaakt. Hieronder kunt u al de 4 hoofdscenes op een rij zien.

<img src="images/vier_scenes.png" width="100%"/>

Daarnaast werden ook nog vragen gesteld of de LED eventueel groen kan 'ademen' in plaats van helemaal uit. Ook de sensorband werd in het wit gemaakt en er werd een hand in de add-on gemaakt, om aan te duiden in welke richting de add-on onder de horlogeband moet. (*sensitive signifier*)

<img src="images/hand_in_add-on.png" width="30%"/>

Deze keuzes werden gemaakt met behulp van *user tests*. Tot slot was er ook nog het idee om de navigatie te testen. Dit aan de hand van leds die links of rechts aanduiden, want de loper kan natuurlijk de route niet zien op zijn gsm. Helaas was hiervoor geen tijd meer, maar zou in de toekomst zeker nog getest kunnen worden. In de tweede render hieronder wordt dit ook voorgesteld.

<p>
    <img src="images/render_add-on_denoise.png" width="32%"/>
    <img src="images/render_add-on_navigatie_denoise2.png" width="32%"/>
    <img src="images/render_sensorband4.png" width="32%"/>
</p>

### Resultaten 
#### Hiërarchische taakanalyse

<img src="images/hiërarchische_taakanalyse.png" width="50%"/>
 
#### User test (N=3)
Uit deze taakanalyse werden volgende deelascpecten verder getailleerd. Dit zijn de resultaten:

<p>
    <img src="images/test_semy_add-on.jpg" width="32%"/>
    <img src="images/test_semy_rugzak.jpg" width="32%"/>
</p>

- batterij:
  - opladen met kabel
- uitzicht:
  - zwarte sensorband
- LED RGB:
 - geen licht bij lage schokken
- applicatie:
    - Rangschikkings knop in home scene.
    - Een ronde opname knop.
    - In de opname scene een homeknop.
    - Ronde tijdsaanduiding.
    - Aftelling zuiver horizontaal.
    - Rapport weergeven met verschillende grafieken.
    - Rapport scene beter met extra knoppen.
    - Geen benaming bij knoppen.

<img src="images/gwin_opnemen.png" width="30%"/>

> [!IMPORTANT]
> #### Design requirements:
>
> - De add-on moet oplaadbaar zijn, met een kabel.
> - De sensorband is zwart.
> - Bij lage schokken blijft de LED gewoon uit.
> - Applicatie:
>    - Rangschikkings knop in home scene.
>    - Een ronde opname knop.
>    - In de opname scene een homeknop.
>    - Ronde tijdsaanduiding.
>    - Aftelling zuiver horizontaal.
>    - Rapport weergeven met verschillende grafieken.
>    - Rapport scene beter met extra knoppen.
>    - Geen benaming bij knoppen.

## Design  requirements

| ID | Design Requirement | Bron |
| --- | --- | --- |
| **Deel 1** | **Add-on** |
| 1.1 | Er wordt een add-on, die licht uitstraalt, gebruikt om de loper te waarschuwen. | Definition: *user tests* en *user interviews* |
| 1.2 | De add-on bevindt zich op de pols. | Definition: *user tests* en *user interviews* |
| 1.3 | De ontwerpstrategie voor de add-on is *design for more types* | Develop 1: antropometrische analyse |
| 1.4 | De uitsparing van de add-on, om de horlogeband in plaatsen, moet dieper. | Develop 1: antropometrische analyse |
| 1.5 | Tijdspanne tussen trillingen, als loper, zelf kunnen instellen. | Develop 2: *expert review* |
| 1.6 | De LED moet voor de rode LED eerst oranje zijn. | Develop 2: *expert review* |
| 1.7 | De add-on moet oplaadbaar zijn. | Develop 2: *expert review* |
| 1.8 | De add-on wordt geplaatst met de LED richting het hoofd van de loper. | Develop 2: *expert review* en *usability tests* |
| 1.9 | De add-on moet oplaadbaar zijn, met een kabel. | Develop 3: *user tests* |
| 1.10 | Bij lage schokken is de LED gewoon uit. | Develop 3: *user tests* |
| **Deel 2** | **Applicatie** |
| 2.1 | Er is een aparte, zelfstandig applicatie voor de dataweergave. | Definition: *user tests* en *user interviews* |
| 2.2 | Er wordt een routebouwer geïplementeerd in de applicatie. | Definition: *user tests* en *user interviews* |
| 2.3 | De functionaliteit van de applicatie zit goed. | Develop 2: *expert review* |
| 2.4 | De belastingscurve is erg interessant. | Develop 2: *expert review* |
| 2.5 | De interface moet aantrekkelijker. | Develop 2: *expert review* |
| 2.6 | De routebouwer leert welke routes goed zijn, door de gegevens van de lopers te bekijken en daaruit de beste terug voor te stellen. | Develop 2: *usability tests* |
| 2.7 | Rangschikkings knop in home scene. | Develop 3: *user tests* |
| 2.8 | Een ronde opname knop. | Develop 3: *user tests* |
| 2.9 | In de opname scene een homeknop. | Develop 3: *user tests* |
| 2.10 | Ronde tijdsaanduiding. | Develop 3: *user tests* |
| 2.11 | Aftelling zuiver horizontaal. | Develop 3: *user tests* |
| 2.12 | Rapport weergeven met verschillende grafieken. | Develop 3: *user tests* |
| 2.13 | Rapport scene beter met extra knoppen. | Develop 3: *user tests* |
| 2.14 | Geen benaming bij knoppen. | Develop 3: *user tests* |
| **Deel 3** | **Sensorband** |
| 3.1 | Bij de sensorband moet *design for adjustability* toegepast worden. | Develop 1: antropometrische analyse |
| 3.2 | De sensorband moet smaller, zodat die minder hapert. | Develop 2: *expert review* |
| 3.3 | De elasticiteit in de sensorband is zeer goed om aan te spannen. | Develop 2: *expert review* |
| 3.4 | De sensorband is zwart. | Develop 3: *user tests* |

## Kritische reflectie
Aangezien het begin van dit proces moeizaam verliep, is er na vanaf februari schot in de zaak gekomen. Met enkele geslaagde testen werd een degelijk concept bedacht en uitgewerkt. De add-n was al vanaf begin een goed idee en is verder uitgewerkt met een RGB LED, een trilling. Via Bluetooth is deze verbonden met de sensorband die de schokken meet. Er werd ook een witte sensorband gemaakt, maar na onderzoek bleef deze zwart. Daarnaast moest alle data nog grafisch weergegeven worden in een applicatie. Deze werd in het begin vooral getest op functionaliteit, maar later ook op visualiteit. Daarnaast kan met trots gezegd worden dat er 2 nieuwe functies in de applicatie verwerkt zijn. Dat zijn de routebouwer, die dankzij de activiteiten van de lopers goed routes weergeeft en de rangschikking, die de lopers motiveren om met minder schokken te lopen en zo bovenaan de lijst terechtkomen. Ook is met een duidelijke belastingscurve, die de belasting over de laatste activiteiten grafisch uitzet, vooruitgang geboekt qua personalisatie en motivatie. 
Het doel van dit product is dat lopers hierdoor, tijdens de training, de loopstijl aanpassen en zo minder blessures oplopen.

## Bijlagen
- Discovery
  - *Benchmarking*
    - [report](https://docs.google.com/document/d/1JfUbHos3zhybmaLJP-YiFlEOg0O1E8SZYjdd3L35vJQ/edit)
  - Sportlab Gent 
    - [report](https://docs.google.com/document/d/1eVAYHaiM8YtlSQzIp9O4Rh9jSH3_wspkmVG7wBDYLsU/edit)
  - *User interviews*
    - [protocol](https://docs.google.com/document/d/1Ds5i_zKur2OjnSJB4rF4CbEXlMRWsTcHIAqmpsxzQDc/edit)
    - [report](https://docs.google.com/document/d/1FYFXpTA5BVXFCcAXG7kBOfN_o8Z9limd2GxG5UwDKqg/edit)
- Definition
  - LED (Oscar Ortega Saez)
    - [protocol](https://docs.google.com/document/d/14RKI3u73EJ5et9bNNRCVGS322qjNWHI3CRWDusgx7Ww/edit)
    - [content](https://drive.google.com/drive/folders/1RqDLnNr1HxHgYtXpxXUg87GblHZwHT1Z)
  - Dataweergave
    - [protocol](https://docs.google.com/document/d/1nL5AD3cuOb6XBmzNJhNB2doB6iqqc5_j05A39bJJuNo/edit)
    - [content](https://drive.google.com/drive/folders/17L1cb4ROWZA2x9M9FQ5hRD_oOJQ906zj)
- Develop 1
  - [protocol](https://docs.google.com/document/d/1Kloh9CuRuLPTNAOVPl9ogjszAQTPNSdJbwxoKbp8yB8/edit)
  - [content](https://drive.google.com/drive/folders/1w9Qr2AmvEAt4PkxIzSWpBm2ejxYxww5P)
  - [report](https://docs.google.com/document/d/13OGesLvXKp1AdMp1K0mX-dShAppVLlxFatK6jt7x6hc/edit)
- Develop 2
  - [protocol](https://docs.google.com/document/d/1OtAYweZF_wQCRTwFmExqQDuNzsftwDbqwzmIXfz2akk/edit)
  - [content_explaining](https://drive.google.com/drive/folders/15XhQi3RXNrJaN7W5Kwfxt3TfCI9sgrKE)
  - [content](https://drive.google.com/drive/folders/15DMeSZ1deatgWpHPhC_Md29zQ8SQLxcL)
  - [report](https://docs.google.com/document/d/14lkTnhygynz4IRsV_9h-YdKm0Tds50YIHdFEBZeTIg4/edit)
  - [report](https://docs.google.com/document/d/103iYNP5TnIp8TD3cescv881n98BtGmH3tTzwa1kZ730/edit)
- Develop 3
  - [protocol](https://docs.google.com/document/d/1W3FYAAPSdmzL2gCnENVWhxrBk0Qv3ZmPza0EpiSr0zc/edit)
  - [content_protocol](https://drive.google.com/drive/folders/1h_ir-iSQ5fhNMbCP564f0-E8MFREXC9T)
  - [content_report](https://drive.google.com/drive/folders/1mjphxrJCp-d5z5XsD5w_k_oEG3GS6cIJ)
  - [report](https://docs.google.com/document/d/1d-04iPY_rcxMElfMVuiAGdHJKzOyZQHkK5JLwmDVuho/edit)

Alle informed consents: [informed consents](https://drive.google.com/drive/folders/1WaEJXOdOcdhHoSp3gnQi2KakQQELSypy)

Het miro-board (enkel gebruikt tijdens de discovery en definition): 
[miro](https://miro.com/app/board/uXjVNeHs5e4=/)

## Bronnen
[^1]: Victoris. (2021, dec.) Music-based biofeedback system for lower impact running.
[URL](https://www.victoris.be/lower-impact-running/)

[^2]: Pubmed. (2015, jul.) Incidence of Running-Related Injuries Per 1000 h of running in Different Types of Runners: A Systematic Review and Meta-Analysis.
[URL](https://pubmed.ncbi.nlm.nih.gov/25951917/)

[^3]: Kickstarter. (z.d.) Glance: World's first smart accessory for your watch. Geraadpleegd op 29/02/2024.
[URL](https://www.kickstarter.com/projects/1742184757/glance-worlds-first-smart-accessory-for-your-watch?fbclid=IwAR0rZDua1Eh5U1iQGI0FTj-k8iF39z1o7G8C-pEZ4MCOvYG8juoK6yZZBmQ)

[^4]: Blumstengel, B.S. (2019). Lunch & Learn Series: Office Ergonomics Done Right van [URL]([https://pdfs.semanticscholar.org/1b99/b3f87a1eef62f601bcd0519c6107bc6e018c.pdf](https://freshworks.io/office-ergonomics-done-right/))
