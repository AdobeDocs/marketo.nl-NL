---
unique-page-id: 3571807
description: Stap 2 van 3 - Marketo Sync User in Dynamics instellen (2011 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Marketo Sync User instellen in Dynamics (2011 op locatie)
exl-id: 807c8902-24a6-48b6-a5c9-96a72764fdef
source-git-commit: 5473e1a78769ba23e9c3a5926407cf42ef9685a0
workflow-type: tm+mt
source-wordcount: '369'
ht-degree: 0%

---

# Stap 2 van 3: Marketo Sync-gebruiker instellen in dynamiek (2011 op locatie) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

Als je de vorige stappen hebt uitgevoerd, ga je door.

>[!PREREQUISITES]
[Stap 1 van 3: De Marketo-oplossing installeren (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md)>
>

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
Dit geldt voor Marketo-insteekmodule versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie [Upgrade de Oplossing van Marketo voor de Dynamica van Microsoft](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
De taalinstelling van de synchronisatiegebruiker [moet worden ingesteld op Engels](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us).

1. Selecteer **Instellingen** in het menu linksonder.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. Selecteer **Beheer** in de structuur.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. Selecteer **Users**.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer uw specifieke Marketo synchronisatiegebruiker of neem contact op met uw [Active Directory Federation Services (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx)-beheerder om een nieuwe gebruiker te maken die speciaal voor Marketo is bestemd. Klik **Rollen beheren**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. Schakel **Marketo Sync User** in en klik **OK**.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   Als u de rol niet ziet, ga terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md) en voer de oplossing in.

   >[!NOTE]
   Updates die door de synchronisatiegebruiker in uw CRM worden gemaakt, worden **niet** gesynchroniseerd naar Marketo.

## Marketo-oplossing {#configure-marketo-solution} configureren

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Selecteer **Instellingen**. Selecteer vervolgens **Marketo Config** in de boomstructuur.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   Vernieuw de pagina als Marketo Config ontbreekt. Als het probleem zich blijft voordoen, [publiceert u de Marketo-oplossing opnieuw](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md) of meldt u zich af en weer aan.

1. Klik **Standaard**.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. Klik op ![](assets/image2015-4-2-14-3a29-3a1.png)

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. Selecteer de synchronisatiegebruiker in het pop-upmenu. Klik vervolgens op **OK**.

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. Klik **Opslaan** om de wijzigingen op te slaan.

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. Klik **Alle aanpassingen publiceren**.

   ![](assets/publish-all-customizations1.png)

## Voordat u doorgaat naar stap 3 {#before-proceeding-to-step}

    * Als u het aantal records dat u synchroniseert wilt beperken, moet u [een aangepast synchronisatiefilter instellen] (/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md).
    * Voer het proces [Validate Microsoft Dynamics Sync] (/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) uit. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
    * Log in the Marketo Sync User in Microsoft Dynamics CRM.

Geweldig werk!

>[!MORELIKETHIS]
[Stap 3 van 3: Connect Microsoft Dynamics met Marketo (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-3-of-3-connect.md)
