---
unique-page-id: 2359807
description: Overzichtsstijlen aanpassen - Marketo Docs - Productdocumentatie
title: Overtrekstijlen aanpassen
exl-id: 2b1437d9-a424-4d05-b614-7502c12e6ba2
source-git-commit: 2671f81f62658447e4b2a3dc2e02a4e0927443e8
workflow-type: tm+mt
source-wordcount: '160'
ht-degree: 0%

---

# Overtrekstijlen aanpassen {#customize-sweepstakes-styles}

Wanneer u [een zweepslag maken](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md), kunt u aanpassen hoe het op uw landingspagina kijkt.

>[!AVAILABILITY]
>
>Niet alle gebruikers van het Marketo Engage hebben deze functionaliteit aangeschaft. Neem contact op met het accountteam van de Adobe (uw accountmanager) voor meer informatie.

1. Ga naar **Marketingactiviteiten**.

![](assets/login-marketing-activities-1.png)

1. Selecteer de overgangen en klik op **Concept bewerken**.

   ![](assets/image2014-9-25-17-3a51-3a45.png)

1. Ga in de Zweedse redacteur naar **App-instellingen** > **Weergave**.

   ![](assets/image2014-9-25-17-3a51-3a59.png)

1. Bewerk de tekst van de aanmeldknop en de voortgangskoppeling.

   ![](assets/image2014-9-25-17-3a52-3a22.png)

1. Voer voor elk element dat u wilt aanpassen uw aangepaste CSS-eigenschappen in.

   ![](assets/image2014-9-25-17-3a52-3a37.png)

   Voorbeeld-CSS voor **Knop Enter**:
   `<pre>border: 5px solid #7B68EE; background-color: purple; padding: 10px; font: 16px; color: #FFFFFF; text-align: center;</pre>`

   Voorbeeldafbeelding voor **Knop Enter**:
   `<pre>background:url(https://app.marketo.com/images/public-site/button_sign-up-now.png) no-repeat center center; width:275px; height:95px; margin:auto; display:block;</pre>` `<pre>`

   >[!NOTE]
   >
   >Als u een afbeelding gebruikt met tekst erop, vergeet dan niet de tekst uit het palet **Knop Enter** veld onder Tekst hierboven.

1. Terwijl u elke wijziging aanbrengt, wordt het resultaat weergegeven in de voorvertoning Weergave en Bewerken.

   ![](assets/image2014-9-25-17-3a55-3a3.png)

   >[!NOTE]
   >
   >Test de knop in verschillende browsers, waaronder oudere versies.

   >[!MORELIKETHIS]
   >
   >De volgende stap bestaat uit toevoegen [e-mails over aanmelden en voldoen aan uw wensen](/help/marketo/product-docs/demand-generation/social/social-functions/use-emails-in-social-promotions.md).
