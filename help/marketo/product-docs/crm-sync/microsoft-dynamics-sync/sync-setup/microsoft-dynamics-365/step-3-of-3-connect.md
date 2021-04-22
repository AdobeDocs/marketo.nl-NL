---
unique-page-id: 3571830
description: Stap 3 van 3 - Connect Microsoft Dynamics met Marketo (Online) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - Connect Microsoft Dynamics met Marketo (Online)
exl-id: e3ede749-f787-45d3-adb4-f71ef1221208
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---

# Stap 3 van 3: Microsoft Dynamics verbinden met Marketo (Online) {#step-of-connect-microsoft-dynamics-with-marketo-online}

Dit is de laatste stap van de synchronisatie. We zijn er bijna!

>[!PREREQUISITES]
>
>* [Stap 1 van 3: De Marketo-oplossing installeren (online)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-1-of-3-install.md)
>* [Stap 2 van 3: Marketo Sync User instellen in Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-2-of-3-set-up.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Voer de gebruikersgegevens voor Dynamische synchronisatie in {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **Admin**.

   ![](assets/login-admin.png)

1. Klik op **CRM**.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. Selecteer **Microsoft**.

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. Klik **Bewerken** in **Stap 1: Voer referenties in**.

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw Marketo-abonnement aanvragen.

1. Voer **Gebruikersnaam**, **Wachtwoord** en de Dynamica van Microsoft **URL** in. Klik **Opslaan** wanneer gereed.

   ![](assets/five-1.png)

   >[!NOTE]
   >
   >* Als uw Marketo vóór oktober 2020 is ingericht, zijn Client ID en Secret optionele velden. Anders zijn ze verplicht. Het verkrijgen van deze informatie zal afhangen van welke versie van MSD u gebruikt.
   >* De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user zijn.
   >* Als u URL niet kent, [leer hoe te om het hier te vinden](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).


## Te synchroniseren velden {#select-fields-to-sync} selecteren

1. Klik **Bewerken** in **Stap 2: Selecteer te synchroniseren velden**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik **Opslaan**.

   ![](assets/image2016-8-25-15-3a6-3a11.png)

>[!NOTE]
>
>Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een gebied in Dynamiek schrapt, adviseren wij dit met [sync gehandicapt](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Vernieuw vervolgens het schema in Marketo door de [Selecteer te synchroniseren velden ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md) te bewerken en op te slaan.

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar Admin en selecteer **de Dynamica van Microsoft**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **Bewerken** op Details van veldsynchronisatie.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik **Opslaan**.

   ![](assets/image2016-8-25-15-3a7-3a35.png)

## Sync {#enable-sync} inschakelen

1. Klik **Bewerken** in **Stap 3: Sync inschakelen**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een Microsoft Dynamics-synchronisatie of wanneer u handmatig personen of leads invoert.

1. Lees alles in pop-up, ga uw e-mailadres in, en klik **Begin Synchronisatie**.

   ![](assets/image2015-3-16-9-3a55-3a10.png)

1. De eerste synchronisatie kan een paar uur duren. Zodra het is gedaan, zult u een e-mailbericht ontvangen.

   ![](assets/image2015-3-16-9-3a59-3a51.png)

Uitstekend werk!
