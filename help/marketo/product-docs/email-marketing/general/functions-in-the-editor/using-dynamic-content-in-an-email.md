---
unique-page-id: 2950617
description: Dynamische inhoud gebruiken in een e-mail - Marketo Docs - Productdocumentatie
title: Dynamische inhoud gebruiken in een e-mail
exl-id: a1178f76-6760-4a4a-9510-f129ee6a9032
feature: Email Editor
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# Dynamische inhoud gebruiken in een e-mail {#using-dynamic-content-in-an-email}

>[!PREREQUISITES]
>
>[Een segmentatie maken](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)

Gebruik Dynamische inhoud in e-mails om de beoogde gegevens voor leads te verzenden.

>[!NOTE]
>
>Het gebruik van variabelen in dynamische inhoud in een e-mailbericht wordt alleen ondersteund bij het gebruik van triggercampagnes. Het is **niet** ondersteund bij het gebruik van Batch-campagnes.

## Segmentering toevoegen {#add-segmentation}

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities.png)

1. Selecteer uw e-mail en klik op **Concept bewerken**.

   ![](assets/1.2.png)

1. In dit voorbeeld maken we de onderwerpregel dynamisch. Klik in het veld Onderwerp en klik vervolgens op de knop **Dynamisch maken** knop.

   ![](assets/1.3.png)

   >[!NOTE]
   >
   >U kunt een element binnen e-mail dynamisch maken. Selecteer hiertoe het gebied, klik op het tandwielpictogram en selecteer **Dynamisch maken** (of [Vervangen door fragment](/help/marketo/product-docs/personalization/segmentation-and-snippets/snippets/create-a-snippet.md), afhankelijk van wat u doet).

1. Voer de naam van de segmentatie in, selecteer deze en klik op **Opslaan**.

   ![](assets/1.4.png)

   De segmentatie en de bijbehorende segmenten worden weergegeven onder het tabblad Dynamisch aan de rechterkant.

   ![](assets/1.5.png)

## Dynamische inhoud toepassen {#apply-dynamic-content}

>[!CAUTION]
>
>Het aantal dynamische inhoudselementen dat is toegestaan, is niet onbeperkt. Hoewel er geen specifieke getallimiet is (kan deze variëren op basis van de combinatie van inhoud), kan het te veel gebruiken van dynamische inhoud negatieve gevolgen hebben voor de prestaties van de e-mail. We raden u aan om de hoeveelheid dynamische inhoudselementen te behouden die wordt gebruikt tot minder dan 20 per e-mail.

1. Klik op de segmenten en voeg de onderwerpregel toe.

![](assets/2.1.png)

1. Herhaal dit voor elk segment.

   ![](assets/2.2.png)

>[!TIP]
>
>Maak een standaard-e-mail voordat u inhoud op de verschillende segmenten toepast.

>[!CAUTION]
>
>Wijzigingen in het inhoudsblok Standaardsegment worden toegepast op alle segmenten.

Zoet! Nu kunt u flexibele e-mails naar uw doelgroep sturen.

>[!MORELIKETHIS]
>
>* [Een voorbeeld van een e-mailbericht weergeven met dynamische inhoud](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/preview-an-email-with-dynamic-content.md)
>* [Dynamische inhoud gebruiken in een bestemmingspagina](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/use-dynamic-content-in-a-free-form-landing-page.md)
