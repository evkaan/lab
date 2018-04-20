UNDER ARBETE - UPPDATERAS KONTINUERLIGT

## Skapa ny Agent - Person
Exemplet nedan baseras på Lagerlöf, Selma, 1858-1940 (i de fall det är möjligt och relevant)


### Skapa ny Agent - Person
Beskrivning av agenten som ska auktoriseras. Lathunden beskriver de fält som finns representerade i mallen. Om något av fälten i mallen inte behövs kan de raderas genom att klicka på papperskorgsikonen intill fältet. Ett urval av fält kopplade till person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden.

* Efternamn (FamilyName)
  <br/>Enkelt eller sammansatt släktnamn/efternamn. Föredragen namnform som tillsammans med förnamn utgör den auktoriserade namnformen.
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

* Variant
  <br/>I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar, ändringar till följd av namnbyten etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: 
  <br/>Efternamn: Lagerlöf 
  <Förnamn: Selma Ottiliana Lovisa```
  
  <br/>```Exempel: 
  <br/>Efternamn: Lagerlœf
  <br/>Förnamn: Selma```
  
* Identifikator (identifiedBy = 024 #a #2)
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
Information av administrativ karaktär som är väsentlig för auktoritetsposten i sig och inte är direkt förknippad med den auktoriserade namnformen.

* Katalogiseringsregler (descriptionConventions = 040 #e)
  <br/>Kod: rda förvalt i mallen. Ändra vid behov. 
  ```Exempel: Kod: rda``` Något mer här?

* Skapad av (descriptionCreator = 040 #a)
  <br/>Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: S```

* Beskrivningsnivå (encodingLevel = 000/Leader/?)
  Ändras ej?

* Translitterering
  Ändras ej?
  
* Typ av auktoritetspost  
  Ändras ej?

* Marc:headingMain
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
  
* Katalogisatörens anmärkning (cataloguersNote = 667 #a)
  Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Författaren vill inte ha sitt födelseår i auktoritetsposten. Enligt e-post 2017-05-12, S/NB/annbjo```

* Källa (sourceConsulted = 670)
  <br/>Källa vid belagd uppgift. Den resurs som föranleder auktoriseringen är obligatorisk källa i auktoritetsposten. Hur ska vi ange resurs som källa?
  <br/>```Exempel: NE 2018-04-12```
  <br/>```Exempel: Lagerlöf, Selma. Jerusalem, 1901-1902```


### Valbara fält som inte ingår i mallen
Vid behov är det möjligt att lägga till fält som inte ingår i mallen. Nya fält läggs till med hjälp av +-ikonen.

* Namn
  <br/>Används för namn i rak följd istället för fälten Förnamn och Efternamn. Kan användas i kombination med fälten Förnamn och Efternamn endast för att ange variantnamn.
  <br/>```Exempel: Namn: Bang``` Som variantnamn till den auktoriserade namnformen Alving, Barbro, 1909-1987

* Fullständigare namnform (fullerFormOfName = 100 #q och 378)
  <br/>Används för att ange fullständig namnform i de fall då fortkortning används i den auktoriserade namnformen
  <br/>```Exempel: Efternamn: Smith ```
  <br/>```Exempel: Förnamn: A. D. ```
  <br/>```Exempel: Fullständigare namnform: Adam David```

* Titel eller övrig beteckning (marc:titlesAndOtherWordsAssociatedWithAName = 100 #c)
  <br/>Används som särskiljande tillägg till den auktoriserade namnformen.
  <br/>```Exempel: påve```
  
 ### Fält som inte går att lägga till i första release
 
 * Klassifikation (065 ; 083)
 * Biografiska uppgifter/Biografisk information (678)
