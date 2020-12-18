---
unique-page-id: 7512454
description: Mobiele pushmeldingen configureren - Marketo Docs - Productdocumentatie
title: Melding van mobiele pushberichten configureren
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '470'
ht-degree: 0%

---


# Mobiele pushmelding configureren {#configure-mobile-push-notification}

1. Ga naar het gebied Marketingactiviteiten.

![](assets/2fbf1ab6-2247-40c8-980d-be56b9d94890.png)

1. Selecteer uw drukker en klik **Concept** bewerken.

   ![](assets/image2016-8-23-16-3a49-3a48.png)

1. Ga naar **Setup**.

   ![](assets/image2016-8-23-16-3a51-3a56.png)

1. Selecteer de gewenste app. Android- en Apple-platforms zijn standaard ingeschakeld.

   ![](assets/image2016-8-23-16-3a53-3a33.png)

   Als uw pushbericht slechts op één platform van toepassing is (bijvoorbeeld voor iPhones), kunt u het andere platform uitsluiten door de kiezer naar Uitgeschakeld te schuiven.

   ![](assets/image2016-8-23-16-3a41-3a48.png)

   Klik op Volgende.

   ![](assets/image2016-8-23-16-3a43-3a28.png)

1. Voer een berichttekst in of selecteer het tokenpictogram om tokens toe te voegen. Selecteer vervolgens een **Tik op handeling**.

   ![](assets/image2015-9-14-16-3a7-3a43.png)

   >[!NOTE]
   >
   >Als een platform wordt toegelaten, verschijnt het op de linkerkant van de vertoning van het telefoonscherm. Het wordt in kleur weergegeven wanneer het is geselecteerd.

   >[!NOTE]
   >
   >**Definitie**
   >
   >
   >Er zijn drie typen** Tikacties:**
   >
   >
   >**Start app**  -  **Deze** app opent de startpagina van uw app wanneer op het bericht wordt getikt. **De** klant gebruikt een diepe koppeling om andere delen van uw app of een andere app te openen waarnaar u de koppeling hebt (zie  [Diep koppeling ](#Deeplink) URIsonderaan voor meer informatie).
   >
   >
   >**Openingspagina**  - hiermee gaat u naar een opgegeven bestemmingspagina van Marketo.
   >
   >
   >**Externe URL** : hiermee gaat u naar een landingspagina die niet van markeertekens is.

   Als u een diepe koppeling wilt invoegen voor een aangepaste tikactie, klikt u op Aangepast en voert u de [diepe koppeling URI](#Deeplink) in het veld in.

   ![](assets/image2016-7-28-16-3a19-3a13.png)

   Als u tokens wilt invoegen, selecteert u een token, voert u een standaardwaarde in en klikt u op Invoegen.

   >[!NOTE]
   >
   >De penningen verschijnen waar u de curseur in het tekstvakje plaatst. U kunt meer dan één token gebruiken.

   ![](assets/image2015-8-10-14-3a48-3a52.png)

   >[!NOTE]
   >
   >Berichten en Tap-handelingen zien er op beide platforms hetzelfde uit.

   Alleen voor iOS: schakel het selectievakje in om de app te vertellen dat een geluid moet worden afgespeeld wanneer het bericht arriveert. Android speelt het geluid automatisch af.

   ![](assets/ios-tap-and-notification-hand.png)

   Geef een voorvertoning van het andere platform weer en klik op Voltooien.

   ![](assets/image2015-9-14-16-3a12-3a34.png)

1. Klik **GOEDKEUREN EN SLUITEN**.

   ![](assets/323dda12-0543-4558-8562-563eed5fa0e0.png)

Gefeliciteerd! De pushmelding kan nu worden verzonden.

## Diepe koppeling-URI&#39;s {#deep-link-uris}

Wanneer abonnees op een knop in een pushbericht klikken, kunnen ze deze naar de startpagina van uw app of rechtstreeks naar een specifieke pagina in de app sturen. Een diepe koppeling is een unieke verwijzing naar een specifieke pagina in uw app en ziet er veel uit als een websitekoppeling.

Een diepe verbinding URI bestaat uit drie delen: schemanaam, weg, en herkenningsteken. In het onderstaande voorbeeld is &quot;myappname&quot; het schema. &quot;products&quot; is het pad en &quot;purple-shirt&quot; is de id. Wanneer de klant tikt, worden deze specifiek naar het paarse hemditem op de productpagina&#39;s van uw app geleid.

![](assets/image2016-7-29-12-3a49-3a1.png)

De structuur van de diepe koppeling in uw app kan echter afwijken van het bovenstaande voorbeeld. Uw ontwikkelaar heeft vele opties in het bepalen van diepe verbinding URI&#39;s, zodat vraag uw ontwikkelaar om u URIs (verbindingen) voor de pagina&#39;s te verzenden u geinteresseerd bent in het gebruiken. Zo zorgt u ervoor dat de URI&#39;s die u invoert in de pushberichten naar de juiste plaatsen verwijzen. Uw ontwikkelaar kan [hier meer informatie ](http://developers.marketo.com/mobile/enabling-deep-links-in-your-app/) vinden.

>[!MORELIKETHIS]
>
>* [Een mobiel pushbericht verzenden](send-a-mobile-push-notification.md)

>



