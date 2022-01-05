---
description: Stap 4 van 4 - Verbind de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel - Marketo Docs - de Documentatie van het Product
title: Stap 4 van 4 - Verbind de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel
source-git-commit: 9ee27e22fec4e0ab85c193be2ea99d3c8b40568b
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---

# Stap 4 van 4: Verbind de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel {#step-4-of-4-connect-the-marketo-solution-ropc}

Dit is de laatste stap van de synchronisatie. We zijn er bijna!

>[!PREREQUISITES]
>
>* [Stap 1 van 4: De Marketo-oplossing installeren met de wachtwoordcontroleverbinding van de eigenaar van het resource](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-3-install.md)
>* [Stap 2 van 4: Stel de Marketo-oplossing in met de Wachtwoordbeheerverbinding van de Eigenaar van het Middel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-3-set-up.md)
>* [Stap 3 van 4: Client-toepassing instellen op MS Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Gebruikersgegevens dynamiek synchroniseren invoeren {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **Beheer**.

   ![](assets/login-admin.png)

1. Klikken op **CRM**.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. Selecteren **Microsoft**.

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. Klikken **Bewerken** in **Stap 1: Credentials invoeren**.

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw Marketo-abonnement aanvragen.

1. Voer de **Gebruikersnaam**, **Wachtwoord**, en Microsoft Dynamics **URL**. Klikken **Opslaan** wanneer gereed.

   ![](assets/five-1.png)

   >[!NOTE]
   >
   >* Als uw Marketo vóór oktober 2020 is ingericht, zijn Client ID en Secret optionele velden. Anders zijn ze verplicht. Het verkrijgen van deze informatie zal afhangen van welke versie van MSD u gebruikt.
   >* De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user.
   >* Als u de URL niet kent, [hier leren vinden](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).


## Te synchroniseren velden selecteren {#select-fields-to-sync}

1. Klikken **Bewerken** in **Stap 2: Te synchroniseren velden selecteren**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klikken **Opslaan**.

   ![](assets/image2016-8-25-15-3a6-3a11.png)

>[!NOTE]
>
>Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een veld verwijdert in Dynamics, wordt u aangeraden dit te doen met de opdracht [sync uitgeschakeld](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Vernieuw vervolgens het schema in Marketo door het te bewerken en op te slaan [Te synchroniseren velden selecteren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md).

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar Beheerder en selecteer **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klikken **Bewerken** op Veldsynchronisatiedetails.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klikken **Opslaan**.

   ![](assets/image2016-8-25-15-3a7-3a35.png)

## Sync inschakelen {#enable-sync}

1. Klikken **Bewerken** in **Stap 3: Sync inschakelen**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een Microsoft Dynamics-synchronisatie of wanneer u handmatig personen of leads invoert.

1. Lees alles in pop-up, ga uw e-mailadres in, en klik **Synchronisatie starten**.

   ![](assets/image2015-3-16-9-3a55-3a10.png)

1. De eerste synchronisatie kan een paar uur duren. Zodra het is gedaan, zult u een e-mailbericht ontvangen.

   ![](assets/image2015-3-16-9-3a59-3a51.png)

Uitstekend werk!
