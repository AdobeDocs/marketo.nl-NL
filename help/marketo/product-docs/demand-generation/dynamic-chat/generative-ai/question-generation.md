---
description: Vraag genereren - Marketo Docs - Productdocumentatie
title: Vragengeneratie
feature: Dynamic Chat
exl-id: 05e0fd4c-b8e0-47de-8ca8-d4ba07d6a06a
source-git-commit: 6bdac72f0b9831ba830d842cabffbd0f114325fb
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---

# Vragengeneratie {#question-generation}

Bekijk al uw taken en de relevante details, zoals het tijdstip waarop deze zijn gegenereerd, het totale aantal vragen, de goedkeuringsstatus en meer.

## Vragen genereren {#generate-questions}

1. Klik onder Generative AI op **[!UICONTROL Assisted responses]**.

   ![](assets/question-generation-1.png)

1. Klik op **[!UICONTROL Generate questions]**.

   ![](assets/question-generation-2.png)

1. Geef uw taak een naam en voer een bron-URL (maximaal 10) in waaruit alle inhoud wordt geëxtraheerd. Voer de gewenste onderwerpen/trefwoorden in en druk op Enter op het toetsenbord. Klik wanneer gereed **[!UICONTROL Generate]**.

   ![](assets/question-generation-3.png)

   >[!IMPORTANT]
   >
   >Om ervoor te zorgen dat Marketo Engage inhoud van verstrekte URLs kan schrapen, moet u verscheidene IP adressen eerst lijsten van gewenste personen. [Zie hieronder voor meer informatie](#ip-addresses-to-allowlist).

1. Op basis van uw inhoud kan het genereren van vragen en antwoorden tot 30 minuten duren. Klik op **[!UICONTROL OK]**.

   ![](assets/question-generation-4.png)

   >[!TIP]
   >
   >Druk op Vernieuwen om de nieuwste status van het genereren van uw vraag te bekijken.

   ![](assets/question-generation-5.png)

## Vragen en antwoorden downloaden {#download-questions-and-responses}

>[!NOTE]
>
>Gegenereerde vragen en antwoorden kunnen ook worden weergegeven in het dialoogvenster [Responsbibliotheek](/help/marketo/product-docs/demand-generation/dynamic-chat/generative-ai/response-library.md).

1. Zoek de gewenste taak en klik op het downloadpictogram naast de naam ervan.

   ![](assets/question-generation-6.png)

1. Zoek de downloadmap in uw browser en selecteer het bestand. Dit kan er anders uitzien, afhankelijk van de browser die u gebruikt.

   ![](assets/question-generation-7.png)

1. In het Excel-bestand **[!DNL Task details]** Hierin worden verschillende details over de taak weergegeven, waaronder instructies over het toevoegen/bewerken van vragen en/of antwoorden.

   ![](assets/question-generation-8.png)

   >[!NOTE]
   >
   >Als u toch besluit om add-vragen en/of antwoorden in bulk te verzenden/bewerken, [leren hoe u ze hier opnieuw kunt uploaden](/help/marketo/product-docs/demand-generation/dynamic-chat/generative-ai/response-library.md).

1. De **[!DNL Q&Rs]** bevat aanvullende details, zoals de gegenereerde vragen en antwoorden.

   ![](assets/question-generation-9.png)

## IP Adressen aan Lijst van gewenste personen {#ip-addresses-to-allowlist}

Als u het ophalen van inhoud van uw web-URL&#39;s tijdens het genereren van vragen en antwoorden wilt inschakelen, zoekt u hieronder uw regio en zorgt u ervoor dat het bijbehorende IP-adres door uw webteam wordt gevoegd op lijst van gewenste personen.

<table width="450">
<thead>
  <tr>
    <th>Noord-Amerika</th>
    <th>Europa</th>
    <th>APAC</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>13.68.17.252</td>
    <td>20 105 150 224</td>
    <td>20 213 91 77</td>
  </tr>
</tbody>
</table>
