---
unique-page-id: 11371040
description: E-mailsjabloonsyntaxis - Marketo Docs - Productdocumentatie
title: E-mailsjabloonsyntaxis
exl-id: 84d6c0a8-1108-4b7e-8b4f-ac0682c6bdbb
feature: Email Editor
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '2449'
ht-degree: 0%

---

# E-mailsjabloonsyntaxis {#email-template-syntax}

In de nieuwe Marketo 2.0-ervaring bestaan e-mailsjablonen uit een willekeurige combinatie van elementen, variabelen, modules of containers. Elk object wordt gedefinieerd door Marketo-specifieke syntaxis toe te voegen aan uw HTML. Oude (v1.0) e-mailsjablonen worden ondersteund in E-maileditor 2.0, maar ze bevatten niet alle functies van de nieuwe Editor.

De e-mailsyntaxis van Marketo werkt slechts in malplaatjes en individuele e-mails; het werkt **niet** als ingebed in fragmenten of de tokens van de Tekst van de Rich.

>[!NOTE]
>
>Marketo Support is niet ingesteld als hulpmiddel bij CSS/HTML. Raadpleeg uw ontwikkelaar als u niet bekend bent met CSS/HTML.

>[!CAUTION]
>
>Klassewaarden met Marketo-syntaxis (d.w.z. mktoModule, mktoContainer, mktoText) zijn hoofdlettergevoelig. Namen van aangepaste kenmerken (mktoimgwidth, mktoname) zijn dit niet.

## Elementen {#elements}

Elementen zijn inhoudsgebieden die u in uw e-mailsjabloon definieert als bewerkbaar. De bewerkingservaring van een element is uniek voor het type element en biedt een eenvoudige manier om met inhoud te werken. De mogelijke elementen die in een e-mailsjabloon kunnen worden opgenomen zijn:

* RTF
* Afbeeldingen
* Fragmenten
* Video&#39;s

## RTF {#rich-text}

