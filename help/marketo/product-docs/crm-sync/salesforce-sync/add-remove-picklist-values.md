---
unique-page-id: 4719312
description: Picklist-waarden toevoegen/verwijderen - Marketo Docs - Productdocumentatie
title: Picklist-waarden toevoegen/verwijderen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---


# Picklist-waarden toevoegen/verwijderen {#add-remove-picklist-values}

Hier volgen een paar zaken over het toevoegen en verwijderen van picklist-waarden in Salesforce.

## Picklist-waarden toevoegen {#adding-picklist-values}

1. Als in Salesforce een extra waarde wordt toegevoegd aan een veldtype picklist, ontvangt u een [melding](../../../product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md) waarin wordt aangegeven op welke formulieren dit van invloed is.

   ![](assets/image2015-1-21-14-3a4-3a7.png)

1. Ga naar de formuliereditor en [voeg de extra waarde](../../../product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md) toe aan de lijst met suggesties.

## Picklist-waarden verwijderen {#remove-picklist-values}

Wanneer een keuzelijstwaarde wordt verwijderd uit een veld in Salesforce, moet u deze waarde handmatig verwijderen uit alle formulieren die als host fungeren voor dit veld.

>[!NOTE]
>
>Als een loodveld en een contactveld in Salesforce verschillende waarden hebben, zijn de gemeenschappelijke waarden beschikbaar voor gebruik in Marketo.

Als een loodveld en een contactveld in Salesforce verschillende waarden hebben:

1. Als u een extra waarde in SFDC toevoegt aan een keuzelijst, wordt een melding weergegeven.
1. De melding zal je vertellen waar het wordt gebruikt. U kunt deze nieuwe waarde nu desgewenst als optie toevoegen aan het formulier.

Als een keuzelijst van een SFDC-lead andere waarden heeft dan een keuzelijst voor een SFDC-contactpersoon, worden de algemene waarden gebruikt als standaardopties in het formulier.

Als u een waarde uit een keuzelijst verwijdert, moet u de waarde handmatig uit uw formulieren verwijderen.
