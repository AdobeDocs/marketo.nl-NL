---
unique-page-id: 4719312
description: Picklist-waarden toevoegen/verwijderen - Marketo Docs - Productdocumentatie
title: Picklist-waarden toevoegen/verwijderen
exl-id: f1230c43-10cb-47ff-89d7-9f835b034db0
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---

# Picklist-waarden toevoegen/verwijderen {#add-remove-picklist-values}

Hier volgen een paar zaken over het toevoegen en verwijderen van picklist-waarden in Salesforce.

## Picklist-waarden toevoegen {#adding-picklist-values}

1. Als er in Salesforce een extra waarde wordt toegevoegd aan een keuzelijsttype, ontvangt u een [melding](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md){target="_blank"} welke vormen dit zal beïnvloeden.

   ![](assets/image2015-1-21-14-3a4-3a7.png)

1. Ga naar de formuliereditor en [de extra waarde toevoegen](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md){target="_blank"} aan uw lijst met suggesties.

## Picklist-waarden verwijderen {#remove-picklist-values}

Wanneer een keuzelijstwaarde wordt verwijderd uit een veld in Salesforce, moet u deze waarde handmatig verwijderen uit alle formulieren die als host fungeren voor dit veld.

>[!NOTE]
>
>Als een loodveld en een contactveld in Salesforce verschillende waarden hebben, zijn de gemeenschappelijke waarden beschikbaar voor gebruik in Marketo Engage.

Als een loodveld en een contactveld in Salesforce verschillende waarden hebben:

1. Als u een extra waarde in SFDC toevoegt aan een keuzelijst, wordt een melding weergegeven.
1. De melding zal je vertellen waar het wordt gebruikt. U kunt deze nieuwe waarde nu desgewenst als optie toevoegen aan het formulier.

Als een keuzelijst van een SFDC-lead andere waarden heeft dan een keuzelijst voor een SFDC-contactpersoon, worden de algemene waarden gebruikt als standaardopties in het formulier.

Als u een waarde uit een keuzelijst verwijdert, moet u de waarde handmatig uit uw formulieren verwijderen.
