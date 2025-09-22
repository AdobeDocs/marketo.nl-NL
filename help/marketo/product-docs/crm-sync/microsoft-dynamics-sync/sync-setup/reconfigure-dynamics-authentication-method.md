---
description: Wijzig  [!DNL Dynamics]  Methode van de Authentificatie - de Documenten van Marketo - de Documentatie van het Product
title: Wijzig  [!DNL Dynamics]  Methode van de Authentificatie
exl-id: 2bd6a992-3dfd-4e91-bec5-9fb3f7bbb840
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '253'
ht-degree: 0%

---

# Dynamische verificatiemethode opnieuw configureren {#reconfigure-dynamics-authentication-method}

Voer de onderstaande stappen uit om uw [!DNL Dynamics] verificatiemethode bij te werken.

>[!PREREQUISITES]
>
>Stel de toepassing in [!DNL Microsoft Dynamics] en in de actieve map (Azure AD/ADFS) in met de gewenste verificatiemethode in een van de volgende artikelen:
>
>* [ Stap 2 van 3: De Oplossing van Marketo van de opstelling met Server aan de Verbinding van de Server ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md){target="_blank"}
>* [ Stap 2 van 4: Opstelling de Oplossing van Marketo met de Verbinding van de Controle van het Wachtwoord van de Eigenaar van het Middel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}

1. Klik in Marketo op **[!UICONTROL Admin]** .

   ![](assets/reconfigure-dynamics-authentication-method-1.png)

1. Klik **Microsoft Dynamics**, toen **[!UICONTROL Disable Sync]**.

   ![](assets/reconfigure-dynamics-authentication-method-2.png)

   >[!NOTE]
   >
   >U moet de algemene synchronisatie tijdelijk uitschakelen om de verificatiemethode bij te werken.

1. Klik op de tab **[!UICONTROL Reconfigure New Auth Method]** .

   ![](assets/reconfigure-dynamics-authentication-method-3.png)

1. Selecteer de gewenste nieuwe Methode van de Authentificatie (in dit voorbeeld kiezen wij Web API).

   ![](assets/reconfigure-dynamics-authentication-method-4.png)

1. Voer de vereiste gegevens voor de nieuwe verificatiemethode in en klik op **[!UICONTROL Validate]** .

   ![](assets/reconfigure-dynamics-authentication-method-5.png)

   >[!NOTE]
   >
   >* De specifieke velden variëren per gekozen verificatiemethode en het formulier wordt automatisch bijgewerkt, afhankelijk van de vorige verificatiemethode.
   >* Als u al eerder hebt gesynchroniseerd, zijn de gegevens in het bovenstaande formulier mogelijk vooraf ingevuld. Voer alle gegevens opnieuw in om de juiste waarden te controleren.

1. Als alles in orde is, zal Validate Synchronisatie alle groene controletekens ![](assets/green-check.png) produceren. Controleer het bericht en klik op **[!UICONTROL Switch]** om de verificatiemethode bij te werken.

   ![](assets/reconfigure-dynamics-authentication-method-6.png)

   >[!NOTE]
   >
   >Als u een ![](assets/red-x.png) ziet, heeft die stap een probleem. Zie [ Vloeiend {de Kwesties van de Synchronisatie van 1} Bevestiging  [!DNL Dynamics]  om het probleem (de problemen) te identificeren en te bevestigen. ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) Voer vervolgens de validatiestappen voor synchroniseren opnieuw uit totdat het resultaat eruit ziet zoals in de bovenstaande afbeelding.

1. Klik op **[!UICONTROL Confirm]** om door te gaan.

   ![](assets/reconfigure-dynamics-authentication-method-7.png)

1. Klik nogmaals op **[!UICONTROL Confirm]** .

   ![](assets/reconfigure-dynamics-authentication-method-8.png)

1. Klik op **[!UICONTROL OK]**.

   >[!IMPORTANT]
   >
   >Het systeem neemt 15 minuten in beslag om de nieuwe verificatiemodus te accepteren. Wacht 15 minuten vanaf het tijdstip van de switch voordat u de synchronisatie opnieuw inschakelt.
