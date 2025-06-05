---
description: Stap 4 van 4 - Verbind de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel - Marketo Docs - de Documentatie van het Product
title: Stap 4 van 4 - Verbind de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel
exl-id: 71a52a3e-f31e-45ee-8196-d536528e42ca
feature: Microsoft Dynamics
source-git-commit: 2d3264ab75d2327f9226373aad383e7a51508589
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---

# Stap 4 van 4: Verbind de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel {#step-4-of-4-connect-the-marketo-solution-ropc}

Dit is de laatste stap van de synchronisatie. Je bent er bijna!

>[!PREREQUISITES]
>
>* [ Stap 1 van 4: Installeer de Oplossing van Marketo met de Verbinding van de Controle van het Wachtwoord van de Eigenaar van het Middel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md){target="_blank"}
>* [ Stap 2 van 4: Opstelling de Oplossing van Marketo met de Verbinding van de Controle van het Wachtwoord van de Eigenaar van het Middel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}
>* [ Stap 3 van 4: De App van de Cliënt van de opstelling op de Dynamica van MS ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md){target="_blank"}

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!NOTE]
>
>Als u van Basisauthentificatie aan OAuth bevordert, kunt u [ dit artikel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"} gebruiken om uw authentificatie opnieuw te vormen.

## Gebruikersgegevens dynamiek synchroniseren invoeren {#enter-dynamics-sync-user-information}

1. Login aan Marketo en klik **A  dmin**.

   ![](assets/login-admin.png)

1. Klik op **[!UICONTROL CRM]**.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. Selecteer **[!UICONTROL Microsoft]** .

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Enter Credentials]** .

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >Controleer of de URL van uw org correct is omdat we de volgende schemawijzigingen na verzending niet kunnen herstellen. Als een onjuiste URL voor de organisatie wordt gebruikt, moet u een nieuw Marketo-abonnement aanvragen. Als u niet URL kent, [ leert hoe te om het hier ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"} te vinden.

   >[!NOTE]
   >
   >Alvorens u nieuwe geloofsbrieven ingaat, kunt u [ hen hier bevestigen ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"}.

1. Ga **[!UICONTROL Username]** in, **[!UICONTROL Password]**, Microsoft Dynamics **URL**, **[!UICONTROL Client ID]**, en **[!UICONTROL Client Secret]**. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/step-4-of-4-connect-ropc-5.png)

   >[!NOTE]
   >
   >De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user zijn.

## Te synchroniseren velden selecteren {#select-fields-to-sync}

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Select Fields to Sync]** .

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a6-3a11.png)

>[!NOTE]
>
>Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een gebied in Dynamiek schrapt, adviseerden wij het doen dit met [ gehandicapte synchronisatie ](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md){target="_blank"}. Dan vernieuw het schema in Marketo door [ Uitgezochte Gebieden uit te geven en op te slaan om ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md){target="_blank"} te synchroniseren.

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar Beheer en selecteer **[!DNL Microsoft Dynamics]** .

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **[!UICONTROL Edit]** Veldsynchronisatiedetails.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a7-3a35.png)

## Synchronisatie inschakelen {#enable-sync}

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Enable Sync]** .

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd tegen een Microsoft Dynamics-synchronisatie of wanneer u handmatig personen of leads invoert.

1. Lees alles in pop-up, ga uw e-mailadres in, en klik **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-16-9-3a55-3a10.png)

1. Afhankelijk van het aantal records kan de eerste synchronisatie een paar uur tot een paar dagen duren. U ontvangt een e-mailbericht wanneer het is voltooid.

   ![](assets/image2015-3-16-9-3a59-3a51.png)

>[!MORELIKETHIS]
>
>[ verbeter de Methode van de Authentificatie van de Dynamiek ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"}
