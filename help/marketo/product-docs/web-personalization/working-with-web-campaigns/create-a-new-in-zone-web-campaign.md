---
unique-page-id: 4719400
description: Een nieuwe webcampagne voor zones maken - Marketo Docs - Productdocumentatie
title: Nieuwe webcampagne maken in zone
exl-id: 5cbe80a2-5e20-4e35-a722-b4cb479b4df7
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '673'
ht-degree: 0%

---

# Nieuwe webcampagne maken in zone {#create-a-new-in-zone-web-campaign}

Een Webcampagne is een aangepaste reactie verbonden aan een specifiek segment en kan a [ dialoogdoos ](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md) op uw website, een in zonevervanging, a [ widgeteigenschap ](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md) of een e-mailalarm zijn. Met een In Zone-webcampagne vervangt u een element van uw website op basis van de Zone-id door inhoud of grafische banners.

## Een webcampagne in zone maken {#create-an-in-zone-web-campaign}

1. Ga naar **[!UICONTROL Web Campaigns]** .

   ![](assets/image2016-8-18-15-3a54-3a21.png)

1. Selecteren **[!UICONTROL Create New Web Campaign].**

   ![](assets/create-new-web-campaign-hand.png)

1. Selecteer het type campagne van **[!UICONTROL In Zone]** . U kunt een **[!UICONTROL Zone id]aanpassen en toevoegen.** Stel de campagne in op **[!UICONTROL Sticky]** en voeg uw creatieve inhoud toe in de editor. Voeg de URL van de pagina toe die u wilt voorvertonen en klik op **[!UICONTROL Preview]** om te zien hoe de campagne op uw site reageert.

   ![](assets/new-3-1.png)

   >[!NOTE]
   >
   >**wat een identiteitskaart van de Zone is?**
   >
   >Een identiteitskaart van de Gebied is waar u uw &quot;[!UICONTROL In Zone]&quot;Webcampagne zou willen worden gevestigd onsite. Als u &quot;[!UICONTROL Zone ID]&quot;wilt vinden, ga eenvoudig naar uw website selecteren het gebied u met een Webcampagne wilt vervangen en klik met de rechtermuisknop aan. In Chrome is de optie &quot;Element controleren&quot;. In andere browsers kan deze optie variëren.
   >
   >Vervolgens zoekt u naar de id die is gekoppeld aan deze sectie van de website. Deze id wordt gemarkeerd omdat u dat element inspecteert. Als u bijvoorbeeld met de rechtermuisknop in Chrome klikt en op de gemarkeerde tekst staat `<div id="featured-slider">` , typt u &#39;aanbevolen-schuifregelaar&#39; in de sectie &#39;zone-id&#39;. Doorgaans wordt &quot;div-id&quot; gebruikt, maar elke id kan ook worden gebruikt, zoals h1-id, p-id enzovoort.

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
   <td colspan="1" rowspan="1"><p>Voer de naam in van de id die u hebt gevonden in de HTML-code van uw website-element dat de campagne vervangt.</p></td>
  </tr>
  <tr>
   <td colspan="1" rowspan="1"><p><strong> Vast </strong></p></td>
   <td colspan="1" rowspan="1">Het selectievakje Vaste is standaard ingeschakeld voor de campagne In zone en houdt de campagne In zone in de positie van de zone-id tijdens de sessie van de bezoeker op de website. Het wordt aanbevolen om altijd een In-zone in te stellen op Vaste waarde.</td>
  </tr>
  <tr>
   <td colspan="1" rowspan="1"><p><strong> Infaden </strong> </p></td>
   <td colspan="1" rowspan="1">Als u het selectievakje Effect gebruiken en Infaden selecteert, krijgt het gebied met zone-id op de website een faduw effect. Als In Zone een grafische banner is, wordt de pagina eerst geladen en wordt de campagne vervolgens geactiveerd met een fazig effect.</td>
  </tr>
  <tr>
   <td colspan="1"><strong>Schuivend</strong></td>
   <td colspan="1">Als u het selectievakje Effect gebruiken en de optie Schuiven selecteert, wordt een schuifeffect toegepast op het gebied Id van zone op de website. Als In Zone een grafische banner is, wordt de pagina eerst geladen en wordt de campagne vervolgens geactiveerd met een verschuivend effect van links naar rechts.</td>
  </tr>
  <tr>
   <td colspan="1"><strong> RTF-editor  </strong></td>
   <td colspan="1">Met de RTF-editor kunt u tekst opmaken, koppelen en afbeeldingen invoegen. <a href="/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md"> lees meer hier </a>.</td>
  </tr>
  <tr>
   <td colspan="1"><strong> Voorvertonen op site   </strong></td>
   <td colspan="1">Een voorvertoning weergeven van campagnes voordat deze worden gestart. <br>
    <ul>
     <li> URL - Voer een voorbeeld-URL in waar de campagne wordt uitgevoerd om een voorbeeld te zien van hoe de campagne er live uitziet.</li>
     <li>Apparaat - Voorproef hoe uw campagne door apparaat zal verschijnen: Desktop, Mobiel Staand, Mobiel Liggend, het Staand van de Tablet, Staand Staand.</li>
     <li> Voorproef - klik <strong> Voorproef </strong> om een nieuw venster van voorbeeld URL te openen om te zien hoe de campagne reageert.</li>
     <li> Delen - Gebruik de knop Delen om een e-mail te sturen naar een collega met een koppeling om de proxycampagne te bekijken.</li>
    </ul></td>
  </tr>
 </tbody>
</table>

>[!TIP]
>
>Versnel en vereenvoudig uw proces van de campagneverwezenlijking door onze [ ingebouwde malplaatjes ](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) te gebruiken of door [ uw bestaande campagne ](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) als malplaatje voor hergebruik op te slaan.

>[!NOTE]
>
>**wil A/B uw Webcampagnes testen?** Één of meerdere Webcampagnes kunnen [ A/B worden getest voor optimale resultaten ](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/ab-test-your-web-campaign.md). Met de functie Automatisch afstemmen herkent het platform automatisch de beter presterende campagnes, gaat het verder met de hoogste conversiecampagnes en pauzeert het de andere campagnes.

## Een webcampagne bewerken {#edit-a-web-campaign}

Van de **Campagnes van het Web** pagina, klik **uitgeven** op de Campagne.

![](assets/in-zone-web-campaign-edit.png)

>[!NOTE]
>
>Om het gemakkelijker te maken om de campagne te vinden u wilt, gebruik de [ filtereigenschap ](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/filter-web-campaigns.md).

## Een webcampagne voorvertonen {#preview-a-web-campaign}

1. Klik op de pagina [!UICONTROL Web Campaigns] op **[!UICONTROL Preview]** in de webcampagne die u wilt weergeven.

   ![](assets/in-zone-web-campaign-preview.png)

## Een webcampagne klonen {#clone-a-web-campaign}

Zie [ Klonen een Campagne van het Web ](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/clone-a-web-campaign.md).

## Een webcampagne verwijderen {#delete-a-web-campaign}

1. Klik op de pagina Webcampagnes op **[!UICONTROL Delete]** de campagne die u wilt verwijderen.

   ![](assets/in-zone-web-campaign-delete.png)

1. Er verschijnt een bevestigingsbericht om te bevestigen of u de campagne wilt verwijderen.

>[!MORELIKETHIS]
>
>* [ creeer een Nieuwe Campagne van het Web Widget ](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md)
>* [ creeer een Nieuwe Campagne van het Web van de Dialoog ](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)
