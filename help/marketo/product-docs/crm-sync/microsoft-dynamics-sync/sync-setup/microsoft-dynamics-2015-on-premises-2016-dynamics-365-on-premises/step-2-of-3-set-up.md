---
unique-page-id: 7504739
description: Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 2 van 3 - Marketo Docs - Productdocumentatie
title: Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Step 2 of 3
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 0%

---


# Stap 2 van 3

<!--Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 2 of 3-->

Geweldig werk bij het voltooien van de vorige stappen. Laten we hier doorheen gaan.

>[!PREREQUISITES]
>
>* [Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3](step-1-of-3-install.md)

>



## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de rol Marketo Sync User alleen toe aan Marketo Sync user. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om uw Marketo te bevorderen, zie [Upgrade de Oplossing van de Marketo voor de Dynamica van Microsoft](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md).

1. Klik onder **Instellingen** op **Beveiliging**.

   ![](assets/assign1.png)

1. Klik **Users**.

   ![](assets/assign2.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer de specifieke Marketo Sync gebruiker of neem contact op met uw [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx)(ADFS) beheerder om een speciale gebruiker voor Marketo te maken.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klik **Rollen beheren**.

   ![](assets/assign4.png)

   Schakel Marketo Sync User in en klik op OK.

   ![](assets/assign5.png)

   >[!TIP]
   >
   >Als u de rol niet ziet, ga terug naar [stap 1 van 3](step-1-of-3-install.md) en voer de oplossing in.

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen **not** worden gesynchroniseerd terug naar Marketo.

## Marketo-oplossing {#configure-marketo-solution} configureren

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Klik onder **Instellingen** op **Marketo Config**.

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als de kwestie voortduurt, [publiceer de Oplossing van het Marketo](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) of probeer het programma openen en terug binnen.

1. Klik **Standaard**.

   ![](assets/configure2.png)

1. Klik op het veld **Marketo User** en selecteer de synchronisatiegebruiker.

   ![](assets/configure3.png)

1. Klik op het pictogram Opslaan in de rechterbenedenhoek.

   ![](assets/configure4.png)

1. Klik **Alle aanpassingen publiceren**.

   ![](assets/publish-all-customizations1.png)

## Voordat u doorgaat naar stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [moet u nu een aangepast synchronisatiefilter](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) instellen.
* Voer het proces [Validate Microsoft Dynamics Sync](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) uit. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Log in de Marketo Sync User in Microsoft Dynamics CRM.

>[!NOTE]
>
>**Verwante artikelen**
>
>[Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Step 3 van 3](step-3-of-3-connect.md)
