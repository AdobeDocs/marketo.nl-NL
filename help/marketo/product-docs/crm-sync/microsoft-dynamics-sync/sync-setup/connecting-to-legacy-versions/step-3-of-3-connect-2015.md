---
unique-page-id: 7504744
description: Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 3 van 3 - Marketo Docs - Productdocumentatie
title: Marketo voor Microsoft Dynamics 2015 op locatie installeren Stap 3 van 3
exl-id: 054bf725-7a80-4114-8360-2d86e2e33dd7
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '359'
ht-degree: 0%

---

# Stap 3 van 3: Connect Marketo [!DNL Dynamics] (2015 op voorgrond) {#step-of-connect-marketo-dynamics-on-premises-2015}

>[!PREREQUISITES]
>
>* [ installeer Marketo voor  [!DNL Microsoft Dynamics]  2015 On-Premises Stap 1 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md)
>* [ installeer Marketo voor  [!DNL Microsoft Dynamics]  2015 On-Premises Stap 2 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2015.md)

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## Voer [!DNL Dynamics] Gebruikersgegevens synchroniseren in {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **[!UICONTROL Admin]** .

   ![](assets/login-admin.png)

1. Klik op **[!UICONTROL CRM]**.

   ![](assets/image2015-3-16-9-47-34.png)

1. Selecteer **[!UICONTROL Microsoft]** .

   ![](assets/image2015-3-16-9-50-6.png)

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 1: Enter Credentials]** .

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw Marketo-abonnement aanvragen.

1. Ga **[!UICONTROL Username]** in, **[!UICONTROL Password]** a [!DNL Microsoft Dynamics] **URL**, en a **[!UICONTROL Client Id]/[!UICONTROL Client Secret]**. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/step-3-of-3-5.png)

   >[!NOTE]
   >
   >* Als uw Marketo vóór oktober 2020 is ingericht, zijn Client ID en Secret optionele velden. Anders zijn ze verplicht. Het verkrijgen van deze informatie hangt af van de versie van MSD die u gebruikt.
   >* De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user zijn.
   >* Als u niet URL kent, [ leert hoe te om het hier ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"} te vinden.

   >[!TIP]
   >
   >Kent u de URL niet? Wij zullen u tonen hoe te om uw [ Dienst URL van de Organisatie van de Dynamiek ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"} hier te vinden.

## Te synchroniseren velden selecteren {#select-fields-to-sync}

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 2: Select Fields to Sync]** .

   ![](assets/image2015-3-16-9-51-28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

>[!NOTE]
>
>Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een gebied in [!DNL Dynamics] schrapt, adviseerden wij het doen dit met [ gehandicapte synchronisatie ](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Vernieuw vervolgens het schema in Marketo door het [[!UICONTROL Select Fields to Sync]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md) te bewerken en op te slaan.

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar [!UICONTROL Admin] en selecteer **[!UICONTROL Microsoft Dynamics]** .

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **[!UICONTROL Edit]** op [!UICONTROL Field Sync Details] .

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## Synchronisatie inschakelen {#enable-sync}

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 3: Enable Sync]** .

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd via een [!DNL Microsoft Dynamics] -synchronisatie of wanneer u handmatig personen invoert.

1. Lees alles in de pop-up, ga uw e-mail in, en klik **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. Afhankelijk van het aantal records kan de eerste synchronisatie een paar uur tot een paar dagen duren. U ontvangt een e-mailbericht wanneer het is voltooid.

   ![](assets/image2015-3-16-9-59-51.png)
