---
unique-page-id: 3571807
description: Stap 2 van 3 - Marketo Sync User in Dynamics instellen (2011 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Marketo Sync User instellen in Dynamics (2011 op locatie)
exl-id: 807c8902-24a6-48b6-a5c9-96a72764fdef
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 0%

---

# Stap 2 van 3: Marketo Sync User instellen in Dynamics (2011 op locatie) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

Als je de vorige stappen hebt uitgevoerd, ga je door.

>[!PREREQUISITES]
>
>[Stap 1 van 3: Installeer de Marketo-oplossing (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"}

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-insteekmodule versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Ga voor een upgrade van Marketo naar [Upgrade de Marketo-oplossing voor Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}.

>[!IMPORTANT]
>
>De taalinstelling van de synchronisatiegebruiker [moet worden ingesteld op Engels](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us){target="_blank"}.

1. Selecteer in het menu linksonder de optie **[!UICONTROL Settings]**.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. Selecteer in de structuur de optie **[!UICONTROL Administration]**.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. Selecteren **[!UICONTROL Users]**.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer uw toegewijde Marketo-synchronisatiegebruiker of neem contact op met [Active Directory Federation Services (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} beheerder om een nieuwe gebruiker te creëren die aan Marketo wordt gewijd. Klik op **[!UICONTROL Manage Roles]**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. Controleren **[!UICONTROL Marketo Sync User]** en klik op **[!UICONTROL OK]**.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >Als je de rol niet ziet, ga dan terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"} en importeer de oplossing.

   >[!NOTE]
   >
   >Alle updates die door de synchronisatiegebruiker in uw CRM worden aangebracht, worden _niet_ worden gesynchroniseerd naar Marketo.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Selecteren **[!UICONTROL Settings]**. Selecteer vervolgens **[!UICONTROL Marketo Config]** in de boom.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als het probleem zich blijft voordoen, [Marketo-oplossing opnieuw publiceren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"} of logout and back in.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. Klikken op ![](assets/image2015-4-2-14-3a29-3a1.png)

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. Selecteer de synchronisatiegebruiker in het pop-upmenu. Klik vervolgens op **[!UICONTROL OK]**.

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. Klikken **[!UICONTROL Save]** om de wijzigingen op te slaan

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. Klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [een aangepast synchronisatiefilter instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} nu.
* Voer de [Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

  Geweldig werk!

>[!MORELIKETHIS]
>
>[Stap 3 van 3: Connect Microsoft Dynamics met Marketo (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2011.md){target="_blank"}
