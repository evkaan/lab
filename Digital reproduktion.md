---
section: Materialtyper
title: Digital reproduktion
order: 
date: 2020-06-10
tags:
- under arbete
- Digital reproduktion
- Digitalisering
--- 

# Digital reproduktion
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av en digital produktion av ett fysiskt original, t.ex. monografi, bild, karta, äldre tryck. Det finns en mall för Digital reproduktion då alla värden behöver anges manuellt. För att dra maximal nytta av funktionaliteten är rekommendationen att man använder funktionen Skapa digital reproduktion i verktygsmenyn i posten för en fysik förlaga som utgångspunkt. Då genereras en ny post för den digitala reproduktionen förvalda värden där endast en del behöver kompletteras manuellt. Mallen är skapad för tryckt text så för andra fysiska original behöver justeringar göras av de förvalda värdena.

I de fall egenskaperna finns beskrivna i generell hjälptext upprepas inte informationen här utan istället finns en länk till relevant hjälptext. Egenskaper som är specifika för digital reproduktion redovisas däremot enbart här.

## Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | [Bestånd](#bestand)
| ----------- | ----------- |  ----------- | ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) | [Generell hjälptext för Bestånd](https://libris.kb.se/katalogisering/help/workflow-holding)
| [Bibliografi](#bibliografi) | [Instanstyp](#instanstyp) | | |
| [Anmärkning](#anmarkning) | [Reproduktion av](#reproduktion-av) | | |
| | [Identifikator](#identifikator) | | |
| | [Utgivningssätt](#utgivningssatt) | | |
| | [Medietyp](#medietyp) | | |
| | [Bärartyp](#barartyp) | | |
| | [Produktion](#produktion) | | |
| | [Indirekt identifierad av](#indirekt-identifierad-av) | | |
| | [Digital karaktäristika](#digital-karaktaristika) | | |
| | [Tillhörande media](#tillhorande-media) | | |
| | [Villkor för användning och åtkomst](#villkor-for-användning-och-atkomst) | | |
| | [Relaterad beskrivning eller innehåll](#relaterad-beskrivning-eller-innehall) | | |
| | [Anmärkning](#anmarkning)| |



## Inledning
Beskrivningen av en digital reproduktion innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans för ett bidrag är titel, upphov och utgivning.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. 

För information om katalogiseringsregler och Librispraxis, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") samt [se RDA Toolkit](https://access.rdatoolkit.org/). 

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).

### Bibliografi
* Bibliografi/Bibliotek/Sigel (bibliography/Library/sigel = 042 #9)
I mallen är DIGI ifyllt. Korrigera/komplettera vid behov.

### Beskrivningsnivå 
* Beskrivningsnivå (encodingLevel = 000/17)
Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken).

### Anmärkning
* Anmärkning/Anmärkning om katalogiseringskälla/Benämning (hasNote/marc:SourceOfDescriptionNote/label = 588 #a)
<br/>```Exempel: S: Digitaliserat vardagstryck```

## Instans
[Se generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance)

För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn. 

### Instanstyp
* Instanstyp
Förval i mallen: Elektronisk
  
### Reproduktion av
* Reproduktion av (ReproductionOf = 776 #a #s #t #z #w)
Länk till fysiskt original då funktionen Skapa digital reproduktion använts.

Saknas länk får man manuellt länka till det fysiska originalet. Klicka på plustecknet inom Reproduktion av, sidorutan Lägg til entitet öppnas. Sök efter och länka till korrekt instans.

### Identifikator
* Identifikator (identifiedBy = 024 #a #2)
Välj typ Identifikator i rullgardinsmeny. Ange identifikator och eventuell typanmärkning.
<br/>```Exempel:```
<br/>* ```Värde: urn:nbn:se:kb:dig-17390055 Typanmärkning: uri```
<br/>* ```Värde: HS Ia 27a Typanmärkning: KB-signum```

### Utgivningssatt
* Utgivningssätt (issuanceType = 008/07)  
  Förval i mallen: Monografisk resurs

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Förval i mallen: Computer 
  Ändra vid behov(?)
  
### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Förval i mallen: term/rda/OnlineResource, marc/Online, marc/OnlineResource
  Ändra vid behov(?)

### Produktion 
* Produktion/Digital produktion/Typanmärkning/Plats/Agent/Datum (production/DigitalReproduction/typeNote/place/agent/date = 533 #a #b #c #d)
<br/>```Exempel:``` 
<br/>```Typanmärkning: Digitalt faksimil``` 
<br/>```Plats/Benämning: Stockholm```
<br/>```Agent/Benämning: Kungliga biblioteket```
<br/>```Datum: 2020```

### Indirekt identifierad av
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/ISBN/value = 020 #z)
ISBN hämtas från den fysiska förlagan (om sådant förekommer). Uppgiften är ifylld då funktionen Skapa digital reproduktion används.

### Digital karaktäristika
* Digital karaktäristika/Kodningsformat/Benämning (digatalCharacteristics = 347 #b)

### Tillhörande media
* Tillhörande media (associatedMedia)

### Villkor för anvädning och åtkomst
* Villkor för anvädning och åtkomst/Användningsvillkor/Benämning/URI (usageAndAccessPolicy = 540 #a #u)
<br/>```Exempel:``` 
<br/>```Benämning: CC0``` 
<br/>```URI: https://creativecommons.org/publicdomain/zero/1.0/```

### Relaterad beskrivning eller innehåll
* Relaterad beskrivning eller innehåll/Dokument/Katalogisatörens anmärkning/Offentlig anmärkning/URI (isPrimaryTopicOf = 856 #u #x #z)
<br/>```Exempel:```
<br/>```Katalogisatörens anmärkning: digipic``` 
<br/>```Offentlig anmärkning: tumnagelbild``` 
<br/>```URI: http://weburn.kb.se/tumnaglar/24/001655024,1,i,1.jpg```

### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)
<br/>```Exempel:```
<br/>```Digitaliserat exemplar``` 
<br/>```Fritt tillgängligt via Internet``` 

## Verk 
[För information om egenskaperna, se den generella beskrivningen av Verk](https://libris.kb.se/katalogisering/help/workflow-work)

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

## Bestånd
INFO

### Katalogisatörens anmärkning
* Katalogisatörens anmärkning (852 #x) 
