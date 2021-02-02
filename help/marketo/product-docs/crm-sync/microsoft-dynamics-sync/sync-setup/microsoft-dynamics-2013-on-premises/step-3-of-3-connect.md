---
unique-page-id: 3571819
description: Stap 3 van 3 -Connect Marketo and Dynamics (2013 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 -Connect Marketo and Dynamics (2013 op locatie)
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---


# Stap 3 van 3: Marketo en dynamiek verbinden (2013 op locatie) {#step-of-connect-marketo-and-dynamics-on-premises}

Goed! We hebben de oplossing geïnstalleerd en de synchronisatiegebruiker geconfigureerd. Daarna, moeten wij Marketo en Dynamiek verbinden.

>[!PREREQUISITES]
>
>* [Stap 1 van 3: De Marketo-oplossing in Dynamics installeren (2013 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-1-of-3-install.md)
>* [Stap 2 van 3: Sync User for Marketo configureren (2013 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-2-of-3-configure.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Voer gebruikersgegevens voor dynamicasynchronisatie {#enter-dynamics-sync-user-information} in

1. Meld u aan bij Marketo en klik op **Admin**.

   ![](assets/login-admin.png)

1. Klik op **CRM**.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Selecteer **Microsoft**.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. Klik **Bewerken** in **Stap 1: Voer referenties in**.

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw abonnement op Marketo aanvragen.

1. Voer **Gebruikersnaam**, **Wachtwoord** en de Dynamiek van Microsoft **URL** in dan klik **sparen**.

   ![](assets/image2015-3-26-11-3a47-3a59.png)

   >[!NOTE]
   >
   >De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan user@domain.com of DOMAIN\user zijn.

   >[!TIP]
   >
   >Kent u de URL niet? Wij zullen u tonen hoe te om [de Dienst URL van de Organisatie van de Dynamiek ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) hier te vinden.

## Te synchroniseren velden {#select-fields-to-sync} selecteren

Nu moeten we de velden selecteren waarover we willen synchroniseren.

1. Klik **Bewerken** in **Stap 2: Selecteer te synchroniseren velden**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik **Opslaan**.

   ![](assets/image2016-8-25-15-3a10-3a17.png)

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar Admin en selecteer **de Dynamica van Microsoft**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **Bewerken** op Details van veldsynchronisatie.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik **Opslaan**.

   ![](assets/image2016-8-25-15-3a11-3a4.png)

## Sync {#enable-sync} inschakelen

1. Klik **Bewerken** in **Stap 3: Sync inschakelen**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een synchronisatie met Microsoft Dynamics, of wanneer u handmatig personen of leads invoert.

1. Lees alles in pop-up, ga uw e-mail in, en klik **Begin Synchronisatie**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. De eerste synchronisatie kan een paar uur duren. Nadat het is gedaan, zult u een e-mailbericht ontvangen.

   ![](assets/image2014-12-11-11-3a55-3a15.png)

Uitstekend werk! U hebt net de kracht van de bidirectionele synchronisatie tussen Marketo en de Dynamica van Microsoft ontketend. Als je Marketo Sales Insight hebt aangeschaft, is het meer leuk om te hebben:

>[!MORELIKETHIS]
>
>[Het Inzicht van de Verkoop van de Marketo in de Dynamica 2013 van Microsoft installeren en vormen](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2013.md)
