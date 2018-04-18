TESTSIDA

## Redigera befintlig Agent - Person
Exemplet nedan baseras på Jansson, Erik, f. 1848. Fiktiva tillägg, enbart för att exemplifiera.


### Redigera befintlig Agent - Person
Beskrivning av agenten som ska auktoriseras. Lathunden beskriver de fält som finns i den befintliga auktoritetsposten och vilka fält som bör läggas till. Ett urval av fält kopplade till person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden.

## Befintliga fält

* Efternamn (FamilyName)
  <br/>```Exempel: Jansson```

* Förnamn (GivenName)
  <br/>```Exempel: Erik```

* Biografiska uppgifter
  <br/>```Exempel: Väckelsepredikant i Österbotten```
  
* Födelse- och/eller dödstid (lifeSpan = 100 #d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. Redigera om det behövs.
  <br/>```Exempel: 1848-1920```

* Nationalitet/verksamhetsland
  <br/>Vid behov kan denna ändras eller raderas. Lägg till ytterligare kod genom att klicka på ```+Nationalitet ```
  <br/>Sök i rutan till vänster, välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger.
  <br/>```Exempel: ?```

* Samma sak som
  <br/>Gammalt Libris-ID. Ändra ej, radera ej.
   <br/>```Exempel: resource/auth/247521```
  
## Fält att lägga till

* Födelsedatum (birthDate = 046 #f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 18480219```
  
* Dödsdatum (deathDate = 046 #g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 19201209```

* Exakt match/har variant
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
