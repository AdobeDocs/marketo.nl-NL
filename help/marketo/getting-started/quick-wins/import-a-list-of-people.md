---
unique-page-id: 2359418
description: Een lijst met personen importeren - Marketo Docs - Productdocumentatie
title: Een lijst met personen importeren
exl-id: a85ec787-7b22-4666-84fd-d7bf23d32cd4
source-git-commit: 0da33dfa840dd1e5a5618fcd762b482f7a2e0789
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Een lijst met personen importeren {#import-a-list-of-people}

## Opdracht: Een spreadsheetlijst met presentatoren in uw database importeren {#mission-import-a-spreadsheet-list-of-trade-show-attendees-into-your-database}

>[!PREREQUISITES]
>
>[Instellen en een persoon toevoegen](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target=&quot;_blank&quot;}

In deze zelfstudie leert u hoe u personen uit een spreadsheetbestand kunt importeren in Marketo.

## Stap 1: Een werkblad downloaden en bewerken {#step-download-and-edit-a-spreadsheet}

1. Download ons werkbladbestand ([**tradeshow-aanwezigen.csv**](/help/marketo/getting-started/assets/tradeshow-attendees.csv){target=&quot;_blank&quot;}) naar uw computer.

   ![](assets/image2014-9-24-12-3a5-3a0.png)

   >[!NOTE]
   >
   >Gebruik bij het importeren van een datum de volgende notatie: **21-09-20** (Maand/Dag/Jaar).

   >[!NOTE]
   >
   >Alle datum-/tijdvelden die worden geïmporteerd, worden behandeld als Central Time. Als u datum-/tijdgebieden in een verschillende tijdzone hebt, kunt u een formule van Excel gebruiken om het in Centrale Tijd (Amerika/Chicago) om te zetten.

1. Voeg uw eigen voornaam, achternaam, feitelijk e-mailadres toe (zodat u de verzorgende e-mails kunt ontvangen die u in de volgende missie verzendt) en functie. Sla het bestand op uw computer op.

   ![](assets/image2014-9-24-12-3a5-3a30.png)

   >[!CAUTION]
   >
   >Marketo doet het **niet** e-mailadressen met emojis ondersteunen.

## Stap 2: Een programma maken {#step-create-a-program}

1. Ga naar de **Marketingactiviteiten** gebied.

   ![](assets/ma-2.png)

1. Selecteer uw **Leren** map, vervolgens onder **Nieuw** klikken **Nieuw programma**.

   ![](assets/image2014-9-24-12-3a21-3a13.png)

1. **Naam** het programma &quot;My Tradeshow Program&quot; en selecteer &quot;Event&quot; voor de **Type programma**.

   ![](assets/image2014-9-24-12-3a21-3a25.png)

1. Selecteren **Handelsversie** voor de **Kanaal** en klik op **Maken**.

   ![](assets/image2014-9-24-12-3a21-3a39.png)

>[!NOTE]
>
>Gebeurtenisprogramma&#39;s vinden plaats op specifieke datums. Meer informatie over [**Gebeurtenissen**](/help/marketo/product-docs/demand-generation/events/understanding-events/understanding-event-programs.md){target=&quot;_blank&quot;}.

## Stap 3: Uw spreadsheet importeren in Marketo {#step-import-your-spreadsheet-into-marketo}

1. In **Mijn handelsprogramma**, klikt u op **Nieuw** en selecteert u **Nieuw lokaal element**.

   ![](assets/seven-3.png)

1. Klikken **Lijst**.

   ![](assets/image2014-9-24-12-3a22-3a56.png)

1. **Naam** de lijst &quot;Handelaars Aanwezigen&quot; en klik op **Maken**.

   ![](assets/image2014-9-24-12-3a23-3a9.png)

1. In uw **Handelsdeelnemers** lijst, klikt u op **Handelingen weergeven** en selecteert u **Lijst importeren**.

   ![](assets/ten-2.png)

   >[!CAUTION]
   >
   >Als u uw eigen CSV-bestand gebruikt, moet u ervoor zorgen dat het UTF-8, UTF-16, Shift-JIS of EUC-JP is gecodeerd.

   >[!NOTE]
   >
   >De maximale grootte voor CSV-bestanden is 100 MB.

1. **Bladeren** aan de **tradeshow-aanwezigen.csv** spreadsheetbestand op de computer en klik op **Volgende**.

   ![](assets/eleven-2.png)

   >[!NOTE]
   >
   >Kies in de lijstimportmodus de optie **Nieuwe personen en updates overslaan** betekent dat u geen invloed hebt op bestaande persoonrecords of activiteiten registreert. Gebruik deze modus als u een snelle, vooraf gefilterde statische lijst met bestaande personen wilt gebruiken in uw marketingactiviteiten. Als u deze modus selecteert, wordt:
   >
   > * Nieuwe persoon maken overslaan
   > * Updates van persoonvelden overslaan
   > * Activiteitenregistratie overslaan


1. Wijs de velden Lijstkolom toe aan hun respectievelijke Marketo-veld en klik op **Volgende**.

   ![](assets/image2014-9-24-12-3a24-3a49.png)

   >[!TIP]
   >
   >Kolomkoppen moeten altijd exact overeenkomen met het veld (hoofdlettergevoelig) om de beste resultaten voor automatische toewijzing te verkrijgen. Als u aangepaste velden gebruikt en deze niet ziet in de vervolgkeuzelijst, gaat u terug en [maken](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md){target=&quot;_blank&quot;} zodat ze opties kunnen worden.

   >[!NOTE]
   >
   >Als er velden zijn die u niet wilt importeren, selecteert u **Negeren** in de vervolgkeuzelijst Marketo-veld.

1. Selecteren **Mijn handelsprogramma** voor de **Overnameprogramma** en klik vervolgens op **Importeren**.

   ![](assets/image2014-9-24-12-3a25-3a1.png)

1. Wacht tot uw personen zijn geïmporteerd en sluit vervolgens het pop-upvenster met voortgang bij importeren.

   ![](assets/image2014-9-24-12-3a25-3a13.png)

1. Terug naar **Mijn handelsprogramma** klikt u op de knop **Leden** tab. Je ziet alle mensen die je net hebt geïmporteerd.

   ![](assets/fifteen-1.png)

>[!NOTE]
>
>U kunt het succes van uw programma analyseren door het lidmaatschap van het programma te volgen. Meer informatie over [**Programma&#39;s**](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md){target=&quot;_blank&quot;}.

## Opdracht voltooid {#mission-complete}

Uw deelnemers aan de beurs zijn nu lid van uw Marketo-programma!

<br> 

[◄ Missie 4: Automatische reactie e-mail](/help/marketo/getting-started/quick-wins/email-auto-response.md)

[Missie 6: Drip, Drip, Nurtuur ►](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)
