---
unique-page-id: 11378814
description: Accountlijsten - Marketo Docs - Productdocumentatie
title: Accountlijsten
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---


# Accountlijsten {#account-lists}

Een accountlijst is een verzameling benoemde accounts die gezamenlijk kunnen worden geactiveerd. Met accountlijsten kunt u benoemde accounts instellen op branche, locatie of grootte van het bedrijf.

Naast accountlijsten kunt u ook dynamische accountlijsten maken die worden gegenereerd op basis van openbare CRM-accountweergaven. Een mening van de Rekening van CRM is een reeks regels die als filter dienst doet wanneer het tonen van rekeningen. U kunt het bijvoorbeeld gebruiken om te zoeken naar accounts waarin de industrie gezondheidszorg *en*-inkomsten hoger zijn dan $100M.

![](assets/one.png)

>[!NOTE]
>
>Accountlijsten die zijn gemaakt in Marketo Account Based Marketing zijn automatisch beschikbaar wanneer u slimme lijsten en webcampagnes maakt in [Webpersonalisatie](/help/marketo/product-docs/web-personalization/using-web-segments/web-segments.md).

## Een nieuwe accountlijst maken {#create-a-new-account-list}

1. Klik op de vervolgkeuzelijst **Nieuw** en selecteer **Nieuwe accountlijst maken**.

   ![](assets/1a.png)

1. Geef uw lijst een naam en klik **Create**.

   ![](assets/three-0.png)

1. Nadat u uw rekeningslijst creeert, begin op [toevoegend genoemde rekeningen aan het](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)!

   >[!NOTE]
   >
   >Marketo geeft alleen inzichten weer voor accountlijsten met 2.000 of minder benoemde accounts.

## Nieuwe dynamische accountlijst maken {#create-a-new-dynamic-account-list}

1. Klik op de vervolgkeuzelijst **Nieuw** en selecteer **Nieuwe dynamische lijst maken**.

   ![](assets/1.png)

1. In de dialoog, selecteer **de Mening van de Rekening van CRM** van drop-down, of typ in de naam om naar het te zoeken.

   ![](assets/image2017-7-18-9-48-23.png)

1. Klik **Maken**.

   ![](assets/step4.jpg)

   >[!NOTE]
   >
   >Zorg er in Salesforce voor dat u de rechten voor lijstweergaveobjecten doorgeeft aan de synchronisatiegebruiker.

## De naam van een accountlijst wijzigen {#rename-an-account-list}

>[!NOTE]
>
>Deze stappen zijn alleen van toepassing op accountlijsten. _In de lijst_ Dynamicaccount wordt de naam van de bijbehorende CRM-accountweergaven gebruikt.

1. Selecteer de account waarvan u de naam wilt wijzigen, klik op de vervolgkeuzelijst **Accountlijst Handelingen** en selecteer **Naam van accountlijst wijzigen**.

   ![](assets/three.png)

1. Voer de nieuwe naam in en klik op **Naam wijzigen**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >De weergave CRM-account wordt om de 8 uur gesynchroniseerd met de lijst met dynamische accounts. Als ze nog niet zijn gesynchroniseerd, synchroniseert Marketo ze tijdens de volgende cyclus.

## Een accountlijst verwijderen {#delete-an-account-list}

>[!NOTE]
>
>Deze stappen zijn hetzelfde voor zowel accountlijsten als dynamische accountlijsten.

1. Selecteer de account die u wilt verwijderen, klik op de vervolgkeuzelijst **Accountlijsthandelingen** en selecteer **Accountlijst verwijderen**.

   ![](assets/five.png)

1. Klik **Delete**.

   ![](assets/six.png)

>[!MORELIKETHIS]
>
>* [Een bestaand benoemd account toevoegen aan een accountlijst](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)
>* [Accountlijstinzichten](/help/marketo/product-docs/target-account-management/measure/account-list-insights.md)

