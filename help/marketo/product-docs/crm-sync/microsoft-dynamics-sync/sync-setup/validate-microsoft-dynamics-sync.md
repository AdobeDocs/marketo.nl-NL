---
unique-page-id: 8783322
description: Validatie Microsoft Dynamics Sync - Marketo Docs - Productdocumentatie
title: Synchronisatie van Microsoft-dynamiek valideren
translation-type: tm+mt
source-git-commit: 20d4c8a079916f47267df3dab5a8e663f6eb019b
workflow-type: tm+mt
source-wordcount: '266'
ht-degree: 0%

---


# Synchronisatie van Microsoft Dynamics {#validate-microsoft-dynamics-sync} valideren

>[!CAUTION]
>
>Als u Multi-Factor Authentificatie (MFA) hebt toegelaten voor uw Synchronisatie van de Dynamiek, moet u het onbruikbaar maken opdat de Dynamica behoorlijk met Marketo synchroniseert. Neem voor meer informatie contact op met [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

## Sync valideren in markeerteken {#run-validate-sync-in-marketo}

Het is zeer belangrijk om het Validate hulpmiddel van de Synchronisatie in werking te stellen om ervoor te zorgen uw Synchronisatie van de Dynamiek van Microsoft met Marketo correct opstelling alvorens de definitieve verbinding tussen hen te maken. Het proces produceert een controlelijst van zeven opstellingsstappen die waar de kwesties bestaan. Als u controleert of deze correct zijn uitgevoerd, bespaart u later veel tijd.

1. Klik **Admin** tabel en dan de **verbinding van de Dynamiek van Microsoft** in het gebied van de Integratie.

   ![](assets/image2015-9-28-16-3a7-3a51.png)

1. Selecteer **Microsoft**.

   ![](assets/image2015-9-28-16-3a10-3a47.png)

1. Klik op het tabblad **Synchronisatie-instellingen valideren**.

   ![](assets/image2015-9-28-16-3a11-3a45.png)

1. Voer uw gebruikersnaam, wachtwoord en URL in (Client-id en clientgeheim zijn optioneel). Klik **Volgende** wanneer gereed.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >Als u eerder hebt gesynchroniseerd, **CRM** in de linkerboom **Microsoft Dynamics** zal lezen, en de gegevens in de bovengenoemde vorm kunnen prepopulated zijn.

1. Als alles prima is, produceert Validate Sync een controlelijst vol groene controletekens ![—](assets/check.png).

   ![](assets/image2015-9-22-15-3a58-3a12.png)

1. Als u ![—](assets/delete.png) ziet, dan heeft die stap een kwestie. Zie [Problemen met validatie van dynamiek corrigeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) om het probleem op te sporen en te verhelpen. Voer vervolgens de validatiestappen voor synchroniseren opnieuw uit totdat het resultaat eruit ziet zoals in de bovenstaande afbeelding.

   >[!CAUTION]
   >
   >Momenteel ondersteunen we sandbox-vernieuwing voor Marketo Dynamics Sync niet. Als u uw zandbak van CRM van de Dynamica moet verfrissen, zal een nieuwe zandbak van de Marketo worden vereist. Neem contact op met de succesmanager van de klant voor meer informatie.

>[!MORELIKETHIS]
>
>[Problemen met validatie synchroniseren van dynamiek verhelpen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)
