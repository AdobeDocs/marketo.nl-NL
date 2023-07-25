---
unique-page-id: 4719400
description: Een nieuwe webcampagne voor zones maken - Marketo Docs - Productdocumentatie
title: Nieuwe webcampagne maken in zone
exl-id: 5cbe80a2-5e20-4e35-a722-b4cb479b4df7
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '693'
ht-degree: 0%

---

# Nieuwe webcampagne maken in zone {#create-a-new-in-zone-web-campaign}

Een webcampagne is een aangepaste reactie die is gekoppeld aan een specifiek segment en kan een [dialoogvenster](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md) op uw website, een vervanging in zone, een [widget, functie](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md) of een e-mailwaarschuwing. Met een In Zone-webcampagne vervangt u een element van uw website op basis van de Zone-id door inhoud of grafische banners.

## Een webcampagne in zone maken {#create-an-in-zone-web-campaign}

1. Ga naar **Webcampagnes**.

   ![](assets/image2016-8-18-15-3a54-3a21.png)

1. Selecteren **Nieuwe webcampagne maken.**

   ![](assets/create-new-web-campaign-hand.png)

1. Selecteer **In zone** type campagne. Een **Zone-id.** De campagne instellen op **Vast** en voeg uw creatief in de redacteur toe. Voeg de URL van de pagina toe die u wilt voorvertonen en klik op **Voorvertoning** om te zien hoe de campagne op uw site zal reageren.

   ![](assets/new-3-1.png)

   >[!NOTE]
   >
   >**Wat is een zone-id?**
   >
   >Een zone-id is de locatie van uw &quot;In Zone&quot;-webcampagne op de site. Als u een &#39;Zone-id&#39; wilt zoeken, gaat u gewoon naar uw website en selecteert u het gebied dat u wilt vervangen door een webcampagne. Klik vervolgens met de rechtermuisknop. In Chrome is de optie &quot;Inspect Element&quot;, in andere browsers kan deze variëren.
   >
   >Vervolgens zoekt u naar de id die is gekoppeld aan deze sectie van de website. Deze id wordt gemarkeerd omdat u dat element inspecteert. Als u bijvoorbeeld eenmaal met de rechtermuisknop in Chrome klikt, staat de gemarkeerde tekst `<div id="featured-slider">` Vervolgens typt u de sectie &#39;zone-id&#39;. Doorgaans wordt &quot;div-id&quot; gebruikt, maar elke id kan ook worden gebruikt, zoals h1-id, p-id enzovoort.

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">Naam</th> 
   <th colspan="1" rowspan="1">Beschrijving</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1"><strong> Zone-id </strong></td> 
   <td colspan="1" rowspan="1"><p>Voer de naam in van de id in de HTML-code van uw website-element die de campagne vervangt.</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong> Vast </strong></p></td> 
   <td colspan="1" rowspan="1">Het selectievakje Vaste is standaard ingeschakeld voor de campagne In zone en houdt de campagne In zone in de positie van de zone-id tijdens de sessie van de bezoeker op de website. Het wordt aanbevolen om altijd een In-zone in te stellen op Vaste waarde.</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong> Infaden</strong> </p></td> 
   <td colspan="1" rowspan="1">Als u het selectievakje Effect gebruiken en Infaden selecteert, krijgt het gebied met zone-id op de website een faduw effect. Als In Zone een grafische banner is, wordt de pagina eerst geladen en wordt de campagne vervolgens geactiveerd met een fazig effect.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong>Schuivend</strong></td> 
   <td colspan="1">Als u het selectievakje Effect gebruiken en de optie Schuiven selecteert, wordt een schuifeffect toegepast op het gebied Id van zone op de website. Als In Zone een grafische banner is, wordt de pagina eerst geladen en wordt de campagne vervolgens geactiveerd met een verschuivend effect van links naar rechts.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> RTF-editor  </strong></td> 
   <td colspan="1">Met de RTF-editor kunt u tekst opmaken, koppelen en afbeeldingen invoegen. <a href="/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md">Meer hier lezen</a> .</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> Voorvertonen op site   </strong></td> 
   <td colspan="1">Voorvertoning van campagnes weergeven voordat deze worden gestart. <br> 
    <ul> 
     <li> URL - Voer een voorbeeld-URL in waar de campagne wordt uitgevoerd om een voorbeeld te zien van hoe de campagne er live uitziet.</li> 
     <li>Apparaat - Voorproef hoe uw campagne door apparaat zal verschijnen: Desktop, mobiel portret, mobiel landschap, tablet-Staand, staand liggend.</li> 
     <li> Voorbeeld - klikken <strong>Voorvertoning</strong> om een nieuw venster van voorbeeldURL te openen om te zien hoe de campagne reageert.</li> 
     <li> Delen - Gebruik de knop Delen om een e-mail te sturen naar een collega met een koppeling om de proxycampagne te bekijken.</li> 
    </ul></td> 
  </tr> 
 </tbody> 
</table>

>[!TIP]
>
>Versnel en vereenvoudig het maken van uw campagne met onze [ingebouwde sjablonen](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) of door [opslaan van uw bestaande campagne](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) als een sjabloon voor hergebruik.

>[!NOTE]
>
>**Wilt u A/B uw webcampagnes testen?** Een of meer webcampagnes kunnen [A/B getest op optimale resultaten](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/ab-test-your-web-campaign.md). Met de functie Automatisch afstemmen herkent het platform automatisch de beter presterende campagnes, gaat het verder met de hoogste conversiecampagnes en pauzeert het de andere campagnes.

## Een webcampagne bewerken {#edit-a-web-campaign}

Van de **Webcampagnes** pagina, klikt u op **Bewerken** over de campagne.

![](assets/in-zone-web-campaign-edit.png)

>[!NOTE]
>
>Om het gemakkelijker te maken om de campagne te vinden wilt u, gebruik [filterfunctie](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/filter-web-campaigns.md).

## Een webcampagne voorvertonen {#preview-a-web-campaign}

1. Van de pagina van de Campagnes van het Web, klik **Voorvertoning** op de webcampagne die u wilt bekijken.

   ![](assets/in-zone-web-campaign-preview.png)

## Een webcampagne klonen {#clone-a-web-campaign}

Zie [Een webcampagne klonen](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/clone-a-web-campaign.md).

## Een webcampagne verwijderen {#delete-a-web-campaign}

1. Van de pagina van de Campagnes van het Web, klik **Verwijderen** in de campagne die u wilt verwijderen.

   ![](assets/in-zone-web-campaign-delete.png)

1. Er verschijnt een bevestigingsbericht om te bevestigen of u de campagne wilt verwijderen.

>[!MORELIKETHIS]
>
>* [Nieuwe widgetwebcampagne maken](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md)
>* [Nieuwe webcampagne voor dialoog maken](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)
