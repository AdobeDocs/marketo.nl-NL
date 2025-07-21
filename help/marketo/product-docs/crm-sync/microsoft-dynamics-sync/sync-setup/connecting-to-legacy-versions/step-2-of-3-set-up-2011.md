---
unique-page-id: 3571807
description: Stap 2 van 3 - De Gebruiker van de Synchronisatie van Marketo van de opstelling in  [!DNL Dynamics]  (2011 op-Woonplaatsen) - de Documenten van Marketo - de Documentatie van het Product
title: Stap 2 van 3 - De Gebruiker van de Synchronisatie van Marketo van de opstelling in  [!DNL Dynamics]  (2011 op-Premises)
exl-id: 807c8902-24a6-48b6-a5c9-96a72764fdef
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '345'
ht-degree: 0%

---

# Stap 2 van 3: Marketo Sync User instellen in [!DNL Dynamics] (2011 op locatie) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

Als je de vorige stappen hebt uitgevoerd, ga je door.

>[!PREREQUISITES]
>
>[ Stap 1 van 3: Installeer de Oplossing van Marketo (2011 On-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"}

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-insteekmodule versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie [ Verbetering de Oplossing van Marketo voor  [!DNL Microsoft Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
>
>Taal het plaatsen van de Gebruiker van de Synchronisatie [ zou aan Engels ](https://learn.microsoft.com/en-us/power-platform/admin/enable-languages){target="_blank"} moeten worden geplaatst.

1. Selecteer **[!UICONTROL Settings]** in het menu linksonder.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. Selecteer **[!UICONTROL Administration]** in de structuur.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. Selecteer **[!UICONTROL Users]** .

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer uw specifieke synchronisatiegebruiker van Marketo of contacteer uw [ Actieve Diensten van de Federatie van de Folder (AFDS) ](https://msdn.microsoft.com/en-us/library/bb897402.aspx) beheerder om een nieuwe gebruiker tot stand te brengen die aan Marketo gewijd is. Klik op **[!UICONTROL Manage Roles]**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. Controleer **[!UICONTROL Marketo Sync User]** en klik op **[!UICONTROL OK]** .

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >Als u niet de rol ziet, ga terug naar [ stap 1 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"} en voer de oplossing in.

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen _niet_ terug naar Marketo worden gesynchroniseerd.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Selecteer **[!UICONTROL Settings]** . Selecteer vervolgens **[!UICONTROL Marketo Config]** in de structuur.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >Als [!UICONTROL Marketo Config] ontbreekt, vernieuw de pagina. Als de kwestie voortduurt, [ publiceer opnieuw de oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md) of logout en terug binnen.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. Klik op ![](assets/image2015-4-2-14-3a29-3a1.png)

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. Selecteer de synchronisatiegebruiker in het pop-upmenu. Klik vervolgens op **[!UICONTROL OK]** .

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. Klik op **[!UICONTROL Save]** om de wijzigingen op te slaan.

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. Klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

    * Als u het aantal records dat u synchroniseert wilt beperken, [stel een aangepast synchronisatiefilter in] (/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md).
    * stel het [Valideer  [!DNL Microsoft Dynamics]  Synchronisatie] (/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) proces in werking. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
    * Logboek in de Gebruiker van de Synchronisatie van Marketo in  [!DNL Microsoft Dynamics]  CRM.

Geweldig werk!

>[!MORELIKETHIS]
>
>[ Stap 3 van 3: Verbind  [!DNL Microsoft Dynamics]  met Marketo (2011 On-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2011.md)
