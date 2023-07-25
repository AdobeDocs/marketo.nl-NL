---
unique-page-id: 11378814
description: Accountlijsten - Marketo Docs - Productdocumentatie
title: Accountlijsten
exl-id: 31bb4341-d012-4239-8f40-10a07cd4c51c
feature: Target Account Management
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---

# Accountlijsten {#account-lists}

Een accountlijst is een verzameling benoemde accounts die gezamenlijk kunnen worden geactiveerd. Met accountlijsten kunt u benoemde accounts instellen op branche, locatie of grootte van het bedrijf.

Naast accountlijsten kunt u ook dynamische accountlijsten maken die worden gegenereerd op basis van openbare CRM-accountweergaven. Een mening van de Rekening van CRM is een reeks regels die als filter dienst doet wanneer het tonen van rekeningen. U kunt het bijvoorbeeld gebruiken om te zoeken naar accounts waarin de industrie gezondheidszorg is *en* De omzet is meer dan $100M.

![](assets/one.png)

>[!NOTE]
>
>Accountlijsten die zijn gemaakt in Marketo Target Account Management zijn automatisch beschikbaar wanneer u slimme lijsten en webcampagnes maakt in [Webpersonalisatie](/help/marketo/product-docs/web-personalization/using-web-segments/web-segments.md).

## Een nieuwe accountlijst maken {#create-a-new-account-list}

1. Klik op de knop **Nieuw** vervolgkeuzelijst en selecteer **Nieuwe accountlijst maken**.

   ![](assets/1a.png)

1. Geef uw lijst een naam en klik op **Maken**.

   ![](assets/three-0.png)

1. Nadat u uw accountlijst hebt gemaakt, kunt u aan de slag [benoemde accounts toevoegen aan het bestand](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)!

   >[!NOTE]
   >
   >Marketo geeft alleen inzichten weer voor accountlijsten met 2.000 of minder benoemde accounts.

## Een nieuwe dynamische accountlijst maken {#create-a-new-dynamic-account-list}

1. Klik op de knop **Nieuw** vervolgkeuzelijst en selecteer **Nieuwe dynamische lijst maken**.

   ![](assets/1.png)

1. Selecteer in het dialoogvenster een **CRM-accountweergave** in de vervolgkeuzelijst of typ de naam om ernaar te zoeken.

   ![](assets/image2017-7-18-9-48-23.png)

1. Klikken **Maken**.

   ![](assets/step4.jpg)

   >[!NOTE]
   >
   >Zorg er in Salesforce voor dat u de rechten voor lijstweergaveobjecten doorgeeft aan de synchronisatiegebruiker.

## De naam van een accountlijst wijzigen {#rename-an-account-list}

>[!NOTE]
>
>Deze stappen zijn alleen van toepassing op accountlijsten. _Dynamisch_ in accountlijsten wordt de naam van de bijbehorende CRM-accountweergaven gebruikt.

1. Selecteer de account waarvan u de naam wilt wijzigen, klik op de knop **Handelingen in accountlijst** vervolgkeuzelijst en selecteer **Accountlijst hernoemen**.

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

1. Selecteer de account die u wilt verwijderen, klik op de knop **Handelingen in accountlijst** vervolgkeuzelijst en selecteer **Accountlijst verwijderen**.

   ![](assets/five.png)

1. Klikken **Verwijderen**.

   ![](assets/six.png)

>[!MORELIKETHIS]
>
>* [Een bestaand benoemd account toevoegen aan een accountlijst](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)
>* [Accountlijstinzichten](/help/marketo/product-docs/target-account-management/measure/account-list-insights.md)
