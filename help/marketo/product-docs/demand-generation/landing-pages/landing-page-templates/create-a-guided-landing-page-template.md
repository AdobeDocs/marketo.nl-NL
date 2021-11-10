---
unique-page-id: 7515401
description: Een sjabloon voor een bestemmingspagina met instructies maken - Marketo Docs - Productdocumentatie
title: Een sjabloon voor een bestemmingspagina met instructies maken
exl-id: 7d097162-d862-4d09-9440-aba1628450c2
source-git-commit: c309b69198c6f61d7475c6d3a6b1672e045b9b4a
workflow-type: tm+mt
source-wordcount: '1254'
ht-degree: 0%

---

# Een sjabloon voor een bestemmingspagina met instructies maken {#create-a-guided-landing-page-template}

Sjablonen voor bestemmingspagina&#39;s met instructies hebben een speciale syntaxis. Gebruik deze syntaxis om op te geven wat aanpasbaar is en waar de inhoud terechtkomt op elke bestemmingspagina die op basis van uw sjabloon is gemaakt. Alleen de gebieden of variabelen die u als bewerkbaar opgeeft, kunnen worden aangepast in de landingspagina-editor &quot;Met instructies&quot;.

>[!TIP]
>
>Gebruik goede naamconventies en uw marketingteam zal verliefd op u worden.

Er zijn twee manieren om te declareren dat iets op uw pagina bewerkbaar moet zijn:

* Declareer een object als een &quot;element&quot;. De maker van de bestemmingspagina kan afbeeldingen, tekst of Marketo-elementen toevoegen aan die opgegeven gebieden.
* Declareer een tekenreeks als een &quot;variabele&quot;. De maker van de bestemmingspagina kan die variabele vervangen door een tekenreeks, kleur of booleaanse status vanuit een echte/false hendel.

## Bewerkbare elementen {#editable-elements}

Elementen worden gedeclareerd door een normaal DOM-element aan de sjabloon toe te voegen en het element vervolgens te versieren met een Marketo-specifieke klassenaam.

## Tekst {#text}

Als u een gebied definieert als RTF-tekst, kunnen gebruikers de inhoud ervan bewerken [Marketo Rich Text Editor gebruiken](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md).

Vereiste kenmerken:\
**class**: &quot;mktoText&quot;\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:\
De inhoud van een element met de klasse mktoText (indien opgegeven) wordt gebruikt als standaardwaarde voor het bewerkbare gebied.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area.</div></pre>`

## Afbeelding {#image}

U hebt twee opties om bewerkbare afbeeldingselementen te definiëren. U kunt beide `<div>`, die een container aangeeft waarin de afbeelding wordt ingevoegd, of een `<img>` tag.

## Optie 1 - Een `<div>` {#option-use-a-div}

Vereiste kenmerken:

klasse: &quot;mktoImg&quot;\
id: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
mktoName : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:\
mktoImgClass: Tekenreeks. De waarde hier wordt toegevoegd aan het klassenkenmerk van het dialoogvenster `<img>` -element in het div-element.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoImg" id="exampleImg" mktoName="Example Image"></div></pre>`

## Optie 2 - Een `<img>` {#option-use-a-img}

Vereiste kenmerken:\
klasse: &quot;mktoImg&quot;\
id: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
mktoName : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:\
src: URL tekenreeks. Dit wordt gebruikt als standaardwaarde voor de afbeelding.

Voorbeeld:

`<pre data-theme="Confluence"><img class="mktoImg" id="exampleImg" mktoName="Example Image"></pre>`

>[!NOTE]
>
>Wanneer u de `<img>` versie, zal de teruggegeven HTML een geproduceerde div omslag rond `<img>` tag. Deze wordt ingesteld op class.&quot;mktoImg.mktoGen&quot; en wordt weergegeven:inline-block.

## Formulier {#form}

Voorbeeld:Vereiste kenmerken:\
**class**: &quot;mktoForm&quot;\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

`<pre data-theme="Confluence"><div class="mktoForm" id="exampleForm" mktoName="Example Form"></div></pre>`

## Fragment {#snippet}

Vereiste kenmerken:\
**class**: &quot;mktoSnippet&quot;\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoSnippet" id="exampleSnippet" mktoName="Example Snippet"></div></pre>`

## Knop Delen {#share-button}

Vereiste kenmerken:\
**class**: &quot;mktoShareButton&quot;\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoShareButton" id="exampleShareButton" mktoName="Example Share Button"></div></pre>`

## Video {#video}

>[!NOTE]
>
>Marketo ondersteunt alleen video&#39;s van YouTube wanneer het video-element op een openingspagina wordt gebruikt. Als u een andere service gebruikt, is het raadzaam een RTF-vak te gebruiken en in de insluitcode van de video te plakken.

