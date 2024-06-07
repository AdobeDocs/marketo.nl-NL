---
unique-page-id: 10095554
description: Een formulier insluiten in een webcampagne - Marketo Docs - Productdocumentatie
title: Een formulier insluiten in een webcampagne
exl-id: 41e60ae6-9a40-444f-8a55-47fc6ef6c5fb
feature: Web Personalization
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '333'
ht-degree: 0%

---

# Een formulier insluiten in een webcampagne {#embed-a-form-into-a-web-campaign}

Zie hoe u een Marketo-formulier kunt insluiten in een webcampagne (Dialoogvenster, In Zone of Widget).

1. Klik met de rechtermuisknop op een goedgekeurd formulier. Selecteren **Code insluiten**.

   ![](assets/image2015-12-16-10-3a58-3a39.png)

1. Kopieer de code.

   ![](assets/image2015-12-16-11-3a16-3a24.png)

1. Ga in Persoonlijke webweergave naar **Webcampagnes**.

   ![](assets/web-campaigns-hand-7.jpg)

1. Klikken **Nieuwe campagne maken**.

   ![](assets/create-new-web-campaign-hand-1.jpg)

1. Klik in de Rich Text Editor op het HTML-pictogram.

   ![](assets/five-1.png)

1. Plak de insluitcode van het formulier in de HTML Source Editor. Klikken **Bijwerken**.

   ![](assets/six-1.png)

1. Het formulier wordt niet weergegeven in de editorweergave, maar u kunt het voorbeeld bekijken om te zien hoe het in een campagne wordt weergegeven.

1. Klikken **Starten** om de campagne te starten.

   >[!NOTE]
   >
   >Wijzigingen in de velden van het formulier moeten worden aangebracht in de marketingactiviteiten van Marketo in het concept van het formulier bewerken.

## Op drie manieren een achtergrondafbeelding aan een formulier toevoegen {#three-ways-to-add-a-background-image-to-a-form}

Als u een achtergrondafbeelding aan het formulier wilt toevoegen, kunt u:

* CSS van een formulierthema bewerken
* Dialoogvenster- of widgetkleuren wijzigen in Campagne instellen
* CSS-code toevoegen aan het script

Als u de CSS van een formulierthema wilt bewerken, raadpleegt u [dit artikel](/help/marketo/product-docs/demand-generation/forms/form-design/edit-the-css-of-a-form-theme.md).

U wijzigt als volgt de kleur van het dialoogvenster of de widget in de campagne Set:

1. Selecteer in de Rich Text Editor een type dialoogvenster en een dialoogstijl, koptekstkleur en achtergrondkleur om de achtergrondkleuren van het formulier aan te passen. Klikken **Opslaan**.

   ![](assets/image2015-12-29-18-3a28-3a31.png)

1. Hier is een voorbeeld van hoe een Modern Stijl van de Dialoog van de Versiering met een lichtpaarse kopbal en achtergrondkleur kijkt.

   ![](assets/image2015-12-29-18-3a27-3a31.png)

CSS-code toevoegen aan het script:

1. Klik in de Rich Text Editor op het HTML-pictogram.

   ![](assets/image2015-12-29-17-3a56-3a13.png)

1. Plak de insluitcode van het formulier met de achtergrondstijlcode in de HTML Source Editor. Klikken **Bijwerken**.

   ![](assets/image2015-12-29-18-3a1-3a15.png)

1. Klikken **Voorvertoning** om te zien hoe het in een campagne wordt weergegeven (het formulier wordt niet weergegeven in de editorweergave). Hier volgt een voorbeeld van hoe de bovenstaande formuliercode wordt weergegeven in een campagne met een achtergrondafbeelding.

   ![](assets/image2015-12-29-18-3a20-3a35.png)

>[!MORELIKETHIS]
>
>* [CSS van een formulierthema bewerken](/help/marketo/product-docs/demand-generation/forms/form-design/edit-the-css-of-a-form-theme.md)
>* [Bericht met dank weergeven zonder opvolgingspagina](https://developers.marketo.com/blog/show-thank-you-message-without-a-follow-up-landing-page/)
>* [Forms 2.0](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/forms-api-reference)
