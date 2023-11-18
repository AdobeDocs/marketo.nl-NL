---
unique-page-id: 8783322
description: Microsoft Dynamics Sync valideren - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync valideren
exl-id: 00297a8d-36c3-42f6-a9b8-4a8dd7c1f30d
feature: Microsoft Dynamics
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '258'
ht-degree: 0%

---

# Microsoft Dynamics Sync valideren {#validate-microsoft-dynamics-sync}

>[!CAUTION]
>
>Als u Multi-Factor Authentication (MFA) hebt ingeschakeld voor uw Dynamics Sync, moet u deze uitschakelen om Dynamics correct te synchroniseren met Marketo. Neem voor meer informatie contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

## Synchronisatie voor validatie uitvoeren in Marketo {#run-validate-sync-in-marketo}

Het is erg belangrijk om het gereedschap Synchronisatie valideren uit te voeren om ervoor te zorgen dat de Microsoft Dynamics Sync met Marketo op de juiste wijze is ingesteld voordat de uiteindelijke verbinding tussen beide wordt gemaakt. Het proces produceert een controlelijst van zeven opstellingsstappen die waar de kwesties bestaan. Als u controleert of deze correct zijn uitgevoerd, bespaart u later veel tijd.

1. Klik op de knop **[!UICONTROL Admin]** en vervolgens de **[!DNL Microsoft Dynamics]** koppeling in het integratiegebied.

   ![](assets/image2015-9-28-16-3a7-3a51.png)

1. Selecteren **[!DNL Microsoft]**.

   ![](assets/image2015-9-28-16-3a10-3a47.png)

1. Klik op de knop **[!UICONTROL Validate Sync Setup]** tab.

   ![](assets/image2015-9-28-16-3a11-3a45.png)

1. Voer uw gebruikersnaam, wachtwoord en URL in (Client-id en clientgeheim zijn optioneel). Klikken **[!UICONTROL Next]** wanneer gereed.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >Als u eerder hebt gesynchroniseerd, **[!UICONTROL CRM]** in de linkerstructuur wordt het volgende gelezen **[!DNL Microsoft Dynamics]** en de gegevens in het bovenstaande formulier kunnen vooraf worden ingevuld.

1. Als alles prima is, genereert de functie Sync valideren een controlelijst met groene vinkjes ![—](assets/check.png).

   ![](assets/image2015-9-22-15-3a58-3a12.png)

1. Als u een ![—](assets/delete.png)Dan is er nog een probleem. Zie [Problemen met validatie synchroniseren van dynamiek verhelpen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md){target="_blank"} om het probleem te identificeren en te bevestigen. Voer vervolgens de validatiestappen voor synchroniseren opnieuw uit totdat het resultaat eruit ziet zoals in de bovenstaande afbeelding.

   >[!CAUTION]
   >
   >Sandboxvernieuwing voor Marketo Dynamics Sync wordt momenteel niet ondersteund. Als u uw zandbak van CRM van de Dynamica moet verfrissen, zal een nieuwe zandbak van Marketo worden vereist. Neem contact op met het accountteam van de Adobe (uw accountmanager) voor meer informatie.

>[!MORELIKETHIS]
>
>[Problemen met validatie synchroniseren van dynamiek verhelpen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md){target="_blank"}
