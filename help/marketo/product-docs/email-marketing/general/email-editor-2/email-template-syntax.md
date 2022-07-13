---
unique-page-id: 11371040
description: E-mailsjabloonsyntaxis - Marketo Docs - Productdocumentatie
title: E-mailsjabloonsyntaxis
exl-id: 84d6c0a8-1108-4b7e-8b4f-ac0682c6bdbb
source-git-commit: a59b6b2505c6e5a83c6137a1925aa4e60e56eac8
workflow-type: tm+mt
source-wordcount: '2423'
ht-degree: 0%

---

# E-mailsjabloonsyntaxis {#email-template-syntax}

In de nieuwe Marketo 2.0-ervaring bestaan e-mailsjablonen uit een willekeurige combinatie van elementen, variabelen, modules of containers. Elk wordt bepaald door Marketo-specifieke syntaxis aan uw HTML toe te voegen. Oude (v1.0) e-mailsjablonen worden ondersteund in E-maileditor 2.0; echter, zullen zij niet alle eigenschappen van de nieuwe Redacteur omvatten.

De Marketo-syntaxis voor e-mail werkt alleen in sjablonen en afzonderlijke e-mails. het **niet** werken als deze zijn ingesloten in fragmenten of RTF-tokens.

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

Als u een gebied definieert als RTF-tekst, kunnen gebruikers de inhoud ervan bewerken [Marketo Rich Text Editor gebruiken](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md). Er zijn twee manieren om een Rich Text-element binnen een e-mailsjabloon te definiëren: mktEditable en mktoText. Een Rich Text-element kan altijd vanuit de e-maileditor worden omgezet in een fragment.

### Optie 1 - marktEditable {#option-mkteditable}

Omdat e-maileditor 2.0 compatibel is met oudere versies, kunnen sommige oude e-mailsjablonen tekstelementen met tekstopmaak opgeven door class=&quot;mktEditable&quot; toe te voegen aan elk HTML-element. Dit wordt nog steeds ondersteund en de id van het element is de id die wordt gebruikt als weergavenaam in de e-maileditor.

Vereiste kenmerken

* **class**: &quot;mktEditable&quot;.
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

* **class**: &quot;mktoText&quot;
* **id**: ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName** : Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde

De inhoud binnen het HTML-element (indien aanwezig) met class=&quot;mktoText&quot; wordt gebruikt als standaardwaarde voor het Rich Text-element.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>`

## Afbeeldingen {#images}

U hebt twee opties om bewerkbare afbeeldingselementen te definiëren. U kunt beide `<div>`, die een container opgeeft die `<img>` wordt ingevoegd in, of `<img>` tag. Als de eindgebruiker gewoon een afbeelding wil kiezen die de afbeeldings-URL retourneert (in tegenstelling tot het DOM), raadpleegt u &quot;afbeeldingsvariabelen&quot; in de onderstaande sectie. De volgende twee opties voegen een HTML in `<img>` element.

### Optie 1 - Een `<div>` {#option-use-a-div}

Vereiste kenmerken

* **klasse:** &quot;mktoImg&quot;.
* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName :** Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoImgClass:** Tekenreeks. De waarde hier wordt toegevoegd aan het klassenkenmerk van het dialoogvenster `<img>` -element in het div-element.
* **mktoImgSrc:** Wordt gebruikt als standaardwaarde voor de afbeelding die binnen dit div-element wordt geplaatst. Er wordt een tijdelijke aanduiding gebruikt als deze wordt weggelaten.
* **mktoImgLink:** Geef aan dat de `<img>` moet worden omgeven door een `<a>` -tag met deze doel-URL. De gebruiker kan dit wijzigen in de e-maileditor.
* **mktoImgLinkTarget:** Geef aan dat de `<a>` -tag uit het kenmerk mktoImgLink moet dit doel gebruiken. Heeft geen effect als mktoImgLink niet ook wordt gebruikt.
* **mktoImgWidth:** Wordt gebruikt als de breedte op het omsluitende gebied `<img>`.
* **mktoImgHeight:** Wordt gebruikt als de hoogte op de omsloten ruimte `<img>`.
* **mktoLockImgSize:** Wordt gebruikt om de `<img>` de hoogte- en breedte-eigenschap van het element zodat de eindgebruiker deze kan wijzigen (de standaardinstelling is waar als deze wordt weggelaten).
* **mktoLockImgStyle:** Wordt gebruikt om het `<img>` de stijleigenschap van het element (de standaardwaarde is false).

Standaardwaarde (optioneel)

**`<img>`**: Te gebruiken als de `<img>` -element waarin de afbeelding wordt geplaatst. Nuttig als u inline opmaak aan de afbeelding wilt toevoegen. Omringende elementen opnemen `<a> </a>` -tags, dus als de gebruiker een koppeling toevoegt, wordt de stijl niet verwijderd!

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com"> <a><img style="border:10px solid red;"></a> </div></pre>`

