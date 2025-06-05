---
unique-page-id: 3571830
description: Stap 3 van 3 - Verbind de Oplossing van Marketo met Server aan de Verbinding van de Server - de Documenten van Marketo - de Documentatie van het Product
title: Stap 3 van 3 - Verbind de Oplossing van Marketo met de Verbinding van de Server aan
exl-id: e3ede749-f787-45d3-adb4-f71ef1221208
feature: Microsoft Dynamics
source-git-commit: 2d3264ab75d2327f9226373aad383e7a51508589
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 0%

---

# Stap 3 van 3: Verbind de Oplossing van Marketo met de Verbinding van de Server aan {#step-3-of-3-connect-microsoft-dynamics-with-marketo-solution-s2s}

Dit is de laatste stap van de synchronisatie. We zijn er bijna!

>[!PREREQUISITES]
>
>* [ Stap 1 van 3: Installeer de Oplossing van Marketo met Server aan de Verbinding van de Server ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md){target="_blank"}
>* [ Stap 2 van 3: Opstelling de Oplossing van Marketo met Server aan de Verbinding van de Server ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md){target="_blank"}

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!IMPORTANT]
>
>Als u van BasisAuthentificatie aan OAuth bevordert, zult u [ Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} voor hulp met het bijwerken van de extra parameters moeten contacteren. Als u deze functie inschakelt, wordt de synchronisatie tijdelijk gestopt totdat nieuwe referenties worden ingevoerd en de synchronisatie opnieuw wordt ingeschakeld. De functie kan worden uitgeschakeld (tot april 2022) als u wilt terugkeren naar de oude verificatiemodus.

>[!NOTE]
>
>Alvorens u nieuwe geloofsbrieven ingaat, kunt u [ hen hier bevestigen ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"}.

## Gebruikersgegevens dynamiek synchroniseren invoeren {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **[!UICONTROL Admin]** .

   ![](assets/login-admin.png)

1. Klik op **[!UICONTROL CRM]**.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. Selecteer **[!DNL Microsoft]** .

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Enter Credentials]** .

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >Controleer of de URL van uw org correct is omdat we de volgende schemawijzigingen na verzending niet kunnen herstellen. Als een onjuiste URL voor de organisatie wordt gebruikt, moet u een nieuw Marketo-abonnement aanvragen. Als u niet URL kent, [ leert hoe te om het hier ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"} te vinden.

1. Voer de gegevens van de gebruiker voor het synchroniseren van dynamiek in en klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/step-3-of-3-connect-s2s-5.png)

   >[!NOTE]
   >
   >De gebruikersbenaming in Marketo moet het [ e-mailadres ](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user){target="_blank"} van de Gebruiker van de Toepassing in CRM aanpassen. De indeling kan `user@domain.com` of DOMAIN\user zijn.

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
