---
unique-page-id: 2359793
description: E-mails gebruiken in sociale aanbiedingen - Marketo Docs - Productdocumentatie
title: E-mails gebruiken in sociale aanbiedingen
exl-id: 633ad86e-d085-420f-8e28-9b722e345852
feature: Social
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# E-mails gebruiken in sociale aanbiedingen {#use-emails-in-social-promotions}

Wanneer u een [verwijzingsaanbod](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) of [zweten](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md), kun je e-mails opnemen die je kunt sturen wanneer de persoon zich aanmeldt, en opnieuw wanneer de persoon de beloning heeft gewonnen.

>[!TIP]
>
>Als u een e-mail wilt maken, raadpleegt u [Een e-mailschok verzenden](/help/marketo/getting-started/quick-wins/send-an-email.md).

Gebruik in de e-mails de volgende tokens:

* **E-mail aanmelden**: Gebruiken **`{{social.Share Url}}`** iedere deelnemer een persoonlijke koppeling sturen.

* **E-mailadres voor afhandeling**: Gebruiken **`{{social.Promo Code}}`** om elke winnaar een [promotiecode](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md).

>[!PREREQUISITES]
>
>Voordat u een e-mail kunt toevoegen aan een sociale app, moet deze _operationeel_ en _goedgekeurd_. Zie [Instellingen voor een e-mail bewerken](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Selecteer de app en klik op **Concept bewerken**.

   ![](assets/image2014-9-19-16-3a12-3a33.png)

1. Ga in de sociale-app-editor naar **App-instellingen > Details voorstel** (of **Details van sweepstakes**).

   ![](assets/image2014-9-19-16-3a12-3a41.png)

1. Voeg de aanmeldings-e-mail toe.

   ![](assets/image2014-9-19-16-3a12-3a49.png)

   >[!NOTE]
   >
   >Het bevestigingsbericht wordt automatisch verzonden wanneer een persoon zich aanmeldt.

1. Voeg de e-mail voor het voldoen aan de voorwaarde toe.

   ![](assets/image2014-9-19-16-3a15-3a26.png)

1. Kies in een verwijzingsaanbod of het e-mailbericht voor het voldoen van de voorwaarden automatisch of handmatig wordt verzonden.

   ![](assets/image2014-9-19-16-3a15-3a36.png)

>[!NOTE]
>
>In een zweepslagen wordt de e-mail over het voldoen altijd automatisch verzonden wanneer u [de winnaar selecteren](/help/marketo/product-docs/demand-generation/social/sweepstakes/select-sweepstakes-winners.md).

>[!NOTE]
>
>**Definitie**
>
>* **auto-on-doel**: Het e-mailbericht voor afhandeling wordt automatisch verzonden wanneer elke deelnemer het doel bereikt.
>* **handmatig verzenden**: Zodra de mensen beginnen het doel te ontmoeten, terugkeer naar uw verwijzingsaanbod aan manueel [verzend het afhandelingsbericht](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md).
>

>[!MORELIKETHIS]
>
>Vervolgens kunt u [Kies de gedeelde URL](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md) of, in uw verwijzingsvoorstel, kunt u [uploaden van de promotiecodes](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md) je verzendt het.
