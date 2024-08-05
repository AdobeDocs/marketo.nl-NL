---
unique-page-id: 2359807
description: Overzichtsstijlen aanpassen - Marketo Docs - Productdocumentatie
title: Overtrekstijlen aanpassen
exl-id: 2b1437d9-a424-4d05-b614-7502c12e6ba2
source-git-commit: 97324d932b65020d041f728928d3792140bea71c
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---

# Overtrekstijlen aanpassen {#customize-sweepstakes-styles}

Wanneer u [ creeert een transporten ](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md), kunt u aanpassen hoe het op uw het landen pagina kijkt.

>[!IMPORTANT]
>
>Op 31 juli 2024 begonnen we met het afschaffen van deze functie. U kunt geen nieuwe elementen maken. Bestaande activa blijven werken tot 31 januari 2025. [ leer meer ](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977) {target="_blank"}

>[!AVAILABILITY]
>
>Niet alle gebruikers van het Marketo Engage hebben deze functionaliteit aangeschaft. Neem contact op met het accountteam van de Adobe (uw accountmanager) voor meer informatie.

1. Ga naar **de Marketing Activiteiten**.

![](assets/login-marketing-activities-1.png)

1. Selecteer de transporten, en klik **uitgeven Ontwerp**.

   ![](assets/image2014-9-25-17-3a51-3a45.png)

1. In de redacteur van de Vegen, ga **Montages van de Toepassing** > **Verschijning**.

   ![](assets/image2014-9-25-17-3a51-3a59.png)

1. Bewerk de tekst van de aanmeldknop en de voortgangskoppeling.

   ![](assets/image2014-9-25-17-3a52-3a22.png)

1. Voer voor elk element dat u wilt aanpassen uw aangepaste CSS-eigenschappen in.

   ![](assets/image2014-9-25-17-3a52-3a37.png)

   Voorbeeld CSS voor **gaat Knoop** binnen:
   `<pre>border: 5px solid #7B68EE; background-color: purple; padding: 10px; font: 16px; color: #FFFFFF; text-align: center;</pre>`

   Het Beeld van het voorbeeld voor **gaat Knoop** binnen:
   `<pre>background:url(https://app.marketo.com/images/public-site/button_sign-up-now.png) no-repeat center center; width:275px; height:95px; margin:auto; display:block;</pre>` `<pre>`

   >[!NOTE]
   >
   >Als u een beeld met tekst op het gebruikt, herinner me om de tekst uit **binnen te verwijderen Knoop** gebied onder Tekst hierboven.

1. Terwijl u elke wijziging aanbrengt, wordt het resultaat weergegeven in de voorvertoning Weergave en Bewerken.

   ![](assets/image2014-9-25-17-3a55-3a3.png)

   >[!NOTE]
   >
   >Test de knop in verschillende browsers, waaronder oudere versies.

   >[!MORELIKETHIS]
   >
   >De volgende stap is [ teken-up en vervulling e-mails aan uw transporten ](/help/marketo/product-docs/demand-generation/social/social-functions/use-emails-in-social-promotions.md) toe te voegen.