Als u een gebied als Rijke Tekst bepaalt, zullen de gebruikers zijn inhoud [&#x200B; kunnen uitgeven gebruikend de Redacteur van de Tekst van de RTF van Marketo Rich &#x200B;](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md). Er zijn twee manieren om een Rich Text-element in een e-mailsjabloon te definiëren: mktEditable en mktoText. Een Rich Text-element kan altijd vanuit de e-maileditor worden omgezet in een fragment.

### Optie 1 - marktEditable {#option-mkteditable}

Omdat e-maileditor 2.0 compatibel is met oudere versies, kunnen rijke tekstelementen worden opgegeven door class=&quot;mktEditable&quot; toe te voegen aan elk HTML-element. Dit wordt nog steeds ondersteund en de id van het element is de id die wordt gebruikt als de weergavenaam in de e-maileditor.

Vereiste kenmerken

* **klasse**: &quot;mktEditable&quot;.
* **identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.

Optionele kenmerken

* **mktoName** : Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde

De inhoud binnen het HTML-element (indien aanwezig) met class=&quot;mktEditable&quot; wordt gebruikt als standaardwaarde voor het Rich Text-element.

Voorbeeld:

`<div class="mktEditable" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div>`

### Optie 2 - mktoText {#option-mktotext}

Het wordt aanbevolen RTF-elementen op te geven met de syntaxis class=&quot;mktoText&quot;. Dit zorgt ervoor dat er altijd een juiste weergavenaam voor het element is.

Vereiste kenmerken

* **klasse**: &quot;mktoText&quot;
* **identiteitskaart**: Het koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName** : Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde

De inhoud binnen het HTML-element (indien aanwezig) met class=&quot;mktoText&quot; wordt gebruikt als standaardwaarde voor het Rich Text-element.

Voorbeeld:

`<div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div>`

## Afbeeldingen {#images}

U hebt twee opties om bewerkbare afbeeldingselementen te definiëren. U kunt een `<div>` -tag gebruiken, waarmee een container wordt opgegeven waarin `<img>` wordt ingevoegd, of een `<img>` -tag. Als de eindgebruiker gewoon een afbeelding wil kiezen die de afbeeldings-URL retourneert (in tegenstelling tot het DOM), raadpleegt u &quot;afbeeldingsvariabelen&quot; in de onderstaande sectie. Met de volgende twee opties wordt een HTML `<img>` -element ingevoegd.

### Optie 1 - Een `<div>` gebruiken {#option-use-a-div}

Vereiste kenmerken

* **klasse:** &quot;mktoImg&quot;.
* **identiteitskaart:** koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoImgClass:** Koord. De waarde hier wordt toegevoegd aan het klassenkenmerk van het element `<img>` binnen de div.
* **mktoImgSrc:** als standaardwaarde voor het beeld moet worden gebruikt dat binnen dit div wordt geplaatst. Er wordt een tijdelijke aanduiding gebruikt als deze wordt weggelaten.
* **mktoImgLink:** wijs erop dat `<img>` door een `<a>` markering met deze bestemmingsURL zou moeten worden omringd. De gebruiker kan dit wijzigen in de e-maileditor.
* **mktoImgLinkTarget:** wijs erop dat de `<a>` markering van het mktoImgLink attribuut dit doel zou moeten gebruiken. Heeft geen effect als mktoImgLink niet ook wordt gebruikt.
* **mktoImgWidth:** Gebruikt als breedte op ingesloten `<img>`.
* **mktoImgHeight:** Gebruikt als hoogte op ingesloten `<img>`.
* **mktoLockImgSize:** Gebruikt om het `<img>` bezit van de de hoogte en breedte van het element te ontgrendelen zodat de eindgebruiker kan wijzigen (gebrek is waar als weggelaten).
* **mktoLockImgStyle:** Gebruikt om het `<img>` de stijleigenschap van het element te sluiten (het gebrek is vals).

Standaardwaarde (optioneel)

**`<img>`**: te gebruiken als het `<img>` -element waarin de afbeelding wordt geplaatst. Nuttig als u inline opmaak aan de afbeelding wilt toevoegen. Denk eraan dat u de omringende `<a> </a>` -tags opneemt, dus als de gebruiker een koppeling toevoegt, wordt de opmaak niet verwijderd!

Voorbeeld:

`<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com"> <a><img style="border:10px solid red;"></a> </div>`

### Optie 2 - Een \&lt;img\> gebruiken {#option-use-an-img}

>[!NOTE]
>
>Met deze optie kunnen eindgebruikers geen koppeling naar hun afbeelding toevoegen. Gebruik Optie 1 als dit belangrijk is voor uw sjabloon.

Vereiste kenmerken

* **klasse:** &quot;mktoImg&quot;.
* **identiteitskaart:** koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.  Standaardwaarde (optioneel)
* **src:** als standaardwaarde voor het beeld worden gebruikt. Er wordt een tijdelijke aanduiding gebruikt als deze wordt weggelaten.
* **mktoLockImgSize:** Gebruikt om het `<img>` bezit van de de hoogte en breedte van het element te ontgrendelen zodat de eindgebruiker kan wijzigen (gebrek is waar als weggelaten).
* **mktoLockImgStyle:** Gebruikt om het `<img>` de stijleigenschap van het element te sluiten (het gebrek is vals).

Voorbeeld:
`<img class="mktoImg" id="exampleImg" mktoName="Example Image">`

## Fragmenten {#snippets}

Als u een gebied als Fragment bepaalt, zullen de eindgebruikers kunnen kiezen welk goedgekeurd [&#x200B; Fragment &#x200B;](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md) zij in dit gebied willen opnemen. Hoewel RTF-elementen vanuit de e-maileditor kunnen worden omgezet in fragmenten, kan een gebied dat u specifiek als een fragment definieert, niet worden omgezet in RTF-tekst. U kunt een fragmentgebied opgeven met een `<div>` met class=&quot;mktoSnippet&quot;

Vereiste kenmerken

* **identiteitskaart:** koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde (optioneel)

**mktoDefaultSnippetId**: De numerieke identiteitskaart van het Fragment van Marketo dat door gebrek zou moeten verschijnen (zal slechts werken als een Fragment met die identiteitskaart bestaat en in die werkruimte goedgekeurd is).

Voorbeeld:

`<div class="mktoSnippet" id="unsubscribeFooter" mktoName="Unsubscribe Footer" mktoDefaultSnippetId="12"></div>`

## Video {#video}

Als u een gebied definieert als een video, kunnen eindgebruikers een YouTube- of Vimeo-URL invoegen die wordt weergegeven als een miniatuurafbeelding (met de knop Afspelen) in de e-mail. U kunt een videogebied opgeven met een `<div>` met class=&quot;mktoVideo&quot;

Vereiste kenmerken

* **identiteitskaart:** koord van identiteitskaart Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoImgClass:** Koord. De waarde wordt hier toegevoegd aan het klassenkenmerk van de videominiatuur `<img>` in het div-element.

Voorbeeld:

`<div class="mktoVideo" id="productVideo" mktoName="Product Announcement Video"></div>`

## Variabelen {#variables}

Variabelen zijn vergelijkbaar met tokens. U definieert ze eerst binnen de sectie `<head>` van uw e-mailsjabloon met `<meta>` -tags en gebruikt ze vervolgens zo vaak als u wilt in de hele sjabloon. Omdat zij in het malplaatje worden bepaald, zal de eindgebruiker hun waarden volgens hun regels kunnen wijzigen. Merk op dat u een variabele als lokaal of globaal in werkingsgebied kunt bepalen. Als u een variabele binnen een &quot;Module&quot;gebruikt (zie hieronder), en een eindgebruiker die module dupliceert, zullen de lokale variabelen onafhankelijke waarden hebben, terwijl globale variabelen op beide modules van toepassing zullen zijn.

## String {#string}

Als u een variabele opgeeft als een tekenreeks, kan de eindgebruiker tekst invoeren in een tekstvak in de e-maileditor. U geeft een tekenreeksvariabele op met `<meta>` with class=&quot;mktoString&quot;

Vereiste kenmerken

* **identiteitskaart:** hoe u de variabele binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName:** Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **allowHTML:** Van Boole. Controls if the variable&#39;s value is HTML-escaped. De standaardwaarde is False als dit wordt weggelaten.
* **gebrek**: Standaardwaarde voor het koord. Blanco indien weggelaten.
* **mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<meta class="mktoString" id="textHeader" mktoName="Text Header" default="Edit Me">`

Voorbeeld:

`${textHeader}`

## Lijst {#list}

Als u een variabele opgeeft als een List, kan de eindgebruiker kiezen uit een set waarden die u in de e-maileditor definieert. U geeft een variabele List op met `<meta>` with class=&quot;mktoList&quot;

Vereiste kenmerken

* **identiteitskaart**: Hoe u de variabele binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName:** Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.
* **waarden:** komma gescheiden lijst van waarden. Moet ten minste één tekenreeks hebben.

Optionele kenmerken

* **gebrek:** Standaardwaarde van uitgezochte dropdown. Indien weggelaten, wordt de eerste waarde van het kenmerk &quot;values&quot; gebruikt.
* **mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<meta class="mktoList" id="textFontFamily" mktoName="Main Text Font Family" values="Arial,Verdana,Times New Roman">`

Voorbeeld:

`${textFontFamily}`

## Getal {#number}

Als u een variabele opgeeft als een Getal, kan de eindgebruiker een getal invoeren in de e-maileditor. U geeft een variabele Number op met `<meta>` with class=&quot;mktoNumber&quot;

Vereiste kenmerken

* **identiteitskaart**: Hoe u de variabele binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName**: Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.
* **gebrek:** Standaard numerieke waarde voor de variabele.

Optionele kenmerken

* **min:** Min toegelaten waarde.
* **maximum:** Max toegelaten waarde.
* **eenheden:** eenheden die aan de aantalwaarde (ex: px, pt, em, enz.) moeten worden toegevoegd wanneer getoond in de E-mailredacteur, evenals in de resulterende code.
* **stap:** hoeveel eenheden de aantalvariabele zou moeten verhogen/verminderen door (0.1, 1, 10, enz.). Als deze waarde wordt weggelaten, wordt standaard ingesteld op 1.
* **mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<meta class="mktoNumber" id="textFontSize" mktoName="Main Text Font Size" default="12" min="8" max="18" units="px" step="1">`

Voorbeeld:

`${textFontSize}`

## Kleur {#color}

Als u een variabele opgeeft als een kleur, kan de eindgebruiker een hexadecimale kleurwaarde invoeren of een kleur kiezen in de kleurkiezer in de e-maileditor. U geeft een kleurvariabele op met `<meta>` with class=&quot;mktoColor&quot;

Vereiste kenmerken

* **identiteitskaart**: Hoe u de variabele binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName**: Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **gebrek:** Standaardwaarde voor de kleur. Hexadecimale 6-cijferige kleurcode. Voorbeeld: #ffffff.
* **mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<meta class="mktoColor" id="textColor" mktoName="Main Text Color" default="#FFFFFF">`

Voorbeeld:

`${textColor}`

## Boolean {#boolean}

Als u een variabele opgeeft als een Booleaanse waarde, kan de eindgebruiker de optie in- en uitschakelen in de e-maileditor. U geeft een Booleaanse variabele op met `<meta>` with class=&quot;mktoBoolean&quot;

Vereiste kenmerken

* **identiteitskaart**: Hoe u de variabele binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName**: Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **gebrek:** waarde Van Boole die de standaardstaat van de knevelschakelaar bepaalt. Onwaar indien weggelaten.
* **false_value:** Waarde die moet worden opgenomen wanneer de knevel in OFF positie is. Onwaar indien weggelaten.
* **true_value:** Waarde die moet worden opgenomen wanneer de knevel in OP positie is. Waar als weggelaten.
* **false_value_name:** UI die in knevel wordt getoond wanneer in uit positie. Onwaar indien weggelaten.
* **true_value_name:** UI die in knevel wordt getoond wanneer binnen op positie. Waar als weggelaten.
* **mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<meta class="mktoBoolean" id="showFooter" mktoName="Show Footer BG?" default="false" false_value="transparent" true_value="black" false_value_name="NO" true_value_name="YES">`

Voorbeeld:

`${showFooter}`

## HTML Block {#html-block}

Als u een variabele opgeeft als een HTML Block, kan de eindgebruiker letterlijk HTML invoeren in de e-maileditor. U geeft een HTML Block-variabele op met `<meta>` with class=&quot;mktoHTML&quot;

Vereiste kenmerken

* **identiteitskaart**: Hoe u de variabele binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName**: Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **gebrek:** HTML gecodeerde waarde om als standaardinhoud van het blok te dienen.
* **mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<meta class="mktoHTML" id="trackingPixel" mktoName="Add Tracking Pixel">`

Voorbeeld:

`${trackingPixel}`

## Afbeeldingsvariabele {#image-variable}

Als u een variabele opgeeft als een afbeelding, kan de eindgebruiker een afbeelding kiezen in de afbeeldingskiezer in de e-maileditor. De geselecteerde afbeeldings-URL is de waarde van de variabele. U geeft een afbeeldingsvariabele op met `<meta>` with class=&quot;mktoImg&quot;

Vereiste kenmerken

* **identiteitskaart**: Hoe u de variabele binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName**: Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **gebrek:** Standaard beeld URL voor het element.
* **mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<meta class="mktoImg" id="heroBackgroundImage" mktoName="Hero Background Image" default="https://www.company.com/image.jpg">`

Voorbeeld:

`${heroBackgroundImage}`

## Modules {#modules}

Modules zijn sjabloonsecties die op sjabloonniveau zijn gedefinieerd en die worden weergegeven zodat eindgebruikers deze in hun e-mail kunnen invoegen. Omdat u deze modules vooraf hebt gemaakt, kunt u ervoor zorgen dat ze netjes communiceren met de rest van uw e-mailinhoud (op een volledig reagerende manier). U kunt een module alleen in een container plaatsen.

>[!IMPORTANT]
>
>Wanneer een e-mail van een e-mailmalplaatje wordt geproduceerd dat bepaalde modulecomponenten bevat, zullen om het even welke veranderingen die aan de modules van het malplaatje worden aangebracht **niet** worden geduwd aan bovengenoemde e-mail.

**voor containers van type `<table>`, `<tbody>`, `<thead>`, of `<tfoot>`:**

Opgegeven met `<tr>` with class=&quot;mktoModule&quot;

**voor containers van type `<td>`:**

Opgegeven met `<table>` with class=&quot;mktoModule&quot;

Vereiste kenmerken

* **identiteitskaart**: Hoe u de module binnen uw e-mailmalplaatje van verwijzingen voorziet.
* **mktoName**: Koord. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoActive:** bepaalt of deze module in de lijst van modules binnen de e-mailredacteur verschijnt. Heeft als standaardwaarde true. Indien onwaar, kan de module niet door een eindgebruiker aan een e-mail worden toegevoegd.
* **mktoAddByDefault:** bepaalt of deze module in het canvas van een nieuwe e-mail zal zijn die dit malplaatje op verwezenlijking gebruikt. De standaardwaarde is true (als mktoActive false is, wordt deze waarde genegeerd).

>[!NOTE]
>
>Klassewaarden met Marketo-syntaxis (d.w.z. mktoModule, mktoContainer, mktoText) zijn hoofdlettergevoelig. Namen van aangepaste kenmerken (mktoimgwidth, mktoname) zijn dit niet.

## Containers {#containers}

Een container houdt Modules en bepaalt waar zij kunnen worden geplaatst. Wanneer eindgebruikers modules opnieuw bestellen en in hun e-mail opnemen, controleert de container waar zij kunnen gaan.

**specificeerde gebruikend of `<table>`, `<tbody>`, `<thead>`, `<tfoot>` of `<td>` met class= &quot;mktoContainer&quot;**

Vereiste kenmerken

**identiteitskaart**: Hoe u de module binnen uw e-mailmalplaatje van verwijzingen voorziet.

>[!CAUTION]
>
>De containers kunnen slechts modules-bevatten als er iets anders aanwezig is, wordt de Container beschouwd ongeldig! Per sjabloon is slechts één container toegestaan.