### Optie 2 - Een \&lt;img> {#option-use-an-img}

>[!NOTE]
>
>Met deze optie kunnen eindgebruikers geen koppeling naar hun afbeelding toevoegen. Gebruik Optie 1 als dit belangrijk is voor uw sjabloon.

Vereiste kenmerken

* **klasse:** &quot;mktoImg&quot;.
* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.  Standaardwaarde (optioneel)
* **src:** Wordt gebruikt als standaardwaarde voor de afbeelding. Er wordt een tijdelijke aanduiding gebruikt als deze wordt weggelaten.
* **mktoLockImgSize:** Wordt gebruikt om de `<img>` de hoogte- en breedte-eigenschap van het element zodat de eindgebruiker deze kan wijzigen (de standaardinstelling is waar als deze wordt weggelaten).
* **mktoLockImgStyle:** Wordt gebruikt om het `<img>` de stijleigenschap van het element (de standaardwaarde is false).

Voorbeeld:
`<pre data-theme="Confluence"><img class="mktoImg" id="exampleImg" mktoName="Example Image"></pre>`

## Fragmenten {#snippets}

Als u een gebied definieert als een fragment, kunnen eindgebruikers kiezen welke goedgekeurd [Fragment](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md)ze willen graag in deze regio inbrengen . Hoewel RTF-elementen vanuit de e-maileditor kunnen worden omgezet in fragmenten, kan een gebied dat u specifiek als een fragment definieert, niet worden omgezet in RTF-tekst. U kunt een gebied van het Fragment specificeren gebruikend een `<div>` with class=&quot;mktoSnippet&quot;

Vereiste kenmerken

* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Standaardwaarde (optioneel)

**mktoDefaultSnippetId**: De numerieke id van het Marketo-fragment dat standaard moet worden weergegeven (werkt alleen als een fragment met die id bestaat en in die werkruimte is goedgekeurd).

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoSnippet" id="unsubscribeFooter" mktoName="Unsubscribe Footer" mktoDefaultSnippetId="12"></div></pre>`

## Video {#video}

Als u een gebied definieert als een video, kunnen eindgebruikers een YouTube- of Vimeo-URL invoegen die wordt weergegeven als een miniatuurafbeelding (met de knop Afspelen) in de e-mail. U kunt een videogebied opgeven met een `<div>` with class=&quot;mktoVideo&quot;

Vereiste kenmerken

* **id:** ID-tekenreeks. Bevat alleen letters, cijfers, streepje &quot;-&quot; en onderstrepingsteken &quot;_&quot;. Geen spaties toegestaan. Moet uniek zijn.
* **mktoName:** Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoImgClass:** Tekenreeks. De waarde hier wordt toegevoegd aan het klassenkenmerk van de videominiatuur `<img>` in de div.

Voorbeeld:

`<pre data-theme="Confluence"><div class="mktoVideo" id="productVideo" mktoName="Product Announcement Video"></div></pre>`

## Variabelen {#variables}

Variabelen zijn als tokens. U definieert deze eerst in het dialoogvenster `<head>` gedeelte van je e-mailtemplate met `<meta>` tags, en deze zo vaak als u wilt gebruiken in de hele sjabloon. Omdat de waarden in de sjabloon zijn gedefinieerd, kan de eindgebruiker de waarden volgens zijn eigen regels wijzigen. Merk op dat u een variabele als lokaal of globaal in werkingsgebied kunt bepalen. Als u een variabele binnen een &quot;Module&quot;gebruikt (zie hieronder), en een eindgebruiker die module dupliceert, zullen de lokale variabelen onafhankelijke waarden hebben, terwijl globale variabelen op beide modules van toepassing zullen zijn.

