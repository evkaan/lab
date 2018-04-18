

## Redigera befintlig Agent - Person
Exemplet nedan baseras på Jansson, Erik, f. 1848


### Redigera befintlig Agent - Person
Beskrivning av agenten som ska auktoriseras. Lathunden beskriver de fält som finns representerade i mallen. Om något av fälten i mallen inte behövs kan de raderas genom att klicka på papperskorgsikonen intill fältet. Ett urval av fält kopplade till person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden.

* Efternamn (FamilyName)
  <br/>Enkelt eller sammansatt släktnamn/efternamn. Föredragen namnform som tillsammans med förnamn utgör den auktoriseade namnformen.
  <br/>```Exempel: Lagerlöf```

* Förnamn (GivenName)
  Förnamn som tillsammans med efternamn utgör den auktoriseade namnformen. 
  <br/>```Exempel: Selma```
  <br/>Om flera förnamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra separerade med mellanslag.
  
* Födelse- och/eller dödstid (lifeSpan = 100 #d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. 
  <br/>```Exempel: 1858-1940```
  <br/>```Exempel: 1968-```

* Födelsedatum (birthDate = 046 #f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 18581120```
  <br/> ```Exempel: 1902```
  
* Dödsdatum (deathDate = 046 #g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 19400316```
    <br/> ```Exempel: 1977```

* Exakt match/har variant
  <br/>I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar, ändringar till följd av namnbyten etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: Lagerlöf, Selma Ottiliana Lovisa```
  <br/>```Exempel: Lagerlœf, Selma```
  
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
