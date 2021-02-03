---
unique-page-id: 2949962
description: Zichtbaarheid van een formulierveld dynamisch in-/uitschakelen - Marketo Docs - Productdocumentatie
title: De zichtbaarheid van een formulierveld dynamisch in-/uitschakelen
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 0%

---


# Zichtbaarheid van formulierveld dynamisch in-/uitschakelen {#dynamically-toggle-visibility-of-a-form-field}

>[!PREREQUISITES]
>
>* [Een lijst met landen toevoegen aan uw formulier](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md)


Een echt coole functie van Marketo-formulieren is dat u formuliervelden of [veldsets](/help/marketo/product-docs/demand-generation/forms/form-fields/add-a-fieldset-to-a-form.md) dynamisch kunt verbergen/weergeven.

>[!NOTE]
>
>**Voorbeeld**
>
>In dit voorbeeld verbergen we het veld **State**, tenzij **Land** is geselecteerd als &quot;United States.&quot;

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-8.png)

1. Selecteer het formulier en klik op **Formulier bewerken**.

   ![](assets/editform-1.png)

1. Selecteer het veld dat u dynamisch wilt verbergen/weergeven en klik op de koppeling voor **Visibility Rules**.

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
   >We hebben eerder een land omgezet in een veldtype voor een keuzelijst en [hebben alle landen toegevoegd als waarden](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md).

1. Klik **Opslaan**.

   ![](assets/image2014-9-15-15-3a18-3a15.png)

En dat is het! Wanneer mensen dit formulier nu invullen en Verenigde Staten voor land selecteren, wordt het veld Staat dynamisch weergegeven met de opgegeven opties.
