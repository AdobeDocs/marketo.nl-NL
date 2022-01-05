---
unique-page-id: 3571827
description: Stap 2 van 3 - Opstelling de Oplossing van Marketo met S2S Verbinding - de Documenten van Marketo - de Documentatie van het Product
title: Stap 2 van 3 - Opstelling de Oplossing van Marketo met Verbinding S2S
exl-id: 324e2142-2aa2-4548-9a04-683832e3ba69
source-git-commit: 598390517dea96b0503fd9c0cdfd47bd7617b48a
workflow-type: tm+mt
source-wordcount: '659'
ht-degree: 0%

---

# Stap 2 van 3: Marketo Sync User instellen in Dynamics met S2S Connection{#step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s}

>[!PREREQUISITES]
>
>[Stap 1 van 3: De Marketo-oplossing installeren met S2S-verbinding](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md)

## Clienttoepassing maken in Azure AD {#create-client-application-in-azure-ad}

1. Navigeren naar [dit Microsoft-artikel](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration).

1. Voer alle stappen uit. Voer bij Stap 3 een relevante toepassingsnaam in (bijvoorbeeld &quot;Marketo Integration&quot;). Selecteer onder Ondersteunde accounttypen de optie **Alleen account in deze organisatiedirectory**.

1. Noteer de toepassings-id (ClientId) en de huurder-id. Je moet het later in Marketo invoeren.

1. Beheerder toestemming verlenen door de stappen uit te voeren [in dit artikel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md).

1. Een clientgeheim genereren in het beheercentrum door op **Certificaten en geheimen**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-1.png)

1. Klik op de knop **Nieuw clientgeheim** knop.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-2.png)

1. Voer een beschrijving van een clientgeheim in en klik op **Toevoegen**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-3.png)

>[!CAUTION]
>
>Zorg ervoor om nota van de Geheime waarde van de Cliënt te nemen (die in het schermafbeelding hieronder wordt gezien), aangezien u het later zult nodig hebben. Het wordt slechts één keer getoond, en u zult niet het opnieuw kunnen terugwinnen.

![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-4.png)

1. Voer stappen uit vanaf de volgende koppeling naar [een toepassingsgebruiker instellen in Microsoft](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/use-single-tenant-server-server-authentication#application-user-creation). Wijs tijdens het geven van machtigingen aan de Application User de gebruikersrol Marketo Sync toe.

## Azure AD Federated met AD FS On-prem {#azure-ad-federated-with-ad-fs-on-prem}

Federated Azure AD to ADFS Onprem heeft de creatie nodig van een Home Realm Discovery-beleid voor de specifieke toepassing. Met dit beleid, zal Azure AD het authentificatieverzoek aan de dienst van de federatie opnieuw richten. Synchronisatie van wachtwoordhash moet hiervoor worden ingeschakeld in AD Connect. Zie voor meer informatie [OAuth met ROPC](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc) en [Een tekenbeleid instellen voor een toepassing](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application).

Aanvullende verwijzingen [hier te vinden](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&amp;text=This%20report%20also%20include%20federated,are%20federated%20to%20Azure%20AD.).

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

1. Wijs de Marketo Sync User-rol alleen toe aan de Marketo sync-gebruiker.

>[!NOTE]
>
>Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om uw Marketo-oplossing te upgraden, [zie dit artikel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

1. Ga terug naar het tabblad Toepassingsgebruikers en vernieuw de gebruikerslijst.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-5.png)

1. Houd de muisaanwijzer boven de nieuwe toepassingsgebruiker en schakel het selectievakje in. Klik om het te selecteren.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-6.png)

1. Klikken **Rollen beheren**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-7.png)

1. Controleren **Marketo Sync-gebruiker** en klik op **OK**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-8.png)

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna daar! Alles wat we nog hebben, is om Marketo Solution te informeren over de nieuwe gebruiker die is gemaakt.

>[!IMPORTANT]
>
>Als u een upgrade uitvoert van Basisverificatie naar OAuth, dient u contact op te nemen met [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support) voor hulp bij het bijwerken van de aanvullende parameters. Als u deze functie inschakelt, wordt de synchronisatie tijdelijk gestopt totdat nieuwe referenties worden ingevoerd en de synchronisatie opnieuw wordt ingeschakeld. De functie kan worden uitgeschakeld (tot april 2022) als u wilt terugkeren naar de oude verificatiemodus.

1. Ga terug naar het gedeelte Geavanceerde instellingen en klik op de knop ![](assets/image2015-5-13-15-3a49-3a19.png) pictogram naast Instellingen en selecteer **Marketo Config**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >Als u het niet ziet **Marketo Config** vernieuwt de pagina in het menu Instellingen. Als dat niet werkt, probeert u [De Marketo-oplossing publiceren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md) opnieuw of logout and back in.

1. Klikken **Standaard**.

   ![](assets/fifteen.png)

1. Klik op de knop Zoeken op de knop **Marketo-gebruiker** en selecteer de synchronisatiegebruiker u creeerde.

   ![](assets/sixteen.png)

1. Klik op de knop ![](assets/image2015-3-13-15-3a10-3a11.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Klik op de knop **X** in de rechterbovenhoek om het scherm te sluiten.

   ![](assets/seventeen.png)

1. Klik op de knop ![](assets/image2015-5-13-15-3a49-3a19-1.png) pictogram naast Instellingen en selecteer **Oplossingen**.

   ![](assets/eighteen.png)

1. Klik op de knop **Alle aanpassingen publiceren** knop.

   ![](assets/nineteen.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [een aangepast synchronisatiefilter instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) nu.
* Voer de [Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

>[!MORELIKETHIS]
>
>[Stap 3 van 3: Verbind de Oplossing van Marketo met Verbinding S2S](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-3-of-3-connect.md)
