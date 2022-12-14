# Accessibilty testing

## 1 Perceivable

- Alt innhold skal ha et ikke-tekstlig alternativ (Bilder har tekstalternativ og lyd har tekstalternativ f.eks)
- Innholdstyper er kodet med riktig type. Overskrifter er overskrifter og har riktig nivå. En knapp er en knapp, og en link er en link.
- Innholdet er presentert i en meningsfylt rekkefølge. Slå av css, rekkefølgen skal være den samme, evt gi samme meningsinnhold.
- Elementer har flere egenskaper for å gi informasjon: Form, farge, størrelse etc. 
  - Lenket tekst skiller seg ut ved mer enn bare farge
  - Skjemaelementer, feilmeldinger
  - Grafer
 - Kontrast på 3:1(4,5:1). Bruk automatiserte verktøy for å verifisere, gjelder tekst som formidler informasjon.
 - Tekst skal kunne forstørres opptil minst 200% uten tap av innhold og funksjonalitet
 - Ikke bruk bilde av tekst unødvendig, vanskelig å skalere.


## 2 Operable

 - Naviger gjennom siden ved bruk av tastatur. Fokus skal være synlig, og sjekk at det ikke er noen tastaturfeller.
 - Det er mulig å slå av, justere eller forlenge tidsavgrensninger. 
 - Innhold som beveger seg, blinker eller ruller skal være mulig å pause, stopppe eller skjule.
   - Innhold som blir automatisk oppdatert er mulig å pause, stoppe eller skjule
   - Innhold som blinker har størrelse på mindre enn 21 824 kvadratpiksler eller færre enn tre blink i sekundet.
 - Hoppe over blokker for å gå til hovedinnhold. Mange sider har innhold som blir gjentatt flere ganger, f. eks menyer og topptekster, skal være mulig å hoppe over denne typen innhold.
 - Siden har sidetitler som er beskrivende for emne eller formål. 
   - Sørg for at de er korrekt kodet, og gir mening delv når de blir lest ut av kontekst.
 - Logisk fokusrekkefølge når man navigerer med tastatur. Trenger ikke å være identisk med leserekkefølge så lenge brukeren kan forstå og bruke innholdet på nettsiden.
 - Lenker skal være formulerte slik at brukeren får informasjon om formålet med lenken, eller at det kommer tydelig frem ved lenketekst og kontekst.
 - Nettsider og innhold/funksjonalitet på nettsider, skal kunne nåes(?) på flere måter. Dette kan være gjennom lenker, søkefunksjonalitet, nettstedkart og lignende.
 - Dersom det er brukt overskrifter, skal de beskrive emne eller formål for innholdet.
 - Ledetekster beskriver emne eller formål med skjemaelementet.
 - Alle element det er mulig å betjene med tastaturet, får synlig fokusmarkering. 


## 3 Understandable

- Språk på siden er rett kodet. Hjelpemiddelteknologi får da rett uttale.
- Man kan navigere gjennom nettsiden uten at det skjer kontekstendringer når ulike elementer får fokus.
- Endringer i brukergrensesnittkomponenter som medfører endring i kontekst skal varsle brukeren.
- Konsekvent navigering, 
- Dersom obligatoriske skjemaelement ikke er fyllt ut, eller ved inndatafeil, gjelder:
   - Brukeren får en tekstlig feilmelding
   - Feilmeldingen er kodet som tekst
   - Feilmeldingen identifiserer skjemaelementet der feilen oppstod
   - Feilmeldingen beskriver feilen
 - Skjemafelt skal ha ledetekster og instruksjoner slik at brukerene forstår hvordan et skjema skal fylles ut:
   - Skjemaelementene har en visuell identifikasjon i form av ledetekst, instruksjon eller ikon/symbol/bilde.
   - Identifikasjonen er visuelt plassert i eller rett ved skjemaelementene.
   - Identifikasjonen er alltid synlig når skjemaelementene er i fokus.
   - Ikon/symbol/bilde er identifisert i koden.
   - Det er opplyst om skjemaelementene er obligatoriske, eventuell merking med symbol skal være forklart før det blir tatt i bruk.
 - Når det skjer feil ved utfylling av skjema, skal brukeren få forslag til retting.
 - Brukeren kan kontrollere og endre informasjon, eller angre innsending av skjema med viktig formål


## 4 Robust

- Ingen syntaksfeil: nøsting, avslutting av element, id'er.
- Skjemaelementer, knapper er koblet til ledetekst i koden.


## Tabeller
Følgende innhold i tabeller er kodet semantisk rett:
- Tabelltittel.
- Overskriftsceller.
- Tabeller med overskrift i bare en rad eller kolonne.
- Overskriftsceller i tabeller med overskrifter både på kolonne og rad.
- Overskriftsceller i tabeller med overskrifter på flere rader og/eller kolonner inne i tabellen.

