---
unique-page-id: 2359663
description: Een waarde voor een verborgen formulierveld instellen - Marketo Docs - Productdocumentatie
title: De waarde van een verborgen formulierveld instellen
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 0%

---


# Waarde van verborgen formulierveld instellen {#set-a-hidden-form-field-value}

Verborgen velden worden gewoonlijk dynamisch gevuld. Zij worden niet getoond aan de persoon die het formulier invult. Hieronder wordt beschreven hoe u de waarde instelt.

>[!PREREQUISITES]
>
>[Een formulierveld instellen als verborgen](set-a-form-field-as-hidden.md)

## Selecteer het veld {#select-the-field}

1. Selecteer het verborgen veld in het formulier en klik op **Bewerken** voor **Automatisch vullen**.

   ![](assets/autofill.png)

## Standaardwaarde {#use-default-value} gebruiken

Als u Standaardwaarde gebruiken selecteert, kunt u code toepassen op een specifieke waarde die altijd moet worden gebruikt wanneer dit formulier wordt verzonden. Voer de standaardwaarde in en klik op Opslaan.

![](assets/image2014-9-15-13-3a5-3a27.png)

## URL-parameter {#url-parameter}

Als u URL-parameters (Query-tekenreeksen) wilt vastleggen vanaf de pagina waarop de persoon zich bevindt bij het invullen van het formulier, kunt u **URL** **Parameters** gebruiken om het verborgen veld te vullen.

>[!NOTE]
>
>Parameters zijn nogal technisch, niet? Maar als je ze krijgt, zijn ze machtig. Deze [Wikipedia-pagina op Query-tekenreeksen](http://en.wikipedia.org/wiki/Query_string) is enigszins handig.

1. Selecteer **URL Parameter** voor **Waardetype ophalen**.

   ![](assets/image2014-9-15-13-3a6-3a48.png)

1. Voer de **Parameternaam** in en klik op **Opslaan**.

   ![](assets/image2014-9-15-13-3a7-3a35.png)

>[!TIP]
>
>U kunt een standaardwaarde invoeren als de URL-parameter niet wordt gevonden.

## Koekjeswaarde {#cookie-value}

Als u gegevens opslaat in cookies, kunt u **Cookie** **Value** gebruiken om gegevens op te halen wanneer het formulier wordt verzonden.

1. Selecteer **Cookie** **Waarde** voor **Get** **Value** **From**.

   ![](assets/image2014-9-15-13-3a8-3a21.png)

1. Voer de gewenste naam voor de cookieparameter in en klik op **Opslaan**.

   ![](assets/image2014-9-15-13-3a8-3a43.png)

   >[!TIP]
   >
   >U kunt een standaardwaarde invoeren als de parameter/cookie niet wordt gevonden.

## Refererparameter {#referrer-parameter}

Als u gegevens wilt vastleggen van de pagina waarvan de bezoeker afkomstig is voordat u het formulier invult, kunt u **Referrer** **Parameter** gebruiken.

1. Stel **Get** **Value** **From** to **Referrer** **Parameter** in.

   ![](assets/image2014-9-15-13-3a9-3a31.png)

1. Voer de **Parameternaam** in die u vanaf de referentie-URL wilt uitlijnen en klik op **Opslaan**.

   ![](assets/image2014-9-15-13-3a9-3a56.png)

   >[!TIP]
   >
   >U kunt een **Standaard** **Waarde** invoeren voor het geval dat de referentieparameter niet wordt gevonden.

1. Klik **Voltooien**.

   ![](assets/image2014-9-15-13-3a10-3a26.png)

1. Klik **Goedkeuren en Sluiten**.

   ![](assets/image2014-9-15-13-3a10-3a43.png)

Zoet! Je doet het behoorlijk goed. Er is meer over [vormen](http://docs.marketo.com/display/docs/forms) te leren.
