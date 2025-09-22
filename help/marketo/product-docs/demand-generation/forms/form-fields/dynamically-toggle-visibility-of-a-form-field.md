---
unique-page-id: 2949962
description: Zichtbaarheid van een formulierveld dynamisch in-/uitschakelen - Marketo Docs - Productdocumentatie
title: De zichtbaarheid van een formulierveld dynamisch in-/uitschakelen
exl-id: 51b9283d-bfa1-4535-89ba-96c0ae2ea909
feature: Forms
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 0%

---

# De zichtbaarheid van een formulierveld dynamisch in-/uitschakelen {#dynamically-toggle-visibility-of-a-form-field}

>[!PREREQUISITES]
>
>* [ voeg een Picklist van het Land aan uw Vorm toe ](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md)

Één werkelijk coole eigenschap van de vormen van Marketo is dat u formuliergebieden of [ gebiedsreeksen ](/help/marketo/product-docs/demand-generation/forms/form-fields/add-a-fieldset-to-a-form.md) dynamisch kunt verbergen/tonen.

>[!NOTE]
>
>**Voorbeeld**
>
>In dit voorbeeld, verbergen wij het **gebied van de Staat** tenzij **Land** als &quot;Verenigde Staten wordt geselecteerd.&quot;

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/login-marketing-activities-8.png)

1. Selecteer het formulier en klik op **[!UICONTROL Edit Form]** .

   ![](assets/editform-1.png)

1. Selecteer het veld dat u dynamisch wilt verbergen/weergeven en klik op de koppeling voor **[!UICONTROL Visibility Rules]** .

   ![](assets/image2014-9-15-15-3a16-3a0.png)

1. Zoek en selecteer het veld waar u een voorwaarde wilt maken.

   ![](assets/image2014-9-15-15-3a16-3a12.png)

1. Selecteer de operator.

   >[!TIP]
   >
   >Dit is cool omdat u vage gelijken zoals &quot;[!UICONTROL starts with]&quot;kunt kiezen.

   ![](assets/image2014-9-15-15-3a16-3a50.png)

1. Selecteer de gewenste waarde(n) en klik buiten de vervolgkeuzelijst.

   ![](assets/image2014-9-15-15-3a17-3a4.png)

   >[!TIP]
   >
   >U kunt meerdere waarden selecteren door erop te klikken terwijl de vervolgkeuzelijst is geopend. U kunt bijvoorbeeld Verenigde Staten en Canada selecteren.

   >[!NOTE]
   >
   >Wij hebben eerder Land in een oogst-lijst gebiedstype omgezet en [ toegevoegd alle landen als waarden ](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md).

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2014-9-15-15-3a18-3a15.png)

En dat is het! Wanneer mensen dit formulier nu invullen en Verenigde Staten voor land selecteren, wordt het veld Staat dynamisch weergegeven met de opgegeven opties.

>[!IMPORTANT]
>
>Het gedrag van het gebied van de vorm zal foutloos werken wanneer de gebiedswaarden door douanescript gebruikend [ API functies ](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/javascriptapi/forms-api-reference){target="_blank"} in Forms 2.0 worden geplaatst/worden bijgewerkt.
>
>Voorwaardelijke velden werken mogelijk niet zoals verwacht als veldwaarden worden gewijzigd door andere externe scripts dan de Forms 2.0 JavaScript API.
