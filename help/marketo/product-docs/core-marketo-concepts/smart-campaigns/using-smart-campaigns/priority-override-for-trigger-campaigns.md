---
description: Prioriteit overschrijven voor triggercampagnes - Marketo Docs - Productdocumentatie
title: Prioriteit overschrijven voor triggercampagnes
hide: true
hidefromtoc: true
source-git-commit: f2b6e0ae4759ed279d4c02ae922e9deba838b1ff
workflow-type: tm+mt
source-wordcount: '220'
ht-degree: 0%

---

# Prioriteit overschrijven voor triggercampagnes {#priority-override-for-trigger-campaigns}

Beheerders kunnen de door Marketo bepaalde prioriteit voor triggercampagnes overschrijven om prioriteiten in te stellen die beter op de bedrijfsdoelstellingen zijn afgestemd.

>[!NOTE]
>
>Deze functie is alleen beschikbaar voor triggercampagnes en voor gebruikers aan wie de [Toestemming voor prioriteit triggercampagne bewerken](#grant-priority-override-access).

>[!CAUTION]
>
>Het wordt sterk geadviseerd dat u deze eigenschap op een beperkte reeks zaken kritieke campagnes (25 is het geadviseerde maximum) gebruikt. Het losjes gebruiken van de eigenschap op een grote reeks kan algemene campagneuitvoering negatief beïnvloeden.

## Toegang bij voorrang overschrijven van subsidie {#grant-priority-override-access}

>[!CAUTION]
>
>Alleen beheerders of gebruikers met beheerdersverantwoordelijkheden hebben voorrang op de toegang tot de campagne.

1. In de [!UICONTROL Admin] gebied, klikken **[!UICONTROL Users & Roles]**.

   ![](assets/priority-override-for-trigger-campaigns-1.png)

1. Klik op de knop **[!UICONTROL Roles]** selecteert u de gebruiker aan wie u toegang wilt verlenen en klikt u vervolgens op **[!UICONTROL Edit Role]**.

   ![](assets/priority-override-for-trigger-campaigns-2.png)

1. Onder [!UICONTROL Access Marketing Activities], selecteert u **[!UICONTROL Edit Trigger Campaign Priority]**. Klikken **[!UICONTROL Save]**.

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
>* Prioritaire overschrijvingen worden vastgelegd in [Audittrail](/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md).
