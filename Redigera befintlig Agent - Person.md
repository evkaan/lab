UNDER ARBETE - UPPDATERAS KONTINUERLIGT

## Redigera befintlig Agent - Person
Exemplet nedan baseras på Jansson, Erik, f. 1848. Tillägg är fiktiva, enbart för att exemplifiera.


### Redigera befintlig Agent - Person
Beskrivning av agenten som ska auktoriseras. Lathunden beskriver de fält som finns i den befintliga auktoritetsposten och vilka fält som bör läggas till. Ett urval av fält kopplade till person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden.

## Befintliga fält i beskrivningen

* Efternamn (FamilyName)
  <br/>```Exempel: Jansson```

* Förnamn (GivenName)
  <br/>```Exempel: Erik```

* Biografiska uppgifter (hasBiographicalInformation = 678)
  <br/>```Exempel: Väckelsepredikant i Österbotten```
  
* Födelse- och/eller dödstid (lifeSpan = 100 #d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. Redigera om det behövs.
  <br/>```Exempel: 1848-1920```

* Nationalitet/verksamhetsland (Nationality = 043 #a)
  <br/>Vid behov kan denna ändras eller raderas. Lägg till ytterligare kod genom att klicka på ```+Nationalitet ```
  <br/>Sök i rutan till vänster, välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger.
  <br/>```Exempel: ?```

* Kontrollnummer ?
  <br/>Libris-ID. Ändras ej, raderas ej.

* Samma sak som (SameAs)
  <br/>Hur ska detta beskrivas?
  <br/>```Exempel: resource/auth/247521```
  
## Fält att lägga till i beskrivningen

* Födelsedatum (birthDate = 046 #f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 18480219```
  
* Dödsdatum (deathDate = 046 #g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 19201209```

* Variant (hasVariant = 400
  <br/>I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar, ändringar till följd av namnbyten etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: Efternamn: Jansson ; Förnamn: Eric```
  <br/>```Exempel: Namn: Lagerlœf ; Förnamn: Selma```
  
* Identifikator (identifiedBy = 024 #a)
  <br/>Isni som identifikator är valfri uppgift men önskvärt om tillgänglig. 
  <br/> ```Exempel: 0000000121339888 ```

* Nationalitet/verksamhetsland
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas. Lägg till ytterligare kod genom att klicka på ```+Nationalitet ```
  <br/>Sök i rutan till vänster, välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger.

* Har yrke eller sysselsättning (hasOccupation = 374)
   <br/>Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. 
   <br/>Lägg till ytterligare yrke eller sysselsättning genom att klicka på ```+Koncept ```
  <br/>Sök i rutan till vänster, välj önskad term och klicka på den gröna Lägg till-rutan till höger. 
   <br/>```Exempel: Romanförfattare ```
   <br/>```Exempel: Översättare```

### Befintliga fält i Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoritetsposten i sig och inte är direkt förknippad med den auktoriserade namnformen.

* Kontrollnummer
  <br/>Gammalt Libris-ID. Ska inte ändras eller radersa.  

* Katalogiseringsregler (descriptionConventions = 040 #e)
  <br/>Radera och lägg till rda vid behov. 
  ```Exempel: marc/CatalogingRulesType-c``` 

* Skapad av (descriptionCreator = 040 #a)
  <br/>Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: S```

* Beskrivningsnivå (encodingLevel = 000/Leader/?)
  Ändras ej?

* Translitterering
  Ändras ej?
  
* Typ av auktoritetspost  
  Ändras ej?



* Poststatus (recordStatus = = 000/Leader/?)
  Ändras ej?

* Uppdatering av posten
  Ändras ej?

* Differentiering av posten
  Ändras ej?

* Auktoritetskontrollnivå
  Ändras ej?

* Katalogiseringsspråk (descriptionLanguage = 040 #b)
  Länka till entitet.  
  ```Exempel: svenska (swe)```

* Identifikator?
  <br/>Libris-ID automatgenereras då posten skapas och kan inte ändras.

* Konsulterad källa (sourceConsulted = 670)
  <br/>Källa vid belagd uppgift. Den resurs som föranleder auktoriseringen är obligatorisk källa i auktoritetsposten. Hur ska vi ange resurs som källa?
  <br/>```Exempel: NE 2018-04-12```
  <br/>```Exempel: Källor i tåredalen, 1999```
