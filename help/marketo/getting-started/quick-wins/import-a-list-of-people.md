---
unique-page-id: 2359418
description: Een lijst met personen importeren - Marketo Docs - Productdocumentatie
title: Een lijst met personen importeren
exl-id: a85ec787-7b22-4666-84fd-d7bf23d32cd4
feature: Getting Started
source-git-commit: 1676c9049c61a637faede4751ea49bbcfa018be5
workflow-type: tm+mt
source-wordcount: '529'
ht-degree: 0%

---

# Een lijst met personen importeren {#import-a-list-of-people}

## Opdracht: importeer een spreadsheetlijst met presentatoren in uw database {#mission-import-a-spreadsheet-list-of-trade-show-attendees-into-your-database}

>[!PREREQUISITES]
>
>[ krijgt Opstelling en voegt een Persoon ](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"} toe

In deze zelfstudie leert u hoe u personen uit een spreadsheetbestand kunt importeren in Marketo.

## Stap 1: Een werkblad downloaden en bewerken {#step-download-and-edit-a-spreadsheet}

1. Om te beginnen, download ons dossier van het praktijkspreadsheet ([**handel-aanwezigen.csv**](/help/marketo/getting-started/assets/tradeshow-attendees.csv){target="_blank"}) aan uw computer.

   ![](assets/import-a-list-of-people-1.png)

   >[!NOTE]
   >
   >Wanneer het invoeren van een datum, gebruik dit formaat: **9/21/20** (Maand/Dag/Jaar).

   >[!NOTE]
   >
   >Alle datum-/tijdvelden die worden geïmporteerd, worden behandeld als Central Time. Als u datum-/tijdgebieden in een verschillende tijdzone hebt, kunt u een formule van Excel gebruiken om het in Centrale Tijd (Amerika/Chicago) om te zetten.

1. Voeg uw eigen voornaam, achternaam, feitelijk e-mailadres toe (zodat u de verzorgende e-mails kunt ontvangen die u in de volgende missie verzendt) en functie. Sla het bestand op uw computer op.

   ![](assets/import-a-list-of-people-2.png)

   >[!CAUTION]
   >
   >* Zorg ervoor dat e-mailadressen alleen ASCII-tekens bevatten.
   >
   >* Marketo steunt **niet** e-mailadressen die emojis bevatten.
   >
   >* Het invoeren van `NULL` waarden via CSV kon een &quot;Waarde van Gegevens van de Verandering&quot;voor numerieke gebieden in het 1} activiteitenlogboek van een persoon ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/locate-the-activity-log-for-a-person.md){target="_blank"} produceren, _zelfs als de gebieden reeds leeg_ zijn. [ Als u om het even welke [ Slimme Campagnes ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md){target="_blank"} gebruikend de &quot;Gewijzigde&quot;filter van de Waarde van Gegevens of &quot;Veranderingen van de Waarde van Gegevens&quot;hebt, ben zeker om [ beperkingen ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md){target="_blank"} te gebruiken om ervoor te zorgen zij niet onnodig worden teweeggebracht wanneer het uitvoeren van invoer.

## Stap 2: Een programma maken {#step-create-a-program}

1. Ga naar het **[!UICONTROL Marketing Activities]** -gebied.

   ![](assets/import-a-list-of-people-3.png)

1. Selecteer uw **Lerende** omslag, dan onder **[!UICONTROL New]** klik **[!UICONTROL New Program]**.

   ![](assets/import-a-list-of-people-4.png)

1. **Naam** het programma &quot;Mijn Programma van de Handel&quot;en selecteert &quot;Gebeurtenis&quot;voor **[!UICONTROL Program Type]**.

   ![](assets/import-a-list-of-people-5.png)

1. Selecteer **[!UICONTROL Tradeshow]** voor **[!UICONTROL Channel]** en klik **[!UICONTROL Create]**.

   ![](assets/import-a-list-of-people-6.png)

>[!NOTE]
>
>Gebeurtenisprogramma&#39;s vinden plaats op specifieke datums. Leer meer over [**Gebeurtenissen**](/help/marketo/product-docs/demand-generation/events/understanding-events/understanding-event-programs.md){target="_blank"}.

## Stap 3: Importeer uw werkblad in Marketo {#step-import-your-spreadsheet-into-marketo}

1. In **Mijn Programma van de Handel**, klik **[!UICONTROL New]** en selecteer **[!UICONTROL New Local Asset]**.

   ![](assets/import-a-list-of-people-7.png)

1. Selecteer **[!UICONTROL List]** .

   ![](assets/import-a-list-of-people-8.png)

1. **Naam** de lijst &quot;de Aanwezigen van het Verkeer&quot;en klikt **[!UICONTROL Create]**.

   ![](assets/import-a-list-of-people-9.png)

1. Klik in de lijst **[!UICONTROL Tradeshow Attendees]** op **[!UICONTROL List Actions]** en selecteer **[!UICONTROL Import List]** .

   ![](assets/import-a-list-of-people-10.png)

   >[!CAUTION]
   >
   >Als u uw eigen CSV-bestand gebruikt, moet u ervoor zorgen dat het UTF-8, UTF-16, Shift-JIS of EUC-JP is gecodeerd.

   >[!NOTE]
   >
   >De maximale grootte voor CSV-bestanden is 100 MB.

1. **[!UICONTROL Browse]** aan het **handel-aanwezigen.csv** spreadsheetdossier op uw computer en klik **[!UICONTROL Next]**.

   ![](assets/import-a-list-of-people-11.png)

   >[!NOTE]
   >
   >Als u in de lijstimportmodus **[!UICONTROL Skip new people and updates]** kiest, hebt u geen invloed op bestaande persoonrecords of worden activiteiten geregistreerd. Gebruik deze modus als u een snelle, vooraf gefilterde statische lijst met bestaande personen wilt gebruiken in uw marketingactiviteiten. Als u deze modus selecteert, wordt:
   >
   > * Nieuwe persoon maken overslaan
   > * Updates van persoonvelden overslaan
   > * Activiteitenregistratie overslaan

1. Wijs uw [!UICONTROL List Column] -velden toe aan hun respectievelijke Marketo-veld en klik op **[!UICONTROL Next]** .

   ![](assets/import-a-list-of-people-12.png)

   >[!TIP]
   >
   >Kolomkoppen moeten altijd exact overeenkomen met het veld (hoofdlettergevoelig) om de beste resultaten voor automatische toewijzing te verkrijgen. Als u douanegebieden gebruikt en hen niet in drop-down ziet, ga terug en [ creeer hen ](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md){target="_blank"} zodat kunnen zij opties worden.

   >[!NOTE]
   >
   >Als er om het even welke gebieden zijn u niet wilt invoeren, uitgezochte **negeert** in het drop-down menu van het Gebied van Marketo.

1. Selecteer **Mijn Programma van de Handel** voor **[!UICONTROL Acquisition Program]**, dan klik **[!UICONTROL Import]**.

   ![](assets/import-a-list-of-people-13.png)

1. Wacht tot uw personen zijn geïmporteerd en sluit vervolgens het pop-upvenster met voortgang bij importeren.

   ![](assets/import-a-list-of-people-14.png)

1. Terug in **Mijn Programma van de Verrichting**, klik het **[!UICONTROL Members]** lusje. Je ziet alle mensen die je net hebt geïmporteerd.

   ![](assets/import-a-list-of-people-15.png)

>[!NOTE]
>
>U kunt het succes van uw programma analyseren door het lidmaatschap van het programma te volgen. Leer meer over [**Programma&#39;s**](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md){target="_blank"}.

## Opdracht voltooid {#mission-complete}

Uw deelnemers aan de beurs zijn nu lid van uw Marketo-programma!

<br> 

[◄ Missie 4: Automatische e-mailrespons](/help/marketo/getting-started/quick-wins/email-auto-response.md)

[Missie 6: Drip, Drip, Nurture ►](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)
