## 2 Ämnesord som lokal entitet

Hjälptexten beskriver hur man anger ämnesord i verksbeskrivningen i Instans av Verk i de fall ämnesorden inte finns auktoriserade.

Utgår katalogiseringen från en mall finns egenskapen Ämne redan tillagd under Instans av Verk. 
<br/>För att lägga till egenskapen Ämne: Klicka på plustecknet inom Instans av Verk, sök efter och lägg till Ämne (subject).

| [1 Ämnesord från system med listkod som länkad entitet](#amnesord-från-system-med-listkod-som-länkad-entitet) | [2 Ämnesord från system med listkod (utan listkod som länkad entitet)](#amnesord-från-system-med-listkod-utan-listkod-som-länkad-entitet) | [3 Ämnesord utan listkod](#amnesord-utan-listkod)
| ----------- |  ----------- |  ----------- |
| [1a Enkelt amnesord som lokal entitet](#1a-enkelt-amnesord-som-lokal-entitet-med-listkod-som-lankad-entitet) | [2a-Enkelt ämnesord som lokal entitet](#2a-enkelt-amnesord-som-lokal entitet-utan-listkod-som-lankad-entitet) |  [3a Ämnesord utan listkod](#3a-amnesord-utan-listkod) |
| [1b Sammansatt ämnesord som lokal entitet](#1a-amnesord-från-system-med-listkod-som-länkad-entitet) | [2b-Sammansatt ämnesord som lokal entitet](#2b-sammansatt-amnesord-som-lokal-entitet)  |




### 1 Ämnesord från system med listkod som länkad entitet
Instruktionen används i de fall man vill ange ämnesord som en lokal entitet från kontrollerade ämnesordslistor vars listkod finns som en länkad enitet, t.ex. **agrovoc**, **kao**, **prvt**, **sfit**, **mesh** m.fl. Vissa ämnesordskonstruktioner från Svenska ämnesord (sao) läggs också in som lokala entiteter om den sammansatta konstruktionen inte finns auktoriserad, t.ex. sammansatta geografiska ämnesord.

#### 1a Enkelt ämnesord som lokal entitet (med listkod som länkad entitet)

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj den typ av ämnesord du vill lägga till i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda lokala entiteten. 
* Sök efter och välj Föredragen benämning och Termlista.
* Skriv in aktuell term i Föredragen benämning.
* Öppna sidorutan Lägg till entitet inom egenskapen Termlista. Sök efter och välj aktuell listkod.

För att lägga till flera termer av samma typ kan den lokala entiteten kopieras.

![Enkelt ämnesord som lokal entitet](LokaltEnkeltKao.png) 


#### 1b Sammansatt ämnesord som lokal entitet (med listkod som länkad entitet)

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till entitet/termlista inom egenskapen Termlista. Sök efter och välj aktuell listkod.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term i rutan.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Underindelning för allmänt ämnesord.
* Skriv in aktuell term i rutan Föredragen benämning.

För att lägga till flera termer av samma typ, eller flera underindelningar inom den sammansatta termen, kan kopierafunktionen användas.

![Lokalt sammansatt ämnesord med listkod kao](LokaltSammansattKao.png) 
![Lokalt sammansatt geografiskt ämnesord med listkod sao](LokaltGeoSammansattSao.png)

### 2 Ämnesord från system med listkod utan listkod som länkad entitet

#### 2a Enkelt ämnesord som lokal entitet (utan listkod som länkad entitet)

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning och Termlista. Skriv in aktuell term i rutan.
* Öppna sidorutan Lägg till entitet/termlista inom egenskapen Termlista. Välj Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom egenskapen Termlista. Sök efter och lägg till egenskapen Kod.
* Skriv in aktuell listkod i rutan, t.ex. ”lcsh”.

SKÄRMDUMP: LokaltEnkeltLcsh

#### 2b Sammansatt ämnesord som lokal entitet (utan listkod som länkad entitet)

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till entitet/termlista inom egenskapen Termlista. Välj Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom egenskapen Termlista. Sök efter och lägg till egenskapen Kod.
* Skriv in aktuell listkod i rutan, t.ex. ”lcsh”.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term i rutan.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Underindelning för allmänt ämnesord.
* Skriv in aktuell term i rutan.

För att lägga till flera termer av samma typ, eller flera underindelningar inom den sammansatta termen, kan kopierafunktionen användas.

![Lokalt sammansatt ämnesord med listkod lcsh](LokaltSammansattLcsh.png)

#### 3 Ämnesord utan listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term i rutan.




