---
unique-page-id: 2359791
description: Doel voor doorverwijzing opgeven - Marketo Docs - Productdocumentatie
title: Doel voor doorverwijzing opgeven
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '298'
ht-degree: 0%

---


# Doel opgeven voor doorverwijzing {#specify-goal-for-referral-offer}

Wanneer u [een verwijzingsaanbieding ](create-a-referral-offer.md) creeert, moet u het nalevingsdoel bepalen. Het doel kan worden gedefinieerd door persoonlijke activiteiten op de webpagina, zoals paginabezoeken of aanmelden. U kunt zelfs een [aangepaste JavaScript-gebeurtenis](../../../../product-docs/demand-generation/social/social-functions/conversion-script-for-custom-events.md) gebruiken.

Alternatief, kunt u een [slimme lijsttrekker](specify-goal-for-referral-offer.md) in Marketo gebruiken om op om het even welke mijlpaal te wachten, zoals een kans die voor de genoemde persoon wordt gecreeerd.

Voorbeelden van doelen:

* 10 bezoeken
* 5 bedoelde aanmeldingen
* 1 bedoelde kans gemaakt
* 2 aankopen van e-commerce
* 5 doorverwezen webinaire deelnemers

1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Selecteer het verwijzingsaanbod en klik op **Concept bewerken.**

   ![](assets/image2014-9-19-15-3a6-3a35.png)

1. In de verwijzingsaanbiedingsredacteur, ga **App Montages** > **Details van de aanbieding.**

   ![](assets/image2014-9-19-15-3a6-3a44.png)

1. Kies onder **Instellingen** een gebeurtenistype in de vervolgkeuzelijst **Fulfillment Goal**.

   ![](assets/image2014-9-19-15-3a6-3a56.png)

>[!TIP]
>
>Als u van plan bent om **Geef Krediet aan Referrer** debietstap te gebruiken, moet u **Slimme Trigger van de Lijst** als het doel van de vervulling hier typen.

* Bezoeken waarnaar wordt verwezen: De deelnemers van de aanbieding krijgen krediet voor elk bezoek van een vriend aan de pagina die uw voorstel ontvangt.
* Aanwijzingen waarnaar wordt verwezen: De deelnemers van de aanbieding krijgen krediet voor elke vriend die zich voor de aanbieding aantekent.
* Trigger voor slimme lijst: De deelnemers van de aanbieding krijgen krediet voor elke vriend die aan de voorwaarden van een [slimme lijst](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists.md) trekker in een [slimme campagne](http://docs.marketo.com/display/docs/smart+campaigns) voldoet. U kunt bijvoorbeeld een trigger gebruiken die wordt geactiveerd wanneer een doorverwezen vooruitzicht zich aanmeldt voor een webinar.

* Aangepaste JavaScript-gebeurtenis: De deelnemers van de aanbieding krijgen krediet voor elke vriend die een bepaalde gebeurtenis JavaScript op uw pagina teweegbrengt. Zie [Conversiescript voor Aangepaste gebeurtenissen](../../../../product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!NOTE]
>
>Er zijn nieuwe filters en triggers beschikbaar in slimme campagnes om sociale activiteit te controleren. Zie [gebruik triggers en filters voor sociale activiteiten](../../../../product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!MORELIKETHIS]
>
>Vervolgens kunt u [de e-mails voor aanmelding en afhandeling selecteren](send-referral-offer-fulfillment-email.md) die u vanuit uw verwijzingsaanbod wilt verzenden.

