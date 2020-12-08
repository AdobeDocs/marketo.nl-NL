---
unique-page-id: 2359807
description: Overzichtsstijlen aanpassen - Marketo Docs - Productdocumentatie
title: Overtrekstijlen aanpassen
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---


# Overtrekstijlen aanpassen {#customize-sweepstakes-styles}

Wanneer u een [overvul](create-sweepstakes.md)maakt, kunt u aanpassen hoe het er op de landingspagina uitziet.

>[!NOTE]
>
>**Beschikbaarheid**
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

1. Ga naar Marketing Activiteiten.

![](assets/login-marketing-activities-1.png)

1. Selecteer de overgangen en klik op **Concept** bewerken ****.

   ![](assets/image2014-9-25-17-3a51-3a45.png)

1. Ga in de redacteur van Sweepstakes, naar **App** **Montages** **>** **Vormgeving**.

   ![](assets/image2014-9-25-17-3a51-3a59.png)

1. Bewerk de tekst van de aanmeldknop en de voortgangskoppeling.
1. ![](assets/image2014-9-25-17-3a52-3a22.png)

1. Voer voor elk element dat u wilt aanpassen uw aangepaste CSS-eigenschappen in.

   ![](assets/image2014-9-25-17-3a52-3a37.png)

   Voorbeeld-CSS voor knop **Enter**:
   `<pre>border: 5px solid #7B68EE; background-color: purple; padding: 10px; font: 16px; color: #FFFFFF; text-align: center;</pre>` Voorbeeld van afbeelding voor knop **Enter**:
   `<pre>background:url(http://app.marketo.com/images/public-site/button_sign-up-now.png) no-repeat center center; width:275px; height:95px; margin:auto; display:block;</pre>` `<pre>`

   >[!NOTE]
   >
   >Als u een afbeelding met tekst gebruikt, vergeet dan niet de tekst uit het veld **Enter** **Button **onder Tekst erboven te verwijderen.

1. Terwijl u elke wijziging aanbrengt, wordt het resultaat weergegeven in de voorvertoning Weergave en Bewerken.

   ![](assets/image2014-9-25-17-3a55-3a3.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Test de knop in verschillende browsers, waaronder oudere versies.

   >[!NOTE]
   >
   >**Verwante artikelen**
   >
   >
   >De volgende stap bestaat uit het toevoegen van e-mails met [aanmelding en vervulling aan uw transporten](../../../../product-docs/demand-generation/social/social-functions/use-emails-in-social-promotions.md).

