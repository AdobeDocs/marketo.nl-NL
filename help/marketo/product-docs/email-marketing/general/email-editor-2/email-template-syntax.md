---
unique-page-id: 11371040
description: E-mailsjabloonsyntaxis - Marketo Docs - Productdocumentatie
title: E-mailsjabloonsyntaxis
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '2395'
ht-degree: 0%

---


# Syntaxis e-mailsjabloon {#email-template-syntax}

In de nieuwe e-mailervaring van Marketo 2.0 bestaan e-mailsjablonen uit een willekeurige combinatie van elementen, variabelen, modules of containers. Elk wordt bepaald door Marketo-specifieke syntaxis aan uw HTML toe te voegen. Oude (v1.0) e-mailsjablonen worden ondersteund in E-maileditor 2.0; echter, zullen zij niet alle eigenschappen van de nieuwe Redacteur omvatten.

Marketo-e-mailsyntaxis werkt alleen in sjablonen en afzonderlijke e-mails. het werkt **niet** als ingebed in fragmenten of de tokens van de RTF.

>[!NOTE]
>
>Ondersteuning voor Marketo is niet ingesteld als hulpmiddel bij CSS/HTML. Raadpleeg uw ontwikkelaar als u niet bekend bent met CSS/HTML.

>[!CAUTION]
>
>Klassewaarden met de syntaxis Marketo (d.w.z. mktoModule, mktoContainer, mktoText) zijn hoofdlettergevoelig. Namen van aangepaste kenmerken (mktoimgwidth, mktoname) zijn dit niet.

## Elementen {#elements}

Elementen zijn inhoudsgebieden die u in uw e-mailsjabloon definieert als bewerkbaar. De bewerkingservaring van een element is uniek voor het type element en biedt een eenvoudige manier om met inhoud te werken. De mogelijke elementen die in een e-mailsjabloon kunnen worden opgenomen zijn:

* RTF
* Afbeeldingen
* Fragmenten
* Video&#39;s

## RTF {#rich-text}

Als u een gebied als RTF bepaalt, zullen de gebruikers zijn inhoud [kunnen uitgeven gebruikend de Rich Text Editor van de Tekst van de Marketo](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md). Er zijn twee manieren om een Rich Text-element binnen een e-mailsjabloon te definiëren: mktEditable en mktoText. Een Rich Text-element kan altijd vanuit de e-maileditor worden omgezet in een fragment.

### Optie 1 - MktEditable {#option-mkteditable}

Omdat e-maileditor 2.0 compatibel is met oudere versies, kunnen rijke tekstelementen worden opgegeven door class=&quot;mktEditable&quot; toe te voegen aan een willekeurig HTML-element. Dit wordt nog steeds ondersteund en de id van het element is de id die wordt gebruikt als weergavenaam in de e-maileditor.

Vereiste kenmerken

* **klasse**: &quot;mktEditable&quot;.
* **id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.

Optionele kenmerken

* **mktoName** : Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde

De inhoud binnen het HTML-element (indien aanwezig) met class=&quot;mktEditable&quot; wordt gebruikt als standaardwaarde voor het Rich Text-element.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktEditable" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>`

### Optie 2 - mktoText {#option-mktotext}

Het wordt aanbevolen RTF-elementen op te geven met de syntaxis class=&quot;mktoText&quot;. Dit zorgt ervoor dat er altijd een juiste weergavenaam voor het element is.

Vereiste kenmerken

* **klasse**: &quot;mktoText&quot;
* **id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName** : Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde

