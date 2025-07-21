---
unique-page-id: 3571809
description: Stap 3 van 3 - verbind  [!DNL Microsoft Dynamics]  met Marketo (2011 On-Premises) - Marketo Docs - de Documentatie van het Product
title: Stap 3 van 3 - verbind  [!DNL Microsoft Dynamics]  met Marketo (2011 On-Premises)
exl-id: e6a5d49d-025a-4899-9e92-7a4c32086c67
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 0%

---

# Stap 3 van 3: Verbinding maken [!DNL Microsoft Dynamics] met Marketo (2011 op locatie) {#step-of-connect-microsoft-dynamics-with-marketo-on-premises}

Goed! We hebben de oplossing geïnstalleerd en de synchronisatiegebruiker geconfigureerd. Vervolgens moeten we Marketo en [!DNL Dynamics] verbinden.

>[!PREREQUISITES]
>
>* [ Stap 1 van 3: Installeer de Oplossing van Marketo (2011 On-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md)
>* [ Stap 2 van 3: De Gebruiker van de Synchronisatie van Marketo van de opstelling in  [!DNL Dynamics]  (2011 On-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md)

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## Voer [!DNL Dynamics] Gebruikersgegevens synchroniseren in {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **[!UICONTROL Admin]** .

   ![](assets/login-admin.png)

1. Klik op **[!UICONTROL CRM]** .

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Klik op **[!UICONTROL Microsoft]**.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 1: Enter credentials]** .

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw Marketo-abonnement aanvragen.

1. Voer **[!UICONTROL Username]** , **[!UICONTROL Password]** en CRM **[!UICONTROL URL]** in en klik op **[!UICONTROL Save]** .

   ![](assets/image2015-4-2-14-3a50-3a7.png)

   >[!NOTE]
   >
   >* [!UICONTROL Username] in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user zijn.
   >* Als u niet URL kent, [ leert hoe te om het hier ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) te vinden.

## Te synchroniseren velden selecteren {#select-fields-to-sync}

Nu moeten we de velden selecteren waarover we willen synchroniseren.

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 2: Select Fields to Sync]** .

   ![](assets/image2015-3-16-9-51-28a.png)

1. Er zijn vooraf geselecteerde velden die worden gesynchroniseerd. Voeg desgewenst meer toe en klik op **[!UICONTROL Save]** .

   ![](assets/image2016-8-25-13-3a26-3a14.png)

   >[!NOTE]
   >
   >Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een gebied in [!DNL Dynamics] schrapt, adviseerden wij het doen dit met [ gehandicapte synchronisatie ](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Dan vernieuw het schema in Marketo door [ Uitgezochte Gebieden uit te geven en op te slaan om ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md) te synchroniseren.

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar Beheer en selecteer **[!UICONTROL Microsoft Dynamics]** .

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **[!UICONTROL Edit]** op [!UICONTROL Field Sync Details] .

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-14-3a14-3a57.png)

## Synchronisatie inschakelen {#enable-sync}

1. Klik op **[!UICONTROL Edit]** in **[!UICONTROL Step 3: Enable Sync]** .

   ![](assets/image2015-3-16-9-52-2b.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd via een [!DNL Microsoft Dynamics] -synchronisatie of wanneer u handmatig personen of leads invoert.

1. Lees alles in de pop-up, ga uw e-mail in, en klik **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. Afhankelijk van het aantal records kan de eerste synchronisatie een paar uur tot een paar dagen duren. U ontvangt een e-mailbericht wanneer het is voltooid.

   ![](assets/image2014-12-11-11-3a55-3a15.png)