Vereiste kenmerken:
**class**: &quot;mktoVideo&quot;
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoVideo" id="exampleVideo" mktoName="Example Video"></div></pre>`

## Pollen {#poll}

Vereiste kenmerken:\
**class**: &quot;mktoPoll&quot;\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoPoll" id="examplePoll" mktoName="Example Poll"></div></pre>`

## Verwijzing {#referral}

Vereiste kenmerken:\
**class**: &quot;mktoReferral&quot;\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoReferral" id="exampleReferral" mktoName="Example Referral"></div></pre>`

## Sweepstake {#sweepstakes}

Vereiste kenmerken:\
**class**: &quot;mktoSweepstakes&quot;\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoSweepstakes" id="exampleSweepstakes" mktoName="Example Sweepstakes"></div></pre>`

## Bewerkbare variabelen {#editable-variables}

Alle variabeletypen worden gebruikt door naar de waarde van hun attribuut id te verwijzen dat binnen van een ${} karakteropeenvolging wordt verpakt. Ze kunnen overal in het document worden gebruikt, behalve binnen in andere declaraties van variabelen.

Voorbeeld:

`<pre data-theme="Confluence">${var1}</pre>`

**Verklaring:**

Variabelen worden gedeclareerd als metatags binnen de `<head>` -element van de sjabloon. Er zijn drie typen variabelen beschikbaar voor gebruik: Tekenreeks, Kleur en Boolean.

## String {#string}

Vereiste kenmerken:\
**class** : &quot;mktoString&quot;,\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:\
**default**: Tekenreekswaarde voor het kenmerk. Blanco als er geen informatie is opgegeven.\
**allowHtml**: &quot;true&quot; of &quot;false&quot;. Bepaalt of de waarde wordt afgedrukt zonder dat de HTML wordt beschermd. De standaardwaarde is &quot;false&quot; als de instelling wordt opgeheven.

Eenvoudig voorbeeld:

`<pre data-theme="Confluence"><meta class="mktoString" id="var1" mktoName="My Variable"></pre>`

Voorbeeld met alle kenmerken:

`<pre data-theme="Confluence"><meta class="mktoString" id="var1" mktoName="My Variable" default="This is my default value" allowHtml="true"></pre>`

## Kleur {#color}

Vereiste kenmerken:\
**class** : &quot;mktoColor&quot;,\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:\
**default**: Een HEX-tekenkleurcode van 7 cijfers. Voorbeeld: &quot;#336699&quot;

Eenvoudig voorbeeld:

`<pre data-theme="Confluence"><meta class="mktoColor" id="color1" mktoName="My Color Variable"></pre>`

Voorbeeld met alle kenmerken:

`<pre data-theme="Confluence"><meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699"></pre>`

## Boolean {#boolean}

Vereiste kenmerken:\
**class** : &quot;mktoBoolean&quot;,\
**id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.\
**mktoName** : Tekenreeks. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:\
**default**: Booleaanse tekenreeks. &quot;true&quot; of &quot;false&quot; als de waarde begint in de aan- of uit-positie. &quot;false&quot; indien niet opgegeven.\
**false_value**: Tekenreeks. De waarde die voor de variabele moet worden ingevoegd wanneer deze zich in de OFF-positie bevindt. &quot;false&quot; indien niet opgegeven.\
**true_value**: Tekenreeks. De waarde die voor de variabele moet worden ingevoegd wanneer deze zich op de positie ON bevindt. &quot;true&quot; indien niet opgegeven.\
**false_value_name**: Tekenreeks. De weergavenaam die wordt weergegeven in de editor voor de bestemmingspagina wanneer de waarde in de uitstand staat. &quot;OFF&quot; indien niet opgegeven.\
**true_value_name**: Tekenreeks. De weergavenaam die wordt weergegeven in de editor voor de bestemmingspagina wanneer de waarde zich op de positie ON bevindt. &quot;ON&quot; indien niet opgegeven.

Eenvoudig voorbeeld:

`<pre data-theme="Confluence"><meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699"></pre>`

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable"></pre>`

Voorbeeld met alle kenmerken:

In dit voorbeeld wordt een veelvoorkomend geval getoond waarin een Booleaanse variabele de zichtbaarheid van een CSS-element regelt door de waarde van de CSS-weergave-eigenschap in te stellen op &quot;block&quot; of &quot;none&quot; om een element met id weer te geven/te verbergen. In de editor van de bestemmingspagina wordt de weergavenaam Tonen/Verbergen gebruikt in plaats van UIT/ON.

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable" default="true" true_value="block" false_value="none" false_value_name="Hide" true_value_name="Show"> <style> #myConditionalDisplayArea { display: ${boolean1}; } </style></pre>`

>[!NOTE]
>
>Programmatokens (my.token) kunnen ook overal worden gebruikt op bestemmingspagina&#39;s met instructies of vrije vorm.
