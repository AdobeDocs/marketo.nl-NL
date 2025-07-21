---
unique-page-id: 11378814
description: '[!UICONTROL Account Lists] - Marketo Docs - Productdocumentatie'
title: '[!UICONTROL Account Lists]'
exl-id: 31bb4341-d012-4239-8f40-10a07cd4c51c
feature: Target Account Management
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '306'
ht-degree: 0%

---

# [!UICONTROL Account Lists] {#account-lists}

Een accountlijst is een verzameling benoemde accounts die gezamenlijk kunnen worden geactiveerd. Met accountlijsten kunt u benoemde accounts instellen op branche, locatie of grootte van het bedrijf.

Naast accountlijsten kunt u ook dynamische accountlijsten maken die worden gegenereerd vanuit openbare CRM-accountweergaven. Een mening van de Rekening van CRM is een reeks regels die als filter dienst doet wanneer het tonen van rekeningen. Bijvoorbeeld, kunt u het gebruiken om rekeningen te vinden waar de Industrie Gezondheidszorg *is en* de Inkomsten is meer dan $100M.

![](assets/one.png)

>[!NOTE]
>
>De lijsten van de rekening die in Marketo [!UICONTROL Target Account Management] worden gecreeerd zijn automatisch beschikbaar wanneer het bouwen van slimme lijsten en Webcampagnes in [ Personalization van het Web ](/help/marketo/product-docs/web-personalization/using-web-segments/web-segments.md).

## Een nieuwe accountlijst maken {#create-a-new-account-list}

1. Klik op de vervolgkeuzelijst **[!UICONTROL New]** en selecteer **[!UICONTROL Create New Account List]** .

   ![](assets/1a.png)

1. Geef de lijst een naam en klik op **[!UICONTROL Create]** .

   ![](assets/three-0.png)

1. Nadat u uw rekeningslijst creeert, begin op [ toevoegend genoemde rekeningen aan het ](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)!

   >[!NOTE]
   >
   >Marketo geeft alleen inzichten weer voor accountlijsten met 2.000 of minder benoemde accounts.

## Een nieuwe dynamische accountlijst maken {#create-a-new-dynamic-account-list}

1. Klik op de vervolgkeuzelijst **[!UICONTROL New]** en selecteer **[!UICONTROL Create New Dynamic List]** .

   ![](assets/1.png)

1. In de dialoog, selecteer de Mening van de Rekening van a **CRM** van drop-down, of type in de naam om naar het te zoeken.

   ![](assets/image2017-7-18-9-48-23.png)

1. Klik op **[!UICONTROL Create]**.

   ![](assets/step4.jpg)

   >[!NOTE]
   >
   >Zorg er in Salesforce voor dat u de rechten voor lijstweergaveobjecten opgeeft aan de synchronisatiegebruiker.

## De naam van een accountlijst wijzigen {#rename-an-account-list}

>[!NOTE]
>
>Deze stappen zijn alleen van toepassing op accountlijsten. _Dynamische_ de rekeningslijsten gebruiken de naam van hun bijbehorende de Rekening van CRM Meningen.

1. Selecteer de account waarvan u de naam wilt wijzigen, klik op de vervolgkeuzelijst **[!UICONTROL Account List Actions]** en selecteer **[!UICONTROL Rename Account List]** .

   ![](assets/three.png)

1. Voer de nieuwe naam in en klik op **[!UICONTROL Rename]** .

   ![](assets/four.png)

   >[!NOTE]
   >
   >De weergave CRM-account wordt om de 8 uur gesynchroniseerd met de lijst met dynamische accounts. Als ze nog niet zijn gesynchroniseerd, synchroniseert Marketo ze tijdens de volgende cyclus.

## Een accountlijst verwijderen {#delete-an-account-list}

>[!NOTE]
>
>Deze stappen zijn hetzelfde voor zowel accountlijsten als dynamische accountlijsten.

1. Selecteer de account die u wilt verwijderen, klik op de vervolgkeuzelijst **[!UICONTROL Account List Actions]** en selecteer **[!UICONTROL Delete Account List]** .

   ![](assets/five.png)

1. Klik op **[!UICONTROL Delete]**.

   ![](assets/six.png)

>[!MORELIKETHIS]
>
>* [ voeg een Bestaand [!UICONTROL Named Account] aan een Lijst van de Rekening toe ](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)
>* [ de Inzichten van de Lijst van de Rekening ](/help/marketo/product-docs/target-account-management/measure/account-list-insights.md)
