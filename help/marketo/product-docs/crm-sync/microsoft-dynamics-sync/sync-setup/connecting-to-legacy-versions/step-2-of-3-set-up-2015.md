---
unique-page-id: 7504739
description: Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 2 van 3 - Marketo Docs - Productdocumentatie
title: Marketo voor Microsoft Dynamics 2015 op locatie installeren Stap 2 van 3
exl-id: 39f00749-4ba3-47f1-b2e3-72cbaa7caf2e
feature: Microsoft Dynamics
source-git-commit: e3f61755dccd9bea1378a429fc428b440fc3ecb4
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 1%

---

# Stap 2 van 3 Opstelling Marketo for Dynamics (2015 On-Prem){#step-of-set-up-for-marketo-on-premises-2015}

Geweldig werk bij het voltooien van de vorige stappen. Laten we hier doorheen gaan.

>[!PREREQUISITES]
>
>[ installeer Marketo voor Microsoft Dynamics 2015 On-Premises Stap 1 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"}

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om uw Marketo te bevorderen, zie [ Verbetering de Oplossing van Marketo voor Microsoft Dynamics ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}.

>[!IMPORTANT]
>
>Taal het plaatsen van de Gebruiker van de Synchronisatie [ zou aan Engels ](https://learn.microsoft.com/en-us/power-platform/admin/enable-languages){target="_blank"} moeten worden geplaatst.

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Security]** .

   ![](assets/assign1.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/assign2.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer de specifieke gebruiker van de Synchronisatie van Marketo of contacteer uw [ Actieve beheerder van de Federatie van de Folder van de Diensten ](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} (ADFS) om een specifieke gebruiker voor Marketo tot stand te brengen.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klik op **[!UICONTROL Manage Roles]**.

   ![](assets/assign4.png)

1. Controleer Marketo Sync User en klik op **[!UICONTROL OK]** .

   ![](assets/assign5.png)

   >[!IMPORTANT]
   >
   >De gebruiker van de Synchronisatie zou lees toestemming aan Marketo Config moeten hebben.

   >[!TIP]
   >
   >Als u niet de rol ziet, ga terug naar [ stap 1 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"} en voer de oplossing in.

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen _niet_ terug naar Marketo worden gesynchroniseerd.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Marketo Config]** .

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als de kwestie voortduurt, [ publiceer de Oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"} of probeer het programma openen en terug binnen.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/configure2.png)

1. Klik op het veld **[!UICONTROL Marketo User]** en selecteer de synchronisatiegebruiker.

   ![](assets/configure3.png)

1. Klik op het pictogram Opslaan in de rechterbenedenhoek.

   ![](assets/configure4.png)

1. Klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

   >[!NOTE]
   >
   >De gebruiker van de Synchronisatie zou lees toestemming aan Marketo Config moeten hebben.

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal verslagen wilt beperken u synchroniseert, [ opstelling een filter van de douanesynchronisatie ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} nu.
* Stel [ in werking bevestigen de Synchronisatie van Microsoft Dynamics ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

>[!MORELIKETHIS]
>
>[ installeer Marketo voor Microsoft Dynamics 2015 On-Premises Stap 3 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2015.md){target="_blank"}
