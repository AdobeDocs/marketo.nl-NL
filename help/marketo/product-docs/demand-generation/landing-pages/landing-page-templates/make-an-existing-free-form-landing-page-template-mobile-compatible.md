---
unique-page-id: 5472348
description: Een bestaande landingspaginasjabloon in vrije vorm geschikt maken voor mobiel - Marketo Docs - Productdocumentatie
title: Een bestaande landingspaginasjabloon in vrije vorm geschikt maken voor mobiele apparaten
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---


# Een bestaande landingspaginasjabloon in vrije vorm geschikt maken voor mobiel {#make-an-existing-free-form-landing-page-template-mobile-compatible}

>[!NOTE]
>
>Landing pages templates that were created before the [January 2015 release](../../../../release-notes/2015/release-notes-january-2015.md)need to be upgrade to be mobile compatible.

Dit kan op twee plaatsen worden gedaan, de Redacteur van het Malplaatje en de het Landen Redacteur van de Pagina.

## Upgrade uitvoeren vanuit de Sjablooneditor {#upgrade-from-the-template-editor}

1. Ga naar **Design Studio**.

   ![](assets/designstudio-1.png)

1. Selecteer **Sjablonen**.

   ![](assets/image2015-1-22-20-3a20-3a2.png)

1. Selecteer een sjabloon waarbij **Mobiel compatibel** **Nee** is.

   ![](assets/image2015-1-22-20-3a22-3a24.png)

1. Klik **Concept bewerken**.

   ![](assets/image2015-1-22-20-3a25-3a36.png)

1. Klik **Mobiel compatibel maken**.

   ![](assets/image2015-1-22-20-3a30-3a33.png)

1. Klik **Upgrade**.

   ![](assets/image2015-1-22-20-3a32-3a45.png)

   Uw sjabloon voor de openingspagina is nu compatibel met mobiele apparaten.

   >[!NOTE]
   >
   >De upgrade moet onschadelijk zijn, maar zorg dat de pagina&#39;s op eventuele verschillen worden gecontroleerd. Als u een upgrade uitvoert, worden concepten gemaakt van alle bestemmingspagina&#39;s die gebruikmaken van die sjabloon.

   ![](assets/image2015-1-22-20-3a36-3a43.png)

## Wat maakt een malplaatje Mobiel Compatibel? {#what-makes-a-template-mobile-compatible}

Geweldige vragen! Uw sjabloon moet de volgende tags hebben:

`<pre data-theme="Confluence">Must have <!DOCTYPE HTML> Must have a <HEAD> element Must have a <TITLE> in the <HEAD> element Must have <META CHARSET="UTF-8"> within the <HEAD> element Must have a <BODY> element that contains one (and only one) <DIV class="mktoContent"></DIV></pre>`  Als alles er goed uitziet, ziet u dit bericht.

![](assets/image2015-1-22-20-3a41-3a31.png)

Als er iets misgaat, wordt er een foutbericht weergegeven. Klik op Herstellen om het probleem op te lossen en herhaal het validatieproces.

![](assets/image2015-1-22-20-3a43-3a20.png)

Als u wijzigingen aanbrengt in de sjabloon, klikt u op Sjabloonhandelingen en selecteert u Mobiele compatibiliteit valideren.

## Een sjabloon bijwerken vanuit de Landing Page Editor in vrije vorm {#upgrading-a-template-from-the-free-form-landing-page-editor}

Wanneer u een bestemmingspagina uitgeeft en u op het mobiele lusje klikt, zult u soms merken het malplaatje niet is bevorderd. Vrees niet! U kunt het daar upgraden.

1. Klik op het tabblad **Mobiel**.

   ![](assets/image2015-1-22-20-3a48-3a19.png)

1. Klik op het selectievakje en klik op **Activeren**.

   ![](assets/image2015-1-22-20-3a49-3a34.png)

   >[!NOTE]
   >
   >Als u de mobiele versie van een sjabloon activeert, worden concepten gemaakt van alle bestemmingspagina&#39;s die deze gebruiken.

Geweldig! U kunt nu [de mobiele weergave aanpassen](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/customize-mobile-view-for-your-free-form-landing-page.md) van al uw bestemmingspagina&#39;s die deze sjabloon gebruiken.

>[!MORELIKETHIS]
>
>* [De mobiele weergave aanpassen voor uw openingspagina](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/customize-mobile-view-for-your-free-form-landing-page.md)

>



