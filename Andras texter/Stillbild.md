

## Stillbild

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid katalogisering av stillbilder. I de fall egenskaperna finns beskrivna i generell hjälptext upprepas inte informationen här utan istället finns en länk till relevant hjälptext. Egenskaper som är specifika för stillbilder redovisas däremot enbart här. 

För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/) samt [RDA Toolkit](https://access.rdatoolkit.org/).

### Innehåll
| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ------ | ----------- |  ----------- |
| [Kontrollnummer](Länk adminmetadata) | [Utgivningssätt](Länk instans) | [Verkets titel](#verkets-titel) |
| [Skapad av](Länk adminmetadata) | [Medietyp](Länk instans) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Uppgraderad eller importerad av](Länk adminmetadata) | [Bärartyp](Länk instans) | [Språk](#sprak) |
| [Katalogiserande instans](Länk adminmetadata) | [Titel](Länk instans) | [Genre](#genre) |
| [Poststatus](Länk adminmetadata) | [Upphovsuppgift](Länk instans) | [Ämne](#amne) |
| [Systemnummer](Länk adminmetadata) | [Upplageuppgift](Länk instans) | [Innehållstyp](#innehallstyp) |
| [Katalogiseringsspråk](Länk adminmetadata) | [Produktion](Länk instans) | [Sammanfattning av innehåll](#sammanfattning-av-innehåll) |
| [Katalogiseringsregler](Länk adminmetadata) | [Utgivning](Länk instans)  |
| [Beskrivningsnivå](Länk adminmetadata) | [Huvudsakligt tillgängliggörande](Länk instans) | |
| [Bibliografikod](Länk adminmetadata  | [Tillverkning](Länk instans) | |
| [Systemteknisk anmärkning](Länk adminmetadata) | [Copyrightår](Länk instans) | |
| | [Identifikator](Länk instans) | |
| | [Omfång](Länk instans) | |
| | [Övriga fysiska detaljer](Länk instans) | | 
| | [Mått](Länk instans) | |                                                                  
| | [Produktionsmetod](#produktionsmetod) | |  
| | [Applicerat material](#applicerat-material) | |
| | [Bärande material](#bärande-material) | |
| | [Färginnehåll](#färginnehåll) | |
| | [Genre/form](#polaritet) | |
| | [Polaritet](#polaritet) | |
| | [Bilagor](Länk instans) | | 
| | [Seriemedlemskap](Länk instans) | | 
| | [Anmärkning](Länk instans) | | 
| | [Innehållsanmärkning](Länk instans) | | 
| | [Annat bärarformat](Länk instans) | | 


### Adminmetadata

Använd generell hjälptext för adminmetadata - Länk till allmän sida


### Instans

I de fall egenskaperna relevanta för Instans finns beskrivna i generell hjälptext upprepas inte informationen här. Följ länkar i innehållsförteckningen till hjälptext för Instans. Egenskaper som är specifika för Instans vid katalogisering av stillbilder redovisas nedan. 

#### Produktionsmetod
*	Produktionsmetod/Benämning (productionMethod/label = 340 ‡d)
  </br>Ange produktionsmetod som lokal entitet. 
  </br>Lista över termer att använda vid beskrivning av produktionsmetod gällande kartor och stillbilder finns i [RDA-anvisningarna](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/#Produktionsmetod).

#### Applicerat material
*	Applicerat material/Benämning (appliedMaterial/label = 340 ‡c)
  </br>Ange applicerat material som lokal entitet. Om flera entiteter behövs redovisas samtliga i en och samma fältetikett.
  </br>```Exempel: akvarell och penna```  
  </br>Lista över termer att använda vid beskrivning av applicerat material gällande kartor och stillbilder finns i [RDA-anvisningarna](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/#Applicerat%20material).

#### Bärande material 
*	Bärande material (baseMaterial (marc) = 007/00: k/01)
  </br>Länka till enitet. Välj bland entiteterna som benämns ”Bildens bärande material”. Trunkera (sök på * ) för att få upp en lista över samtliga entiteter. I stillbildsmallen finns entiteten Papp och kartong inlagd. Ändra vid behov.

*	Bärande material/Benämning ((baseMaterial/label = 340 ‡a)
  </br>Ange bärande material som lokal entitet.
  </br>I de fall flera entiteter behövs för korrekt beskrivning redovisas samtliga i en och samma ruta.
  </br>```Exempel: papper och textil ```  
  </br>I stillbildsmallen finns entiteten Papper inlagd. Ändra vid behov. 
  </br>Lista över termer att använda vid beskrivning av bärande material gällande kartor och stillbilder finns i [RDA-anvisningarna](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/#B%C3%A4rande%20material).

#### Färginnehåll
* Färginnehåll (colorContent (marc) = 007/00: k/03)
  </br>Länka till enitet. Välj bland följande entiteter: 
    </br> * En färg
    </br> * Svartvit
    </br> * Flera färger
    </br> * Handkolorerad (Bilden, som framställts genom tryck- eller fotografisk process, har handkolorerats.)
    </br> * Blandad färgstatus (En färg, svartvitt, flera färger och/eller handkolorering har kombinerats i ett verk eller en samling.)

  </br>I stillbildsmallen finns entiteten svartvit (marc/BlackAndWhite)  inlagd. Ändra vid behov. 
  </br>Observera att uppgift om färginnehåll (färg, svartvit eller kolorerad) även anges i klartext i egenskapen Övriga fysiska detaljer.

#### Genre/form
*	Genre/form (genreForm (marc) = 007/00: k/01)
  </br>Länka till entitet. Välj bland entiteterna med rubriken ”Särskild bärarbeteckning för bilder”. Trunkera (sök på * ) för att få upp en lista över samtliga entiteter. 
  </br>I stillbildsmallen finns entiteten bilder (marc/Picture)  inlagd. Ändra vid behov till mer specifik entitet.
 	
#### Polaritet
*	Polaritet/Benämning (polarity/label= 340 ‡o)
  </br>Använd Polaritet vid katalogisering av fotografier. Ange polaritet som lokal entitet. Välj bland följande två entiteter:
    </br> * positiv
    </br> * negativ


### Verk

#### Språk
•	Språk (language (marc) = 008/35-37)
Länka till entitet. För stillbilder utan text, välj Icke-språkligt medium (=language/zxx). Denna entitet är förvald i stillbildsmallen, ändra vid behov.

Se även: Länk till allmän hjälptext om språk

#### Genre/form 
*	Genre/form(genreForm (marc) = 007/00:k/00)
Länka till enitet. För stillbilder välj: Bild (marc/picture).
I stillbildsmallen finns redan entiteten Bild (marc/picture) inlagd.


*	Genre/form – TGM-termer (genreForm = 655 -/7 ‡a, ‡2 TGM)
Länka till entitet. Välj Genre/form i listan över typer. Sök på önskad term. 
I stillbildsmallen finns redan TGM-termen Bilder inlagd. Lägg till fler vid behov.

I nuläget går det inte att filtrera på enbart TGM-termer. Vid många sökträffar kan det därför vara bra att söka på termens id-nummer, som i nuläget enklast söks fram i Auktoritetsdatabasen (välj Genre i index, sök efter aktuell term).  
