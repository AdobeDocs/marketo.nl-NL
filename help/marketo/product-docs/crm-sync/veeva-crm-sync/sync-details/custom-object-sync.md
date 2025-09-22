---
description: Aangepaste objectsynchronisatie - Marketo Docs - Productdocumentatie
title: Aangepaste objectsynchronisatie
hide: true
hidefromtoc: true
exl-id: 68bc14e7-dfc9-4dce-b159-24d734ee3c6f
feature: Veeva CRM
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '177'
ht-degree: 1%

---

# Aangepaste objectsynchronisatie {#custom-object-sync}

Aangepaste objecten die in uw [!DNL Veeva] CRM-instantie zijn gemaakt, kunnen ook deel uitmaken van Marketo Engage. Hier is hoe u het kunt instellen.

>[!NOTE]
>
>**vereiste toestemmingen Admin**

>[!PREREQUISITES]
>
>Als u een aangepast object wilt gebruiken, moet dit worden gekoppeld aan een contact- of accountobject in [!DNL Veeva] CRM.

## Aangepast object inschakelen {#enable-custom-object}

1. Klik in Marketo op **[!UICONTROL Admin]** en vervolgens op **[!UICONTROL Veeva Objects Sync]** .

   ![](assets/custom-object-sync-1.png)

1. Klik op **[!UICONTROL Sync Schema]** als dit uw eerste aangepaste object is.

   ![](assets/custom-object-sync-2.png)

1. Klik op **[!UICONTROL Disable Global Sync]**.

   ![](assets/custom-object-sync-3.png)

   >[!NOTE]
   >
   >De eerste synchronisatie van het schema voor aangepaste objecten van [!DNL Veeva] kan een paar minuten duren.

1. Sleep het aangepaste object dat u wilt synchroniseren naar het canvas.

   ![](assets/custom-object-sync-4.png)

   >[!NOTE]
   >
   >Aangepaste objecten moeten unieke namen hebben. Marketo ondersteunt geen twee verschillende aangepaste objecten met dezelfde naam.

1. Klik op **[!UICONTROL Enable Sync]**.

   ![](assets/custom-object-sync-5.png)

1. Klik nogmaals op **[!UICONTROL Enable Sync]** .

   ![](assets/custom-object-sync-6.png)

1. Ga terug naar de tab **[!UICONTROL Veeva]** .

   ![](assets/custom-object-sync-7.png)

1. Klik op **[!UICONTROL Enable Sync]**.

   ![](assets/custom-object-sync-8.png)

1. Klik op [!DNL Veeva] en **[!UICONTROL Admin]** om al uw aangepaste **[!UICONTROL Veeva Objects Sync]** objecten weer te geven.

   ![](assets/custom-object-sync-9.png)

   >[!NOTE]
   >
   >Marketo ondersteunt alleen aangepaste entiteiten die een tot twee niveaus diep zijn gekoppeld aan standaardentiteiten.

Uitstekend! U kunt nu gegevens uit dit aangepaste object gebruiken in slimme campagnes en slimme lijsten.

>[!MORELIKETHIS]
>
>* [ synchroniserend Vraag en de Zeer belangrijke Berichten van de Vraag ](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
>* [ voeg/verwijder het Gebied van de Objecten van de Douane als Slimme Beperkingen List/Trigger ](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"} toe
