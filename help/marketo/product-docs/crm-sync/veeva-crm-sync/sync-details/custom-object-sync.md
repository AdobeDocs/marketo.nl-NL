---
description: Aangepaste objectsynchronisatie - Marketo Docs - Productdocumentatie
title: Aangepaste objectsynchronisatie
hide: true
hidefromtoc: true
exl-id: 68bc14e7-dfc9-4dce-b159-24d734ee3c6f
feature: Veeva CRM
source-git-commit: bebf61037f37a06b40b4d9c1df872f1cf62a1403
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 1%

---

# Aangepaste objectsynchronisatie {#custom-object-sync}

Aangepaste objecten die in uw Veeva CRM-instantie zijn gemaakt, kunnen ook deel uitmaken van het Marketo Engage. Hier is hoe u het kunt instellen.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!PREREQUISITES]
>
>Als u een aangepast object wilt gebruiken, moet dit zijn gekoppeld aan een contact- of accountobject in Veeva CRM.

## Aangepast object inschakelen {#enable-custom-object}

1. Klik in Marketo op **[!UICONTROL Admin]** vervolgens **[!UICONTROL Veeva Objects Sync]**.

   ![](assets/custom-object-sync-1.png)

1. Als dit uw eerste aangepaste object is, klikt u op **[!UICONTROL Sync Schema]**.

   ![](assets/custom-object-sync-2.png)

1. Klik op **[!UICONTROL Disable Global Sync]**.

   ![](assets/custom-object-sync-3.png)

   >[!NOTE]
   >
   >De eerste synchronisatie van het schema van aangepaste Veeva-objecten kan een paar minuten duren.

1. Sleep het aangepaste object dat u wilt synchroniseren naar het canvas.

   ![](assets/custom-object-sync-4.png)

   >[!NOTE]
   >
   >Aangepaste objecten moeten unieke namen hebben. Marketo ondersteunt geen twee verschillende aangepaste objecten met dezelfde naam.

1. Klik op **[!UICONTROL Enable Sync]**.

   ![](assets/custom-object-sync-5.png)

1. Klikken **[!UICONTROL Enable Sync]** opnieuw.

   ![](assets/custom-object-sync-6.png)

1. Ga terug naar de **[!UICONTROL Veeva]** tab.

   ![](assets/custom-object-sync-7.png)

1. Klik op **[!UICONTROL Enable Sync]**.

   ![](assets/custom-object-sync-8.png)

1. Als u al uw aangepaste veeva-objecten wilt weergeven, klikt u op **[!UICONTROL Admin]** en **[!UICONTROL Veeva Objects Sync]**.

   ![](assets/custom-object-sync-9.png)

   >[!NOTE]
   >
   >Marketo ondersteunt alleen aangepaste entiteiten die een tot twee niveaus diep zijn gekoppeld aan standaardentiteiten.

Uitstekend! U kunt nu gegevens uit dit aangepaste object gebruiken in slimme campagnes en slimme lijsten.

>[!MORELIKETHIS]
>
>* [Het synchroniseren van Vraag en Vraag Zeer belangrijke Berichten](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
>* [Aangepast objectveld toevoegen/verwijderen als slimme lijst/triggerbeperkingen](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"}
