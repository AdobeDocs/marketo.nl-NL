---
unique-page-id: 2953419
description: Het gebruiken van de Rich Tekstredacteur - Marketo Dos - de Documentatie van het Product
title: De Rich Text Editor gebruiken
translation-type: tm+mt
source-git-commit: c33b7ab59e612f37d3f64bb954579700dc574068
workflow-type: tm+mt
source-wordcount: '736'
ht-degree: 0%

---


# De Rich Text Editor gebruiken {#using-the-rich-text-editor}

De Rich Text Editor (RTE) wordt in Marketo weergegeven en is beschikbaar wanneer u inhoud wilt toevoegen of bewerken. Er wordt een versie van deze versie weergegeven op bestemmingspagina&#39;s, programma&#39;s, e-mails, formulieren en fragmenten. Klik gewoon op Concept **** bewerken en deze verschijnt dan ten dienste van u.

## Editor-instellingen {#editor-settings}

De instelling van het basisblokelement definieert welke tags de inhoud omlopen. Standaard gebruikt het element voor het basisblok van de e-mail <p> -tags. U kunt dit wijzigen door de onderstaande stappen te volgen.

>[!TIP]
>
>Terwijl u de optie hebt om uw basisblokelement te kiezen, adviseren wij altijd gebruikend standaardmontages voor de beste gebruikerservaring.

1. Klik op **Beheerder**.

   ![](assets/one.png)

1. Klik op **E-mail**.

   ![](assets/two.png)

1. Klik op Instellingen **van teksteditor** bewerken.

   ![](assets/three.png)

1. Selecteer in het vervolgkeuzemenu **E-mail / Fragmenteditor** de optie <div> of Geen en klik op **Opslaan**. <div> wordt gebruikt in dit voorbeeld.

   ![](assets/four.png)

   Als u <div class="&ldquo;mktEditable&rdquo;"></div> in een E-mailsjabloon ziet u het volgende gedrag HTML-bron wanneer u de sectie opent en &quot;Tekst gaat hier&quot; in de editor typt:

<table> 
 <tbody> 
  <tr> 
   <th>&lt;p&gt;</th> 
   <th>&lt;div&gt;</th> 
   <th>Geen</th> 
  </tr> 
  <tr> 
   <td><p>&lt;div class="mktEditable"&gt;<br>&lt;p&gt;Hier komt tekst&lt;/p&gt;<br>&lt;/div&gt;</p></td> 
   <td><p>&lt;div class="mktEditable"&gt;<br>&lt;div&gt;Tekst komt hier&lt;/div&gt;<br>&lt;/div&gt;</p></td> 
   <td><p>&lt;div class="mktEditable"&gt;<br>Tekst komt hier<br>&lt;/div&gt;</p></td> 
  </tr> 
 </tbody> 
</table>

>[!TIP]
>
>U kunt ook het basisblokelement van de Landing Page Editor wijzigen door dezelfde stappen uit te voeren, maar door in Stap 4 op de vervolgkeuzelijst **Landing Page Editor** te klikken in plaats van in de Editor e-mail/Fragment.

>[!NOTE]
>
>Het basisblokelement is altijd <p> voor RTF-tokens.

## Functies {#features}

Hier zijn de eigenschappen u in RTE zult vinden.

