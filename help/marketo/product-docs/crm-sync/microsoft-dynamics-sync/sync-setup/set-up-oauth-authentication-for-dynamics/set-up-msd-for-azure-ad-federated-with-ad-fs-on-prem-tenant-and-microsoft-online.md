---
description: MSD instellen voor Azure AD Federated met AD FS On-prem, Tenant and Microsoft Online - Marketo Docs - Productdocumentatie
title: MSD instellen voor Azure AD Federated met AD FS On-prem, Tenant en Microsoft Online
exl-id: b6c10048-d27e-4135-beef-232deddc2984
source-git-commit: 91ce0914755b578c896996fae1805022cb11c438
workflow-type: tm+mt
source-wordcount: '388'
ht-degree: 0%

---

# MSD instellen voor Azure AD Federated met AD FS On-prem, Tenant en Microsoft Online {#set-up-msd-for-azure-ad-federated-with-ad-fs-on-prem-tenant-and-microsoft-online}

## Microsoft Dynamics CRM-app instellen {#set-up-microsoft-dynamics-crm-app}

1. Ga naar https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration.

1. Voer alle stappen uit. Voer bij Stap 3 een relevante toepassingsnaam in (bijvoorbeeld &quot;Marketo Integration&quot;). Selecteer onder Ondersteunde accounttypen alleen Account in deze organisatiemap.

1. Schrijf de toepassings-id (ClientId) op. Je moet het later in Marketo invoeren.

1. Toestemming van beheerder verlenen door de stappen uit te voeren in [dit artikel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md).

1. Een clientgeheim genereren in het beheercentrum door op **Certificaten en geheimen**.

   ![](assets/set-up-msd-for-azure-ad-federated-1.png)

1. Klikken **Nieuw clientgeheim**.

   ![](assets/set-up-msd-for-azure-ad-federated-2.png)

1. Een beschrijving van een clientgeheim toevoegen en klikken **Toevoegen**.

   ![](assets/set-up-msd-for-azure-ad-federated-3.png)

   >[!CAUTION]
   >
   >Zorg ervoor om nota van de Geheime waarde van de Cliënt te nemen (die in het schermafbeelding hieronder wordt gezien), aangezien u het later zult nodig hebben. Het wordt slechts één keer getoond, en u zult niet het opnieuw kunnen terugwinnen.

   ![](assets/set-up-msd-for-azure-ad-federated-4.png)

Marketo verifieert aan Azure AD met OAuth gebruikend Grant_type de Credentials van het Wachtwoord van de Eigenaar van het Middel ( ROPC). Voor dit scenario moet een Home Realm Discovery-beleid worden ontwikkeld voor de specifieke toepassing. Met dit beleid, zal Azure AD het authentificatieverzoek aan de dienst van de federatie opnieuw richten. Synchronisatie van wachtwoordhash moet hiervoor worden ingeschakeld in AD Connect. Zie voor meer informatie [OAuth met ROPC](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc) en [Een tekenbeleid instellen voor een toepassing](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application).

Aanvullende verwijzingen [hier te vinden](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&amp;text=This%20report%20also%20include%20federated,are%20federated%20to%20Azure%20AD.).

Als je klaar bent, is het tijd om **Voer de door CRM gegenereerde client-id voor Dynamics CRM in en geheim naar Marketo**.

## Voer de door CRM gegenereerde client-id voor Dynamics CRM in en geheim naar Marketo {#enter-the-dynamics-crm-generated-client-id-and-secret-into-marketo}

1. Klik in Marketo op **Beheer**.

   ![](assets/set-up-msd-for-azure-ad-federated-5.png)

1. Klikken **Microsoft Dynamics**.

   ![](assets/set-up-msd-for-azure-ad-federated-6.png)

1. Klikken **Sync uitschakelen**.

   ![](assets/set-up-msd-for-azure-ad-federated-7.png)

1. Klik op **Bewerken**.

   ![](assets/set-up-msd-for-azure-ad-federated-8.png)

1. Voer de **Client-id** en **Clientgeheim** u eerder hebt opgehaald en op **Opslaan**.

   ![](assets/set-up-msd-for-azure-ad-federated-9.png)

1. Klikken **Synchronisatie-instelling valideren**.

   ![](assets/set-up-msd-for-azure-ad-federated-10.png)

1. Klikken **Volgende**.

   ![](assets/set-up-msd-for-azure-ad-federated-11.png)

1. Alle groene vinkjes worden weergegeven. Klikken **Sluiten**.

   ![](assets/set-up-msd-for-azure-ad-federated-12.png)

   >[!NOTE]
   >
   >Als u een rode X ziet onder uw groene vinkjes, zie [dit artikel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) voor reparatieopties.

1. Klikken **Sync inschakelen**.

   ![](assets/set-up-msd-for-azure-ad-federated-13.png)

En dat is het!
