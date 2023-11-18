---
description: Dynamische verificatiemethode opnieuw configureren - Marketo Docs - Productdocumentatie
title: Dynamische verificatiemethode opnieuw configureren
exl-id: 2bd6a992-3dfd-4e91-bec5-9fb3f7bbb840
feature: Microsoft Dynamics
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '252'
ht-degree: 0%

---

# Dynamische verificatiemethode opnieuw configureren {#reconfigure-dynamics-authentication-method}

Voer de onderstaande stappen uit om uw Dynamische verificatiemethode bij te werken.

>[!PREREQUISITES]
>
>Stel de toepassing in Microsoft Dynamics en active directory (Azure AD/ADFS) in met de gewenste verificatiemethode in een van de volgende artikelen:
>
>* [Stap 2 van 3: Marketo-oplossing instellen met Server-naar-serververbinding](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md){target="_blank"}
>* [Stap 2 van 4: Opstelling de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}

1. Klik in Marketo Engage op **[!UICONTROL Admin]**.

   ![](assets/reconfigure-dynamics-authentication-method-1.png)

1. Klikken **[!DNL Microsoft Dynamics]** vervolgens **[!UICONTROL Disable Sync]**.

   ![](assets/reconfigure-dynamics-authentication-method-2.png)

   >[!NOTE]
   >
   >U moet de algemene synchronisatie tijdelijk uitschakelen om de verificatiemethode bij te werken.

1. Klik op de knop **[!UICONTROL Reconfigure New Auth Method]** tab.

   ![](assets/reconfigure-dynamics-authentication-method-3.png)

1. Selecteer de gewenste nieuwe Methode van de Authentificatie (in dit voorbeeld kiezen wij Web API).

   ![](assets/reconfigure-dynamics-authentication-method-4.png)

1. Voer de vereiste gegevens voor de nieuwe verificatiemethode in en klik op **[!UICONTROL Validate]**.

   ![](assets/reconfigure-dynamics-authentication-method-5.png)

   >[!NOTE]
   >
   >* De specifieke velden variëren per gekozen verificatiemethode en het formulier wordt automatisch bijgewerkt, afhankelijk van de vorige verificatiemethode.
   >* Als u al eerder hebt gesynchroniseerd, zijn de gegevens in het bovenstaande formulier mogelijk vooraf ingevuld. Voer alle gegevens opnieuw in om de juiste waarden te controleren.

1. Als alles in orde is, zal Validatie Synchronisatie alle groene controletekens produceren ![](assets/green-check.png). Controleer het bericht en klik op **[!UICONTROL Switch]** de verificatiemethode bijwerken.

   ![](assets/reconfigure-dynamics-authentication-method-6.png)

   >[!NOTE]
   >
   >Als u een ![](assets/red-x.png), heeft die stap een probleem. Zie [Problemen met validatie synchroniseren van dynamiek verhelpen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md){target="_blank"} om het probleem of de problemen te identificeren en op te lossen. Voer vervolgens de validatiestappen voor synchroniseren opnieuw uit totdat het resultaat eruit ziet zoals in de bovenstaande afbeelding.

1. Klikken **[!UICONTROL Confirm]** om verder te gaan.

   ![](assets/reconfigure-dynamics-authentication-method-7.png)

1. Klikken **[!UICONTROL Confirm]** opnieuw.

   ![](assets/reconfigure-dynamics-authentication-method-8.png)

1. Klik op **[!UICONTROL OK]**.

   >[!IMPORTANT]
   >
   >Het systeem neemt 15 minuten in beslag om de nieuwe verificatiemodus te accepteren. Wacht 15 minuten vanaf het tijdstip van de switch voordat u de synchronisatie opnieuw inschakelt.
