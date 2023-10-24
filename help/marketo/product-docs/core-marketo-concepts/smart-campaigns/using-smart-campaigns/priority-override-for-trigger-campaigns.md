---
description: Prioriteit overschrijven voor triggercampagnes - Marketo Docs - Productdocumentatie
title: Prioriteit overschrijven voor triggercampagnes
exl-id: cf9b4d27-0e4c-40cf-accd-4f4a102160cc
feature: Smart Campaigns
source-git-commit: 47bc93665a7efa0d64cd4d5f34b868895d407527
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 1%

---

# Prioriteit overschrijven voor triggercampagnes {#priority-override-for-trigger-campaigns}

Beheerders kunnen de door het Marketo Engage bepaalde prioriteit voor triggercampagnes overschrijven om prioriteiten in te stellen die beter aansluiten op bedrijfsdoelstellingen.

>[!NOTE]
>
>Deze functie is alleen beschikbaar voor triggercampagnes en voor gebruikers aan wie de [Toestemming voor prioriteit triggercampagne bewerken](#grant-priority-override-access).

>[!CAUTION]
>
>Het wordt sterk geadviseerd dat u deze eigenschap op een beperkte reeks zaken kritieke campagnes (25 is het geadviseerde maximum) gebruikt. Het losjes gebruiken van de eigenschap op een grote reeks kan algemene campagneuitvoering negatief beïnvloeden.

## Toegang bij voorrang overschrijven van subsidie {#grant-priority-override-access}

>[!NOTE]
>
>Alleen beheerders of gebruikers met beheerdersverantwoordelijkheden hebben voorrang op de toegang tot de campagne.

1. In de [!UICONTROL Admin] gebied, klikken **[!UICONTROL Users & Roles]**.

   ![](assets/priority-override-for-trigger-campaigns-1.png)

1. Klik op de knop **[!UICONTROL Roles]** selecteert u de gebruiker aan wie u toegang wilt verlenen en klikt u vervolgens op **[!UICONTROL Edit Role]**.

   ![](assets/priority-override-for-trigger-campaigns-2.png)

1. Selecteer onder [!UICONTROL Access Marketing Activities] de optie **[!UICONTROL Edit Trigger Campaign Priority]**. Klik op **[!UICONTROL Save]**.

   ![](assets/priority-override-for-trigger-campaigns-3.png)

## Prioriteit overschrijven {#override-priority}

1. Zoek de triggercampagne. Klik er met de rechtermuisknop op en selecteer **[!UICONTROL Override Campaign Priority]**.

   ![](assets/priority-override-for-trigger-campaigns-4.png)

1. Klik op de knop **[!UICONTROL Override Campaign Priority]** in te schakelen. Kies een nieuw prioriteitsniveau en klik op **[!UICONTROL Confirm]**.

   ![](assets/priority-override-for-trigger-campaigns-5.png)

   Het nieuwe prioritaire niveau zal in het lusje van het Programma tonen.

   ![](assets/priority-override-for-trigger-campaigns-6.png)

>[!NOTE]
>
>* U kunt de standaardprioriteit van uw campagne weergeven in het dialoogvenster [!UICONTROL Campaign Queue] krachtens [!UICONTROL Marketing Activities]. Om het uitvoeringspercentage te verhogen, raden we u aan uw campagneprioriteit op één niveau hoger in te stellen dan het standaardniveau.
>* De door de gebruiker ingestelde prioriteit geldt alleen voor nieuwe personen die in aanmerking komen voor de campagne. Dit heeft geen invloed op personen die al in de wachtrij staan.
>* Prioritaire overschrijvingen worden vastgelegd in [Audittrail](/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md){target="_blank"}.
