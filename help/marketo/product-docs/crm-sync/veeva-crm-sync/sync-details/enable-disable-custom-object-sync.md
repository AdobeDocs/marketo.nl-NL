---
description: Aangepaste objectsynchronisatie inschakelen/uitschakelen - Marketo Docs - Productdocumentatie
title: Aangepaste objectsynchronisatie inschakelen/uitschakelen
exl-id: 01417fb6-70f5-449b-ad56-42e1c0b2ff68
source-git-commit: 2ce44b7c44517a6fdb3f616a3d69b25158ea4ec9
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync}

Aangepaste objecten die in uw Veeva CRM-instantie zijn gemaakt, kunnen ook deel uitmaken van Marketo Engage. Hieronder wordt beschreven hoe u dit instelt.

## Aangepaste objectsynchronisatie inschakelen of uitschakelen {#enable-or-disable-the-custom-object-sync}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Klik in Marketo op **Beheer** vervolgens **Veeva-objecten synchroniseren**.

   ![](assets/enable-disable-custom-object-sync-1.png)

1. Als dit het eerste aangepaste object is, klikt u op Schema synchroniseren. Als dat niet het geval is, klikt u op **Schema vernieuwen** om ervoor te zorgen dat u over de nieuwste informatie beschikt.

   ![](assets/enable-disable-custom-object-sync-2.png)

1. Als de algemene synchronisatie wordt uitgevoerd, schakelt u deze uit door op **Globale synchronisatie uitschakelen**.

   ![](assets/enable-disable-custom-object-sync-3.png)

   >[!NOTE]
   >
   >Het kan een paar minuten duren om het schema van het aangepaste object van Veeva te synchroniseren.

1. Klikken **Schema vernieuwen**.

   ![](assets/enable-disable-custom-object-sync-4.png)

Selecteer het object dat u wilt synchroniseren en klik op Synchronisatie inschakelen.

![](assets/enable-disable-custom-object-sync-5.png)

>[!TIP]
>
>Marketo kan een aangepast object alleen synchroniseren als het een directe relatie heeft met het object Contact of Account in Veeva CRM.

1. Klikken **Sync inschakelen** opnieuw.

   ![](assets/enable-disable-custom-object-sync-6.png)

1. Ga terug naar het tabblad Veeva en klik op **Sync inschakelen**.

   ![](assets/enable-disable-custom-object-sync-7.png)

## Aangepaste objecten gebruiken {#using-your-custom-objects}

>[!NOTE]
>
>U kunt aangepaste objecten niet gebruiken in slimme campagnes met triggers.

1. Sleep in de slimme lijst over het filter &quot;Heeft opportuniteit&quot; en stel dit in op **Waar**.

   ![](assets/enable-disable-custom-object-sync-8.png)

1. Gebruik eventueel filterbeperkingen om de focus te beperken.

   ![](assets/enable-disable-custom-object-sync-9.png)

Uitstekend! U kunt de gegevens van dit aangepaste object nu gebruiken in slimme campagnes en slimme lijsten.

>[!MORELIKETHIS]
>
>[Aangepast objectveld toevoegen/verwijderen als slimme lijst/triggerbeperkingen](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target=&quot;_blank&quot;}