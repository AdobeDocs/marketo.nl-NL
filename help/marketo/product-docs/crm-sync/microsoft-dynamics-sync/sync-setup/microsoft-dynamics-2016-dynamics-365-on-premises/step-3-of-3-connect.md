---
description: Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 3 van 3 - Marketo Docs - Productdocumentatie installeren
title: Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 3 van 3 installeren
exl-id: ae801a59-8e29-479c-84c5-a18c7511f21f
feature: Microsoft Dynamics
source-git-commit: 15cb3ddcd82fa1ba60fae3aa1adaac3d5964a0fa
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---

# Stap 3 van 3: Connect Marketo Dynamics (2016 op Prem/Dynamics 365 op locatie) {#step-of-connect-marketo-dynamics-on-premises-2016}

>[!PREREQUISITES]
>
>* [Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 1 van 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md){target="_blank"}
>* [Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Step 2 of 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-2-of-3-set-up.md){target="_blank"}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Gebruikersgegevens dynamiek synchroniseren invoeren {#enter-dynamics-sync-user-information}

1. Aanmelden bij Marketo en klikken op **[!UICONTROL Admin]**.

   ![](assets/login-admin.png)

1. Klik op **[!UICONTROL CRM]**.

   ![](assets/image2015-3-16-9-47-34.png)

1. Selecteren **[!DNL Microsoft]**.

   ![](assets/image2015-3-16-9-50-6.png)

1. Klikken **[!UICONTROL Edit]** in **[!UICONTROL Enter Credentials]**.

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >Controleer of uw gegevens juist zijn omdat de volgende schemawijzigingen na verzending niet kunnen worden hersteld. Als onjuiste gegevens worden opgeslagen, moet u een nieuw Marketo-abonnement aanvragen.

1. Voer de **[!UICONTROL Username]**, **[!UICONTROL Password]** een Microsoft Dynamics **[!UICONTROL URL]** en **Client-id/geheim**. Klikken **[!UICONTROL Save]** wanneer gereed.

   ![](assets/step-3-of-3-5.png)

   >[!NOTE]
   >
   >* Als uw Marketo vóór oktober 2020 is ingericht, zijn Client ID en Secret optionele velden. Anders zijn ze verplicht. Het verkrijgen van deze informatie zal afhangen van welke versie van MSD u gebruikt.
   >* De gebruikersnaam in Marketo moet overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker in CRM. De indeling kan `user@domain.com` of DOMAIN\user.
   >* Als u de URL niet kent, [hier leren vinden](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"}.

   >[!TIP]
   >
   >Kent u de URL niet? We zullen u laten zien hoe u uw [URL van de Dynamic Organization-service](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) hier.

## Te synchroniseren velden selecteren {#select-fields-to-sync}

1. Klikken **[!UICONTROL Edit]** in **[!UICONTROL Select Fields to Sync]**.

   ![](assets/image2015-3-16-9-51-28.png)

1. Selecteer de velden die u wilt synchroniseren met Marketo, zodat deze vooraf worden geselecteerd. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

>[!NOTE]
>
>Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een veld verwijdert in Dynamics, wordt u aangeraden dit te doen met de opdracht [sync uitgeschakeld](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md){target="_blank"}. Then refresh the schema in Marketo by editing and saving the [Select Fields to Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md){target="_blank"}.

## Velden synchroniseren voor een aangepast filter {#sync-fields-for-a-custom-filter}

Als u een aangepast filter hebt gemaakt, moet u naar binnen gaan en de nieuwe velden selecteren die u wilt synchroniseren met Marketo.

1. Ga naar Beheerder en selecteer **[!DNL Microsoft Dynamics]**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klikken **[!UICONTROL Edit]** op veld Sync details.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## Synchronisatie inschakelen {#enable-sync}

1. Klikken **[!UICONTROL Edit]** in **[!UICONTROL Enable Sync]**.

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een Microsoft Dynamics-synchronisatie of wanneer u handmatig personen invoert.

1. Lees alles in pop-up, ga uw e-mail in, en klik **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. De eerste synchronisatie kan een paar uur duren. Nadat het is gedaan, zult u een e-mailbericht ontvangen.

   ![](assets/image2015-3-16-9-59-51.png)

Uitstekend werk!