De inhoud binnen het HTML-element (indien aanwezig) met class=&quot;mktoText&quot; wordt gebruikt als standaardwaarde voor het Rich Text-element.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>`

## Afbeeldingen {#images}

U hebt twee opties om bewerkbare afbeeldingselementen te definiëren. U kunt een `<div>` gebruiken, die een container specificeert dat `<img>` in, of een `<img>` markering zal worden opgenomen. Als de eindgebruiker gewoon een afbeelding wil kiezen die de afbeeldings-URL retourneert (in tegenstelling tot het DOM), raadpleegt u &quot;afbeeldingsvariabelen&quot; in de onderstaande sectie. Met de volgende twee opties wordt een HTML `<img>`-element ingevoegd.

### Optie 1 - Gebruik een `<div>` {#option-use-a-div}

Vereiste kenmerken

* **klasse:** &quot;mktoImg&quot;.
* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName :** String. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoImgClass:** String. De waarde hier zal aan de klassenattributen van het `<img>` element binnen div worden toegevoegd.
* **mktoImgSrc:** Te gebruiken als standaardwaarde voor de afbeelding die binnen dit div-element wordt geplaatst. Er wordt een tijdelijke aanduiding gebruikt als deze wordt weggelaten.
* **mktoImgLink:** Geef aan dat de URL  `<img>` moet worden omringd door een  `<a>` tag met deze doel-URL. De gebruiker kan dit wijzigen in de e-maileditor.
* **mktoImgLinkTarget:** Geef aan dat de  `<a>` tag van het kenmerk mktoImgLink dit doel moet gebruiken. Heeft geen effect als mktoImgLink niet ook wordt gebruikt.
* **mktoImgWidth:** Gebruikt als breedte op ingesloten  `<img>`.
* **mktoImgHeight:** Wordt gebruikt als de hoogte op de ingesloten ruimte  `<img>`.
* **mktoLockImgSize:** Gebruikt om het de hoogte en breedte bezit van het  `<img>` element te ontgrendelen zodat de eindgebruiker kan wijzigen (gebrek is waar als weggelaten).
* **mktoLockImgStyle:** Wordt gebruikt om de stijleigenschap van het  `<img>` element te vergrendelen (de standaardwaarde is false).

Standaardwaarde (optioneel)

**`<img>`**: Te gebruiken als het  `<img>` element waarin de afbeelding wordt geplaatst. Nuttig als u inline opmaak aan de afbeelding wilt toevoegen. Denk eraan dat u de omringende `<a> </a>`-tags opneemt, dus als de gebruiker een koppeling toevoegt, wordt de opmaak niet verwijderd!

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com"> <a><img style="border:10px solid red;"></a> </div></pre>`

### Option 2 - Een \&lt;img\> {#option-use-an-img} gebruiken

>[!NOTE]
>
>Met deze optie kunnen eindgebruikers geen koppeling naar hun afbeelding toevoegen. Gebruik Optie 1 als dit belangrijk is voor uw sjabloon.

Vereiste kenmerken

* **klasse:** &quot;mktoImg&quot;.
* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** String. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.  Standaardwaarde (optioneel)
* **src:** Te gebruiken als standaardwaarde voor de afbeelding. Er wordt een tijdelijke aanduiding gebruikt als deze wordt weggelaten.
* **mktoLockImgSize:** Gebruikt om het de hoogte en breedte bezit van het  `<img>` element te ontgrendelen zodat de eindgebruiker kan wijzigen (gebrek is waar als weggelaten).
* **mktoLockImgStyle:** Wordt gebruikt om de stijleigenschap van het  `<img>` element te vergrendelen (de standaardwaarde is false).

Voorbeeld:
`<pre data-theme="Confluence"><img class="mktoImg" id="exampleImg" mktoName="Example Image"></pre>`

## Fragmenten {#snippets}

Als u een gebied definieert als een fragment, kunnen eindgebruikers kiezen welk goedgekeurd [Fragment](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md)zij in dit gebied willen invoegen. Hoewel RTF-elementen vanuit de e-maileditor kunnen worden omgezet in fragmenten, kan een gebied dat u specifiek als een fragment definieert, niet worden omgezet in RTF-tekst. U kunt een fragmentgebied opgeven met een `<div>` met class=&quot;mktoSnippet&quot;

Vereiste kenmerken

* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** String. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde (optioneel)

**mktoDefaultSnippetId**: De numerieke id van het Marketo-fragment dat standaard moet worden weergegeven (werkt alleen als een fragment met die id bestaat en in die werkruimte is goedgekeurd).

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoSnippet" id="unsubscribeFooter" mktoName="Unsubscribe Footer" mktoDefaultSnippetId="12"></div></pre>`

## Video {#video}

Als u een gebied definieert als een video, kunnen eindgebruikers een YouTube- of Vimeo-URL invoegen die als miniatuurafbeelding (met de knop Afspelen) in de e-mail wordt weergegeven. U kunt een videogebied opgeven met een `<div>` met class=&quot;mktoVideo&quot;

