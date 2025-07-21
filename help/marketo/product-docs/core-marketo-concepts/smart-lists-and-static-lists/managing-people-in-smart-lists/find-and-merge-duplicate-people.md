---
unique-page-id: 557339
description: Dubbele personen zoeken en samenvoegen - Marketo Docs - Productdocumentatie
title: Dubbele personen zoeken en samenvoegen
exl-id: a6d46096-587a-4e3a-b37a-917c0d2098b1
feature: Smart Lists
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 0%

---

# Dubbele personen zoeken en samenvoegen {#find-and-merge-duplicate-people}

Marketo Engage dedupliceert automatisch wanneer nieuwe personen het systeem betreden. Uw CRM kan echter oorspronkelijk meerdere duplicaten hebben verzonden. Hieronder wordt beschreven hoe u ze samenvoegt.

>[!CAUTION]
>
>Het samenvoegen van mensen is permanent, er is geen optie &quot;ongedaan maken&quot;.

>[!PREREQUISITES]
>
>Het vinden en het samenvoegen van duplicaten zal het gebruik van [ ingebouwde/systeem Slimme Lijsten ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-built-in-system-smart-lists.md){target="_blank"} impliceren.

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
   >U kunt ook [ Dubbele Mensen met de Logica van de Douane ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-duplicate-people-with-custom-logic.md){target="_blank"} vinden.

## Personen handmatig samenvoegen {#merge-people-manually}

>[!CAUTION]
>
>Wanneer het samenvoegen van mensen, als de verliezende persoon een douanevoorwerp van Marketo heeft, zal het __ niet opnieuw worden geassocieerd aan de winnende persoon. Geef het aangepaste object opnieuw het bovenliggende element voordat u het samenvoegt.

1. Selecteer de duplicaten door Ctrl/Cmd ingedrukt te houden en te klikken en vervolgens op **[!UICONTROL Merge People]** te klikken.

   ![](assets/find-and-merge-duplicate-people-3.png)

   >[!TIP]
   >
   >U kunt twee of meer duplicaten hebben voor dezelfde persoon - en deze in één keer selecteren.

1. U zult de waarden tussen de verslagen zien die _niet_ aanpassen. Selecteer de waarde die u voor elk veld wilt behouden. Klik op **[!UICONTROL Merge]** als u klaar bent. Als u geen van beide waarden wilt, kunt u **[!UICONTROL Custom]** controleren en een waarde van uw keus ingaan.

   ![](assets/find-and-merge-duplicate-people-4.png)

   >[!NOTE]
   >
   >Wanneer u handmatig personen samenvoegt, is de eerste geselecteerde persoon de &quot;winnaar&quot;. Dus op het tabblad Personen als u record-id&#39;s 198 en 199 samenvoegt en u toevallig eerst op 199 klikt, wordt 199 de record-id van de samengevoegde personen. Dit geldt ook als meer dan twee records worden samengevoegd.

   >[!TIP]
   >
   >Samenvoegen is beter dan verwijderen. U bespaart alle historie (paginabezoeken, klikken op koppelingen, e-mail openen, invullen van formulieren, enzovoort).

## Effect in Salesforce {#effect-in-salesforce}

Als je Salesforce integreert, zijn er een paar opmerkingen over het effect van het samenvoegen van Leads in Salesforce.

* Wanneer alleen leads of alleen Contacten worden samengevoegd, worden ze samengevoegd volgens de normale [!DNL Salesforce] -regels.
* Bij het samenvoegen van leads en contactpersonen worden alle leads geconverteerd naar contactpersonen voordat de regels [!DNL Salesforce] normaal worden samengevoegd.

Voor details van Salesforce-gedrag bij het samenvoegen van leads of contactpersonen raadpleegt u de volgende [!DNL Salesforce] -documenten:

* [ het samenvoegen dubbele Leidingen ](https://help.salesforce.com/HTViewHelpDoc?id=leads_merge.htm&language=en_US){target="_blank"}
* [ het samenvoegen van Dubbele Contacten ](https://help.salesforce.com/HTViewHelpDoc?id=contacts_merge.htm&language=en_US){target="_blank"}

## Bulksamenvoeging {#bulk-merging}

Als u te veel duplicaten hebt om handmatig samen te voegen, neemt u contact op met het Adobe-accountteam (uw accountmanager) om uw opties te bespreken.