| Pictogram | Naam | Wat het doet |
|---|---|---|
| ![--](assets/image2015-7-9-10-3a23-3a24.png) | Lettertypefamilie | Kies uw stijl—We hebben genoeg! |
| ![--](assets/image2015-7-9-10-3a22-3a11.png) | Tekengrootte | Hoe groot wil je het? 25 keuzen, van 8 px tot 90 px. |
| ![--](assets/image2015-7-9-10-3a59-3a4.png) | Stijlen | Kies Alinea of zes stijlen voor kop (voor bestemmingspagina&#39;s). |
| ![--](assets/image2015-7-9-10-3a20-3a1.png) | Regelafstand | Kies de afstand tussen de lijnen. |
| ![--](assets/image2015-7-9-10-3a25-3a52.png) | Tekstkleur | Zwart, rood of wat je maar wilt. |
| ![--](assets/image2015-7-9-10-3a24-3a38.png) | Achtergrondkleur | Benadruk voor nadruk. |
| ![--](assets/image2015-7-9-10-3a28-3a4.png) | Vet | **Donkerder en dikker**. |
| ![--](assets/image2015-7-9-10-3a29-3a1.png) | Cursief | *Hoekig, voor accenten of* noteringen. |
| ![--](assets/image2015-7-9-10-3a30-3a56.png) | Onderstrepen | Hiermee plaatst u een lijn onder de tekst. |
| ![--](assets/image2015-7-9-10-3a31-3a57.png) | Uitlijning | Gebruik deze vervolgkeuzelijst om uw tekst en afbeeldingen op te maken. Centreer de randen, kies links of rechts uitlijnen of spreid de rand naar rand met volledige uitvulling. |  | ![--](assets/image2015-7-9-10-3a32-3a47.png) | Lijst | Kies opsommingstekens of nummers in het vervolgkeuzemenu. Opsommingstekens zijn geschikt voor lijsten en nummers met stappen. |
| ![--](assets/image2015-7-9-10-3a38-3a0.png) | Inspringen | Kies meer of minder inspringing. Gebruik deze optie voor alinea&#39;s of tekst die u wilt uitspringen. |
| ![--](assets/image2015-7-9-10-3a38-3a58.png) | Koppeling invoegen/bewerken | Een koppeling naar een website of andere inhoud plaatsen; u kunt er gemakkelijk wijzigingen in aanbrengen. |
| ![--](assets/image2015-7-9-10-3a39-3a42.png) | Afbeelding invoegen/bewerken | Een foto is duizend woorden waard. Zet er een neer. Klik op het camerapictogram om door uw Design Studio te bladeren. U kunt afbeeldingen naast elkaar neerzetten. |
| ![--](assets/image2015-7-9-10-3a40-3a36.png) | Token invoegen | Een krachtig hulpmiddel, ideaal voor het aanpassen van e-mail en het bijhouden van gegevens. Voer een standaardwaarde in. |
| ![--](assets/image2015-7-9-10-3a41-3a21.png) | Ongedaan maken | Oeps! Laten we een stap terugzetten en het opnieuw proberen. |
| ![--](assets/image2015-7-9-10-3a42-3a13.png) | Opnieuw | Als het echt oké is zoals het is, ga terug naar het origineel. |
| ![--](assets/image2015-7-9-10-3a43-3a29.png) | Tabel | Bouw je eigen, zoals deze. Met een vervolgkeuzemenu kunt u de toepassing configureren. |
| ![--](assets/image2015-7-9-10-3a45-3a1.png) | Anker invoegen | Anker neerzetten! |
| ![--](assets/image2015-7-9-10-3a45-3a48.png) | Horizontale lijn | Veel toepassingen - Ideaal voor scheidingsgedeelten. |
| ![--](assets/image2015-10-6-12-3a12-3a17.png) | HTML bewerken | Hiermee wordt de HTML-broneditor weergegeven, zodat u de code kunt afstemmen. |
| ![--](assets/image2015-7-9-10-3a47-3a36.png) | Subscript | Lage hangende letters (zoals in O`<sub>2</sub>`). |
| ![--](assets/image2015-7-9-10-3a48-3a35.png) | Superscript | U hebt de macht! (2`<sup>6</sup>`). |
| ![--](assets/image2015-7-9-10-3a49-3a31.png) | Doorhalen | `<s>Put a line through text, like this</s>`. |
| ![--](assets/image2015-7-9-10-3a50-3a11.png) | Speciaal teken | Wil je over euro&#39;s praten? Mathematisch? Je hebt 243 keuzen. |
| ![--](assets/image2015-7-9-10-3a52-3a26.png) | Zoeken en vervangen | U kunt veel sneller naar dingen zoeken en deze wijzigen dan elke instantie zelf. |
| ![--](assets/image2015-7-9-10-3a53-3a37.png) | Opmaak wissen | Terugkeren naar standaard. |
| ![--](assets/image2015-7-9-10-3a55-3a2.png) | Annuleren | Druk op de knop om te zeggen: &quot;Het geeft niet.&quot; |
| ![--](assets/image2015-7-9-10-3a56-3a2.png) | Opslaan | Druk op de knop om te zeggen: &quot;OK, ik vind het leuk.&quot; |

>[!TIP]
>
>U bewerkt de HTML en de tekst op afzonderlijke schermen. Klik op **Kopiëren vanuit HTML** op het tabblad **Tekst** en **** sla de tekst op zodat deze overeenkomt met de HTML.

>[!NOTE]
>
>U bent niet beperkt tot de lettertypen in de vervolgkeuzelijst. U kunt een object gebruiken dat niet wordt vermeld, door de HTML-code te openen. Alle weblettertypen worden ondersteund in Marketo, maar weblettertypen werken niet overal in e-mailclients.

## Openingspagina&#39;s {#landing-pages}

De instelling van het basisblokelement definieert welke tags de inhoud omlopen. Standaard gebruikt het basisblokelement van de landingspagina <div> -tags. U kunt dit wijzigen door de onderstaande stappen te volgen.

>[!TIP]
>
>Terwijl u de optie hebt om uw basisblokelement te kiezen, adviseren wij altijd gebruikend standaardmontages voor de beste gebruikerservaring.

1. Klik op **Beheerder**.

   ![](assets/one.png)

1. Klik op **E-mail**.

   ![](assets/two.png)

1. Klik op Instellingen **van teksteditor** bewerken.

   ![](assets/three.png)

1. Selecteer in het vervolgkeuzemenu **Landing Page Editor** de optie <p> of Geen en klik op **Opslaan**. <p> wordt gebruikt in dit voorbeeld.

   ![](assets/five.png)

   En dat is het!

