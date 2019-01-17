## 2 Ämnesord som lokal entitet

Hjälptexten beskriver hur man anger ämnesord i verksbeskrivningen i Instans av Verk i de fall ämnesorden inte finns auktoriserade.

Utgår katalogiseringen från en mall finns egenskapen Ämne redan tillagd under Instans av Verk. 
<br/>För att lägga till egenskapen Ämne: Klicka på plustecknet inom Instans av Verk, sök efter och lägg till Ämne (subject).

| [Ämnesord från system med listkod som länkad entitet](#amnesord-från-system-med-listkod-som-länkad-entitet) | [Ämnesord från system utan listkod som länkad entitet](#amnesord-från-system-utan-listkod-som-länkad-entitet) | 
| ------ |  ----------- |
| | |
| [Enkelt ämnesord som lokal entitet](#enkelt-amnesord-som-lokal-entitet) | [Enkelt ämnesord som lokal entitet](#enkelt-ämnesord-som-lokal entitet) |
| [Sammansatt ämnesord som lokal entitet](#amnesord-från-system-med-listkod-som-länkad-entitet) | [Sammansatt ämnesord som lokal entitet](#sammansatt-amnesord-som-lokal-entitet)  |
| | [Amnesord utan listkod](#amnesord-utan-listkod) |

| | |


### Amnesord från system med listkod som länkad entitet
Instruktionen används i de fall man vill ange ämnesord som en lokal entitet från kontrollerade ämnesordslistor vars listkod finns som en länkad enitet, t.ex. **agrovoc**, **kao**, **prvt**, **sfit**, **mesh** m.fl. Vissa ämnesordskonstruktioner från Svenska ämnesord (sao) läggs också in som lokala entiteter om den sammansatta konstruktionen inte finns auktoriserad, t.ex. sammansatta geografiska ämnesord.

#### 2a-1 Enkelt ämnesord som lokal entitet (med listkod som länkad entitet)

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj den typ av ämnesord du vill lägga till i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda lokala entiteten. 
* Sök efter och välj Föredragen benämning och Termlista.
* Skriv in aktuell term i Föredragen benämning.
* Öppna sidorutan Lägg till entitet inom egenskapen Termlista. Sök efter och välj aktuell listkod.

![Enkelt ämnesord som lokal entitet](LokaltEnkeltKao.png) 

För att lägga till flera termer av samma typ kan den lokala entiteten kopieras.

#### 2a-2 Sammansatt ämnesord som lokal entitet (med listkod som länkad entitet)

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

### Amnesord från system utan listkod som länkad entitet

#### 2b-1 Enkelt ämnesord som lokal entitet (utan länkbar listkod)

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning och Termlista. Skriv in aktuell term i rutan.
* Öppna sidorutan Lägg till entitet/termlista inom egenskapen Termlista. Välj Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom egenskapen Termlista. Sök efter och lägg till egenskapen Kod.
* Skriv in aktuell listkod i rutan, t.ex. ”lcsh”.

SKÄRMDUMP: LokaltEnkeltLcsh

#### 2b-2 Sammansatt ämnesord som lokal entitet (utan länkbar listkod)

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

Klicka på plustecknet intill Termkomponenter, sidorutan Lägg till entitet öppnas. Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
Klicka på plustecknet vid den tillagda ämnesordstypen, sidorutan Lägg till egenskaper under öppnas. Sök efter och välj Föredragen benämning.
Skriv in aktuell term i Föredragen benämning.
Klicka på plustecknet intill Termkomponenter, sidorutan Lägg till entitet öppnas. Välj typ av underindelning i rullgardinsmenyn Skapa lokal entitet.

![Lokalt sammansatt ämnesord med listkod lcsh](LokaltSammansattLcsh.png)

#### 2 c Amnesord utan listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term i rutan.




