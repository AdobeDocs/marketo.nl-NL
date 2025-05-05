---
unique-page-id: 2949962
description: Zichtbaarheid van een formulierveld dynamisch in-/uitschakelen - Marketo Docs - Productdocumentatie
title: De zichtbaarheid van een formulierveld dynamisch in-/uitschakelen
exl-id: 51b9283d-bfa1-4535-89ba-96c0ae2ea909
feature: Forms
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---

# De zichtbaarheid van een formulierveld dynamisch in-/uitschakelen {#dynamically-toggle-visibility-of-a-form-field}

>[!PREREQUISITES]
>
>* [Een lijst met landen toevoegen aan uw formulier](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md)

Een heel leuke functie van Marketo-formulieren is dat u formuliervelden dynamisch kunt verbergen/weergeven of [veldsets](/help/marketo/product-docs/demand-generation/forms/form-fields/add-a-fieldset-to-a-form.md).

>[!NOTE]
>
>**Voorbeeld**
>
>In dit voorbeeld verbergen we de **Staat** veld tenzij **Land** is geselecteerd als &quot;Verenigde Staten&quot;.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-8.png)

1. Selecteer het formulier en klik op **Formulier bewerken**.

   ![](assets/editform-1.png)

1. Selecteer het veld dat u dynamisch wilt verbergen/weergeven en klik op de koppeling voor **Zichtbaarheidsregels**.

   ![](assets/image2014-9-15-15-3a16-3a0.png)

1. Zoek en selecteer het veld waar u een voorwaarde wilt maken.

   ![](assets/image2014-9-15-15-3a16-3a12.png)

1. Selecteer de operator.

   >[!TIP]
   >
   >Dit is cool omdat u vage gelijken als &quot;begint met.&quot; kunt kiezen

   ![](assets/image2014-9-15-15-3a16-3a50.png)

1. Selecteer de gewenste waarde(n) en klik buiten de vervolgkeuzelijst.

   ![](assets/image2014-9-15-15-3a17-3a4.png)

   >[!TIP]
   >
   >U kunt meerdere waarden selecteren door erop te klikken terwijl de vervolgkeuzelijst is geopend. U kunt bijvoorbeeld Verenigde Staten en Canada selecteren.

   >[!NOTE]
   >
   >We hebben eerder een land omgezet in een veldtype voor een keuzelijst en [alle landen toegevoegd als waarden](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md).

1. Klikken **Opslaan**.

   ![](assets/image2014-9-15-15-3a18-3a15.png)

En dat is het! Wanneer mensen dit formulier nu invullen en Verenigde Staten voor land selecteren, wordt het veld Staat dynamisch weergegeven met de opgegeven opties.

>[!IMPORTANT]
>
>Het gedrag van formuliervelden werkt naadloos wanneer veldwaarden worden ingesteld/bijgewerkt met behulp van een aangepast script [API-functies](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/javascriptapi/forms-api-reference){target="_blank"} in Forms 2.0.
>
>Voorwaardelijke velden werken mogelijk niet zoals verwacht als veldwaarden worden gewijzigd door andere externe scripts dan de JavaScript-API van Forms 2.0.
