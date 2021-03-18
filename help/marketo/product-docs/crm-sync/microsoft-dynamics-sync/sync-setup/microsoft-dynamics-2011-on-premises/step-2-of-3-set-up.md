---
unique-page-id: 3571807
description: Stap 2 van 3 - De Marketo van de Opstelling synchroniseert Gebruiker in Dynamiek (2011 op-Beelden) - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - De Marketo van de Opstelling om Gebruiker in Dynamiek (2011 op-Premises) te synchroniseren
translation-type: tm+mt
source-git-commit: 9d8a6d9880de5d2af211906c2410f2057c1f454d
workflow-type: tm+mt
source-wordcount: '350'
ht-degree: 0%

---


# Stap 2 van 3: Marketo Sync User in Dynamics (2011 op locatie) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises} instellen

Als je de vorige stappen hebt uitgevoerd, ga je door.

>[!PREREQUISITES]
>
>[Stap 1 van 3: De Marketo-oplossing installeren (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md)

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de rol Marketo Sync User alleen toe aan Marketo Sync user. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-plug-in versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie [Upgrade de Oplossing van de Marketo voor de Dynamica van Microsoft](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

1. Selecteer **Instellingen** in het menu linksonder.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. Selecteer **Beheer** in de structuur.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. Selecteer **Users**.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer uw specifieke Marketo synchroniseert gebruiker of contacteer uw [Actieve Diensten van de Federatie van de Folder (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx) beheerder om een nieuwe gebruiker tot stand te brengen die aan Marketo gewijd is. Klik **Rollen beheren**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. Schakel **Marketo Sync User** in en klik **OK**.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >Als u de rol niet ziet, ga terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md) en voer de oplossing in.

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen **not** worden gesynchroniseerd terug naar Marketo.

## Marketo-oplossing {#configure-marketo-solution} configureren

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Selecteer **Instellingen**. Selecteer vervolgens **Marketo Config** in de boomstructuur.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als de kwestie voortduurt, [publiceer opnieuw de oplossing van het Marketo](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md) of logout en terug binnen.

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
    * Login in de Marketo Sync Gebruiker in de Dynamica CRM van Microsoft.

Geweldig werk!

>[!MORELIKETHIS]
>
>[Stap 3 van 3: Microsoft Dynamics verbinden met Marketo (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-3-of-3-connect.md)
