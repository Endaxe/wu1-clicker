# Clicker

Endo Axelsson
2023-04-19

## Inledning

Målet med denna uppgift var att omdesigna en befintlig kod av en klicker med sina egna ideer.
Arbetsprocessen började med att välja ett tema och skissa den. Sedan så var det bara att byta ut textens innehåll och textsnitt, byta färger och hitta passande bilder. Resten var justeringar så att allt såg bra ut tillsammans.

## Bakgrund

![GitHub Logo](/dokumentation/skissh.jpg)

Hela projektet började med skissen. Min tankeprocess var då att ideen ska inte vara alltför svår för att göra men samtidigt vara något som är lättigenkännlig både färger och form. Jag kollade upp bilder för pizzor och då hittade jag bilder som jag tyckte passade perfekt så jag valde bara pizzeria som temat.
Det fanns andra ideer men bilderna som fanns hade antingen väldigt konstiga former eller så var kontrasterna för svåra att arbeta med.

Sedan så gick jag till Github sidan och forkade repot.

I koden så städade jag upp grejer som var irrelevanta i koden. Det var text, bilder och kodrader. När detta var klart så började jag med att byta färger i både bakrund och texten på ett ungefärligt för att få fram en vision av sidan. Det behövdes nya bilder som var gratis att använda. Unsplash var den perfekt sida, det fanns gratis bilder med hög kvalite. Den stora header bilden som är störst var den första jag ville byta så jag gjorde det med denna.

[Header bilden](https://unsplash.com/photos/exSEmuA7R7k)

Sen så valde jag andra liknande bilder till uppgraderings knapparna. Till själva clicker knappen så hade jag dock en png bild vilket var effektivt för att jag ville bara ha en transparens objekt på den existerande knappen. Så jag tog en png bild och bytte ut med bilden som fanns där så var det klart.

Sedan i style-cseen så var man ju tvungen att importera dem nya bilderna så att dem kunde användas. Så jag gjorde det för var och en bild, javascripten behövde också justeras lite på grund av det. I clicker.js så bytte jag class namnen så att dem passar med varandra i både clicker.js och style-css.

Hittade en font på fonts google. Tyckte att Stint Ultra Condensed passade bra så valde den och bytte textsnittet i style-cssen. Den påmminde lite om en klassiskt "italiensk" pizzeria text. 

Ändrade och justerade ännu mera färger så att texten skulle stå ut från både bakrunden och bilderna på knapparna. Gjorde textraden större så att det blev lättare att läsa genom att öka paddingen i text classen.

Länkade bild länkarna i credits och det var allt.

## Positiva erfarenheter

Det gick bra att hitta runt i koden och byta ut dem. Om jag såg att till exempel bakrundens färg behövde ändras så visste jag med stor säkerhet vars koden fanns och visste hur man skulle ändra det. Detta var till stor hjälp för att det var precis det man skulle göra i denna uppgift. 

## Negativa erfarenheter

Bildernas dimensioner var svåra att hantera i uppgraderings knapparna. När jag först försökte så trodde jag att jag kunde röra runt dem inom knappen, men det var svåraree än så. Bilderna som var i knappen blev inzoomade och visade bara toppen. Det var jobbigt för att i ugns bilden till exempel så ville jag visa själva ugnen men det funkade inte. Det tog så länge att försöka hitta en lösning så jag tog plan B och hittade bilder som man kunde se vad det var, fastän man bara kunde se toppen.

## Sammanfattning

Jag tyckte att hela arbete gick rätt så bra, allt gick framåt och det fanns alltid en väg runtom problemet. Erfarenhet jag tar med mig är hur man kan justera i style-css med javascripten så att dem fungerar med varandra. Kändes också som att jag lärde mig att hitta material och sätta dem tillsammans så att det ser ut som en färdig produkt. Det finns fortfarande såklart grejer som kunde ha varit bättre och utvecklats. Som valen av bilder, för att på bara några av bilder så var jag tvungen att ändra text färgen för att den var anting för ljus eller fö mörk, vilket får det att se lite blandat och fult ut.
Själva knappen då man klickar på den hade också kunnat vara lite snyggare. Man hade säkert kunnat fortsätta denna projektet med flera knappar och uppgraderingar.