---
title: Toegankelijke inhoud ontwerpen
description: Leer hoe u toegankelijke inhoud ontwerpt voor uw e-mails in Adobe Marketo Engage.
feature: Email Designer
role: User
level: Beginner, Intermediate
keywords: e-mail, ontwerp, toegankelijkheid
source-git-commit: 5adfebfd8f9f0cdaebb1eb86a68c136d46298446
workflow-type: tm+mt
source-wordcount: '1359'
ht-degree: 0%

---

# Toegankelijke inhoud ontwerpen {#accessible-content}

De [ Europese toegankelijkheidswet ](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882){target="_blank"} is een richtlijn die wordt ontworpen om de interne markt voor toegankelijke producten en diensten te verbeteren door barrières weg te nemen die door verschillende nationale regels in de lidstaten worden veroorzaakt.

Deze verordening bepaalt dat alle digitale communicatie, inclusief e-mails, nieuwsbrieven, PDF&#39;s en downloadbare inhoud, toegankelijk moet zijn. Wanneer u inhoud maakt voor uw ontvangers, moet u daarom bepaalde richtlijnen volgen, zoals het gebruik van toegankelijke lettertypen en leesbare indelingen, en het aanbieden van alternatieve tekst voor afbeeldingen.

Met de Marketo Engage Email Designer kunt u eenvoudig aan deze richtlijn voldoen, op basis van Web Content Accessibility Guidelines (WCAG) 2.1, niveau AA. De beste werkwijzen voor het ontwerpen van toegankelijke inhoud met Marketo Engage worden hieronder weergegeven.

>[!NOTE]
>
>Deze pagina gaat over het toegankelijk maken van uw inhoud voor al uw ontvangers, zodat mensen met een handicap uw e-mails die in Marketo Engage zijn ontworpen, kunnen lezen, begrijpen en ermee kunnen communiceren.

## Zorg ervoor dat de tekst leesbaar is {#text-readability}

Gebruik de tab **[!UICONTROL Styles]** van de component **[!UICONTROL Text]** om ervoor te zorgen dat de tekst leesbaar is, bijvoorbeeld door een juist kleurcontrast en eenvoudige lettertypen te gebruiken.

<!--![](assets/accessible-text-styles.png){width="80%"}-->

Voor lettertypen en tekst moet u de volgende richtlijnen volgen:

**de selectie van de Doopvont**

* Gebruik sans-serif-lettertypen zoals Arial, Verdana, Tahoma, Helvetica of Open Sans.
* Vermijd serif-, cursieve of decoratieve lettertypen in de inhoud van het lichaam.
* Selecteer een beperkte lettertypeset voor consistentie en fallback (bijvoorbeeld: `font-family: Arial, Helvetica, sans-serif;`).

**het rangschikken van doopvont**

* Zorg voor een minimale tekengrootte van 16 px voor platte tekst.
* Gebruik de juiste hiërarchie voor koppen.

**Contrast van de Kleur**

* Houd een contrastverhouding van minstens 4.5 :1 tussen tekst en achtergrond.
* Voor grote tekst (≥ 24px of gewaagd 18px), zorg minstens een 3 :1 contrast.
* Vermijd lichtgrijze of pasteltekst op witte achtergronden.
* Vertrouw niet op kleur alleen om betekenis over te brengen. Gebruik onderstrepingen, pictogrammen, enzovoort.

**de toegankelijkheid van de Tekst**

* Vermijd tekst in afbeeldingen.
* Gebruik niet alle uiteinden in lichaamstekst.
* Zorg ervoor dat op tekst kan worden ingezoomd tot 200% zonder de layout te verbreken.

## Zorg voor visuele toegankelijkheid {#visual-accessibility}

* Vermijd het gebruik van alleen-kleuren-indicatoren voor belangrijke informatie.
* Gebruik tekstlabels of pictogrammen voor meer duidelijkheid.
* Optimaliseer uw ontwerp voor mobiele en responsieve lay-outs, zodat de knoppen groot zijn en de juiste afstand hebben.
* Regelmatig testen op verschillende apparaten en schermformaten om de toegankelijkheid te behouden.

In Marketo Engage kunt u de grootte en tussenruimte van de verschillende elementen in uw inhoud verder verfijnen met de opmaakparameters en -kenmerken uit het deelvenster E-mail Designer **[!UICONTROL Styles]** .

