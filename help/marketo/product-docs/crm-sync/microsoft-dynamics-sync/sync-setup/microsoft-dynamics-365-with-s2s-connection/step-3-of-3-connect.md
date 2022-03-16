---
unique-page-id: 3571830
description: Stap 3 van 3 - Verbind de Oplossing van Marketo met Server aan de Verbinding van de Server - de Documenten van Marketo - de Documentatie van het Product
title: Stap 3 van 3 - Verbind de Oplossing van Marketo met de Verbinding van de Server aan
exl-id: e3ede749-f787-45d3-adb4-f71ef1221208
source-git-commit: 5536b35d71506f11fdf32bf7149bf5c61174ab34
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Stap 3 van 3: De Marketo-oplossing aansluiten op de serververbinding {#step-3-of-3-connect-microsoft-dynamics-with-marketo-solution-s2s}

Dit is de laatste stap van de synchronisatie. We zijn er bijna!

>[!PREREQUISITES]
>
>* [Stap 1 van 3: Marketo-oplossing installeren met Server naar Server-verbinding](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md)
>* [Stap 2 van 3: Marketo-oplossing instellen met Server naar Server-verbinding](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!IMPORTANT]
>
>Als u een upgrade uitvoert van Basisverificatie naar OAuth, dient u contact op te nemen met [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support) voor hulp bij het bijwerken van de aanvullende parameters. Als u deze functie inschakelt, wordt de synchronisatie tijdelijk gestopt totdat nieuwe referenties worden ingevoerd en de synchronisatie opnieuw wordt ingeschakeld. De functie kan worden uitgeschakeld (tot april 2022) als u wilt terugkeren naar de oude verificatiemodus.

>[!NOTE]
>
>Voordat u nieuwe referenties invoert, kunt u [hier valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md).

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
   >Controleer of de URL van uw org correct is omdat we de volgende schemawijzigingen na verzending niet kunnen herstellen. Als een onjuiste URL voor de organisatie wordt gebruikt, moet u een nieuw Marketo-abonnement aanvragen. Als u de URL niet kent, [hier leren vinden](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).

1. Voer de gebruikersgegevens voor Dynamische synchronisatie in en klik op **Opslaan** wanneer gereed.

   ![](assets/step-3-of-3-connect-s2s-5.png)

   >[!NOTE]
   >
   >De gebruikersnaam in Marketo moet overeenkomen met de [e-mailadres](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user) van de Application User in the CRM. De indeling kan `user@domain.com` of DOMAIN\user.

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
