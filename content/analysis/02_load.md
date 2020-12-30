---
Title: 02 load
Description: Analysis for kmom05
Template: analysis
---
Laddningstid på tre mäklarsidor
=======================

Mäklares webbsidor syftar till att visa upp lägenheter och locka till köp. Det är viktigt för mäklare att kunna visa upp många bilder av god kvalité på bostaden. Samtidgt får det inte gå ut över laddningstider för deras sida, eftersom det är viktigt att besökare till webbplatsen stannar kvar och fortsätter titta på bilder. Den här rapporten behandlar laddningstider för tre fastighetsförmedlingars webbplatser. Webbplatserna analyserades utifrån tiden det tog att ladda sidan samt vilka resurser som de använder sig och hur webbplatsernas laddningstider kan bli bättre. Webbplatserna analyserades främst ur perspektivet sett från bostadsspekulanter som letar efter en bostad eftersom de antas utgöra den största gruppen av besökare på webbplatserna.


Urval
-----------------------

Urvalet gjordes utifrån vilka fastighetsförmedlingar som var tidigare kända för författaren. I rapporten analyseras laddningstiderna för Svensk Fastighetsförmedling, Länsförsäkringar Fastighetsförmedling och Historiska Hem.

Metod
-----------------------

Tre sidor från varje webbplats analyserades med Google Pagespeed. Analyserna gjordes den 29/12 2020 och betyget antecknades.

De tre sidorna för varje webbplats analyserades också med fliken Network i Developer Tools i webbläsaren Google Chrome. Antalet resurser, laddningstiden och webbsidans totala storlek antecknades. Tre replikat genomfördes för varje mätning och ett medelvärde av de tre mätningarna beräknades i Google Kalkylark.

Medelbetyget för både mobil och desktop för alla tre webbsidor på varje webbplats beräknades. Medelladdningstiden för alla tre sidor för varje webbplats beräknades också.


Resultat
-----------------------
Snapshots från de tre undersöka webbplatserna kan ses i Figur 1, 3 och 3.

<figure>
    <picture>
        <source media="(min-width: 1500px)" srcset="../image/svensk_fast.PNG?">
        <source media="(min-width: 1000px)" srcset="../image/svensk_fast.PNG?w=1000">
        <source media="(min-width: 700px)" srcset="../image/svensk_fast.PNG?w=700">
        <img src="../image/svensk_fast.PNG?w=500" alt = "Svensk fastighetsförmedlings webbsida">
    <picture>
    <figcaption>Figure 1. Snapshot av webbplatsen för Svensk Fastighetsförmedling.</figcaption>
</figure>

<figure>
    <picture>
        <source media="(min-width: 1500px)" srcset="../image/lansfors.PNG?">
        <source media="(min-width: 1000px)" srcset="../image/lansfors.PNG?w=1000">
        <source media="(min-width: 700px)" srcset="../image/lansfors.PNG?w=700">
        <img src="../image/lansfors.PNG?w=500" alt = "Länsförsäkringar fastighetsförmedlings webbsida">
    <picture>
    <figcaption>Figure 2. Snapshot av webbplatsen för Länsförsäkringar Fastighetsförmedling.</figcaption>
</figure>

<figure>
    <picture>
        <source media="(min-width: 1500px)" srcset="../image/historiska_hem.PNG?">
        <source media="(min-width: 1000px)" srcset="../image/historiska_hem.PNG?w=1000">
        <source media="(min-width: 700px)" srcset="../image/historiska_hem.PNG?w=700">
        <img src="../image/historiska_hem?w=500" alt = "Historiska Hems webbsida">
    <picture>
    <figcaption>Figure 3. Snapshot av webbplatsen för Historiska Hem.</figcaption>
</figure>


Det totala medelbetyget i Google pagespeed var högst för Svensk Fastighetsförmedlings webbplats (69), näst högst för Länsförsäkringar Fastighetsförmedling (64) och lägst för Historiska Hem (51). Betyget var högre för desktop än för mobil för alla undersökta sidor, och det totala medelbetyget för mobil var 46 jämfört med 77 för desktop.

För alla de tre webbplatserna hade startsidan det minsta antalet resurser att ladda och sidan som visade en specifik bostad hade flest resurser att ladda. För all undersöka webbplatser var också sidan som visade en specifik bostad den största sidan av de undersöka sidorna. Skillnaden var störst för Historiska Hem som hade en storlek på 2,2 MB för startsidan och 12,3 MB för bostadssidan.

