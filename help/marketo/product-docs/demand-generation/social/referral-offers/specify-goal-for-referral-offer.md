---
unique-page-id: 2359791
description: Doel voor doorverwijzing opgeven - Marketo Docs - Productdocumentatie
title: Doel voor doorverwijzing opgeven
exl-id: 9869eb66-53df-4ea8-903f-e6650add8da2
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '292'
ht-degree: 0%

---

# Doel voor doorverwijzing opgeven {#specify-goal-for-referral-offer}

Wanneer u [een verwijzingsaanbod maken](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md), moet u het uitvoeringsdoel bepalen. Het doel kan worden gedefinieerd door persoonlijke activiteiten op de webpagina, zoals paginabezoeken of aanmelden. U kunt zelfs een [aangepaste JavaScript-gebeurtenis](/help/marketo/product-docs/demand-generation/social/social-functions/conversion-script-for-custom-events.md).

U kunt ook een trigger voor een slimme lijst in Marketo gebruiken om te wachten op een mijlpaal, zoals een mogelijkheid die wordt gemaakt voor de desbetreffende persoon.

Voorbeelden van doelen:

* 10 bezoeken
* 5 bedoelde aanmeldingen
* 1 bedoelde kans gemaakt
* 2 aankopen van e-commerce
* 5 doorverwezen webinaire deelnemers

1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Selecteer het verwijzingsaanbod en klik op **Concept bewerken**.

   ![](assets/image2014-9-19-15-3a6-3a35.png)

1. Ga in de verwijzingsofferte-editor naar **App-instellingen** > **Aanbiedingsgegevens**.

   ![](assets/image2014-9-19-15-3a6-3a44.png)

1. Onder **Instellingen**, kiest u een gebeurtenistype in het menu **Afwikkelingsdoelstelling** vervolgkeuzelijst.

   ![](assets/image2014-9-19-15-3a6-3a56.png)

>[!TIP]
>
>Als u de **Crediteren aan referentie** stap voor doorloop, selecteert u **Smart List Trigger** als het doel van de vervulling hier typen.

* Bezoeken waarnaar wordt verwezen: De deelnemers van de aanbieding krijgen krediet voor elk bezoek van een vriend aan de pagina die uw voorstel ontvangt.
* Aanwijzingen waarnaar wordt verwezen: De deelnemers van de aanbieding krijgen krediet voor elke vriend die zich voor de aanbieding aantekent.
* Trigger voor slimme lijst: De deelnemers van de aanbieding krijgen krediet voor elke vriend die aan de voorwaarden van een [slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists.md) trigger in een [slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md). U kunt bijvoorbeeld een trigger gebruiken die wordt geactiveerd wanneer een doorverwezen vooruitzicht zich aanmeldt voor een webinar.

* Aangepaste JavaScript-gebeurtenis: De deelnemers van de aanbieding krijgen krediet voor elke vriend die een bepaalde gebeurtenis JavaScript op uw pagina teweegbrengt. Zie [Conversiescript voor aangepaste gebeurtenissen](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!NOTE]
>
>Er zijn nieuwe filters en triggers beschikbaar in slimme campagnes om sociale activiteit te controleren. Zie [gebruik van triggers en filters voor sociale activiteiten](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!MORELIKETHIS]
>
>Vervolgens kunt u [de e-mails voor aanmelding en afhandeling selecteren](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md) om van je verwijzingsvoorstel te verzenden.
