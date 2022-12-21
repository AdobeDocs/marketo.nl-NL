---
unique-page-id: 557339
description: Dubbele personen zoeken en samenvoegen - Marketo Docs - Productdocumentatie
title: Dubbele personen zoeken en samenvoegen
exl-id: a6d46096-587a-4e3a-b37a-917c0d2098b1
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 0%

---

# Dubbele personen zoeken en samenvoegen {#find-and-merge-duplicate-people}

Marketo dedupliceert automatisch wanneer nieuwe personen het systeem betreden. Uw CRM heeft echter mogelijk in eerste instantie dubbele gegevens naar Marketo verzonden. Hieronder wordt beschreven hoe u ze samenvoegt.

>[!NOTE]
>
>Marketo wordt niet automatisch gededupliceerd bij een synchronisatie met Salesforce of Microsoft Dynamics of wanneer u handmatig personen invoert.

>[!PREREQUISITES]
>
>Bij het zoeken naar en het samenvoegen van duplicaten wordt gebruik gemaakt van [ingebouwde/systeem slimme lijsten](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-built-in-system-smart-lists.md).

## Duplicaten zoeken {#find-duplicates}

1. Ga naar de **Database** gebied.

   ![](assets/db.png)

   >[!CAUTION]
   >
   >Het samenvoegen van personen in Marketo werkt mogelijk niet als u een Salesforce Person-account gebruikt. Voeg indien mogelijk de records in Salesforce samen.

1. Selecteer **Mogelijke duplicaten** de slimme lijst van het systeem en klik op **Mensen** tab.

   ![](assets/two.png)

   >[!NOTE]
   >
   >U kunt ook [Dubbele mensen zoeken met aangepaste logica](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-duplicate-people-with-custom-logic.md).

## Personen handmatig samenvoegen {#merge-people-manually}

>[!CAUTION]
>
>Als de verliezende persoon bij het samenvoegen van personen een aangepast Marketo-object heeft, wordt **niet** opnieuw aan de winnende persoon worden geassocieerd. Geef het aangepaste object opnieuw het bovenliggende element voordat u het samenvoegt.

1. Selecteer de duplicaten door Ctrl/Cmd ingedrukt te houden en te klikken en klik vervolgens op **Personen samenvoegen**.

   ![](assets/three.png)

   >[!TIP]
   >
   >U kunt twee of meer duplicaten hebben voor dezelfde persoon - en deze in één keer selecteren.

1. U ziet de waarden tussen de records die _niet_ match. Selecteer de waarde die u voor elk veld wilt behouden. Klikken **Samenvoegen** wanneer gereed. Als u geen van beide waarden wilt, kunt u controleren **Aangepast** en voer een waarde naar keuze in.

   ![](assets/four.png)

   >[!NOTE]
   >
   >Wanneer u handmatig personen samenvoegt, is de eerste geselecteerde persoon de &quot;winnaar&quot;. Dus op het tabblad Personen als u record-id&#39;s 198 en 199 samenvoegt en u toevallig eerst op 199 klikt, wordt 199 de record-id van de samengevoegde personen. Dit geldt ook als meer dan twee records worden samengevoegd.

   >[!TIP]
   >
   >Samenvoegen is beter dan verwijderen. U bespaart alle historie (paginabezoeken, klikken op koppelingen, e-mail openen, invullen van formulieren, enzovoort).

## Effect bij Salesforce {#effect-in-salesforce}

Als je Salesforce-integratie hebt, zijn er een paar notities over het effect van Samenvoegen van Leads in Salesforce.

* Bij het samenvoegen van alleen leads of alleen Contacten worden deze samengevoegd volgens de normale Salesforce-regels.
* Bij het samenvoegen van leads en contactpersonen worden alle leads geconverteerd naar contactpersonen voordat ze worden samengevoegd volgens de normale Salesforce-regels.

Voor details van Salesforce gedrag wanneer het samenvoegen van Leads of Contacten, gelieve de volgende documenten te controleren Salesforce:

* [Dubbele leads samenvoegen](https://help.salesforce.com/HTViewHelpDoc?id=leads_merge.htm&amp;language=en_US)
* [Dubbele contactpersonen samenvoegen](https://help.salesforce.com/HTViewHelpDoc?id=contacts_merge.htm&amp;language=en_US)

## Bulksamenvoeging {#bulk-merging}

Als u te veel duplicaten hebt om handmatig samen te voegen, neemt u contact op met de succesmanager van de klant om uw opties te bespreken.

Super! Als u met CRM wordt verbonden zullen de verslagen daar volgens de hieronder regels samenvoegen.
