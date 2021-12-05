---
Title: Laddningstid
Description: Analyserar laddningstider på tre webbplatser.
---

Analys av laddningstider
=======================

Analyserar laddningstider på tre webbplatser. Diskussion kring resultatet och enklare slutsatser kring vad som kan förbättras för att hemsidan ska få mindre laddningstid.

Urval
-----------------------

Tre av Sveriges nationella idrottsförbund: Basketförbundet, Fotbollsförbundet och Ishockeyförbundet. Hemsidorna kan besökas både med syfte att hitta information, t.ex. om matcher som spelas och kan även användas som marknadsföring för att sälja in sporten. Därför anser jag att både innehåll och design är viktigt på dessa hemsidor.

Metod
-----------------------

Jag har sparat mina mätvärden i ett Google Kalkylark. Sidornas laddningstider mäts med Google Pagespeed, som också ger tips på vad man göra för att det ska gå snabbare. För varje sida noteras också laddningstiden tillsammans med antal resurser som laddas och sidans totala storlek, med hjälp av inspektera-verktyget och fliken Network.

Resultat
-----------------------

## [Svenska Basketförbundet](https://www.basket.se/)

![Basketförbundet](%assets_url%/img/basketforbundet.png)
För att det ska gå snabbare rekommenderar jag att man väntar med att läsa in bilder som inte visas på skärmen.

## [Svenska Fotbollsförbundet](https://www.svenskfotboll.se/)

![Fotbollsförbundet](%assets_url%/img/fotbollsforbundet.png)
Väldigt bra värden överlag. Det enda man borde förbättra är att vänta med inläsning av bilder som inte visas på skärmen, men jag tycker ändå de har väldigt bra värden.

## [Svenska Ishockeyförbundet](https://www.swehockey.se/)

![Ishockeyförbundet](%assets_url%/img/ishockeyforbundet.png)
Här går det lite för långsamt och det är bilderna som saktar ner flödet. Man bör skicka bilderna i ett modernare format, använda rätt storlek och precis som de andra sidorna vänta med inläsning av bilder som inte visas på skärmen.

### Sammanställning
<iframe class="sheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ5JsMP8W-6JKcDZYGimUzrnW3A9ncCi1iI7qBBDDGHSAjlU_nSB4b95fVnTt3tsP9VS1tDnDsLGcTE/pubhtml?widget=true&amp;headers=false" scrolling="no"></iframe>

Analys
-----------------------

### Rangordning
1. Fotbollsförbundet
2. Basketförbundet
2. Ishockeyförbundet

Resultat visar väldigt tydligt att bilderna är det som saktar ner flödet. Det behöver framförallt åtgärdas på Basketförbundet och Ishockeyförbundets hemsidor. För att gå fortare rekommenderar jag att man skickar bilderna i ett modernare format, använder rätt storlek (t.ex. genom width och height som inte finns på alla bilder) och väntar med att läsa in bilderna som inte visas på skärmen. Man bör också reducera JavaScript och CSS som inte används och minifiera dessa filer. Svenska Fotbollsförbundets värden är mycket bra och på flera värden överlägset bäst. Jag tycker att Ishockeyförbundet tar lite väl lång tid på sig och det hade gått betydligt snabbare om man bara åtgärdat hanteringen av bilderna. Då hade de tagit mindre plats och gått snabbare.

Att sätta en gräns för vad som är en snabb/långsam webbplats tycker jag är svårt, det beror på hur mycket innehåll som hemsidan läser in. Jag sätter gränsen till 3 sekunder för dessa webbplatser och tycker inte att det borde ta längre tid än så. Det gör det inte om man fixar till bilderna bättre.

Referenser
-----------------------

Google Kalkylark

[Google Pagespeed](https://pagespeed.web.dev/)

Inspektera - Network

Namn
-----------------------

Namn: Eric Samuelsson
