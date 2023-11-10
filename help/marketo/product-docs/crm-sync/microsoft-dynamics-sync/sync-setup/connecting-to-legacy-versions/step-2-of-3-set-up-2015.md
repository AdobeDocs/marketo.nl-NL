---
unique-page-id: 7504739
description: Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 2 van 3 - Marketo Docs - Productdocumentatie
title: Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 2 van 3
exl-id: 39f00749-4ba3-47f1-b2e3-72cbaa7caf2e
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 1%

---

# Stap 2 van 3 Opstelling Marketo for Dynamics (2015 On-Prem){#step-of-set-up-for-marketo-on-premises-2015}

Geweldig werk bij het voltooien van de vorige stappen. Laten we hier doorheen gaan.

>[!PREREQUISITES]
>
>[Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"}

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Ga voor een upgrade van uw Marketo naar [Upgrade de Marketo-oplossing voor Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}.

>[!IMPORTANT]
>
>De taalinstelling van de synchronisatiegebruiker [moet worden ingesteld op Engels](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us){target="_blank"}.

1. Onder **[!UICONTROL Settings]**, klikt u op **[!UICONTROL Security]**.

   ![](assets/assign1.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/assign2.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer de toegewezen Marketo Sync-gebruiker of neem contact op met uw [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} (ADFS)-beheerder om een specifieke gebruiker voor Marketo te maken.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klik op **[!UICONTROL Manage Roles]**.

   ![](assets/assign4.png)

1. Controleer Marketo Sync User en klik op **[!UICONTROL OK]**.

   ![](assets/assign5.png)

   >[!IMPORTANT]
   >
   >De gebruiker van de Synchronisatie zou lees toestemming aan Marketo Config moeten hebben.

   >[!TIP]
   >
   >Als je de rol niet ziet, ga dan terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"} en importeer de oplossing.

   >[!NOTE]
   >
   >Alle updates die door de synchronisatiegebruiker in uw CRM worden aangebracht, worden _niet_ worden gesynchroniseerd naar Marketo.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Onder **[!UICONTROL Settings]**, klikt u op **[!UICONTROL Marketo Config]**.

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als het probleem zich blijft voordoen, [De Marketo-oplossing publiceren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"} of probeer het afmelden en weer binnen.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/configure2.png)

1. Klik op de knop **[!UICONTROL Marketo User]** en selecteer de synchronisatiegebruiker.

   ![](assets/configure3.png)

1. Klik op het pictogram Opslaan in de rechterbenedenhoek.

   ![](assets/configure4.png)

1. Klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

   >[!NOTE]
   >
   >De gebruiker van de Synchronisatie zou lees toestemming aan Marketo Config moeten hebben.

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [een aangepast synchronisatiefilter instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} nu.
* Voer de [Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

>[!MORELIKETHIS]
>
>[Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 3 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2015.md){target="_blank"}
