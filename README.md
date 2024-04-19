# PRRPRR02-praktiskt-exempelprov

## Prov instruktioner:

### Regler

- Du är välkommen att använda vilket programmeringsspråk du trivs bäst med, men frågorna utgår ifrån att det
  är objektorienterat. Rekommenderade språk är C++, C#, Python, Java, och Javascript.
- (Du bör dock känna till och använda standardklasserna i ditt valda språk)
- Programmet bör se så identiskt ut med programmeringsspråkets regler som det bara går.
  - Fullständig kod är logiskt, matematiskt, och syntaktiskt korrekt.
- Kommentera all din kod, ej kommenterad kod rättas ej. Skriv TYDLIGT.
- Utgå ifrån att koden kommer att testas och felsökas.
- Betygssättning sker givetvis efter Skolverkets betygskriterier:

### Uppgift 1

Ett lån hos Klarna har idag en nominell ränta på 10 - 20%, beroende på din credit score.

Du köper en SpiPhoneSung Ultra AI Turtleneck Exxtreme för 12 000 SEK på avbetalning, du betalar av exakt 5% lånet
varje månad. Minsta avbetalning är dock 100 SEK. När avbetalningen når 100 SEK, och du betalar dessa är lånet
avskrivet och du är åter igen en fri nörd.

Skriv ett program som räknar ut följande egenskaper för lånet:

- Totalkostnad
- Antal månader betalat, samt kvarvarande belopp. Detta ska redovisas som:

  ”Januari 2024: 12000 SEK kvar – betalning 600 SEK – ränta betald 0 SEK”

  ”Februari 2024: 11500 SEK kvar – betalning 575 SEK – ränta betald 100 SEK”

- Programmet SKA kompilera korrekt.
- Programmet SKA hantera felmeddelanden.
- Inputvärden (totalbelopp, ränta, etc.) ska deklareras i början av programmet.
- Kommentera varje rad.

### Uppgift 2 - Sätt ett GUI till programmet ovan. Du får använda valfritt GUI-toolkit (Tkinter, .NET, Forms, JS, etc. etc.)

### Uppgift 3 - Modifiera programmet ovan så att du kan spara värdena till en CSV-fil. Denna CSV-fil ska vara Excel-tolkbar.

### Uppgift 4 - Modifiera programmet ovan så att användaren själv kan ange värden för köpets storlek, avbetalningstakt

(antingen i SEK eller % av kvarvarande belopp, välj själv), samt årsränta. (N.b. att Klarnas ränta aggregeras kontinuerligt,
ej en gång om året.)

### Uppgift 5 - Modifiera programmet ovan så att föregående inställningar sparas när programmet stängs av, och

automatiskt laddas in när programmet startar.

### Uppgift 6 - Modifiera programmet så att detta även fungerar för CSN.

CSNs ränta är f.n. 1.23 %, genomsnittsbelåningen efter tre år är 384 000 SEK.

Återbetalningstakt när 9000 SEK/år.
