---
unique-page-id: 7512454
description: Mobiele pushmeldingen configureren - Marketo Docs - Productdocumentatie
title: Melding van mobiele pushberichten configureren
exl-id: 10368b13-40c9-435a-847c-68aaa5a892ea
feature: Mobile Marketing
source-git-commit: 736e21d45d8a62e50f449e0ee6d0fc4df5963dfb
workflow-type: tm+mt
source-wordcount: '466'
ht-degree: 0%

---

# Melding van mobiele pushberichten configureren {#configure-mobile-push-notification}

1. Ga naar het **Op de markt brengende Activiteiten** gebied.

![](assets/2fbf1ab6-2247-40c8-980d-be56b9d94890.png)

1. Selecteer uw duw activa en klik **uitgeven Ontwerp**.

   ![](assets/image2016-8-23-16-3a49-3a48.png)

1. Ga naar **Opstelling**.

   ![](assets/image2016-8-23-16-3a51-3a56.png)

1. Selecteer de gewenste app. Android- en Apple-platforms zijn standaard ingeschakeld.

   ![](assets/image2016-8-23-16-3a53-3a33.png)

1. Als uw pushbericht slechts op één platform van toepassing is (bijvoorbeeld voor iPhones), kunt u het andere platform uitsluiten door de kiezer naar Uitgeschakeld te schuiven.

   ![](assets/image2016-8-23-16-3a41-3a48.png)

1. Klik **daarna**.

   ![](assets/image2016-8-23-16-3a43-3a28.png)

1. Voer een berichttekst in of selecteer het pictogram voor tokens. Dan, selecteer de Actie van het a **Tik**.

   ![](assets/image2015-9-14-16-3a7-3a43.png)

   >[!NOTE]
   >
   >Als een platform wordt toegelaten, verschijnt het op de linkerkant van de vertoning van het telefoonscherm. Het wordt in kleur weergegeven wanneer het is geselecteerd.

   >[!NOTE]
   >
   >Er zijn drie typen Tap-handelingen:
   >
   >**Toepassing van de Lancering** - **Deze app** opent de homepage van uw app wanneer het bericht wordt getikt. **Douane** gebruikt een diepe verbinding om andere gebieden van uw app of een andere app te openen waaraan u de verbinding hebt (zie [ Diep Verbinding URIs ](#deep-link-uris) hieronder voor details).
   >
   >**het Bestaan Pagina** - neemt u aan een gespecificeerde Marketo landende pagina.
   >
   >**Externe URL** - neemt u aan een niet-Marketo landende pagina.

1. Om een diepe verbinding voor een actie van de douankraan op te nemen, klik Douane en ga [ diepe verbinding URI ](#deep-link-uris) op het gebied in.

   ![](assets/image2016-7-28-16-3a19-3a13.png)

1. Als u tokens wilt invoegen, selecteert u een token, voert u een standaardwaarde in en klikt u op Invoegen.

   >[!NOTE]
   >
   >De penningen verschijnen waar u de curseur in het tekstvakje plaatst. U kunt meer dan één token gebruiken.

   ![](assets/image2015-8-10-14-3a48-3a52.png)

   >[!NOTE]
   >
   >Berichten en Tap-handelingen zien er op beide platforms hetzelfde uit.

1. Alleen voor iOS: schakel het selectievakje in om de app te vertellen dat een geluid moet worden afgespeeld wanneer het bericht arriveert. Android speelt het geluid automatisch af.

   ![](assets/ios-tap-and-notification-hand.png)

1. Voorproef het andere platform en klik **Afwerking**.

   ![](assets/image2015-9-14-16-3a12-3a34.png)

1. Klik **goedkeuren en sluiten**.

   ![](assets/323dda12-0543-4558-8562-563eed5fa0e0.png)

Gefeliciteerd! De pushmelding kan nu worden verzonden.

## Diepe koppeling-URI&#39;s {#deep-link-uris}

Wanneer abonnees op een knop in een pushbericht klikken, kunnen ze deze naar de homepage van uw app of rechtstreeks naar een specifieke pagina in de app sturen. Een diepe koppeling is een unieke verwijzing naar een specifieke pagina in uw app en ziet er veel uit als een websitekoppeling.

Een diepe verbinding URI bestaat uit drie delen: schemanaam, weg, en herkenningsteken. In het onderstaande voorbeeld is &quot;myappname&quot; het schema. &quot;products&quot; is het pad en &quot;purple-shirt&quot; is de id. Wanneer de klant tikt, worden deze specifiek naar het paarse shirt-item op de productpagina&#39;s van uw app geleid.

![](assets/image2016-7-29-12-3a49-3a1.png)

De structuur van de diepe koppeling in uw app kan echter afwijken van het bovenstaande voorbeeld. Uw ontwikkelaar heeft vele opties in het bepalen van diepe verbinding URI&#39;s, zodat vraag uw ontwikkelaar om u URIs (verbindingen) voor de pagina&#39;s te verzenden u geinteresseerd bent in het gebruiken. Zo zorgt u ervoor dat de URI&#39;s die u invoert in de pushberichten naar de juiste plaatsen verwijzen. Uw ontwikkelaar kan [ hier meer informatie ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/enabling-deep-links-in-your-app) vinden.

>[!MORELIKETHIS]
>
>[ verzend een Mobiel Push Bericht ](/help/marketo/product-docs/mobile-marketing/push-notifications/send-a-mobile-push-notification.md)
