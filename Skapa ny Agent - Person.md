TESTSIDA 

## Skapa ny Agent - Person
Exemplet nedan baseras på Lagerlöf, Selma, 1858-1940 (i de fall det är möjligt och relevant)


### Skapa ny Agent - Person
Beskrivning av agenten som ska auktoriseras. Lathunden beskriver de fält som finns representerade i mallen. Om något av fälten i mallen inte behövs kan de raderas genom att klicka på papperskorgsikonen till höger om fältet. Ett urval av fält som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden.

* Familjenamn (FamilyName)
  <br/>Enkelt eller sammansatt släktnamn/efternamn. Föredragen namnform som tillsammans med förnamn utgör den auktoriseade namnformen.
  <br/>```Exempel: Lagerlöf```

* Förnamn (GivenName)
  Förnamn som tillsammans med efternamn utgör den auktoriseade namnformen. 
  <br/>```Exempel: Selma```
  <br/>Om flera förnamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra separerade med mellanslag.

* Titel eller övrig beteckning (marc:titlesAndOtherWordsAssociatedWithAName = 100 #c)
  <br/>Används som särskiljande tillägg till den auktoriserade namnformen.
  <br/>```Exempel: påve```
  
* Födelse- och/eller dödstid (lifeSpan = 100 #d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. 
  <br/>```Exempel: '1858-1940' eller '1968-'```

* Födelsedatum (birthDate = 046 #f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: '18581120' eller '1902'```
  
* Dödsdatum (deathDate = 046 #g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: '19400316' eller '1977'```

* Exakt match/har variant
  <br/>I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar, ändringar till följd av namnbyten etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: Lagerlöf, Selma Ottiliana Lovisa```
  <br/>```Exempel: Lagerlœf, Selma```
  
* Identifikator (identifiedBy = 024 #a?)
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
  
### Adminmetadata
* Skapad av (descriptionCreator = 040 #a)
  <br/>Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: S```
  
* Katalogiseringsregler (descriptionConventions = 040 #e)
  <br/>För post katalogiserad enligt RDA, länka till entitet: marc/Isbd samt skapa lokal entitet med Kod: rda    
  ```Exempel: marc/Isbd (länkad entitet) + lokal entitet, Kod: rda```  

* Katalogiseringsspråk (descriptionLanguage = 040 #b)
  Länka till entitet.  
  ```Exempel: svenska (swe)```

* Beskrivningsnivå (encodingLevel = 000/Leader/?)

* Identifikator?
  <br/>Libris-ID automatgenereras då posten skapas och kan inte ändras.
  
* Katalogisatörens anmärkning (cataloguersNote (?) = 667 #a)
  Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Författaren vill inte ha sitt födelseår i auktoritetsposten. Enligt e-post 2017-05-12, S/NB/annbjo```

* Källa (sourceConsulted)
  <br/>Källa vid belagd uppgift. Den resurs som föranleder auktoriseringen är obligatorisk källa i auktoritetsposten. Hur ska vi ange resurs som källa?
  ```Exempel: NE 2018-04-12```
  
* Poststatus (recordStatus = = 000/Leader/?)

### Valbara fält som inte ingår i mallen
Då behov finns att lägga till fält som inte ingår i mallen

