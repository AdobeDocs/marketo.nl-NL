---
unique-page-id: 3571827
description: Stap 2 van 3 - Opstelling de Oplossing van Marketo met Server aan de Verbinding van de Server - de Documenten van Marketo - de Documentatie van het Product
title: Stap 2 van 3 - Opstelling de Oplossing van Marketo met Server aan de Verbinding van de Server
exl-id: 324e2142-2aa2-4548-9a04-683832e3ba69
feature: Microsoft Dynamics
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '583'
ht-degree: 0%

---

# Stap 2 van 3: Marketo-oplossing instellen met Server-naar-serververbinding {#step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s}

>[!PREREQUISITES]
>
>[Stap 1 van 3: Installeer de Marketo-oplossing met Server naar Server-verbinding](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md){target="_blank"}

## Clienttoepassing maken in Azure AD {#create-client-application-in-azure-ad}

1. Navigeren naar [dit Microsoft-artikel](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration){target="_blank"}.

1. Voer alle stappen uit. Voer bij Stap 3 een relevante toepassingsnaam in (bijvoorbeeld &quot;Marketo Integration&quot;). Selecteer onder Ondersteunde accounttypen de optie **Alleen account in deze organisatiedirectory**.

1. Noteer de toepassings-id (ClientId) en de huurder-id. Je moet het later in Marketo invoeren.

1. Beheerder toestemming verlenen door de stappen uit te voeren [in dit artikel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md){target="_blank"}.

1. Een clientgeheim genereren in het beheercentrum door op **[!UICONTROL Certificates & secrets]**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-1.png)

1. Klik op de knop **[!UICONTROL New client secret]** knop.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-2.png)

1. Voer een beschrijving van een clientgeheim in en klik op **[!UICONTROL Add]**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-3.png)

>[!CAUTION]
>
>Zorg ervoor om nota van de Geheime waarde van de Cliënt te nemen (die in het schermafbeelding hieronder wordt gezien), aangezien u het later zult nodig hebben. Het wordt slechts één keer getoond, en u zult niet het opnieuw kunnen terugwinnen.

![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-4.png)

## Toepassingsgebruiker maken in Microsoft {#create-application-user-in-microsoft}

1. Voer stappen uit vanaf de volgende koppeling naar [een toepassingsgebruiker instellen in Microsoft](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/use-single-tenant-server-server-authentication#application-user-creation){target="_blank"}.

   >[!IMPORTANT]
   >
   >* Zorg ervoor dat u de gebruiker van de toepassing machtigingen geeft en dat u deze toewijst aan &quot;Marketo Sync User Role&quot;.
   >* Neem nota van het e-mailadres van de Gebruiker van de Toepassing van [de optie Details weergeven](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user){target="_blank"} on Power Platform. Dit e-mailadres wordt gebruikt als gebruikersnaam bij het instellen van de verbinding met MS Dynamics in Marketo.
   >* Alle updates die door de synchronisatiegebruiker in uw CRM worden aangebracht, worden **niet** worden gesynchroniseerd naar Marketo.

## Azure AD Federated met AD FS On-prem {#azure-ad-federated-with-ad-fs-on-prem}

Federated Azure AD to ADFS Onprem heeft de creatie nodig van een Home Realm Discovery-beleid voor de specifieke toepassing. Met dit beleid, zal Azure AD het authentificatieverzoek aan de dienst van de federatie opnieuw richten. Synchronisatie van wachtwoordhash moet hiervoor worden ingeschakeld in AD Connect. Zie voor meer informatie [OAuth met ROPC](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc){target="_blank"} and [Set an hrd policy for an application](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application){target="_blank"}.

Aanvullende verwijzingen [hier te vinden](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&amp;text=This%20report%20also%20include%20federated,are%20federated%20to%20Azure%20AD.){target="_blank"}.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna daar! Alles wat we nog hebben, is om Marketo Solution te informeren over de nieuwe gebruiker die is gemaakt.

1. Ga terug naar het gedeelte Geavanceerde instellingen en klik op de knop ![](assets/image2015-5-13-15-3a49-3a19.png) pictogram naast Instellingen en selecteer **[!UICONTROL Marketo Config]**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >Als &quot;Marketo Config&quot; niet wordt weergegeven in het menu Instellingen, vernieuwt u de pagina. Als dat niet werkt, probeert u [De Marketo-oplossing publiceren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md){target="_blank"} opnieuw of logout and back in.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/fifteen.png)

1. Klik op de knop Zoeken op de knop **[!UICONTROL Marketo User]** en selecteer de synchronisatiegebruiker u creeerde.

   ![](assets/sixteen.png)

1. Klik op de knop ![](assets/image2015-3-13-15-3a10-3a11.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Klik op de knop **X** in de rechterbovenhoek om het scherm te sluiten.

   ![](assets/seventeen.png)

1. Klik op de knop ![](assets/image2015-5-13-15-3a49-3a19-1.png) pictogram naast Instellingen en selecteer **[!UICONTROL Solutions]**.

   ![](assets/eighteen.png)

1. Klik op de knop **[!UICONTROL Publish All Customizations]** knop.

   ![](assets/nineteen.png)

   >[!NOTE]
   >
   >Als u van Basisauthentificatie aan OAuth bevordert, kunt u gebruiken [dit artikel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"} om uw verificatie opnieuw te configureren.

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [een aangepast synchronisatiefilter instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} nu.
* Voer de [Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

>[!MORELIKETHIS]
>
>* [Stap 3 van 3: Verbind de Oplossing van Marketo met de Verbinding van de Server aan](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-3-of-3-connect.md){target="_blank"}
>* [Dynamische verificatiemethode opnieuw configureren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"}
