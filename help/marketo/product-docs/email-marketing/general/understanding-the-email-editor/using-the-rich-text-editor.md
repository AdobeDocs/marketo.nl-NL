---
unique-page-id: 2953419
description: De Rich Text Editor - Marketo Docs - Productdocumentatie gebruiken
title: De Rich Text Editor gebruiken
exl-id: 9b2d6d41-f947-4859-aad9-a10c15eb013a
feature: Email Editor
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '659'
ht-degree: 1%

---

# De Rich Text Editor gebruiken {#using-the-rich-text-editor}

De Rich Text Editor (RTE) wordt in Marketo weergegeven en is beschikbaar wanneer u inhoud wilt toevoegen of bewerken. Er wordt een versie van deze versie weergegeven op bestemmingspagina&#39;s, programma&#39;s, e-mails, formulieren en fragmenten. Klik gewoon op **[!UICONTROL Edit Draft]** en het verschijnt om u te dienen.

## Editor-instellingen {#editor-settings}

De instelling van het basisblokelement definieert welke tags de inhoud omlopen. Standaard gebruikt het element voor het basisblok van de e-mail `<p>` -tags. U kunt dit wijzigen door de onderstaande stappen te volgen.

>[!TIP]
>
>Terwijl u de optie hebt om uw basisblokelement te kiezen, adviseren wij altijd gebruikend standaardmontages voor de beste gebruikerservaring.

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/one.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/two.png)

1. Klik op **[!UICONTROL Edit Text Editor Settings]**.

   ![](assets/three.png)

1. Selecteer **[!UICONTROL Email]of[!UICONTROL Snippet Editor]** in de vervolgkeuzelijst `<div>` / [!UICONTROL None] en klik op **[!UICONTROL Save]** . `<div>` wordt gebruikt in dit voorbeeld.

   ![](assets/four.png)

   Als u `<div class=“mktEditable”></div>` in een E-mailsjabloon hebt, wordt het volgende HTML Source-gedrag weergegeven wanneer u de sectie opent en &quot;Tekst gaat hier&quot; in de editor typt:

<table>
 <tbody>
  <tr>
   <th>&lt;p&gt;</th>
   <th>&lt;div&gt;</th>
   <th>Geen</th>
  </tr>
  <tr>
   <td><p>&lt;div class="mktEditable"&gt;<br> &lt;p&gt;Tekst gaat hier&lt;/p&gt;<br>&lt;/div&gt;</p></td>
   <td><p>&lt;div class="mktEditable"&gt;<br> &lt;div&gt;Tekst gaat hier&lt;/div&gt; <br>&lt;/div&gt;</p></td>
   <td><p>&lt;div class="mktEditable"&gt; <br> Tekst gaat hier <br>&lt;/div&gt;</p></td>
  </tr>
 </tbody>
</table>

>[!TIP]
>
>U kunt ook het basisblokelement van de Landing Page Editor wijzigen door dezelfde stappen uit te voeren, maar door in stap 4 op de vervolgkeuzelijst **[!UICONTROL Landing Page Editor]** te klikken in plaats van op [!UICONTROL Email] / [!UICONTROL Snippet Editor] .

>[!NOTE]
>
>Het basisblokelement is altijd `<p>` voor rijke-tekstprogrammeertokens.

## Functies {#features}

Hier zijn de eigenschappen u in RTE zult vinden.

