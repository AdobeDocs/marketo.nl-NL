---
unique-page-id: 3571816
description: Stap 2 van 3 - Synchronisatie van gebruiker voor Marketo configureren (2013 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Sync User for Marketo configureren (2013 op locatie)
exl-id: 27c4407e-0623-4ae0-8aa1-0b28c6c5c4f8
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 1%

---

# Stap 2 van 3: Sync User for Marketo configureren (2013 op locatie) {#step-of-configure-sync-user-for-marketo-on-premises}

Als je de vorige stappen hebt uitgevoerd, ga je door.

>[!PREREQUISITES]
>
>[Stap 1 van 3: Installeer de Marketo-oplossing in Dynamics (2013 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md){target="_blank"}

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-insteekmodule versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Ga voor een upgrade van Marketo naar [Upgrade de Marketo-oplossing voor Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}.

>[!IMPORTANT]
>
>De taalinstelling van de synchronisatiegebruiker [moet worden ingesteld op Engels](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us){target="_blank"}.

1. Onder **Instellingen**, klikt u op **Administratie**.

   ![](assets/image2014-12-11-11-3a13-3a19.png)

1. Selecteren **Gebruikers**.

   ![](assets/image2014-12-11-11-3a13-3a29.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer uw toegewijde Marketo Sync gebruiker of neem contact op met [Active Directory Federation Services (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} administrator to create a new user that's [dedicated to Marketo](https://blogs.technet.com/b/askpfeplat/archive/2014/04/21/introduction-to-active-directory-federation-services-ad-fs-alternateloginid-feature.aspx){target="_blank"}.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klik op ![](assets/image2015-3-26-11-3a16-3a22.png) en selecteer **[!UICONTROL Manage Roles]**.

   ![](assets/image2015-3-26-11-3a18-3a6.png)

1. Controleren **[!UICONTROL Marketo Sync User]** en klik op **[!UICONTROL OK]**.

   ![](assets/image2014-12-11-11-3a14-3a52.png)

   >[!TIP]
   >
   >Als je de rol niet ziet, ga dan terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md){target="_blank"} en importeer de oplossing.

   >[!NOTE]
   >
   >Alle updates die door de synchronisatiegebruiker in uw CRM worden aangebracht, worden _niet_ worden gesynchroniseerd naar Marketo.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Onder **[!UICONTROL Settings]**, klikt u op **[!UICONTROL Marketo Config]**.

   ![](assets/image2014-12-11-11-3a15-3a1.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als &quot;Marketo Config&quot; ontbreekt. Als het probleem zich blijft voordoen, [De Marketo-oplossing publiceren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md) opnieuw of probeer het afmelden en weer.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/image2015-3-26-11-3a30-3a20.png)

1. Klik op de knop **[!UICONTROL Marketo User]** en selecteer de synchronisatiegebruiker.

   ![](assets/image2015-3-26-11-3a29-3a13.png)

1. Klikken ![](assets/image2015-3-13-15-3a10-3a11.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2014-12-11-11-3a15-3a32.png)

1. Klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [een aangepast synchronisatiefilter instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} nu.
* Voer de [Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

Geweldig werk!

>[!MORELIKETHIS]
>
>[Stap 3 van 3: Connect Marketo en Dynamics (2013 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2013.md){target="_blank"}
