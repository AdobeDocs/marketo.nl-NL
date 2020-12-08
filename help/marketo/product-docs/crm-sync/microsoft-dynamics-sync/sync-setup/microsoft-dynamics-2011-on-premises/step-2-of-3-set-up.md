---
unique-page-id: 3571807
description: Stap 2 van 3 - De Marketo van de Opstelling synchroniseert Gebruiker in Dynamiek (2011 op-Beelden) - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - De Marketo van de Opstelling om Gebruiker in Dynamiek (2011 op-Premises) te synchroniseren
translation-type: tm+mt
source-git-commit: dc20aede0894a09e6c0bcd3d1580859b5fecb5f1
workflow-type: tm+mt
source-wordcount: '349'
ht-degree: 0%

---


# Stap 2 van 3: Marketo Sync User in Dynamics (2011 op locatie) instellen {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

Als je de vorige stappen hebt uitgevoerd, ga je door.

>[!NOTE]
>
>**Vereisten**
>
>* [Stap 1 van 3: De Marketo-oplossing installeren (2011 op locatie)](step-1-of-3-install.md)

>



## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de rol Marketo Sync User alleen toe aan Marketo Sync user. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-plug-in versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie [Verbetering de Oplossing van de Marketo voor de Dynamiek](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md)van Microsoft.

1. Selecteer **Instellingen** in het menu linksonder.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. Selecteer **Beheer** in de structuur.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. Selecteer **Gebruikers**.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer uw specifieke Marketo synchroniseert gebruiker of contacteer uw [Actieve beheerder van de Federatie van de Folder van de Diensten (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx) om een nieuwe gebruiker tot stand te brengen die aan Marketo gewijd is. Klik op Rollen **beheren**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. Schakel **Marketo Sync User** in en klik op **OK**.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >Als u de rol niet ziet, ga terug naar [stap 1 van 3](step-1-of-3-install.md) en voer de oplossing in.

   >[!NOTE]
   >
   >Updates die door de synchronisatiegebruiker in uw CRM worden uitgevoerd, worden **niet** weer gesynchroniseerd met Marketo.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Selecteer **Instellingen**. Selecteer vervolgens **Marketo Config **in de boomstructuur.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als het probleem zich blijft voordoen, [publiceert u de Marketo-oplossing opnieuw](step-1-of-3-install.md) of meldt u zich af en weer aan.

1. Klik op **Standaard**.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. Klikken op ![](assets/image2015-4-2-14-3a29-3a1.png)

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. Selecteer de synchronisatiegebruiker in het pop-upmenu. Klik vervolgens op **OK**.

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. Klik op **Opslaan** om de wijzigingen op te slaan.

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. Klik op Alle aanpassingen **publiceren**.

   ![](assets/publish-all-customizations1.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

    * Als u het aantal records dat u synchroniseert wilt beperken, moet u [een aangepast synchronisatiefilter instellen] (../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md).
    * Voer het proces [Validate Microsoft Dynamics Sync] (../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) uit. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
    * Login in de Marketo Sync Gebruiker in de Dynamica CRM van Microsoft.

Geweldig werk!

>[!NOTE]
>
>**Verwante artikelen**
>
>[Stap 3 van 3: Microsoft Dynamics verbinden met Marketo (2011 op locatie)](step-3-of-3-connect.md)

