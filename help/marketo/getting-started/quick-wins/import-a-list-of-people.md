---
unique-page-id: 2359418
description: Een lijst met personen importeren - Marketo Docs - Productdocumentatie
title: Een lijst met personen importeren
exl-id: a85ec787-7b22-4666-84fd-d7bf23d32cd4
source-git-commit: 1b37a750c5e609b9e43e942df752305d85153989
workflow-type: tm+mt
source-wordcount: '490'
ht-degree: 0%

---

# Een lijst met personen importeren {#import-a-list-of-people}

## Opdracht: Een spreadsheetlijst met presentatoren in uw database importeren {#mission-import-a-spreadsheet-list-of-trade-show-attendees-into-your-database}

>[!PREREQUISITES]
>
>[Instellen en een persoon toevoegen](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)

In deze zelfstudie leert u hoe u personen uit een spreadsheetbestand kunt importeren in Marketo.

## Stap 1: Een werkblad downloaden en bewerken {#step-download-and-edit-a-spreadsheet}

1. Als u wilt beginnen, downloadt u ons werkbladbestand ([**tradeshow-attendees.csv**](/help/marketo/getting-started/assets/tradeshow-attendees.csv)) naar uw computer.

   ![](assets/image2014-9-24-12-3a5-3a0.png)

   >[!NOTE]
   >
   >Gebruik bij het importeren van een datum de volgende notatie: **9/21/20** (Maand/Dag/Jaar).

   >[!NOTE]
   >
   >Alle datum-/tijdvelden die worden geïmporteerd, worden behandeld als Central Time. Als u datum-/tijdgebieden in een verschillende tijdzone hebt, kunt u een formule van Excel gebruiken om het in Centrale Tijd (Amerika/Chicago) om te zetten.

1. Voeg uw eigen voornaam, achternaam, e-mailadres en functie toe en sla het bestand op uw computer op.

   ![](assets/image2014-9-24-12-3a5-3a30.png)

>[!NOTE]
>
>Voer uw echte e-mailadres in het CSV-bestand in, zodat u de koesterende e-mails kunt ontvangen die u in de volgende missie verzendt.

## Stap 2: Een programma maken {#step-create-a-program}

1. Ga naar **Marketing Activities** gebied.

   ![](assets/ma-2.png)

1. Selecteer uw **Learning** omslag, dan onder **Nieuw** klik **Nieuw Programma**.

   ![](assets/image2014-9-24-12-3a21-3a13.png)

1. **** Geef het programma de naam &quot;Mijn programma van de Presentatie&quot;en selecteer &quot;Gebeurtenis&quot;voor het Type **van** Programma.

   ![](assets/image2014-9-24-12-3a21-3a25.png)

1. Selecteer **Handtekening** voor **Kanaal** en klik **Maken**.

   ![](assets/image2014-9-24-12-3a21-3a39.png)

>[!NOTE]
>
>Gebeurtenisprogramma&#39;s vinden plaats op specifieke datums. Meer informatie over [**Gebeurtenissen**](/help/marketo/product-docs/demand-generation/events/understanding-events/understanding-event-programs.md).

## Stap 3: Uw spreadsheet importeren in Marketo {#step-import-your-spreadsheet-into-marketo}

1. Klik in **Mijn handelsprogramma** op **Nieuw** en selecteer **Nieuw lokaal element**.

   ![](assets/seven-3.png)

1. Klik **Lijst**.

   ![](assets/image2014-9-24-12-3a22-3a56.png)

1. **** Geef de lijst &quot;Handelaars aanwezigen&quot; een naam en klik op  **Maken**.

   ![](assets/image2014-9-24-12-3a23-3a9.png)

1. Klik in de lijst **Handelingspartners** op **Handelingen weergeven** en selecteer **Lijst importeren**.

   ![](assets/ten-2.png)

   >[!CAUTION]
   >
   >Als u uw eigen CSV-bestand gebruikt, moet u ervoor zorgen dat het UTF-8, UTF-16, Shift-JIS of EUC-JP is gecodeerd.

   >[!NOTE]
   >
   >De maximale grootte voor CSV-bestanden is 100 MB.

1. **** Blader naar het bestand  **tradeshow-attendees.** csvspreadsheet op de computer en klik op  **Volgende**.

   ![](assets/eleven-2.png)

   >[!NOTE]
   >
   >In de Wijze van de Invoer van de Lijst, die **nieuwe mensen en updates overslaan** betekent u bestaande persoonverslagen niet zult beïnvloeden of om het even welke activiteiten registreert. Gebruik deze modus als u een snelle, vooraf gefilterde statische lijst met bestaande personen wilt gebruiken in uw marketingactiviteiten. Als u deze modus selecteert, wordt:
   >
   > * Nieuwe persoon maken overslaan
   > * Updates van persoonvelden overslaan
   > * Activiteitenregistratie overslaan


1. Wijs de gebieden van de Kolom van de Lijst aan hun respectieve Gebied van Marketo toe en klik **Volgende**.

   ![](assets/image2014-9-24-12-3a24-3a49.png)

   >[!TIP]
   >
   >Kolomkoppen moeten altijd exact overeenkomen met het veld (hoofdlettergevoelig) om de beste resultaten voor automatische toewijzing te verkrijgen. Als u douanegebieden gebruikt en hen niet in drop-down ziet, ga terug en [creeer hen](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md) zodat kunnen zij opties worden.

   >[!NOTE]
   >
   >Als er velden zijn die u niet wilt importeren, selecteert u **Negeren** in de vervolgkeuzelijst Marketo-veld.

1. Selecteer **My Tradeshow Program** voor **Acquisition Program** en klik vervolgens op **Import**.

   ![](assets/image2014-9-24-12-3a25-3a1.png)

1. Wacht tot uw personen zijn geïmporteerd en sluit vervolgens het pop-upvenster met voortgang bij importeren.

   ![](assets/image2014-9-24-12-3a25-3a13.png)

1. Terug in **Mijn Programma van de Handel**, klik **Leden** tabel. Je ziet alle mensen die je net hebt geïmporteerd.

   ![](assets/fifteen-1.png)

>[!NOTE]
>
>U kunt het succes van uw programma analyseren door het lidmaatschap van het programma te volgen. Meer informatie over [**Programma&#39;s**](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md).

## Opdracht voltooid {#mission-complete}

Uw deelnemers aan de beurs zijn nu lid van uw Marketo-programma!

<br> 

[◄ Missie 4: Automatische reactie e-mail](/help/marketo/getting-started/quick-wins/email-auto-response.md)

[Missie 6: Drip, Drip, Nurtuur ►](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)