Vereiste kenmerken

* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** String. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoImgClass:** String. De waarde hier wordt toegevoegd aan het klassenkenmerk van de videominiatuur `<img>` in het div-element.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoVideo" id="productVideo" mktoName="Product Announcement Video"></div></pre>`

## Variabelen {#variables}

Variabelen zijn als tokens. U definieert ze eerst binnen de sectie `<head>` van uw e-mailsjabloon met `<meta>`-tags en gebruikt ze vervolgens zo vaak als u wilt in de hele sjabloon. Omdat de waarden in de sjabloon zijn gedefinieerd, kan de eindgebruiker de waarden volgens zijn eigen regels wijzigen. Merk op dat u een variabele als lokaal of globaal in werkingsgebied kunt bepalen. Als u een variabele binnen een &quot;Module&quot;gebruikt (zie hieronder), en een eindgebruiker die module dupliceert, zullen de lokale variabelen onafhankelijke waarden hebben, terwijl globale variabelen op beide modules van toepassing zullen zijn.

## Tekenreeks {#string}

Als u een variabele opgeeft als een tekenreeks, kan de eindgebruiker tekst invoeren in een tekstvak in de e-maileditor. U geeft een tekenreeksvariabele op met `<meta>` met class=&quot;mktoString&quot;

Vereiste kenmerken

* **id:** Hoe u naar de variabele in uw e-mailsjabloon verwijst.
* **mktoName:** String. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **allowHTML :** Boolean. Controls if the variable&#39;s value is HTML-escaped. De standaardwaarde is False als dit wordt weggelaten.
* **standaard**: Standaardwaarde voor de tekenreeks. Blanco indien weggelaten.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoString" id="textHeader" mktoName="Text Header" default="Edit Me"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textHeader}</pre>`

## Lijst {#list}

Als u een variabele opgeeft als een List, kan de eindgebruiker kiezen uit een set waarden die u in de e-maileditor definieert. U geeft een variabele List op met `<meta>` met class=&quot;mktoList&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName:** String. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.
* **waarden:door** komma&#39;s gescheiden lijst met waarden. Moet ten minste één tekenreeks hebben.

Optionele kenmerken

* **standaard:** standaardwaarde van het geselecteerde vervolgkeuzemenu. Indien weggelaten, wordt de eerste waarde van het kenmerk &quot;values&quot; gebruikt.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoList" id="textFontFamily" mktoName="Main Text Font Family" values="Arial,Verdana,Times New Roman"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textFontFamily}</pre>`

## Getal {#number}

Als u een variabele opgeeft als een Getal, kan de eindgebruiker een getal invoeren in de e-maileditor. U geeft een variabele Number op met `<meta>` met class=&quot;mktoNumber&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.
* **standaard:** numerieke standaardwaarde voor de variabele.

Optionele kenmerken

* **min:** Min geaccepteerde waarde.
* **max:** Maximaal toegestane waarde.
* **eenheden:** eenheden die aan de getalwaarde moeten worden toegevoegd (bijv. px, pt, em, enz.) in de e-maileditor en in de resulterende code worden weergegeven.
* **stap:** Hoeveel eenheden de getalvariabele moet verhogen/verlagen met (0,1, 1, 10, enz.). Als deze waarde wordt weggelaten, wordt standaard ingesteld op 1.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoNumber" id="textFontSize" mktoName="Main Text Font Size" default="12" min="8" max="18" units="px" step="1"> </pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textFontSize}</pre>`

## Kleur {#color}

Als u een variabele opgeeft als een kleur, kan de eindgebruiker een hexadecimale kleurwaarde invoeren of een kleur kiezen in de kleurkiezer in de e-maileditor. U geeft een kleurvariabele op met `<meta>` met class=&quot;mktoColor&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaardwaarde:** standaardwaarde voor de kleur. Hexadecimale 6-cijferige kleurcode. Voorbeeld: #ffffff.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoColor" id="textColor" mktoName="Main Text Color" default="#FFFFFF"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textColor}</pre>`

## Booleaans {#boolean}

