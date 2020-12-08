---
unique-page-id: 2359663
description: Een waarde voor een verborgen formulierveld instellen - Marketo Docs - Productdocumentatie
title: De waarde van een verborgen formulierveld instellen
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '323'
ht-degree: 0%

---


# De waarde van een verborgen formulierveld instellen {#set-a-hidden-form-field-value}

Verborgen velden worden gewoonlijk dynamisch gevuld. Zij worden niet getoond aan de persoon die het formulier invult. Hieronder wordt beschreven hoe u de waarde instelt.

>[!NOTE]
>
>**Vereisten**
>
>[Een formulierveld instellen als verborgen](set-a-form-field-as-hidden.md)

## Selecteer het veld {#select-the-field}

1. Selecteer het verborgen veld in het formulier en klik op **Bewerken** voor **automatisch vullen**.

   ![](assets/autofill.png)

## Standaardwaarde gebruiken {#use-default-value}

Als u Standaardwaarde gebruiken selecteert, kunt u code toepassen op een specifieke waarde die altijd moet worden gebruikt wanneer dit formulier wordt verzonden. Voer de standaardwaarde in en klik op Opslaan.

![](assets/image2014-9-15-13-3a5-3a27.png)

## URL-parameter {#url-parameter}

Als u URL-parameters (queryreeksen) wilt vastleggen vanaf de pagina waarop de persoon zich bevindt wanneer u het formulier invult, kunt u **URL** - **parameters** gebruiken om het verborgen veld te vullen.

>[!NOTE]
>
>Parameters zijn nogal technisch, niet? Maar als je ze krijgt, zijn ze machtig. Deze [Wikipedia-pagina over queryreeksen](http://en.wikipedia.org/wiki/Query_string) is wat handig.

1. Selecteer **URL-parameter** voor **waardetype** ophalen.

   ![](assets/image2014-9-15-13-3a6-3a48.png)

1. Voer de naam **van de** parameter in en klik op **Opslaan**.

   ![](assets/image2014-9-15-13-3a7-3a35.png)

>[!TIP]
>
>U kunt een standaardwaarde invoeren als de URL-parameter niet wordt gevonden.

## Koekjeswaarde {#cookie-value}

Als u gegevens in cookies opslaat, kunt u **Cookie** - **waarde** gebruiken om gegevens op te halen wanneer het formulier wordt verzonden.

1. Selecteer **Koekjeswaarde** **voor** Ophalen **** Waarde **** van ****.

   ![](assets/image2014-9-15-13-3a8-3a21.png)

1. Voer de gewenste naam voor de cookieparameter in en klik op **Opslaan**.

   ![](assets/image2014-9-15-13-3a8-3a43.png)

   >[!TIP]
   >
   >U kunt een standaardwaarde invoeren als de parameter/cookie niet wordt gevonden.

## Refererparameter {#referrer-parameter}

Als u gegevens wilt vastleggen van de pagina waarvan de bezoeker afkomstig is voordat u het formulier invult, kunt u **Referrer** **Parameter** gebruiken.

1. Stel **Ophalen** **waarde** in **van** naar **verwijzerparameter** **parameter**.

   ![](assets/image2014-9-15-13-3a9-3a31.png)

1. Voer de naam **van de** parameter in die u vanaf de URL van de referentie wilt uitlijnen en klik op **Opslaan**.

   ![](assets/image2014-9-15-13-3a9-3a56.png)

   >[!TIP]
   >
   >U kunt een **Standaardwaarde** **invoeren** voor het geval dat de verwijzingsparameter niet wordt gevonden.

1. Klik op **Voltooien**.

   ![](assets/image2014-9-15-13-3a10-3a26.png)

1. Klik op **Goedkeuren en Sluiten**.

   ![](assets/image2014-9-15-13-3a10-3a43.png)

Zoet! Je doet het behoorlijk goed. Er is meer te leren over [formulieren](http://docs.marketo.com/display/docs/forms).