## String {#string}

Als u een variabele opgeeft als een tekenreeks, kan de eindgebruiker tekst invoeren in een tekstvak in de e-maileditor. U geeft een tekenreeksvariabele op met `<meta>` with class=&quot;mktoString&quot;

Vereiste kenmerken

* **id:** Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName:** Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **allowHTML:** Booleaans. Controls if the variable&#39;s value is HTML-escaped. De standaardwaarde is False als dit wordt weggelaten.
* **default**: Standaardwaarde voor de tekenreeks. Blanco indien weggelaten.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoString" id="textHeader" mktoName="Text Header" default="Edit Me"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textHeader}</pre>`

## Lijst {#list}

Als u een variabele opgeeft als een List, kan de eindgebruiker kiezen uit een set waarden die u in de e-maileditor definieert. U geeft een variabele List op met `<meta>` with class=&quot;mktoList&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName:** Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.
* **waarden:** Door komma&#39;s gescheiden lijst met waarden. Moet ten minste één tekenreeks hebben.

Optionele kenmerken

* **standaard:** Standaardwaarde van het geselecteerde vervolgkeuzemenu. Indien weggelaten, wordt de eerste waarde van het kenmerk &quot;values&quot; gebruikt.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoList" id="textFontFamily" mktoName="Main Text Font Family" values="Arial,Verdana,Times New Roman"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textFontFamily}</pre>`

## Getal {#number}

Als u een variabele opgeeft als een Getal, kan de eindgebruiker een getal invoeren in de e-maileditor. U geeft een variabele Number op met `<meta>` with class=&quot;mktoNumber&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.
* **standaard:** Standaardnumerieke waarde voor de variabele.

Optionele kenmerken

* **min.:** Min. geaccepteerde waarde.
* **max.:** Maximaal toegestane waarde.
* **eenheden:** Eenheden die aan de getalwaarde moeten worden toegevoegd (ex: px, pt, em, enz.) in de e-maileditor en in de resulterende code worden weergegeven.
* **stap:** Hoeveel eenheden moet de getalvariabele met (0,1, 1, 10, enz.) verhogen/verlagen. Als deze waarde wordt weggelaten, wordt standaard ingesteld op 1.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoNumber" id="textFontSize" mktoName="Main Text Font Size" default="12" min="8" max="18" units="px" step="1"> </pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textFontSize}</pre>`

## Kleur {#color}

Als u een variabele opgeeft als een kleur, kan de eindgebruiker een hexadecimale kleurwaarde invoeren of een kleur kiezen in de kleurkiezer in de e-maileditor. U geeft een kleurvariabele op met `<meta>` with class=&quot;mktoColor&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaard:** Standaardwaarde voor de kleur. Hexadecimale 6-cijferige kleurcode. Voorbeeld: #ffffff.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoColor" id="textColor" mktoName="Main Text Color" default="#FFFFFF"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${textColor}</pre>`

## Boolean {#boolean}

Als u een variabele opgeeft als een Booleaanse waarde, kan de eindgebruiker de optie in- en uitschakelen in de e-maileditor. U geeft een Booleaanse variabele op met `<meta>` with class=&quot;mktoBoolean&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaard:** Booleaanse waarde die de standaardstatus van de schakeloptie bepaalt. Onwaar indien weggelaten.
* **false_value:** Waarde die moet worden ingevoegd wanneer de schakeloptie zich in de uit-stand bevindt. Onwaar indien weggelaten.
* **true_value:** Waarde die moet worden ingevoegd wanneer de schakeloptie is ingeschakeld. Waar als weggelaten.
* **false_value_name:** UI die in knevel wordt getoond wanneer in uit positie. Onwaar indien weggelaten.
* **true_value_name:** UI die in de knevel wordt getoond wanneer op positie. Waar als weggelaten.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="showFooter" mktoName="Show Footer BG?" default="false" false_value="transparent" true_value="black" false_value_name="NO" true_value_name="YES"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${showFooter}</pre>`

## HTML-blok {#html-block}

Als u een variabele opgeeft als een HTML-blok, kan de eindgebruiker letterlijke HTML invoeren in de e-maileditor. U geeft een HTML Block-variabele op met `<meta>` with class=&quot;mktoHTML&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaard:** Met HTML gecodeerde waarde die als standaardinhoud van het blok fungeert.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoHTML" id="trackingPixel" mktoName="Add Tracking Pixel"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${trackingPixel}</pre>`

