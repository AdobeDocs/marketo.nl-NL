---
unique-page-id: 7504744
description: Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 3 van 3 - Marketo Docs - Productdocumentatie
title: Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Step 3 van 3
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '323'
ht-degree: 0%

---


# Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Step 3 van 3 {#install-marketo-for-dynamics-on-prem-and-on-prem-step-of}

>[!PREREQUISITES]
>
>* [Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3](step-1-of-3-install.md)
>* [Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Step 2 of 3](step-2-of-3-set-up.md)

>



>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Gebruikersgegevens dynamiek synchroniseren invoeren {#enter-dynamics-sync-user-information}

1. Meld u aan bij Marketo en klik op **Beheer**.

   ![](assets/login-admin.png)

1. Klik op **CRM**.

   ![](assets/image2015-3-16-9-47-34.png)

1. Selecteer **Microsoft**.

   ![](assets/image2015-3-16-9-50-6.png)

1. Klik op **Bewerken** in **stap 1: Voer referenties** in.

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw abonnement op Marketo aanvragen.

1. Ga de **Gebruikersnaam**, het **Wachtwoord** een **URL** van de Dynamiek van Microsoft, en een facultatieve identiteitskaart **van de** Cliënt in. Klik op **Opslaan** als u klaar bent.

   ![](assets/client-id.png)

   >[!NOTE]
   >
   >De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#8cf9ffe9fecce8e3e1ede5e2a2efe3e1) of DOMAIN\user zijn.

   >[!TIP]
   >
   >Kent u de URL niet? Wij zullen u tonen hoe te om uw Dienst URL [van de Organisatie van de](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) Dynamica hier te vinden.

## Te synchroniseren velden selecteren {#select-fields-to-sync}

1. Klik op **Bewerken** in **stap 2: Selecteer te synchroniseren** velden.

   ![](assets/image2015-3-16-9-51-28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik op **Opslaan**.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar Admin en selecteer **de Dynamica** van Microsoft.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **Bewerken** op Veldsynchronisatiedetails.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **Opslaan**.

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## Sync inschakelen {#enable-sync}

1. Klik op **Bewerken** in **stap 3: Sync** inschakelen.

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gedecomprimeerd tegen een synchronisatie van Microsoft Dynamics of wanneer u handmatig personen invoert.

1. Lees alles in de pop-up, ga uw e-mail in, en klik **Begin Synchronisatie**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. De eerste synchronisatie kan een paar uur duren. Nadat het is gedaan, zult u een e-mailbericht ontvangen.

   ![](assets/image2015-3-16-9-59-51.png)

Uitstekend werk!
