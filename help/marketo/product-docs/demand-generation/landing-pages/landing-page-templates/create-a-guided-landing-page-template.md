---
unique-page-id: 7515401
description: Een sjabloon voor een bestemmingspagina met instructies maken - Marketo Docs - Productdocumentatie
title: Een sjabloon voor een bestemmingspagina met instructies maken
exl-id: 7d097162-d862-4d09-9440-aba1628450c2
feature: Landing Pages
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '1263'
ht-degree: 1%

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

Als u een gebied als Rijke Tekst bepaalt, zullen de gebruikers zijn inhoud [ kunnen uitgeven gebruikend de Redacteur van de Tekst van de RTF van Marketo Rich ](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md).

Vereiste kenmerken:
**klasse**: &quot;mktoText&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:
De inhoud van een element met de klasse mktoText (indien opgegeven) wordt gebruikt als standaardwaarde voor het bewerkbare gebied.

Voorbeeld:

`<div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area.</div>`

## Afbeelding {#image}

U hebt twee opties om bewerkbare afbeeldingselementen te definiëren. U kunt een `<div>` -tag of een `<img>` -tag gebruiken, waarmee u een container opgeeft waarin de afbeelding wordt ingevoegd.

## Optie 1 - Een `<div>` gebruiken {#option-use-a-div}

Vereiste kenmerken:

klasse: &quot;mktoImg&quot;
id: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
mktoName : String. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:
mktoImgClass: String. De waarde hier wordt toegevoegd aan het klassenkenmerk van het element `<img>` binnen de div.

Voorbeeld:

`<div class="mktoImg" id="exampleImg" mktoName="Example Image"></div>`

## Optie 2 - Een `<img>` gebruiken {#option-use-a-img}

Vereiste kenmerken:
klasse: &quot;mktoImg&quot;
id: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
mktoName : String. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:
src: URL tekenreeks. Dit wordt gebruikt als standaardwaarde voor de afbeelding.

Voorbeeld:

`<img class="mktoImg" id="exampleImg" mktoName="Example Image">`

>[!NOTE]
>
>Wanneer u de `<img>` -versie gebruikt, bevat de gerenderde HTML een gegenereerde div-wrapper rond de `<img>` -tag. Deze wordt ingesteld op class.&quot;mktoImg.mktoGen,&quot;en zal vertoning :inline-block zijn.

## Formulier {#form}

Voorbeeld :Required kenmerken:
**klasse**: &quot;mktoForm&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

`<div class="mktoForm" id="exampleForm" mktoName="Example Form"></div>`

## Fragment {#snippet}

Vereiste kenmerken:
**klasse**: &quot;mktoSnippet&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<div class="mktoSnippet" id="exampleSnippet" mktoName="Example Snippet"></div>`

## Knop Delen {#share-button}

Vereiste kenmerken:
**klasse**: &quot;mktoShareButton&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<div class="mktoShareButton" id="exampleShareButton" mktoName="Example Share Button"></div>`

## Video {#video}

>[!NOTE]
>
>Marketo ondersteunt alleen video&#39;s van YouTube wanneer het video-element op een openingspagina wordt gebruikt. Als u een andere service gebruikt, is het raadzaam een RTF-vak te gebruiken en in de insluitcode van de video te plakken.

Vereiste kenmerken:
**klasse**: &quot;mktoVideo&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<div class="mktoVideo" id="exampleVideo" mktoName="Example Video"></div>`

## Pollen {#poll}

Vereiste kenmerken:
**klasse**: &quot;mktoPoll&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<div class="mktoPoll" id="examplePoll" mktoName="Example Poll"></div>`

## Verwijzing {#referral}