Medelladdningstiden för alla tre sidor hos de tre webbplatserna var 2,44 för Svbensk Fastighetsförmedling, 2,91 för länsförsäkringars fastighetsförmedling och 2,96 för Historiska Hem.

Google Pagespeed föreslår förbättringsåtgärder för sidan vid analys. Enligt verktyget skulle laddningstiden för Svensk Fastighetsförmedlings webbplats kunna förbättras genom att ta bort oanvänd CSS och JavaScript kod.

Laddningstiden på länsförsäkringars sidor skulle kunna förbättras bland annat genom att ta bort oanvänd CSS och JavaScript, minifiera CSS och använda rätt bildstorlekar.

Historiska Hem skulle kunna förbättra laddningstiderna på alla sina tre sidor genom att använda rätt bildstorlekar och filformat. Till exempel använder sig Historiska Hem av ett fotografi i filformatet png på sin sida för en specifik bostad. Det filformatet lämpar sig inte för fotografier och gör att bilden behöver vara större för att hålla samma kvalité jämfört med samma fotografi i en annan filtyp.

Rådatan finns tillgänglig i detta kalkylark: [Rådata](https://docs.google.com/spreadsheets/d/1rUGtyroZALIJWDDC8dDFQBfE9L0KVf4AyPfOIfapilE/edit?usp=sharing)

Analys
-----------------------

Google Pagespeed föreslår förbättringsåtgärder för sidan vid analys. Enligt verktyget skulle laddningstiden för alla tre webbplaser kunna förbättras genom att ta bort oanvänd CSS och JavaScript kod. Det är en relativt enkel åtgärd som skulle kunna göra att fler stannar kvar på förmedlingarnas webbplatser och i längden kunna ger mer folk på visningarna och i längden högre försäljningspris för fastighetsförmedlingarnas bostäder.

Mobilsidorna hade sämre betyg i Google Pagespeed jämfört desktop-sidorna. Jag tror att webbplatserna skulle vinna ganska mycket på att förbrättra sina mobilsidor eftersom jag tror att många av deras besökare använder mobilen när de besöker sidorna.

Generellt gäller att det är viktigare att startsidan laddas snabbt än de andra sidorna på en webbplats laddar snabbt, eftersom det är startsidan som besökarna oftast hamnar påp först och kan man få besökarna att bli tillräckligt intresserade för att själva söka mer information på webbplatsen så har man mer tid på sig att väcka intresse som webbsida. Webbplatserna i testet verkar ha prioriterat att ha en kort laddningstid på startsidorna då alla webbplatsernas startsidor är den av de tre testade sidorna som laddar snabbast. Dock tror jag från egen erfarenhet av att kolla på lägenheter att man som spekulant sällan besöker startsidan först på en fastighetsförmedlings webbplats. Oftast kommer man till webbplatsen via en länk till ett specifikt object, till exempel från en annonseringssida som Hemnet eller Booli eller från en länk skickad av en bekant. Då är det viktigt att sidorna för specifika bostäder laddar snabbt så att beökaren väljer att stanna kvar på mäklarens webbplats istället för att till exempel gå tillbaka till Hemnet och titta på bilderna där. Det är mycket mer fördelaktigt för mäklarna att det är deras webbplats som används till att titta på bilderna eftersom de då får chansen att locka besökaren till andra bostadsannonser, eller till information om hur man säljer sin nuvarande bostad genom dem. Därför skulle jag rekommendera webbplaserna att lägga mer fokus på hur snabbt det tar för den specifika bostadssidan laddar och där finns mycket förbättringspotential eftersom den laddar långsammast av alla undersöka sidor på alla tre webbplatser. Dock är det antagligen svårare att få till en snabbare laddningstid på sidan som visar upp en bostad eftersom den behöver ha fler bilder, men då borde de sidorna prioriteras i arbetet med att ta bort oanvänd kod, justera bildstorlekar och filformat och så vidare.

Sett till alla mätningar utses Svensk Fastighetsförmedling till vinnare i testet. Deras webbplats har högre betyg, kortare genomsnittlig laddningstid, och en mindre total storlek jämfört med de andra webbplatserna i testet. Näst bäst var Länsförsäkringar Fastighetsförmedling. Deras webbplats har högre betyg, något bättre genomsnittlig laddningstid och betydligt mindre total storlek jämfört med webbplastsen för Historiska Hem. De är också den sida som hade totalt sett minst antal resurser som skulle laddas.

Rapportförfattare: klara Djurberg
