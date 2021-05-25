---
unique-page-id: 7504739
description: Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 2 van 3 - Marketo Docs - Productdocumentatie installeren
title: Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Step 2 of 3 installeren
exl-id: 39f00749-4ba3-47f1-b2e3-72cbaa7caf2e
source-git-commit: 5473e1a78769ba23e9c3a5926407cf42ef9685a0
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---

# Stap 2 van 3 Opstelling Marketo for Dynamics (2015 On-Prem en 2016 365 On-Prem){#step-of-set-up-for-marketo-on-premises-and-365}

Geweldig werk bij het voltooien van de vorige stappen. Laten we hier doorheen gaan.

>[!PREREQUISITES]
[Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-1-of-3-install.md)>
>

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om uw Marketo te bevorderen, zie [Upgrade de Oplossing van Marketo voor de Dynamica van Microsoft](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
De taalinstelling van de synchronisatiegebruiker [moet worden ingesteld op Engels](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us).

1. Klik onder **Instellingen** op **Beveiliging**.

   ![](assets/assign1.png)

1. Klik **Users**.

   ![](assets/assign2.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer de specifieke Marketo Sync-gebruiker of neem contact op met uw [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx)(ADFS)-beheerder om een speciale gebruiker voor Marketo te maken.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klik **Rollen beheren**.

   ![](assets/assign4.png)

   Controleer Marketo Sync User en klik op OK.

   ![](assets/assign5.png)

   >[!TIP]
   Als u de rol niet ziet, ga terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-1-of-3-install.md) en voer de oplossing in.

   >[!NOTE]
   Updates die door de synchronisatiegebruiker in uw CRM worden gemaakt, worden **niet** gesynchroniseerd naar Marketo.

## Marketo-oplossing {#configure-marketo-solution} configureren

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Klik onder **Instellingen** op **Marketo Config**.

   ![](assets/configure1.png)

   >[!NOTE]
   Vernieuw de pagina als Marketo Config ontbreekt. Als de kwestie voortduurt, [publiceer de Oplossing van Marketo](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-1-of-3-install.md) of probeer het programma openen en terug binnen.

1. Klik **Standaard**.

   ![](assets/configure2.png)

1. Klik op het veld **Marketo User** en selecteer de synchronisatiegebruiker.

   ![](assets/configure3.png)

1. Klik op het pictogram Opslaan in de rechterbenedenhoek.

   ![](assets/configure4.png)

1. Klik **Alle aanpassingen publiceren**.

   ![](assets/publish-all-customizations1.png)

## Voordat u doorgaat naar stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [moet u nu een aangepast synchronisatiefilter](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) instellen.
* Voer het proces [Validate Microsoft Dynamics Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) uit. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

>[!MORELIKETHIS]
[Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Step 3 van 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-3-of-3-connect.md)