## Afbeeldingsvariabele {#image-variable}

Als u een variabele opgeeft als een afbeelding, kan de eindgebruiker een afbeelding kiezen in de afbeeldingskiezer in de e-maileditor. De geselecteerde afbeeldings-URL is de waarde van de variabele. U geeft een afbeeldingsvariabele op met `<meta>` with class=&quot;mktoImg&quot;

Vereiste kenmerken

* **id**: Hoe u verwijst naar de variabele in uw e-mailsjabloon.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **standaard:** Standaardafbeeldings-URL voor het element.
* **mktoModuleScope**: Booleaans. Controls whether the variable is local (true) or global (false) when used in a module. De standaardwaarde is False als dit wordt weggelaten.

Voorbeelddeclaratie:

`<pre data-theme="Confluence"><meta class="mktoImg" id="heroBackgroundImage" mktoName="Hero Background Image" default="https://www.company.com/image.jpg"></pre>`

Voorbeeld:

`<pre data-theme="Confluence">${heroBackgroundImage}</pre>`

## Modules {#modules}

Modules zijn sjabloonsecties die op sjabloonniveau zijn gedefinieerd en die worden weergegeven zodat eindgebruikers deze in hun e-mail kunnen invoegen. Omdat u deze modules vooraf hebt gemaakt, kunt u ervoor zorgen dat ze netjes communiceren met de rest van uw e-mailinhoud (op een volledig reagerende manier). U kunt een module alleen in een container plaatsen.

>[!IMPORTANT]
>
>Wanneer een e-mail van een e-mailmalplaatje wordt geproduceerd dat bepaalde modulecomponenten bevat, zullen om het even welke veranderingen die in de modules van het malplaatje worden aangebracht **niet** naar die e-mail worden gestuurd.

**Voor containers van het type `<table>`, `<tbody>`, `<thead>`, of `<tfoot>`:**

Opgegeven met `<tr>` with class=&quot;mktoModule&quot;

**Voor containers van het type `<td>`:**

Opgegeven met `<table>` with class=&quot;mktoModule&quot;

Vereiste kenmerken

* **id**: Hoe u in uw e-mailsjabloon naar de module verwijst.
* **mktoName**: Tekenreeks. Dit is de weergavenaam die wordt weergegeven in E-maileditor 2.0. U kunt het beste een beschrijvende naam gebruiken.

Optionele kenmerken

* **mktoActive:** Bepaalt of deze module in de lijst van modules binnen de e-mailredacteur verschijnt. Heeft als standaardwaarde true. Indien onwaar, kan de module niet door een eindgebruiker aan een e-mail worden toegevoegd.
* **mktoAddByDefault:** Hiermee bepaalt u of deze module zich op het canvas bevindt van een nieuwe e-mail waarin deze sjabloon bij het maken wordt gebruikt. De standaardwaarde is true (als mktoActive false is, wordt deze waarde genegeerd).

>[!NOTE]
>
>Klassewaarden met Marketo-syntaxis (d.w.z. mktoModule, mktoContainer, mktoText) zijn hoofdlettergevoelig. Namen van aangepaste kenmerken (mktoimgwidth, mktoname) zijn dit niet.

## Containers {#containers}

Een container houdt Modules en bepaalt waar zij kunnen worden geplaatst. Wanneer eindgebruikers modules opnieuw bestellen en in hun e-mail opnemen, controleert de container waar zij kunnen gaan.

**Opgegeven met `<table>`, `<tbody>`, `<thead>`, `<tfoot>` of `<td>` with class=&quot;mktoContainer&quot;**

Vereiste kenmerken

**id**: Hoe u in uw e-mailsjabloon naar de module verwijst.

>[!CAUTION]
>
>De containers kunnen slechts modules-bevatten als er iets anders aanwezig is, wordt de Container beschouwd ongeldig! Per sjabloon is slechts één container toegestaan.
