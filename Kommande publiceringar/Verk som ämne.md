## Verk som ämne
I de fall det finns en auktoriserad beskrivning av ett verk går den att länka till. De auktoriserade beskrivningar för verk som finns i Libris är i många fall ganska tunna men bör trots det användas för länkning till för att undvika att skapa lokala entiteter i onödan.

Börja alltid med att söka efter länkbar entitet. Lokal entitet skapas endast då det inte finns auktoriserad beskrivning att länka till. Rekommendationen att inte bryta ut verk som länkbar entitet gäller fortfarande, se [information i Librisbloggen](http://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).

### Länka till verk
* Öppna sidorutan Lägg till entitet inom egenskapen Ämne.
* Filtrera på typen Verk.
* Sök efter och lägg till aktuellt verk. Det auktoriserade verket länkas då till verksbeskrivningen i Instans av Verk.

Exempel:
![Länkat verk som ämne](LankatVerkAmne.png)

Tillvägagångssättet är detsamma för verk med primärt upphov (600 1/- #a #d #t) och anonyma verk (630 -/4 #a).
</br>Flera verk kan sökas efter/läggas till när sidorutan Lägg till entitet är öppen.

### Verk som lokal entitet
* Öppna sidorutan Lägg till entitet inom egenskapen Ämne.
* Välj typen Verk i rullgardinsmenyn för Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper inom den tillagda typen Verk. Sök efter och lägg till egenskaperna Har titel och Medverkan och funktion.
* Välj Titel i rullgardinsmenyn och skriv in den föredragna titeln i rutan för Huvudtitel (Övrig titelinformation raderas).
* Välj Primär medverkan i rullgardinsmenyn och sök efter och länka till auktoriserad namnform. (Om auktoriserad namnform saknas: Välj typen Person under Skapa lokal entitet och fyll i uppgifterna).
* Öppna sidorutan Lägg till funktion och länka till aktuell funktion.

Exempel:
![Verk som lokal entitet som ämne](VerkLokalEntitetAmne.png)
