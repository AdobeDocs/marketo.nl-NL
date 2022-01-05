---
description: Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Step 2 of 3 - Marketo Docs - Productdocumentatie installeren
title: Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Step 2 of 3 installeren
exl-id: c789b977-7ada-4f5d-8488-e1b58963f7e3
source-git-commit: 3fb93520a653109845c3b40aba20304c6163214f
workflow-type: tm+mt
source-wordcount: '492'
ht-degree: 0%

---

# Stap 2 van 3 Opstelling Marketo for Dynamics (2016 On-Prem/Dynamics 365 On-Premises){#step-of-set-up-for-marketo-on-premises-2016}

Geweldig werk bij het voltooien van de vorige stappen. Laten we hier doorheen gaan.

>[!PREREQUISITES]
>
>[Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 1 van 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md)

## Een nieuwe gebruiker maken {#create-a-new-user}

1. Meld u aan bij Dynamics. Klik op het pictogram Instellingen en selecteer Geavanceerde instellingen.

   ![](assets/step-2-of-3-marketo-on-premises-2016-1.png)

1. Klikken **Instellingen** en selecteert u **Beveiliging**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-2.png)

1. Klikken **Gebruikers**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-3.png)

1. Klikken **Nieuw**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-4.png)

1. Klikken **Gebruikers toevoegen en licentie geven**. Er moet een nieuw tabblad worden geopend.

   ![](assets/step-2-of-3-marketo-on-premises-2016-5.png)

1. Klikken **Beheer** boven aan de pagina. Er moet een ander nieuw tabblad worden geopend.

   ![](assets/step-2-of-3-marketo-on-premises-2016-6.png)

1. Klikken **Een gebruiker toevoegen**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-7.png)

1. Voer al uw gegevens in. Als u klaar bent, klikt u op **Toevoegen**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-8.png)

   >[!NOTE]
   >
   >Deze naam moet een specifieke synchronisatiegebruiker zijn en geen bestaande rekening van de gebruiker van CRM. Het hoeft geen echt e-mailadres te zijn.

1. Voer het e-mailbericht in waarin u de nieuwe gebruikersgegevens wilt ontvangen en klik op E-mail verzenden en sluit het.

   ![](assets/step-2-of-3-marketo-on-premises-2016-9.png)

## Een nieuwe clienttoepassing maken {#create-a-new-client-application}

Voer de stappen uit in [dit Microsoft-artikel](https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/development/enabling-oauth-confidential-clients-with-ad-fs#create-an-application-group-in-ad-fs-2016-or-later) om een nieuwe Toepassing van de Cliënt tot stand te brengen en toestemmingen te verlenen. Noteer de client-id/-geheim van de Dynamic-clienttoepassing.

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Ga voor een upgrade van uw Marketo naar [Upgrade de Marketo-oplossing voor Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
>
>De taalinstelling van de synchronisatiegebruiker [moet worden ingesteld op Engels](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us).

1. Onder **Instellingen**, klikt u op **Beveiliging**.

   ![](assets/assign1.png)

1. Klikken **Gebruikers**.

   ![](assets/assign2.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer de toegewezen Marketo Sync-gebruiker of neem contact op met uw [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx)(ADFS)-beheerder om een specifieke gebruiker voor Marketo te maken.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klikken **Rollen beheren**.

   ![](assets/assign4.png)

   Controleer Marketo Sync User en klik op OK.

   ![](assets/assign5.png)

   >[!TIP]
   >
   >Als je de rol niet ziet, ga dan terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md) en importeer de oplossing.

   >[!NOTE]
   >
   >Alle updates die door de synchronisatiegebruiker in uw CRM worden aangebracht, worden **niet** worden gesynchroniseerd naar Marketo.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Onder **Instellingen**, klikt u op **Marketo Config**.

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als het probleem zich blijft voordoen, [De Marketo-oplossing publiceren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md) of probeer het afmelden en weer binnen.

1. Klikken **Standaard**.

   ![](assets/configure2.png)

1. Klik op de knop **Marketo-gebruiker** en selecteer de synchronisatiegebruiker.

   ![](assets/configure3.png)

1. Klik op het pictogram Opslaan in de rechterbenedenhoek.

   ![](assets/configure4.png)

1. Klikken **Alle aanpassingen publiceren**.

   ![](assets/publish-all-customizations1.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [een aangepast synchronisatiefilter instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) nu.
* Voer de [Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

>[!MORELIKETHIS]
>
>[Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 3 van 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-3-of-3-connect.md)
