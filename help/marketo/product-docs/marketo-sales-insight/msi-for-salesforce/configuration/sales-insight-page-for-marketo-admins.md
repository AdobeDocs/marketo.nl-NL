---
unique-page-id: 42762409
description: Verkoop Insight-pagina voor Marketo Admins - Marketo Docs - Productdocumentatie
title: Insight-pagina voor verkoop voor Marketo Admins
exl-id: d98bc9d8-1a72-405f-b1d7-b71ad88c8493
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '364'
ht-degree: 0%

---

# [!DNL Sales Insight] Pagina voor Marketo-beheerders {#sales-insight-page-for-marketo-admins}

Marketo Admins heeft bepaalde rechten in [!DNL Sales Insight] . Leer hieronder wat ze zijn.

## Soap API-configuratie {#soap-api-configuration}

Deze gegevens worden gebruikt om uw [!DNL Salesforce] -account te verbinden met uw Marketo-instantie, zodat u MSI in [!DNL Salesforce] kunt gebruiken.

![](assets/one-1.png)

## API-configuratie opnieuw instellen {#rest-api-configuration}

Deze gegevens worden gebruikt om uw [!DNL Salesforce] -account aan te sluiten op uw Marketo-instantie, zodat u het MSI Insights-dashboard in [!DNL Salesforce] kunt gebruiken.

![](assets/two-1.png)

## Instellingen persoonlijke score {#person-score-settings}

* **[!UICONTROL Stars]**: sterren geven de totale loodscore aan in vergelijking met andere leads.
* **[!UICONTROL Flames]**: vlammen geven de urgentie aan - hoeveel de score van een lead de laatste tijd is gewijzigd.

Standaard gebruikt [!DNL Marketo Sales Insight] het veld Loodscore om sterren en vlammen te berekenen. Maar als je een ander veld wilt kiezen, is dit hoe:

1. Klik in het gebied **[!UICONTROL Admin]** van Marketo op **[!UICONTROL Sales Insight]** .

   ![](assets/four.png)

1. Klik onder [!UICONTROL Lead Scoring Settings] op **[!UICONTROL Edit]** .

   ![](assets/five.png)

1. Selecteer het veld dat u voor sterren wilt gebruiken.

   ![](assets/six.png)

1. Selecteer het veld dat u voor vlammen wilt gebruiken.

   ![](assets/seven.png)

1. Klik op **[!UICONTROL Save]**. Verkoopmanager insight heeft enige tijd nodig om opnieuw te berekenen. U kunt uw CRM later controleren om de sterren en de vlammen te zien.

   ![](assets/eight.png)

   >[!TIP]
   >
   >Als u reeds uw gebieden van de douanescore niet hebt, is hier hoe te [&#x200B; hen &#x200B;](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md) creëren.

   >[!MORELIKETHIS]
   >
   >[&#x200B; Sterren en Vlamjes &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md)

## Instellingen {#settings}

![](assets/nine.png)

**Unsubscribe Montages:**

U kunt kiezen uit de volgende instellingen voor abonnementen voor [!UICONTROL No Template] , [!UICONTROL Standard Emails] &amp; [!UICONTROL Operational emails]

* [!UICONTROL Respect Unsubscribe Setting]
* [!UICONTROL Respect Unsubscribe Settings when more than 1 recipient]
* [!UICONTROL Respect Unsubscribe Settings when more than 5 recipients]
* [!UICONTROL Ignore Unsubscribe Settings]

**laat capaciteit toe om malplaatjes te sluiten:**

MSI-gebruikers kunnen sjablonen niet bewerken wanneer ze e-mails verzenden vanuit [!DNL Salesforce]

**laat RSS Feed toe:**

Als deze optie is ingeschakeld, kunnen MSI-gebruikers hun lead feed in een RSS-feed bekijken (in aanvulling op de lead feed in [!DNL Salesforce] ). RSS voer kan slechts functioneren als &quot;[!UICONTROL Token Expiration]&quot;eigenschap gehandicapt is.

**Symbolische Vervalsing:**

De Symbolische Vervaldatum wordt gecontroleerd in de Manager van de Eigenschap. Om het te hebben toegelaten/gehandicapt, reik uit aan [&#x200B; Steun van Marketo &#x200B;](https://nation.marketo.com/t5/Support/ct-p/Support). Als deze optie is ingeschakeld, verlopen alle Marketo-tokens binnen 10 minuten. Als Marketo-tokens zijn uitgeschakeld, verlopen deze niet.

Tokens die vóór het toelaten van de Symbolische Vervalsing worden geproduceerd zullen geen verlooptijd hebben om tegen te bevestigen, zodat zullen zij niet verlopen zelfs als de eigenschap momenteel wordt toegelaten.

Tokens die na het toelaten van Symbolische Vervaltijd worden geproduceerd zullen een vervaltijd van 10 minuten hebben, zodat zullen zij nog over 10 minuten verlopen zelfs nadat de eigenschap wordt onbruikbaar gemaakt.

Tokengedrag wordt gebaseerd op het tijdstip waarop het is gegenereerd (wanneer de functie Symbolische vervaldatum is in-/uitgeschakeld in plaats van de huidige status van de functie).
