---
unique-page-id: 3571816
description: Stap 2 van 3 - vorm de Gebruiker van de Synchronisatie voor Marketo (2013 op-Woonplaatsen) - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - vorm de Gebruiker van de Synchronisatie voor Marketo (2013 op-gebouw)
translation-type: tm+mt
source-git-commit: 9d8a6d9880de5d2af211906c2410f2057c1f454d
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---


# Stap 2 van 3: Sync User for Marketo (2013 On-Premises) {#step-of-configure-sync-user-for-marketo-on-premises} configureren

Als je de vorige stappen hebt uitgevoerd, ga je door.

>[!PREREQUISITES]
>
>[Stap 1 van 3: De Marketo-oplossing in Dynamics installeren (2013 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-1-of-3-install.md)

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de rol Marketo Sync User alleen toe aan Marketo Sync user. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-plug-in versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie [Upgrade de Oplossing van de Marketo voor de Dynamica van Microsoft](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

1. Klik onder **Instellingen** op **Beheer**.

   ![](assets/image2014-12-11-11-3a13-3a19.png)

1. Selecteer **Users**.

   ![](assets/image2014-12-11-11-3a13-3a29.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer uw specifieke Marketo Sync gebruiker of neem contact op met uw [Active Directory Federation Services (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx) [beheerder om een nieuwe gebruiker te maken die is toegewezen aan Marketo.](https://blogs.technet.com/b/askpfeplat/archive/2014/04/21/introduction-to-active-directory-federation-services-ad-fs-alternateloginid-feature.aspx)

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klik ![](assets/image2015-3-26-11-3a16-3a22.png) en selecteer **Rollen beheren**

   ![](assets/image2015-3-26-11-3a18-3a6.png)

1. Schakel **Marketo Sync User** in en klik **OK**.

   ![](assets/image2014-12-11-11-3a14-3a52.png)

   >[!TIP]
   >
   >Als u de rol niet ziet, ga terug naar [stap 1 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-1-of-3-install.md) en voer de oplossing in.

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen **not** worden gesynchroniseerd terug naar Marketo.

## Marketo-oplossing {#configure-marketo-solution} configureren

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Klik onder **Instellingen** op **Marketo Config**.

   ![](assets/image2014-12-11-11-3a15-3a1.png)

   >[!NOTE]
   >
   >Als **Marketo Config** ontbreekt, probeer verfrissend de pagina. Als de kwestie voortduurt, [publiceer opnieuw de oplossing van het Marketo](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-1-of-3-install.md) of probeer het programma openen en weer binnen.

1. Klik **Standaard**.

   ![](assets/image2015-3-26-11-3a30-3a20.png)

1. Klik op het veld **Marketo User** en selecteer de synchronisatiegebruiker.

   ![](assets/image2015-3-26-11-3a29-3a13.png)

1. Klik ![](assets/image2015-3-13-15-3a10-3a11.png) in de bodem juiste hoek om de veranderingen te bewaren.

   ![](assets/image2014-12-11-11-3a15-3a32.png)

1. Klik **Alle aanpassingen publiceren**.

   ![](assets/publish-all-customizations1.png)

## Voordat u doorgaat naar stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [moet u nu een aangepast synchronisatiefilter](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) instellen.
* Voer het proces [Validate Microsoft Dynamics Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) uit. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Log in de Marketo Sync User in Microsoft Dynamics CRM.

Geweldig werk!

>[!MORELIKETHIS]
>
>[Stap 3 van 3: Connect Marketo en Dynamics (2013 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-3-of-3-connect.md)