Als u een variabele opgeeft als een Booleaanse waarde, kan de eindgebruiker de optie in- en uitschakelen in de e-maileditor. U geeft een Booleaanse variabele op met `<meta>` met class=&quot;mktoBoolean&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaard:** Booleaanse waarde die de standaardstatus van de schakeloptie bepaalt. Onwaar indien weggelaten.
* **false_value:** Waarde die moet worden ingevoegd wanneer de schakeloptie uit-positie is. Onwaar indien weggelaten.
* **true_value:** Waarde die moet worden ingevoegd wanneer de schakeloptie zich op de ON-positie bevindt. Waar als weggelaten.
* **false_value_name:** UI getoond in knevel wanneer in OFF positie. Onwaar indien weggelaten.
* **true_value_name:** UI getoond in de knevel wanneer op positie. Waar als weggelaten.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="showFooter" mktoName="Show Footer BG?" default="false" false_value="transparent" true_value="black" false_value_name="NO" true_value_name="YES"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${showFooter}</pre>`

## HTML-blok {#html-block}

Als u een variabele opgeeft als een HTML-blok, kan de eindgebruiker letterlijke HTML invoeren in de e-maileditor. U kunt een variabele van het Blok van HTML specificeren gebruikend `<meta>` met class=&quot;mktoHTML&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaard:** HTML-gecodeerde waarde die als de standaardinhoud van het blok fungeert.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoHTML" id="trackingPixel" mktoName="Add Tracking Pixel"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${trackingPixel}</pre>`

## Afbeeldingsvariabele {#image-variable}

Als u een variabele opgeeft als een afbeelding, kan de eindgebruiker een afbeelding kiezen in de afbeeldingskiezer in de e-maileditor. De geselecteerde afbeeldings-URL is de waarde van de variabele. U geeft een afbeeldingsvariabele op met `<meta>` met class=&quot;mktoImg&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaard:** standaardafbeeldings-URL voor het element.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoImg" id="heroBackgroundImage" mktoName="Hero Background Image" default="https://www.company.com/image.jpg"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${heroBackgroundImage}</pre>`

## Modules {#modules}

Modules zijn sjabloonsecties die op sjabloonniveau zijn gedefinieerd en die worden weergegeven zodat eindgebruikers deze in hun e-mail kunnen invoegen. Omdat u deze modules vooraf hebt gemaakt, kunt u ervoor zorgen dat ze netjes communiceren met de rest van uw e-mailinhoud (op een volledig reagerende manier). U kunt een module alleen in een container plaatsen.

**Voor containers van het type  `<table>`,  `<tbody>`,  `<thead>`of  `<tfoot>`:**

Opgegeven met `<tr>` met class=&quot;mktoModule&quot;

**Voor containers van het type  `<td>`:**

Opgegeven met `<table>` met class=&quot;mktoModule&quot;

Vereiste kenmerken

* **id**: Hoe u in uw e-mailsjabloon naar de module verwijst.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoActive:** Bepaalt of deze module in de lijst van modules binnen de e-mailredacteur verschijnt. Heeft als standaardwaarde true. Indien onwaar, kan de module niet door een eindgebruiker aan een e-mail worden toegevoegd.
* **mktoAddByDefault:** Hiermee wordt bepaald of deze module zich op het canvas bevindt van een nieuwe e-mail waarin deze sjabloon bij het maken wordt gebruikt. De standaardwaarde is true (als mktoActive false is, wordt deze waarde genegeerd).

>[!NOTE]
>
>Klassewaarden met de syntaxis Marketo (d.w.z. mktoModule, mktoContainer, mktoText) zijn hoofdlettergevoelig. Namen van aangepaste kenmerken (mktoimgwidth, mktoname) zijn dit niet.

## Containers {#containers}

Een container houdt Modules en bepaalt waar zij kunnen worden geplaatst. Wanneer eindgebruikers modules opnieuw bestellen en in hun e-mail opnemen, controleert de container waar zij kunnen gaan.

**Opgegeven met  `<table>`,  `<tbody>`,  `<thead>`of  `<tfoot>`   `<td>` met class=&quot;mktoContainer&quot;**

Vereiste kenmerken

**id**: Hoe u in uw e-mailsjabloon naar de module verwijst.

>[!CAUTION]
>
>De containers kunnen slechts modules-bevatten als er iets anders aanwezig is, wordt de Container beschouwd ongeldig! Per sjabloon is slechts één container toegestaan.
