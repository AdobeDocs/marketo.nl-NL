---
unique-page-id: 3571819
description: Stap 3 van 3 - Connect Marketo en Dynamics (2013 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - Connect Marketo en Dynamics (2013 op locatie)
exl-id: e28f1cc3-ee15-4981-a537-6c4a1682c4c1
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '374'
ht-degree: 0%

---

# Stap 3 van 3: Connect Marketo en [!DNL Dynamics] (2013 op locatie) {#step-of-connect-marketo-and-dynamics-on-premises}

Goed! We hebben de oplossing geïnstalleerd en de synchronisatiegebruiker geconfigureerd. Vervolgens moeten we Marketo en [!DNL Dynamics] verbinden.

>[!PREREQUISITES]
>
>* [ Stap 1 van 3: Installeer de Oplossing van Marketo in  [!DNL Dynamics]  (2013 On-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md)
>* [ Stap 2 van 3: Vorm de Gebruiker van de Synchronisatie voor Marketo (2013 On-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-configure-2013.md)

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## Voer [!DNL Dynamics] Gebruikersgegevens synchroniseren in {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **[!UICONTROL Admin]** .

   ![](assets/login-admin.png)

1. Klik op **[!UICONTROL CRM]** .

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Selecteer **[!DNL Microsoft]** .

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 1: Enter Credentials]** .

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw Marketo-abonnement aanvragen.

1. Ga **[!UICONTROL Username]** in, **[!UICONTROL Password]** en [!DNL Microsoft Dynamics] **URL** dan klik **[!UICONTROL Save]**.

   ![](assets/image2015-3-26-11-3a47-3a59.png)

   >[!NOTE]
   >
   >* De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user zijn.
   >* Als u niet URL kent, [ leert hoe te om het hier ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"} te vinden.

## Te synchroniseren velden selecteren {#select-fields-to-sync}

Nu moeten we de velden selecteren waarover we willen synchroniseren.

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 2: Select Fields to Sync]** .

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a10-3a17.png)

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

   ![](assets/image2016-8-25-15-3a11-3a4.png)

## Synchronisatie inschakelen {#enable-sync}

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 3: Enable Sync]** .

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd via een [!DNL Microsoft Dynamics] -synchronisatie of wanneer u handmatig personen of leads invoert.

1. Lees alles in de pop-up, ga uw e-mail in, en klik **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. Afhankelijk van het aantal records kan de eerste synchronisatie een paar uur tot een paar dagen duren. U ontvangt een e-mailbericht wanneer het is voltooid.

   ![](assets/image2014-12-11-11-3a55-3a15.png)

Uitstekend werk! U hebt net de kracht van de bidirectionele synchronisatie tussen Marketo en [!DNL Microsoft Dynamics] ontketend. Als u [!DNL Marketo Sales Insight] hebt aangeschaft, is het nog leuker om te doen:

>[!MORELIKETHIS]
>
>[ installeer en vorm  [!DNL Marketo Sales Insight]  in  [!DNL Microsoft Dynamics]  2013 ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2013.md)