U kunt bijvoorbeeld de achtergrond bijwerken of de marges, opvulling en uitlijning wijzigen om de visuele toegankelijkheid te verbeteren.

<!--![](assets/accessible-styles.png){width="80%"}-->

Met de Marketo Engage Email Designer kunt u een voorvertoning weergeven van het ontwerp voor verschillende apparaten en schermformaten en kunt u het ontwerp optimaliseren. U kunt op elk gewenst moment **[!UICONTROL Switch to live view]** controleren hoe uw inhoud op verschillende apparaatgrootten wordt gerenderd.

<!--![](assets/accessible-live-view.png){width="80%"}-->

>[!CAUTION]
>
>De live weergave is een algemene voorvertoning die is ontworpen om te vergelijken hoe de inhoud kan worden gerenderd in verschillende apparaatgrootten. De uiteindelijke rendering kan variëren afhankelijk van de e-mailclient van de ontvanger.

## Alternatieve tekst gebruiken voor afbeeldingen {#alt-text}

Gebruik de component **[!UICONTROL Image]** om alternatieve tekst voor afbeeldingen te bieden.

<!--![](assets/accessible-alt-text.png){width="90%"}-->

* Beschrijf het doel van de afbeelding beknopt en contextueel.
* Vermijd overbodige zinnen zoals &quot;Afbeelding van ...&quot; en gebruik lege alt-tekst voor decoratieve afbeeldingen.
* Gebruik voor pictogrammen met betekenis, nuttige labels en voor complexe afbeeldingen een korte alt-tekst plus een langere beschrijving elders.

## Leesbare indeling gebruiken {#readable-format}

Gebruik de relevante structuur- en inhoudscomponenten van e-mail Designer en de opties in het deelvenster **[!UICONTROL Styles]** om de inhoud op een duidelijke, logische en beknopte manier te ordenen die voor iedereen toegankelijk is.

<!--![](assets/accessible-components.png){width="100%"}-->

* Gebruik gestructureerde, semantische HTML met de juiste koppen, alinea&#39;s, lijsten en tabellen.
* Zorg ervoor dat de inhoud een logische stroom volgt van links naar rechts en van boven naar beneden.
* Gebruik duidelijke, beknopte taal.
* Alternatieve indelingen bieden voor PDF&#39;s en informatie.
* Formaat van tekst wijzigen en opnieuw plaatsen toestaan en ervoor zorgen dat typografie met een passend kleurcontrast in alle indelingen kan worden gelezen.

## Leesbaarheid van inhoud garanderen {#readability}

Om leesbaar te zijn, moet uw inhoud duidelijk zijn, goed gestructureerd, en bruikbaar voor iedereen, met inbegrip van mensen met visuele, cognitieve, of lezingsmoeilijkheden, en die hulptechnologieën gebruiken. Enkele punten waarmee u rekening moet houden bij het maken van toegankelijke inhoud zijn:

* Laat zinnen ongeveer 20 woorden of minder bedragen.
* Bewerk de kopie om direct en beknopt te zijn.
* Gebruik actieve stem om de zinsstructuur eenvoudiger te houden.
* Vermijd slang, jargon of regionale woorden die sommige mensen misschien niet kennen.

