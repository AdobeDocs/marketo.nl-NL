---
unique-page-id: 7504744
description: Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 3 van 3 - Marketo Docs - Productdocumentatie installeren
title: Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Step 3 van 3 installeren
exl-id: 054bf725-7a80-4114-8360-2d86e2e33dd7
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 0%

---

# Stap 3 van 3: Connect Marketo Dynamics (2015 On-Prem en 2016 365 On-Prem) {#step-of-connect-marketo-dynamics-on-premises-and-365}

>[!PREREQUISITES]
>
>* [Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-1-of-3-install.md)
>* [Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Step 2 of 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-2-of-3-set-up.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Voer de gebruikersgegevens voor Dynamische synchronisatie in {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **Admin**.

   ![](assets/login-admin.png)

1. Klik **CRM**.

   ![](assets/image2015-3-16-9-47-34.png)

1. Selecteer **Microsoft**.

   ![](assets/image2015-3-16-9-50-6.png)

1. Klik **Bewerken** in **Stap 1: Voer referenties in**.

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw Marketo-abonnement aanvragen.

1. Voer **Gebruikersnaam**, **Wachtwoord** een Dynamiek van Microsoft **URL**, en een **Cliënt ID/Geheim** in. Klik **Opslaan** wanneer gereed.

   ![](assets/step-3-of-3-5.png)

   >[!NOTE]
   >
   >* Als uw Marketo vóór oktober 2020 is ingericht, zijn Client ID en Secret optionele velden. Anders zijn ze verplicht. Het verkrijgen van deze informatie zal afhangen van welke versie van MSD u gebruikt.
   >* De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user zijn.
   >* Als u URL niet kent, [leer hoe te om het hier te vinden](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).


   >[!TIP]
   >
   >Kent u de URL niet? Wij zullen u tonen hoe te om uw [Dienst URL van de Organisatie van de Dynamica te vinden](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) hier.

## Te synchroniseren velden {#select-fields-to-sync} selecteren

1. Klik **Bewerken** in **Stap 2: Selecteer te synchroniseren velden**.

   ![](assets/image2015-3-16-9-51-28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik **Opslaan**.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

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

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## Sync {#enable-sync} inschakelen

1. Klik **Bewerken** in **Stap 3: Sync inschakelen**.

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gedegradeerd tegen een synchronisatie van Microsoft Dynamics of wanneer u handmatig personen invoert.

1. Lees alles in pop-up, ga uw e-mail in, en klik **Begin Synchronisatie**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. De eerste synchronisatie kan een paar uur duren. Nadat het is gedaan, zult u een e-mailbericht ontvangen.

   ![](assets/image2015-3-16-9-59-51.png)

Uitstekend werk!
