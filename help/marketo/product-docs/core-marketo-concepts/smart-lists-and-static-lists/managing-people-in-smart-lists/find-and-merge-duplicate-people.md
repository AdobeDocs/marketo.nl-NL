---
unique-page-id: 557339
description: Dubbele personen zoeken en samenvoegen - Marketo Docs - Productdocumentatie
title: Dubbele personen zoeken en samenvoegen
exl-id: a6d46096-587a-4e3a-b37a-917c0d2098b1
feature: Smart Lists
source-git-commit: 3456e4d0d9fdcd4590884d9a5b15ef206fcff875
workflow-type: tm+mt
source-wordcount: '411'
ht-degree: 0%

---

# Dubbele personen zoeken en samenvoegen {#find-and-merge-duplicate-people}

Marketo Engage dedupliceert automatisch wanneer nieuwe personen het systeem betreden. Uw CRM kan echter oorspronkelijk meerdere duplicaten hebben verzonden. Hieronder wordt beschreven hoe u ze samenvoegt.

>[!CAUTION]
>
>Het samenvoegen van mensen is permanent, er is geen optie &quot;ongedaan maken&quot;.

>[!PREREQUISITES]
>
>Het vinden van en het samenvoegen van duplicaten impliceert het gebruik van [&#x200B; ingebouwde/systeem Slimme Lijsten &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-built-in-system-smart-lists.md){target="_blank"}.

>[!NOTE]
>
>Marketo wordt niet automatisch gededupliceerd via een [!DNL Salesforce] - of [!DNL Microsoft Dynamics] -synchronisatie of wanneer u handmatig personen invoert.

## Duplicaten zoeken {#find-duplicates}

1. Ga naar het **[!UICONTROL Database]** -gebied.

   ![](assets/find-and-merge-duplicate-people-1.png)

   >[!CAUTION]
   >
   >Het samenvoegen van personen in Marketo werkt mogelijk niet als u een [!DNL Salesforce] Person-account gebruikt. Voeg indien mogelijk de records in [!DNL Salesforce] samen.

1. Selecteer de **[!UICONTROL Possible Duplicates]** slimme lijst voor systemen en klik op het tabblad **[!UICONTROL People]** .

   ![](assets/find-and-merge-duplicate-people-2.png)

   >[!NOTE]
   >
   >U kunt ook [&#x200B; Dubbele Mensen met de Logica van de Douane &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-duplicate-people-with-custom-logic.md){target="_blank"} vinden.

## Personen handmatig samenvoegen {#merge-people-manually}

>[!CAUTION]
>
>Wanneer het samenvoegen van mensen, als de verliezende persoon een douanevoorwerp van Marketo heeft, zal het __ niet opnieuw worden geassocieerd aan de winnende persoon. Geef het aangepaste object opnieuw het bovenliggende element voordat u het samenvoegt.

1. Selecteer de duplicaten door Ctrl/Cmd ingedrukt te houden en te klikken en vervolgens op **[!UICONTROL Merge People]** te klikken.

   ![](assets/find-and-merge-duplicate-people-3.png)

   >[!TIP]
   >
   >U kunt twee of meer duplicaten hebben voor dezelfde persoon - en deze in één keer selecteren.

1. De waarden tussen records die niet overeenkomen, worden weergegeven. _selecteer de waarde u voor elk gebied_ wilt houden. Klik op **[!UICONTROL Merge]** als u klaar bent. Als u geen van beide waarden wilt, kunt u **[!UICONTROL Custom]** controleren en een waarde van uw keus ingaan.

   ![](assets/find-and-merge-duplicate-people-4.png)

   >[!NOTE]
   >
   >* In tegenstelling tot Salesforce, wanneer het samenvoegen van mensen in Marketo, zijn hun scores _niet_ samengevat. U selecteert de waarden die u wilt behouden.
   >
   >* Wanneer u handmatig personen samenvoegt, is de eerste geselecteerde persoon de &quot;winnaar&quot;. Dus op het tabblad Personen als u record-id&#39;s 198 en 199 samenvoegt en u toevallig eerst op 199 klikt, wordt 199 de record-id van de samengevoegde personen. Dit geldt ook als meer dan twee records worden samengevoegd.

   >[!TIP]
   >
   >Samenvoegen is beter dan verwijderen. U bespaart alle historie (paginabezoeken, klikken op koppelingen, e-mail openen, invullen van formulieren, enzovoort).

## Effect in Salesforce {#effect-in-salesforce}

Als je Salesforce integreert, zijn er een paar opmerkingen over het effect van het samenvoegen van Leads in Salesforce.

* Wanneer alleen leads of alleen Contacten worden samengevoegd, worden ze samengevoegd volgens de normale [!DNL Salesforce] -regels.
* Bij het samenvoegen van leads en contactpersonen worden alle leads geconverteerd naar contactpersonen voordat de regels [!DNL Salesforce] normaal worden samengevoegd.

Voor details van Salesforce-gedrag bij het samenvoegen van leads of contactpersonen raadpleegt u de volgende [!DNL Salesforce] -documenten:

* [&#x200B; het samenvoegen dubbele Leidingen &#x200B;](https://help.salesforce.com/HTViewHelpDoc?id=leads_merge.htm&language=en_US){target="_blank"}
* [&#x200B; het samenvoegen van Dubbele Contacten &#x200B;](https://help.salesforce.com/HTViewHelpDoc?id=contacts_merge.htm&language=en_US){target="_blank"}

## Bulksamenvoeging {#bulk-merging}

Als u te veel duplicaten hebt om handmatig samen te voegen, neemt u contact op met het Adobe-accountteam (uw accountmanager) om uw opties te bespreken.
