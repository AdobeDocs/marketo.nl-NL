---
unique-page-id: 2359793
description: E-mails gebruiken in sociale aanbiedingen - Marketo Docs - Productdocumentatie
title: E-mails gebruiken in sociale aanbiedingen
exl-id: 633ad86e-d085-420f-8e28-9b722e345852
feature: Social
source-git-commit: 97324d932b65020d041f728928d3792140bea71c
workflow-type: tm+mt
source-wordcount: '266'
ht-degree: 0%

---

# E-mails gebruiken in sociale aanbiedingen {#use-emails-in-social-promotions}

Wanneer u a [ verwijzingsaanbod ](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) of a [ transporten ](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md) creeert, kunt u e-mails omvatten om te verzenden wanneer de persoon omhoog ondertekent, en opnieuw wanneer de persoon de beloning heeft gewonnen.

>[!IMPORTANT]
>
>Op 31 juli 2024 begonnen we met het afschaffen van deze functie. U kunt geen nieuwe elementen maken. Bestaande activa blijven werken tot 31 januari 2025. [ leer meer ](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977) {target="_blank"}

>[!TIP]
>
>Om een e-mail tot stand te brengen, zie [ een E-mailschoen ](/help/marketo/getting-started/quick-wins/send-an-email.md) verzenden.

Gebruik in de e-mails de volgende tokens:

* **Teken-up e-mail**: Gebruik **`{{social.Share Url}}`** om elke deelnemende persoon een gepersonaliseerde aandeelverbinding te verzenden.

* **e-mail van de vervulling**: Gebruik **`{{social.Promo Code}}`** om elke winnaar te verzenden a [ promo code ](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md).

>[!PREREQUISITES]
>
>Alvorens u een e-mail aan een sociale app kunt toevoegen, moet het _operationeel_ zijn en _goedgekeurd_. Zie [ Montages voor e-mail ](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md) uitgeven.

1. Ga naar **de Marketing Activiteiten**.

   ![](assets/ma.png)

1. Selecteer app, en klik **uitgeven Ontwerp**.

   ![](assets/image2014-9-19-16-3a12-3a33.png)

1. In de sociale app redacteur, ga naar **Montages van de Toepassing > de Details van het Aanbod** (of **Details van het Aanbod**).

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
>In een truc, wordt de vervulling e-mail altijd verzonden automatisch wanneer u [ de winnaar ](/help/marketo/product-docs/demand-generation/social/sweepstakes/select-sweepstakes-winners.md) selecteert.

>[!NOTE]
>
>**Definitie**
>
>* **auto op doel**: De vervulling e-mail wordt verzonden automatisch aangezien elke deelnemer het doel ontmoet.
>* **verzendt manueel**: Zodra de mensen beginnen het doel te ontmoeten, terugkeer naar uw verwijzingsaanbieding aan manueel [ verzendt de vervulling e-mail ](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md).
>

>[!MORELIKETHIS]
>
>Daarna, kunt u [ het aandeel URL ](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md) kiezen of, in uw verwijzingsaanbieding, kunt u [ de bevorderingscodes ](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md) uploaden u uit zult verzenden.
