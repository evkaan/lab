UNDER ARBETE - UPPDATERAS KONTINUERLIGT

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns.

## Redigera befintlig Agent - Person
Exemplet nedan baseras på Jansson, Erik, f. 1848. Tillägg är fiktiva, enbart för att exemplifiera.


### Redigera befintlig Agent - Person
Beskrivning av agenten som ska auktoriseras. Lathunden beskriver de fält som finns i den befintliga auktoritetsposten och vilka fält som bör läggas till. Ett urval av fält kopplade till person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden.

## Befintliga fält i beskrivningen

* Efternamn (FamilyName = 100 i1=1 ‡a)
  <br/>```Exempel: Jansson```

* Förnamn (GivenName = = 100 ‡a)
  <br/>```Exempel: Erik```

* Biografiska uppgifter (hasBiographicalInformation = 678)
  <br/>```Exempel: Väckelsepredikant i Österbotten```
  
* Födelse- och/eller dödstid (lifeSpan = 100 ‡d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. Redigera om det behövs.
  <br/>```Exempel: 1848-1920```

* Nationalitet/verksamhetsland (Nationality = 043 ‡a)
  <br/>Vid behov kan denna ändras eller raderas.
  <br/>```Exempel: swe```
  <br/>För att lägga till fält: Klicka på +-ikonen under Nationalitet/verksamhetsland. Sök i rutan till vänster, välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger.

* Samma sak som (SameAs)
  <br/>```Exempel: resource/auth/247521```
  
## Fält att lägga till i beskrivningen

* Födelsedatum (birthDate = 046 ‡f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/>```Exempel: 18480219```
  
* Dödsdatum (deathDate = 046 ‡g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/>```Exempel: 19201209```

* Variant (hasVariant = 400 ‡a ‡d)
  <br/>I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar, ändringar till följd av namnbyten etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: Efternamn: Jansson ; Förnamn: Eric```
  <br/>```Exempel: Namn: Janzon ; Förnamn: Erik Gustaf```
  <br/>För att lägga till fält: Klicka på +-ikonen under Variant, välj Person under Skapa lokal entitet. Klicka på +-ikonen inom det tillagda Person-fältet, sök efter och lägg till fältet Efternamn. Upprepa för Förnamn och Födelse- och/eller dödstid (ELLER Namn och Födelse- och/eller dödstid)
  
* Identifikator (identifiedBy = 024 ‡a)
  <br/>ISNI som identifikator är valfri uppgift men önskvärt om tillgänglig. 
  <br/>```Exempel: 0000000121339888 ```
  <br/>För att lägga till fält: Klicka på +-ikonen under Identifikator, välj typ (ISNI). Klicka på +-ikonen inom det tillagda Identifikator-fältet, sök efter och lägg till fältet Värde.

* Nationalitet/verksamhetsland (nationality = 043)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas. 
  <br/>[Länk till Att länka entitet]

* Har yrke eller sysselsättning (hasOccupation = 374)
   <br/>Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord.
   <br/>```Exempel: Romanförfattare ```
   <br/>```Exempel: Översättare```
   <br/>[Länk till Att länka entitet]

## Befintliga fält i Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoritetsposten i sig och inte är direkt förknippad med den auktoriserade namnformen.

* Kontrollnummer (controlNumber = 001)
  <br/>LibrisID. Ändras ej.

* Katalogiseringsregler (descriptionConventions = 040 ‡e)
  <br/>Förval: rda. Ändra vid behov. 
  <br/>```Kod: rda``` 

* Skapad av (descriptionCreator = 040 ‡a)
  <br/>Förval: Sigel för skapare av agenten. Ändras ej.  
  <br/>```Exempel: Organisation: S```

* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
  <br/>Förval: Svenska

* Senast ändrad av (descriptionLastModifier)  
  <br/>Förval: Sigel som gjort senaste ändring. Ändras ej.  
  
* Beskrivningsnivå (encodingLevel = 000)
  <br/>Ändras ej.

* Katalogiserande instans (marc:catalogingSource = 008/39)
  <br/>Ändras ej.

* Marc:headingMain (marc:headingMain = 008/14)
  <br/>Ändras ej.
  
* Typ av auktoritetspost (marc:kindOfRecord = 008/9)
  <br/>Ändras ej.

* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>Ändras ej.
  
* Differentiering av posten (marc:personalName = 008/32)
  <br/>Ändras ej.

* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>Ändras ej.

* Poststatus (recordStatus = 000)
  <br/>Ändras ej.

* Samma sak som 
  <br/>Ändras ej.
  
* Konsulterad källa (sourceConsulted = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Källa vid belagd uppgift. 
  <br/>Välj typ av konsulterad källa i rullgardinsmenyn till vänster. Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl källa som uppgift hämtad från källa. 
  <br/>```Exempel: Källa: NE 2018-04-12. Uppgift från källa: Levnadstid: 1848-1920```
  <br/>Den resurs som föranleder auktoriseringen är obligatorisk källa.
  <br/>```Exempel: Källor i tåredalen, 1999```
  
## Fält att lägga till i adminmetadata

* Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
<br/>```Exempel: Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03/S/marjan```
  
