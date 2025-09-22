---
unique-page-id: 8783322
description: Valideer  [!DNL Microsoft Dynamics]  Synchronisatie - de Documenten van Marketo - de Documentatie van het Product
title: Valideer  [!DNL Microsoft Dynamics]  Synchronisatie
exl-id: 00297a8d-36c3-42f6-a9b8-4a8dd7c1f30d
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] Sync valideren {#validate-microsoft-dynamics-sync}

>[!CAUTION]
>
>Als u MFA (Multi-Factor Authentication) hebt ingeschakeld voor uw [!DNL Dynamics] -synchronisatie, moet u deze uitschakelen voordat [!DNL Dynamics] correct kan synchroniseren met Marketo. Voor extra informatie, gelieve te contacteren {de Steun van 0} Marketo [.](https://nation.marketo.com/t5/Support/ct-p/Support)

## Synchronisatie voor validatie uitvoeren in Marketo {#run-validate-sync-in-marketo}

Het is erg belangrijk dat u het gereedschap Synchronisatie valideren uitvoert om te controleren of [!DNL Microsoft Dynamics] Synchroniseren met Marketo op de juiste wijze is ingesteld voordat u de uiteindelijke verbinding tussen beide maakt. Het proces produceert een controlelijst van zeven opstellingsstappen die waar de kwesties bestaan. Als u controleert of deze correct zijn uitgevoerd, bespaart u later veel tijd.

1. Klik op de tab **[!UICONTROL Admin]** en vervolgens op de koppeling **[!DNL Microsoft Dynamics]** in het gebied Integratie.

   ![](assets/image2015-9-28-16-3a7-3a51.png)

1. Selecteer **[!DNL Microsoft]**.

   ![](assets/image2015-9-28-16-3a10-3a47.png)

1. Klik op de tab **[!UICONTROL Validate Sync Setup]** .

   ![](assets/image2015-9-28-16-3a11-3a45.png)

1. Voer uw gebruikersnaam, wachtwoord en URL in (Client-id en clientgeheim zijn optioneel). Klik op **[!UICONTROL Next]** als u klaar bent.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >Als u eerder hebt gesynchroniseerd, **CRM** in de linkerboom zal **[!DNL Microsoft Dynamics]** lezen, en de gegevens in de bovengenoemde vorm kunnen prepopulated zijn.

1. Als alles in orde is, produceert Validate Synchronisatie een controlelijst vol groene controletekens ![— ](assets/check.png).

   ![](assets/image2015-9-22-15-3a58-3a12.png)

1. Als u ![ ](assets/delete.png) ziet, dan heeft die stap een kwestie. Zie [ Vloeiend {de Kwesties van de Synchronisatie van 1} Bevestiging  [!DNL Dynamics]  om het probleem te identificeren en te bevestigen. ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) Voer vervolgens de validatiestappen voor synchroniseren opnieuw uit totdat het resultaat eruit ziet zoals in de bovenstaande afbeelding.

   >[!CAUTION]
   >
   >Sandboxvernieuwing voor [!DNL Marketo Dynamics] synchronisatie wordt momenteel niet ondersteund. Als u de [!DNL Dynamics] CRM-sandbox moet vernieuwen, is een nieuwe Marketo-sandbox vereist. Neem contact op met de succesmanager van de klant voor meer informatie.

>[!MORELIKETHIS]
>
>[ bevestig {de Kwesties van de Synchronisatie van 1} Bevestiging  [!DNL Dynamics] ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)
