---
unique-page-id: 3571809
description: Stap 3 van 3 - de Dynamiek van Microsoft van Connect met Marketo (2011 op-Premises) - Marketo Docs - de Documentatie van het Product
title: Stap 3 van 3 - de Dynamiek van Microsoft van Connect met Marketo (2011 op-Premises)
translation-type: tm+mt
source-git-commit: 20eb3389b267101fb277152f150c2119a5be65a8
workflow-type: tm+mt
source-wordcount: '364'
ht-degree: 0%

---


# Stap 3 van 3: Connect Microsoft Dynamics with Marketo (2011 op locatie) {#step-of-connect-microsoft-dynamics-with-marketo-on-premises}

Goed! We hebben de oplossing geïnstalleerd en de synchronisatiegebruiker geconfigureerd. Daarna, moeten wij Marketo en Dynamiek verbinden.

>[!PREREQUISITES]
>
>* [Stap 1 van 3: De Marketo-oplossing installeren (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md)
>* [Stap 2 van 3: Marketo Sync User in Dynamics (2011 op locatie) instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-2-of-3-set-up.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Voer gebruikersgegevens voor dynamicasynchronisatie {#enter-dynamics-sync-user-information} in

1. Meld u aan bij Marketo en klik op **Admin**.

   ![](assets/login-admin.png)

1. Klik op **CRM**.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Klik **Microsoft**.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. Klik **Bewerken** in **Stap 1: Voer referenties in.**

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw abonnement op Marketo aanvragen.

1. Voer **Gebruikersnaam**, **Wachtwoord** en CRM **URL** in en klik vervolgens **Opslaan**.

   ![](assets/image2015-4-2-14-3a50-3a7.png)

   >[!NOTE]
   >
   >* De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user zijn.
   >* Als u URL niet kent, [leer hoe te om het hier te vinden](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).


## Te synchroniseren velden {#select-fields-to-sync} selecteren

Nu moeten we de velden selecteren waarover we willen synchroniseren.

1. Klik **Bewerken** in **Stap 2: Selecteer te synchroniseren velden.**

   ![](assets/image2015-3-16-9-51-28a.png)

1. Er zijn vooraf geselecteerde velden die worden gesynchroniseerd. Voeg desgewenst meer toe en klik op **Opslaan**.

   ![](assets/image2016-8-25-13-3a26-3a14.png)

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

   ![](assets/image2016-8-25-14-3a14-3a57.png)

## Sync {#enable-sync} inschakelen

1. Klik **Bewerken** in **Stap 3: Sync inschakelen**.

   ![](assets/image2015-3-16-9-52-2b.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een synchronisatie met Microsoft Dynamics, of wanneer u handmatig personen of leads invoert.

1. Lees alles in pop-up, ga uw e-mail in, en klik **Begin Synchronisatie**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. De eerste synchronisatie kan een paar uur duren. Nadat het is gedaan, zult u een e-mailbericht ontvangen.

   ![](assets/image2014-12-11-11-3a55-3a15.png)

   Uitstekend werk!
