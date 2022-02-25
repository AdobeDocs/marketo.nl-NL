---
description: Dynamische verificatiemethode opnieuw configureren - Marketo Docs - Productdocumentatie
title: Dynamische verificatiemethode opnieuw configureren
exl-id: 2bd6a992-3dfd-4e91-bec5-9fb3f7bbb840
source-git-commit: ab20d9683aa5987778970fd32793dc0f3056c84b
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---

# Dynamische verificatiemethode opnieuw configureren {#reconfigure-dynamics-authentication-method}

Voer de onderstaande stappen uit om uw Dynamische verificatiemethode bij te werken.

>[!PREREQUISITES]
>
>Stel de toepassing in Microsoft Dynamics en active directory (Azure AD/ADFS) in met de gewenste verificatiemethode in een van de volgende artikelen:
>
>* [Stap 2 van 3: Marketo-oplossing instellen met Server naar Server-verbinding](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md)
>* [Stap 2 van 4: Stel de Marketo-oplossing in met de Wachtwoordbeheerverbinding van de Eigenaar van het Middel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md)


1. Klik in Marketo op **Beheer**.

   ![](assets/reconfigure-dynamics-authentication-method-1.png)

1. Klikken **Microsoft Dynamics** vervolgens **Sync uitschakelen**.

   ![](assets/reconfigure-dynamics-authentication-method-2.png)

   >[!NOTE]
   >
   >U moet de globale synchronisatie tijdelijk onbruikbaar maken om de Methode van de Authentificatie bij te werken.

1. Klik op de knop **Nieuwe Auteursmethode opnieuw configureren** tab.

   ![](assets/reconfigure-dynamics-authentication-method-3.png)

1. Selecteer de gewenste nieuwe Methode van de Authentificatie (in dit voorbeeld kiezen wij Web API).

   ![](assets/reconfigure-dynamics-authentication-method-4.png)

1. Voer de vereiste gegevens voor de nieuwe verificatiemethode in en klik op **Valideren**.

   ![](assets/reconfigure-dynamics-authentication-method-5.png)

   >[!NOTE]
   >
   >* De specifieke velden variëren per gekozen verificatiemethode en het formulier wordt automatisch bijgewerkt, afhankelijk van de vorige verificatiemethode.
   >* Als u al eerder hebt gesynchroniseerd, zijn de gegevens in het bovenstaande formulier mogelijk vooraf ingevuld. Voer alle gegevens opnieuw in om de juiste waarden te controleren.


1. Als alles in orde is, zal Validatie Synchronisatie alle groene controletekens produceren ![](assets/green-check.png). Controleer het bericht en klik op **Overschakelen** om de verificatiemethode bij te werken.

   ![](assets/reconfigure-dynamics-authentication-method-6.png)

   >[!NOTE]
   >
   >Als u een ![](assets/red-x.png), heeft die stap een probleem. Zie [Problemen met validatie synchroniseren van dynamiek verhelpen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) om het probleem of de problemen te identificeren en op te lossen. Voer vervolgens de validatiestappen voor synchroniseren opnieuw uit totdat het resultaat eruit ziet zoals in de bovenstaande afbeelding.

1. Klikken **Bevestigen** om verder te gaan.

   ![](assets/reconfigure-dynamics-authentication-method-7.png)

1. Klikken **Bevestigen** opnieuw.

   ![](assets/reconfigure-dynamics-authentication-method-8.png)

1. Klikken **OK**.

   >[!IMPORTANT]
   >
   >Het systeem neemt 15 minuten in beslag om de nieuwe verificatiemodus te accepteren. Wacht 15 minuten vanaf het tijdstip van de switch voordat u de synchronisatie opnieuw inschakelt.
