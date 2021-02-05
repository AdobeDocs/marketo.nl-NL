---
unique-page-id: 2359793
description: E-mails gebruiken in sociale aanbiedingen - Marketo Docs - Productdocumentatie
title: E-mails gebruiken in sociale aanbiedingen
translation-type: tm+mt
source-git-commit: 074701d1a5f75fe592ac7f44cce6fb3571e94710
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---


# E-mails gebruiken in sociale aanbiedingen {#use-emails-in-social-promotions}

Wanneer u een [verwijzingsaanbod](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) of een [sweepstakes](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md) creeert, kunt u e-mails omvatten om te verzenden wanneer de persoon omhoog ondertekent, en opnieuw wanneer de persoon de beloning heeft gewonnen.

>[!TIP]
>
>Zie [Een e-mailschoen verzenden](/help/marketo/getting-started/quick-wins/send-an-email.md) om een e-mailbericht te maken.

Gebruik in de e-mails de volgende tokens:

* **E-mail** aanmelden: Gebruik deze optie  **`{{social.Share Url}}`** om elke deelnemer een persoonlijke gedeelde koppeling te sturen.

* **E-mailadres** voor afhandeling: Gebruik deze optie  **`{{social.Promo Code}}`** om aan elke winnaar een  [promotiecode](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md) te sturen.

>[!PREREQUISITES]
>
>Voordat u een e-mail kunt toevoegen aan een sociale app, moet deze _operationeel_ en _goedgekeurd_ zijn. Zie [Instellingen bewerken voor een e-mail](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Selecteer de app en klik op **Concept** bewerken.

   ![](assets/image2014-9-19-16-3a12-3a33.png)

1. Ga in de sociale app-editor naar **App-instellingen > Aanbiedingsgegevens** (of **Gegevens van items wissen**).

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
>In een zweepslag wordt de e-mail voor afhandeling altijd automatisch verzonden wanneer u [de winnaar](/help/marketo/product-docs/demand-generation/social/sweepstakes/select-sweepstakes-winners.md) selecteert.

>[!NOTE]
>
>**Definitie**
>
>* **auto on target**: Het e-mailbericht voor afhandeling wordt automatisch verzonden wanneer elke deelnemer het doel bereikt.
>* **handmatig verzenden**: Zodra de mensen beginnen het doel te bereiken, terugkeer naar uw verwijzingsaanbod om de vervulling e-mail [ manueel te ](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md)verzenden.

>



>[!MORELIKETHIS]
>
>Vervolgens kunt u [de gedeelde URL kiezen](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md) of u kunt [in uw verwijzingsaanbieding de promo-codes uploaden](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md) die u wilt verzenden.
