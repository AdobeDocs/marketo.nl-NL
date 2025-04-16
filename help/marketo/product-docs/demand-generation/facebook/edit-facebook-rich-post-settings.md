---
unique-page-id: 2950555
description: Facebook Rich Post Settings bewerken - Marketo Docs - Productdocumentatie
title: Instellingen Facebook Rich Post bewerken
exl-id: f72bfb03-9bc7-46c4-bfb8-b377b2d23fc9
hide: true
hidefromtoc: true
feature: Integrations
source-git-commit: 7a8f5146126d6e8a4902be9337eef4d51e108cf0
workflow-type: tm+mt
source-wordcount: '316'
ht-degree: 0%

---

# Instellingen Facebook Rich Post bewerken {#edit-facebook-rich-post-settings}

Pas advertenties aan wanneer mensen je delen op Facebook.

>[!AVAILABILITY]
>
>Niet alle Marketo Engage-gebruikers hebben deze functionaliteit aangeschaft. Neem contact op met het Adobe-accountteam (uw accountmanager) voor meer informatie.

Marketo _sociale apps_ staat uw lood toe om uw landende pagina&#39;s met hun verbindingen op sociale netwerken zoals Facebook, Twitter, enz. te delen. Met Facebook OpenGraph-tags (OG-tags) kunt u opgeven welke informatie van uw bestemmingspagina in Facebook-berichten wordt opgenomen.

## Opties voor rijke berichten selecteren {#select-rich-post-options}

U kunt de typen paginagegevens opgeven die u wilt gebruiken in de uitgebreide Facebook-berichten die worden gegenereerd door shares van uw bestemmingspagina.

1. Selecteer **het Bericht van Facebook** in de redacteur voor uw **YouTube** video of sociale knoop.

   ![](assets/image2014-9-22-16-3a47-3a21.png)

1. Maak een keuze uit de volgende opties voor uw Facebook-bericht.

   * Statische inhoud toevoegen: selecteer deze optie om de titel, het bijschrift en de beschrijving handmatig in te voeren.

   ![](assets/image2014-9-22-16-3a48-3a0.png)

   * Dynamische inhoud toevoegen: uw sociale app kan de tags `<TITLE>`, `<CAPTION>` en `<DESCRIPTION>` van uw bestemmingspagina gebruiken om uw rijke advertentie te vullen.

   ![](assets/image2014-9-22-16-3a48-3a9.png)

   >[!NOTE]
   >
   >Deze zouden al in de paginabron moeten bestaan, maar voor meer controle, kunt u specifieke markeringen van Facebook OG aan uw landende pagina toevoegen.

   * Voeg geen rijke inhoud toe: beperkt de Facebook-berichten van uw openingspagina tot het hoofdbericht en de koppeling.

   ![](assets/image2014-9-22-16-3a48-3a18.png)

## Facebook OG-tags toevoegen aan een bestemmingspagina {#add-facebook-og-tags-to-a-landing-page}

Als u de pagina-elementen wilt beheren die vanaf de bestemmingspagina in de Facebook-shares worden opgenomen, kunt u Facebook OG-tags (Open Graph) voor titel, bijschrift en beschrijving toevoegen aan uw bestemmingspagina.

1. Open de het landen pagina die uw **video van YouTube** of sociale knoop bevat.

   ![](assets/image2014-9-22-16-3a51-3a28.png)

   **het Bestaan van de Pagina Designer** opent in een nieuw venster.

1. Selecteer **het Bestaan van de Pagina Acties** > **uitgeven de Markeringen van Meta van de Pagina**.

   ![](assets/image2014-9-22-16-3a51-3a36.png)

1. Voeg de HTML toe die og:title, og:caption, en og:description bepaalt. Kopieer en plak deze regels en vervang de plaatsaanduidingstekst:

   `<meta property="og:title" content="My Post Title"/>`

   `<meta property="og:caption" content="My Post Caption"/>`

   `<meta property="og:description" content="This text appears in the post description"/>`

   ![](assets/image2014-9-22-16-3a52-3a8.png)

>[!NOTE]
>
>Let op dat u de juiste HTML-syntaxis gebruikt wanneer u de OG-tags toevoegt.