Vereiste kenmerken:
**klasse**: &quot;mktoReferral&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<div class="mktoReferral" id="exampleReferral" mktoName="Example Referral"></div>`

## Sweepstake {#sweepstakes}

Vereiste kenmerken:
**klasse**: &quot;mktoSweepstakes&quot;
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Voorbeeld:

`<div class="mktoSweepstakes" id="exampleSweepstakes" mktoName="Example Sweepstakes"></div>`

## Bewerkbare variabelen {#editable-variables}

Alle variabeletypen worden gebruikt door naar de waarde van hun attribuut id te verwijzen dat binnen van een ${} karakteropeenvolging wordt verpakt. Ze kunnen overal in het document worden gebruikt, behalve binnen in andere declaraties van variabelen.

Voorbeeld:

`${var1}`

**Verklaring:**

Variabelen worden gedeclareerd als metatags binnen het element `<head>` van de sjabloon. Er zijn drie typen variabelen beschikbaar voor gebruik: String, Color en Boolean.

## String {#string}

Vereiste kenmerken:
**klasse** : &quot;mktoString&quot;,
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:
**gebrek**: De waarde van het koord voor de attributen. Blanco als er geen informatie is opgegeven.
**allowHtml**: &quot;waar&quot;of &quot;vals&quot;. Bepaalt of de waarde wordt afgedrukt zonder dat HTML wordt beschermd. De standaardwaarde is &quot;false&quot; als de instelling wordt ongedaan gemaakt.

Basisvoorbeeld:

`<meta class="mktoString" id="var1" mktoName="My Variable">`

Voorbeeld met alle kenmerken:

`<meta class="mktoString" id="var1" mktoName="My Variable" default="This is my default value" allowHtml="true">`

## Kleur {#color}

Vereiste kenmerken:
**klasse** : &quot;mktoColor&quot;,
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:
**gebrek**: Een 7-cijferige het karakterkleurcode van de HEX. Bijvoorbeeld: &quot;#336699&quot;

Basisvoorbeeld:

`<meta class="mktoColor" id="color1" mktoName="My Color Variable">`

Voorbeeld met alle kenmerken:

`<meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699">`

## Boolean {#boolean}

Vereiste kenmerken:
**klasse** : &quot;mktoBoolean&quot;,
**identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
**mktoName** : Koord. Dit is de vertoningsnaam die in de het landen paginaredacteur zal worden getoond. U kunt het beste een beschrijvende naam gebruiken.

Optioneel:
**gebrek**: Het koord van Boolean. &quot;true&quot; of &quot;false&quot; als de waarde begint in de aan- of uit-positie. &quot;false&quot; indien niet opgegeven.
**false_value**: Koord. De waarde die voor de variabele moet worden ingevoegd wanneer deze zich in de uitstand bevindt. &quot;false&quot; indien niet opgegeven.
**true_value**: Koord. De waarde die voor de variabele moet worden ingevoegd wanneer deze zich op de positie ON bevindt. &quot;true&quot; indien niet opgegeven.
**false_value_name**: Koord. De weergavenaam die wordt weergegeven in de editor voor de bestemmingspagina wanneer de waarde in de uitstand staat. &quot;OFF&quot; indien niet opgegeven.
**true_value_name**: Koord. De weergavenaam die wordt weergegeven in de editor voor de bestemmingspagina wanneer de waarde zich op de positie ON bevindt. &quot;ON&quot; indien niet opgegeven.

Basisvoorbeeld:

`<meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699">`

`<meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable">`

Voorbeeld met alle kenmerken:

In dit voorbeeld wordt een veelvoorkomend geval getoond waarin een Booleaanse variabele de zichtbaarheid van een CSS-element regelt door de waarde van de CSS-weergave-eigenschap in te stellen op &quot;block&quot; of &quot;none&quot; om een element met id weer te geven/te verbergen. In de editor van de bestemmingspagina wordt de weergavenaam Tonen/Verbergen gebruikt in plaats van UIT/ON.

`<meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable" default="true" true_value="block" false_value="none" false_value_name="Hide" true_value_name="Show"> <style> #myConditionalDisplayArea { display: ${boolean1}; } </style>`

>[!NOTE]
>
>Programmatokens (my.token) kunnen ook overal worden gebruikt op bestemmingspagina&#39;s met instructies of vrije vorm.
