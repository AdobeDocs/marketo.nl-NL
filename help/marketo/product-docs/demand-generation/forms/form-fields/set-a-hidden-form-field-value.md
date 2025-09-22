---
unique-page-id: 2359663
description: Een waarde voor een verborgen formulierveld instellen - Marketo Docs - Productdocumentatie
title: De waarde van een verborgen formulierveld instellen
exl-id: acec7de1-8567-42c0-a6ce-a91b0bf69f41
feature: Forms
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 0%

---

# De waarde van een verborgen formulierveld instellen {#set-a-hidden-form-field-value}

Verborgen velden worden gewoonlijk dynamisch gevuld. Zij worden niet getoond aan de persoon die het formulier invult. Hieronder wordt beschreven hoe u de waarde instelt.

>[!PREREQUISITES]
>
>[ plaats een Geborgen Gebied van de Vorm ](/help/marketo/product-docs/demand-generation/forms/form-fields/set-a-form-field-as-hidden.md)

## Selecteer het veld {#select-the-field}

1. Selecteer het verborgen veld in het formulier en klik op **[!UICONTROL Edit]** voor **[!UICONTROL Autofill]** .

   ![](assets/autofill.png)

## Standaardwaarde gebruiken {#use-default-value}

Als u Use **[!UICONTROL Default Value]** selecteert, kunt u code toepassen op een specifieke waarde die altijd moet worden gebruikt wanneer dit formulier wordt verzonden. Voer de **[!UICONTROL Default Value]** in en klik op **[!UICONTROL Save]** .

![](assets/image2014-9-15-13-3a5-3a27.png)

## URL-parameter {#url-parameter}

Als u URL-parameters (queryreeksen) wilt vastleggen vanaf de pagina waarop de persoon zich bevindt wanneer u het formulier invult, kunt u **[!UICONTROL URL Parameters]** gebruiken om het verborgen veld te vullen.

>[!NOTE]
>
>Parameters zijn nogal technisch, niet? Maar als je ze krijgt, zijn ze machtig. Deze [ pagina Wikipedia op de Koorden van de Vraag ](https://en.wikipedia.org/wiki/Query_string) is enigszins nuttig.

1. Selecteer **[!UICONTROL URL Parameter]** voor **[!UICONTROL Get Value Type]** .

   ![](assets/image2014-9-15-13-3a6-3a48.png)

1. Voer de **[!UICONTROL Parameter Name]** in en klik op **[!UICONTROL Save]** .

   ![](assets/image2014-9-15-13-3a7-3a35.png)

>[!TIP]
>
>U kunt een **[!UICONTROL Default Value]** invoeren als de URL-parameter niet wordt gevonden.

## Koekjeswaarde {#cookie-value}

Als u gegevens in cookies opslaat, kunt u met **[!UICONTROL Cookie Value]** gegevens ophalen wanneer het formulier wordt verzonden.

1. Selecteer **[!UICONTROL Cookie Value]** voor **[!UICONTROL Get Value From]** .

   ![](assets/image2014-9-15-13-3a8-3a21.png)

1. Voer de gewenste cookie **[!UICONTROL Parameter Name]** in en klik op **[!UICONTROL Save]** .

   ![](assets/image2014-9-15-13-3a8-3a43.png)

   >[!TIP]
   >
   >U kunt een **[!UICONTROL Default Value]** invoeren als de parameter/cookie niet wordt gevonden.

## Refererparameter {#referrer-parameter}

Als u gegevens wilt vastleggen van de pagina waarvan de bezoeker afkomstig is voordat u het formulier invult, kunt u **[!UICONTROL Referrer Parameter]** gebruiken.

1. Stel **[!UICONTROL Get Value From]** in op **[!UICONTROL Referrer Parameter]** .

   ![](assets/image2014-9-15-13-3a9-3a31.png)

1. Voer de **[!UICONTROL Parameter Name]** in die u vanaf de URL van de referentie wilt uitlijnen en klik op **[!UICONTROL Save]** .

   ![](assets/image2014-9-15-13-3a9-3a56.png)

   >[!TIP]
   >
   >U kunt een **[!UICONTROL Default Value]** invoeren voor het geval dat de verwijzingsparameter niet wordt gevonden.

1. Klik op **[!UICONTROL Finish]**.

   ![](assets/image2014-9-15-13-3a10-3a26.png)

1. Klik op **[!UICONTROL Approve and Close]**.

   ![](assets/image2014-9-15-13-3a10-3a43.png)