| Pictogram | Naam | Wat doet het? |
|---|---|---|
| ![—](assets/image2015-7-9-10-3a23-3a24.png) | [!UICONTROL Font Family] | Kies uw stijl—We hebben genoeg! |
| ![—](assets/image2015-7-9-10-3a22-3a11.png) | [!UICONTROL Font Size] | Hoe groot wil je het? 25 keuzen, van 8 px tot 90 px. |
| ![—](assets/image2015-7-9-10-3a59-3a4.png) | [!UICONTROL Styles] | Kies Alinea of zes stijlen voor kop (voor bestemmingspagina&#39;s). |
| ![—](assets/image2015-7-9-10-3a20-3a1.png) | [!UICONTROL Line Spacing] | Kies de afstand tussen de lijnen. |
| ![—](assets/image2015-7-9-10-3a25-3a52.png) | [!UICONTROL Text Color] | Zwart, rood of wat je maar wilt. |
| ![—](assets/image2015-7-9-10-3a24-3a38.png) | [!UICONTROL Background Color] | Benadruk voor nadruk. |
| ![—](assets/image2015-7-9-10-3a28-3a4.png) | [!UICONTROL Bold] | **Donkerder en dikker**. |
| ![—](assets/image2015-7-9-10-3a29-3a1.png) | [!UICONTROL Italic] | *Angled, voor nadruk of citatie* s. |
| ![—](assets/image2015-7-9-10-3a30-3a56.png) | [!UICONTROL Underline] | Hiermee plaatst u een lijn onder de tekst. |
| ![—](assets/image2015-7-9-10-3a31-3a57.png) | [!UICONTROL Alignment] | Gebruik deze vervolgkeuzelijst om uw tekst en afbeeldingen op te maken. Centreer de randen, kies links of rechts uitlijnen of spreid de rand naar rand met volledige uitvulling. |  | ![—](assets/image2015-7-9-10-3a32-3a47.png) | Lijst | Kies opsommingstekens of nummers in het vervolgkeuzemenu. Opsommingstekens zijn geschikt voor lijsten en nummers met stappen. |
| ![—](assets/image2015-7-9-10-3a38-3a0.png) | [!UICONTROL Indent] | Kies meer of minder inspringing. Gebruik deze optie voor alinea&#39;s of tekst die u wilt uitspringen. |
| ![—](assets/image2015-7-9-10-3a38-3a58.png) | [!UICONTROL Insert/Edit Link] | Plaats een koppeling naar een website of andere inhoud en breng gemakkelijk wijzigingen aan. |
| ![—](assets/image2015-7-9-10-3a39-3a42.png) | [!UICONTROL Insert/Edit Image] | Een foto is duizend woorden waard. Zet er een neer. Klik op het camerapictogram om door uw Design Studio te bladeren. U kunt afbeeldingen naast elkaar neerzetten. |
| ![—](assets/image2015-7-9-10-3a40-3a36.png) | [!UICONTROL Insert Token] | Een krachtig hulpmiddel, ideaal voor het aanpassen van e-mail en het bijhouden van gegevens. Voer een standaardwaarde in. |
| ![—](assets/image2015-7-9-10-3a41-3a21.png) | [!UICONTROL Undo] | Oeps! Laten we een stap terugzetten en het opnieuw proberen. |
| ![—](assets/image2015-7-9-10-3a42-3a13.png) | [!UICONTROL Redo] | Als het echt oké is zoals het is, ga terug naar het origineel. |
| ![—](assets/image2015-7-9-10-3a43-3a29.png) | [!UICONTROL Table] | Bouw je eigen, zoals deze. Met een vervolgkeuzemenu kunt u de toepassing configureren. |
| ![—](assets/image2015-7-9-10-3a45-3a1.png) | [!UICONTROL Insert Anchor] | Anker neerzetten! |
| ![—](assets/image2015-7-9-10-3a45-3a48.png) | [!UICONTROL Horizontal Line] | Veel toepassingen - Ideaal voor scheidingsgedeelten. |
| ![—](assets/image2015-10-6-12-3a12-3a17.png) | [!UICONTROL Edit HTML] | Hiermee opent u de HTML Source Editor zodat u de code kunt afstemmen. |
| ![—](assets/image2015-7-9-10-3a47-3a36.png) | [!UICONTROL Subscript] | Lage-hangende brieven (zoals in O `<sub>2</sub>`). |
| ![—](assets/image2015-7-9-10-3a48-3a35.png) | [!UICONTROL Superscript] | U hebt de macht! (2 `<sup>6</sup>`). |
| ![—](assets/image2015-7-9-10-3a49-3a31.png) | [!UICONTROL Strikethrough] | `<s>Put a line through text, like this</s>`. |
| ![—](assets/image2015-7-9-10-3a50-3a11.png) | [!UICONTROL Special Character] | Wil je het hebben over euro&#39;s? Mathematisch? Je hebt 243 keuzen. |
| ![—](assets/image2015-7-9-10-3a52-3a26.png) | [!UICONTROL Find and Replace] | U kunt veel sneller naar dingen zoeken en deze wijzigen dan elke instantie zelf. |
| ![—](assets/image2015-7-9-10-3a53-3a37.png) | [!UICONTROL Clear Formatting] | Terugkeren naar standaard. |
| ![—](assets/image2015-7-9-10-3a55-3a2.png) | [!UICONTROL Cancel] | Druk op de knop om te zeggen: &quot;Het geeft niet.&quot; |
| ![—](assets/image2015-7-9-10-3a56-3a2.png) | [!UICONTROL Save] | Druk op de knop om te zeggen: &quot;OK, ik vind het leuk.&quot; |

>[!TIP]
>
>U bewerkt de HTML en de tekst op afzonderlijke schermen. Klik eerst op **[!UICONTROL Copy from HTML]** op de tab **[!UICONTROL Text]** en vervolgens op **[!UICONTROL Save]** , zodat de tekst overeenkomt met de HTML.

>[!NOTE]
>
>U bent niet beperkt tot de lettertypen in de vervolgkeuzelijst. U kunt een object gebruiken dat niet wordt vermeld, door de HTML-code te openen. Alle weblettertypen worden ondersteund in Marketo, maar weblettertypen werken niet overal in e-mailclients.

## Landingspagina&#39;s {#landing-pages}

De instelling van het basisblokelement definieert welke tags de inhoud omlopen. Standaard gebruikt het basisblokelement van de landingspagina `<div>` -tags. U kunt dit wijzigen door de onderstaande stappen te volgen.

>[!TIP]
>
>Terwijl u de optie hebt om uw basisblokelement te kiezen, adviseren wij altijd gebruikend standaardmontages voor de beste gebruikerservaring.

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/one.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/two.png)

1. Klik op **[!UICONTROL Edit Text Editor Settings]**.

   ![](assets/three.png)

1. Selecteer **[!UICONTROL Landing Page Editor]** of `<p>` in de vervolgkeuzelijst [!UICONTROL None] en klik op **[!UICONTROL Save]** . `<p>` wordt gebruikt in dit voorbeeld.

   ![](assets/five.png)

   En dat is het!
