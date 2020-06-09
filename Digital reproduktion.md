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
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av en digital produktion av en fysisk förlaga, 
t.ex. en bok eller en bild (?) För mer utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, 
se innehållsförteckningen nedan. Det finns en mall för Digital reproduktion då alla värden behöver anges manuellt. Funktionen Skapa digital 
reproduktion i verktygsmenyn med posten för en fysik förlaga som utgångspunkt genererar förifyllda värden där endast en del behöver kompletteras manuellt.

## Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- | ----------- |  ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Medietyp](#medietyp) | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Bärartyp](#barartyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Titel](#titel) | [Språk](#sprak) |
| | [Upphovsuppgift](#upphovsuppgift) |[Genre/form](#genre-form)|
| | [Utgivning](#utgivning) | [Klassifikation](#klassifikation)  |
| | [Anmärkning](#anmarkning)| [Ämne](#amne)|
| | [Är del av](#ar-del-av) | [Innehållstyp](#innehallstyp) |
| | [Placering i värdpublikation](#placering-i-vardpublikation) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |


## Inledning
Beskrivningen av ett bidrag innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans för ett bidrag är titel, upphov och utgivning.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. 

För information om katalogiseringsregler och Librispraxis, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") samt [se RDA Toolkit](https://access.rdatoolkit.org/). 

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).
* Bibliografi
  I mallen är DIGI ifyllt. Korrigera/komplettera vid behov.
* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken).
* Anmärkning ?

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn. 

### Instanstyp

### Reproduktion av

### Identifikator

### Utgivningssatt
* Utgivningssätt (issuanceType = 008/07)  
  Förval i mallen: Monografisk resurs

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Förval i mallen: Computer
  
### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Förval i mallen: 
   * ```onlineresurs, cr``` (bidrag i elektronisk publikation) 
  
### Titel 
#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)</br>
  ```Exempel: Herrgårdsbyggnader i Mälardalen under 1700- och 1800-talet```
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
   ```Exempel: när, var och av vem?```

För att ange föredragen titel, t.ex. om bidraget är översatt, se [Verkets titel](#verkets-titel).  

#### Varianttitel
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)

#### Delbeteckning och deltitel
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 #n)
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 #p)
  
#### Parallelltitel  
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)
     
### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)<br/>
  ```Exempel: Johan Ahlner, Karin Kjellgren```

### Upplageuppgift
Se generell hjälptext för Instans

### Utgivning  
Se generell hjälptext för Instans

### Produktion 

### Copyright
Se generell hjälptext för Instans

### Omfång
Se generell hjälptext för Instans

### Övriga fysiska detaljer
Se generell hjälptext för Instans

### Digital karaktäristika
* Digital karaktäristika/Kodningsformat/Benämning (digatalCharacteristics = 347)

### Seriemedlemskap
Se generell hjälptext för Instans

### Tillhörande media (associatedMedia)

### Villkor för anvädning och åtkomst (usageAndAccessPolicy = 540)

### Relaterad beskrivning eller innehåll (isPrimaryTopicOf = 856)

### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)<br/>

## Verk 
För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

[För information om egenskaperna, se den generella beskrivningen av Verk](https://libris.kb.se/katalogisering/help/workflow-work)

## Bestånd
