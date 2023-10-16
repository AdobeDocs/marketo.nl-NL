---
unique-page-id: 2950555
description: Facebook Rich Post Settings bewerken - Marketo Docs - Productdocumentatie
title: Facebook Rich Post-instellingen bewerken
exl-id: f72bfb03-9bc7-46c4-bfb8-b377b2d23fc9
feature: Integrations
source-git-commit: 2671f81f62658447e4b2a3dc2e02a4e0927443e8
workflow-type: tm+mt
source-wordcount: '316'
ht-degree: 0%

---

# Facebook Rich Post-instellingen bewerken {#edit-facebook-rich-post-settings}

Pas advertenties aan wanneer mensen je delen op Facebook.

>[!AVAILABILITY]
>
>Niet alle gebruikers van het Marketo Engage hebben deze functionaliteit aangeschaft. Neem contact op met het accountteam van de Adobe (uw accountmanager) voor meer informatie.

Marketo [sociale apps](/help/marketo/product-docs/demand-generation/social/social-functions/add-a-social-button-on-a-landing-page.md) toestaan dat uw leads uw bestemmingspagina&#39;s delen met hun verbindingen op sociale netwerken zoals Facebook, Twitter, enz. Met facebook OpenGraph-tags (OG-tags) kunt u opgeven welke informatie van uw bestemmingspagina wordt opgenomen in Facebook-advertenties.

## Opties voor rijke berichten selecteren {#select-rich-post-options}

U kunt de typen pagina-informatie opgeven die moeten worden gebruikt in de opgemaakte Facebook-berichten die worden gegenereerd door shares van uw bestemmingspagina.

1. Selecteren **Facebook-bericht** in de redacteur voor uw **YouTube** video of sociale knop.

   ![](assets/image2014-9-22-16-3a47-3a21.png)

1. Selecteer een van de volgende opties voor je Facebook-bericht.

   * Statische inhoud toevoegen: selecteer deze optie om de titel, het bijschrift en de beschrijving handmatig in te voeren.

   ![](assets/image2014-9-22-16-3a48-3a0.png)

   * Dynamische inhoud toevoegen: uw sociale toepassing kan de landingspagina&#39;s gebruiken `<TITLE>`, `<CAPTION>`, en `<DESCRIPTION>` tags om je rijke advertentie te vullen.

   ![](assets/image2014-9-22-16-3a48-3a9.png)

   >[!NOTE]
   >
   >Deze moeten al in de paginabron staan, maar voor meer controle kunt u specifieke Facebook OG-tags toevoegen aan uw bestemmingspagina.

   * Voeg geen rijke inhoud toe: beperkt de Facebook-berichten van uw landingspagina tot alleen het hoofdbericht en de koppeling.

   ![](assets/image2014-9-22-16-3a48-3a18.png)

## Facebook OG-tags toevoegen aan een bestemmingspagina {#add-facebook-og-tags-to-a-landing-page}

Als u de pagina-elementen wilt beheren die worden opgenomen in de Facebook-shares van uw bestemmingspagina, kunt u Facebook OG-tags (Open Graph) voor titel, bijschrift en beschrijving toevoegen aan uw bestemmingspagina.

1. Open de openingspagina met uw **YouTube-video** of sociale knop.

   ![](assets/image2014-9-22-16-3a51-3a28.png)

   De **Landingspagina Designer** wordt geopend in een nieuw venster.

1. Selecteren **Handelingen op bestemmingspagina** > **Metacodes van pagina bewerken**.

   ![](assets/image2014-9-22-16-3a51-3a36.png)

1. Voeg de HTML toe die og:title, og:caption, en og:description bepaalt. Kopieer en plak deze regels en vervang de plaatsaanduidingstekst:

   `<meta property="og:title" content="My Post Title"/>`

   `<meta property="og:caption" content="My Post Caption"/>`

   `<meta property="og:description" content="This text appears in the post description"/>`

   ![](assets/image2014-9-22-16-3a52-3a8.png)

>[!NOTE]
>
>Let op dat u de juiste syntaxis voor HTML gebruikt wanneer u de OG-tags toevoegt.