Om uw e-mailleesbaarheid te evalueren, kunt u de populaire [ test van de Versnelling van de Lezing van de Vlesch gebruiken ](https://support.microsoft.com/en-us/office/get-your-document-s-readability-and-level-statistics-85b4969e-e80a-4777-8dd3-f7fc3c8b3fd2){target="_blank"}, die in Microsoft Word kan worden gevonden en berekent hoe gemakkelijk uw inhoud op een schaal van 0-100 moet lezen.

## Uw inhoud testen {#test}

Om de toegankelijkheid van uw inhoud te controleren, kunt u de testmogelijkheden gebruiken die door Marketo Engage worden verstrekt. Ze zijn niet specifiek ontworpen om te controleren of uw inhoud volledig toegankelijk is, maar ze kunnen wel een eerste verificatieniveau bieden.

* Geef een voorvertoning van de inhoud weer met testprofielen.

* Gebruik de [ E-mail die ](/help/marketo/product-docs/email-marketing/email-designer/test-email-rendering.md){target="_blank"} optie teruggeeft die hefboomwerkingen Litmus om uw ontwerpen over belangrijke e-mailcliënten (de Post van Apple, Gmail, Vooruitzichten) te simuleren en te zien of maken de tekst, de kleuren en de beelden uw inhoud toegankelijk. <!--Litmus includes accessibility testing-->

* Verzend proefdrukken om de rendering van uw inhoud te testen voordat u deze naar uw echte publiek stuurt.

<!--![](assets/accessible-simulate.png){width="90%"}-->

Als u op een meer consistente manier wilt controleren of uw inhoud betrouwbaar toegankelijk is, gaat u naar specifieke externe gereedschappen, zoals:

* De [ contrastcontrole WebAim ](https://webaim.org/resources/contrastchecker/){target="_blank"} en het [ hulpmiddel van de de evaluatie van de Webtoegankelijkheid van de WAVE ](https://wave.webaim.org/){target="_blank"} om contrast en naleving te evalueren;

* De technologieën van de hulp zoals het schermlezers (bijvoorbeeld: [ NVDA ](https://www.nvaccess.org/download/){target="_blank"}, of [ VoiceOver ](https://support.apple.com/en-ie/guide/iphone/iph3e2e415f/ios){target="_blank"} op iPhone) om e-mails van het perspectief van visueel gehandicapte gebruikers te ervaren.

## Donkere modus gebruiken {#dark-mode}

[ Donkere wijze ](/help/marketo/product-docs/email-marketing/email-designer/dark-mode.md){target="_blank"} verbetert visuele toegankelijkheid voor gebruikers met lichtgevoeligheid of visuele bijzondere beperkingen, voor een betere het bekijken ervaring.

<!--![](assets/accessible-dark-mode.png){width="90%"}-->

Voorbeelden van best practices voor het ontwerpen van inhoud in de donkere modus zijn:

* Transparante PNG&#39;s of SVG&#39;s gebruiken
* De juiste metatags en CSS instellen
* Toegankelijke fallback-stijl bieden als de donkere modus niet wordt ondersteund.

Zorg ervoor dat de e-mailberichten correct worden weergegeven in de donkere modus door alle e-mailinhoud en UI-elementen te testen in zowel de lichte als de donkere modus.

## Specifieke kenmerken voor toegankelijkheid gebruiken {#attributes}

### Taalkenmerken {#language}

Wanneer u ontwerpen maakt, neemt u de kenmerken `lang` (taal) en `dir` (tekstrichting) op in de hoofdtekst van de inhoud. Deze kenmerken helpen ondersteunende hulpmiddelen (zoals schermlezers) bij het interpreteren en op de juiste manier presenteren van uw inhoud.

* Het attribuut `lang` geeft de taal van de e-mail aan ondersteunende technologieën aan, zodat woorden correct worden uitgesproken.

  +++Voorbeelden

  Voorbeeld voor Engels:

  ```
  <body lang="en">
  ```

  Voorbeeld voor Frans:

  ```
  <body lang="fr">
  ```

  +++

* Het kenmerk `dir` geeft de tekstrichting op. De meeste talen, waaronder Engels en Frans, worden van links naar rechts (ltr) gelezen, terwijl talen zoals Arabisch en Hebreeuws van rechts naar links (rtl) worden gelezen.

  +++Voorbeelden

  Voorbeeld voor Engels (van links naar rechts):

  ```html
  <body lang="en" dir="ltr">
  ```

  Voorbeeld voor Arabisch (van rechts naar links):

  ```html
  <body lang="ar" dir="rtl">
  ```

  +++

Schermlezers vertrouwen op het kenmerk `lang` om de juiste uitspraakregels toe te passen, terwijl de tekstrichting ervoor zorgt dat de inhoud op natuurlijke wijze doorloopt voor talen die van links naar rechts of van rechts naar links worden geschreven. Zonder deze kenmerken kunnen gebruikers last krijgen van verwarrende leesvolgorde of verkeerde uitspraak. Plaats altijd de juiste kenmerken voor `lang` en `dir` in de tekst van de e-mail.

>[!TIP]
>
>Als uw e-mail meerdere talen bevat, wijst u de juiste taalkenmerken toe aan specifieke secties (zoals `<table>` - of `<td>` -blokken) om ervoor te zorgen dat elk onderdeel correct wordt gelezen.

### Tabellen {#tables}

In HTML-inhoud worden tabellen vaak gebruikt voor de lay-out. Standaard behandelen schermlezers elke `<table>` als een gegevenstabel, waarbij rijen, kolommen en structuur worden aangekondigd. Dit kan verwarrend zijn als de tabel alleen wordt gebruikt voor opmaak.

Voeg `role="presentation"` (of `role="none"` ) toe aan indelingstabellen om ervoor te zorgen dat ondersteunende hulpmiddelen hun structuur overslaan en alleen de werkelijke inhoud activeren.

+++Voorbeeld - Lay-outtabel (met `role="presentation"`)

```html
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%"> 
  <tr> 
    <td align="center"> 
      <h1>Hello World</h1> 
      <p>Welcome to our newsletter</p> 
    </td> 
  </tr> 
</table>
```

De schermlezers lezen:
&quot;Hallo wereld. Welkom bij onze nieuwsbrief.&quot; _(Geen vermelding van rijen, kolommen of tabel)_

+++

+++Voorbeeld - Gegevenstabel (zonder `role="presentation"`)

```html
<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th scope="col">Name</th>
    <th scope="col">Score</th>
  </tr>
  <tr> 
    <td>Peter</td>
    <td>19</td>
  </tr>
  <tr>
    <td>Parker</td>
    <td>62</td>
  </tr>
</table>
```

De schermlezers lezen:
&quot;Tabel met 2 kolommen en 3 rijen.&quot;

&quot;Naam, Peter. Score, 19.&quot;

&quot;Naam, Parker. Score, 62.&quot;

+++

>[!TIP]
>
>Gebruik `role="presentation"` uitsluitend voor lay-outtabellen. Voor gegevenstabellen, behoud de semantische `<table>` structuur zodat de schermlezers correct kopballen en verhoudingen kunnen aankondigen.

### Tekst voor koppelingen {#links}

Schermlezers lezen koppelingen voor met behulp van hun tekst. Als een koppeling alleen &#39;Klik hier&#39; of &#39;Meer lezen&#39; heet, weten gebruikers van ondersteunende hulpmiddelen niet wat het doel is. Om toegankelijkheid te waarborgen, hebben ze beschrijvende tekst nodig die het doel of de actie duidelijk aangeeft.

Gebruik de Designer-mailtoepassing om een koppeling naar uw inhoud toe te voegen en het label te bewerken, zodat deze herkenbaar (zichtbaar) en beschrijvend (duidelijk over het doel) is. Vermijd vage labels zoals &#39;here&#39; of &#39;more&#39;.

<!--![](assets/accessible-link.png){width="70%"}-->

+++Voorbeeld - Goede koppeling (beschrijvend): 

```
<p>Learn more in the  
<a href="https://adobe.com/release-notes">August release notes</a>. 
</p>
```

De schermlezers lezen:
&quot;Link, August release notes.&quot;

+++

+++Voorbeeld - Ongeldige koppeling (niet beschrijvend)

```
<p>Learn more about our new features.  
  <a href="https://adobe.com/release-notes">Click here</a>. 
</p>
```

De schermlezers lezen:
&quot;Link, klik hier.&quot; *(Verstrekt geen context uit leesorde)*

+++

<!--for Landing Pages-->

<!--## Provide keyboard navigation and focus support {#keyboard}

Providing keyboard navigation and focus support allows people who cannot use a mouse to fully access and interact with content. It also improves overall usability by giving all users a clear and consistent way to move through information.

* Focus via keyboard
    * Ensure all interactive elements (such as buttons, checkboxes, links) have `tabindex="0"` so they are included in the natural tab order. 
    * Allow navigation using the Tab and arrow keys (↑ ↓ ← →), which should visibly highlight the focused element. 
* Custom focus styling 
    * Apply clear and distinguishable styles for focusing on actionable elements: 
        +++Example (CSS)

        ```
        [tabindex="0"] : focus { 
        outline: 2px solid #00AEEF;  /* Cyan border */ 
        background-color: #20CEFF;   /* Optional background */ 
        }
        ```
        
        +++

    * Ensure that focus indicators meet the WCAG 2.2 focus appearance standards, including: 
        * Minimum area: 2 CSS pixel thick outline.
        * Contrast ratio: ≥ 3:1 between focused and unfocused state. 

* Keyboard activation support 
    * Ensure checkboxes and buttons respond to the Enter and Space keys. 
    * Validate the interaction using the keyboard alone: 
        * Enter or Space should toggle checkboxes.
        * Enter or Space should trigger the buttons.-->
