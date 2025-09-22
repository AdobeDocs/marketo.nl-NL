---
unique-page-id: 3571827
description: Stap 2 van 3 - Opstelling de Oplossing van Marketo met Server aan de Verbinding van de Server - de Documenten van Marketo - de Documentatie van het Product
title: Stap 2 van 3 - Opstelling de Oplossing van Marketo met Server aan de Verbinding van de Server
exl-id: 324e2142-2aa2-4548-9a04-683832e3ba69
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '496'
ht-degree: 0%

---

# Stap 2 van 3: Marketo-oplossing instellen met Server-naar-serververbinding {#step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s}

>[!PREREQUISITES]
>
>[ Stap 1 van 3: Installeer de Oplossing van Marketo met Server aan de Verbinding van de Server ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md){target="_blank"}

## Clienttoepassing maken in [!DNL Azure AD] {#create-client-application-in-azure-ad}

1. Navigeer aan [ dit artikel van Microsoft ](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration){target="_blank"}.

1. Voer alle stappen uit. Voor Stap 3, ga een relevante toepassingsnaam (bijvoorbeeld, &quot;[!DNL Marketo Integration]&quot;) in. Onder de Gesteunde Types van Rekening, uitgezochte **Rekening in slechts deze Organisatorische Folder**.

1. Noteer de toepassings-id (ClientId) en de huurder-id. Je moet het later in Marketo invoeren.

1. De toestemming van Admin van de subsidie door de stappen [ in dit artikel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md){target="_blank"} te volgen.

1. Genereer een clientgeheim in het beheercentrum door op **[!UICONTROL Certificates & secrets]** te klikken.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-1.png)

1. Klik op **[!UICONTROL New client secret]** .

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-2.png)

1. Voer een beschrijving van het clientgeheim in en klik op **[!UICONTROL Add]** .

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-3.png)

>[!CAUTION]
>
>Zorg ervoor om nota van de Geheime waarde van de Cliënt te nemen (die in het schermafbeelding hieronder wordt gezien), aangezien u het later zult nodig hebben. Het wordt slechts één keer getoond, en u zult niet het opnieuw kunnen terugwinnen.

![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-4.png)

## Toepassingsgebruiker maken in Microsoft {#create-application-user-in-microsoft}

1. Volg stappen van de volgende verbinding aan [ opstelling een toepassingsgebruiker in Microsoft ](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/use-single-tenant-server-server-authentication#application-user-creation){target="_blank"}.

   >[!IMPORTANT]
   >
   >* Zorg ervoor dat u de gebruiker van de toepassing machtigingen geeft en dat u deze toewijst aan &quot;Marketo Sync User Role&quot;.
   >* Noteer het e-mailadres van de Gebruiker van de Toepassing van de [ optie van meningsdetails ](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user) op het Platform van de Macht. Dit e-mailadres wordt gebruikt als gebruikersnaam bij het instellen van de verbinding met MS [!DNL Dynamics] in Marketo.

## [!DNL Azure AD] Gecombineerd met [!DNL AD FS On-prem] {#azure-ad-federated-with-ad-fs-on-prem}

Federated [!DNL Azure AD] to [!DNL ADFS Onprem] heeft de creatie van een beleid van de Ontdekking van het Huis voor de specifieke toepassing nodig. Met dit beleid, [!DNL Azure AD] zal het authentificatieverzoek aan de dienst van de federatie opnieuw richten. Synchronisatie van wachtwoordhash moet hiervoor in [!DNL AD Connect] zijn ingeschakeld. Voor meer informatie, gelieve te zien [[!DNL OAuth]  met  [!DNL ROPC] ](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc) en [ plaats een harde beleid voor een toepassing ](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application).

De extra verwijzingen [ kunnen hier ](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&text=This%20report%20also%20include%20federated,are%20federated%20to%20Azure%20AD.){target="_blank"} worden gevonden.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna daar! Alles wat we nog hebben, is om Marketo Solution te informeren over de nieuwe gebruiker die is gemaakt.

1. Ga terug naar de sectie [!UICONTROL Advanced Settings] , klik op het pictogram ![](assets/image2015-5-13-15-3a49-3a19.png) naast [!UICONTROL Settings] en selecteer **[!UICONTROL Marketo Config]** .

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >Als &quot;Marketo Config&quot; niet wordt weergegeven in het menu Instellingen, vernieuwt u de pagina. Als dat niet werkt, probeer [ om de Oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md){target="_blank"} opnieuw te publiceren of logout en terug binnen.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/fifteen.png)

1. Klik op de zoekknop in het veld **[!UICONTROL Marketo User]** en selecteer de synchronisatiegebruiker die u hebt gemaakt.

   ![](assets/sixteen.png)

1. Klik op het pictogram ![](assets/image2015-3-13-15-3a10-3a11.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Klik **X** in het hoger-recht om het scherm te sluiten.

   ![](assets/seventeen.png)

1. Klik op het pictogram ![](assets/image2015-5-13-15-3a49-3a19-1.png) naast [!UICONTROL Settings] en selecteer **[!UICONTROL Solutions]** .

   ![](assets/eighteen.png)

1. Klik op **[!UICONTROL Publish All Customizations]** .

   ![](assets/nineteen.png)

   >[!NOTE]
   >
   >Als u van Basisauthentificatie aan [!DNL OAuth] bevordert, kunt u [ dit artikel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md) gebruiken om uw authentificatie aan te passen.

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal verslagen wilt beperken u synchroniseert, [ opstelling een filter van de douanesynchronisatie ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) nu.
* Stel [ in werking bevestigt  [!DNL Microsoft Dynamics]  Synchronisatie ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in [!DNL Microsoft Dynamics] CRM.

>[!MORELIKETHIS]
>
>* [ Stap 3 van 3: Verbind de Oplossing van Marketo met Server met de Verbinding van de Server ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-3-of-3-connect.md)
>* [ herfiguur  [!DNL Dynamics]  Methode van de Authentificatie ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md)
