---
unique-page-id: 11383953
description: Facebook Offline conversies instellen - Marketo Docs - Productdocumentatie
title: Facebook-offlineconversies instellen
exl-id: e1974943-8fc8-41f6-be7e-1b594de13db6
feature: Integrations
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '331'
ht-degree: 0%

---

# Facebook-offlineconversies instellen {#set-up-facebook-offline-conversions}

Door offline conversiegegevens terug te sturen naar Facebook voor mensen die via advertenties zijn gemaakt, kan uw advertentieteam hun advertentie beter dan ooit optimaliseren. Hier is hoe je het instelt.

>[!PREREQUISITES]
>
>* U moet [facebook Lead Ads instellen](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md).
>* U moet een goedgekeurd model hebben in [Revenue Cycle Modeler](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/understanding-revenue-models.md).

## Beheerdersconfiguratie {#admin-configuration}

1. Ga naar Marketo **Beheer**.

   ![](assets/image2016-11-29-13-3a8-3a45.png)

1. Ga naar **LaunchPoint** en dubbelklik op de eerder gemaakte Facebook Lead Ads-service.

   >[!NOTE]
   >
   >Als je dat nog niet hebt gedaan, ga dan door en [Facebook Lead Ads instellen](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md), kom dan terug hier.

   ![](assets/image2016-11-29-13-3a10-3a43.png)

1. Indien gewenst, bewerkt u de **Weergavenaam** om Offlineconversies op te nemen. Klikken **Volgende**.

   ![](assets/image2016-11-29-13-3a12-3a19.png)

1. Controleren **Offlineconversies inschakelen** en klik op **Volgende**.

   ![](assets/image2016-11-29-13-3a13-3a32.png)

1. Klikken **Volgende**.

   ![](assets/image2016-11-29-13-3a14-3a17.png)

1. Klikken **Opslaan**.

   ![](assets/image2016-11-29-13-3a14-3a52.png)

   Zoet! U bent al halverwege klaar met het inschakelen van Facebook Offline conversies. Laten we verder gaan naar de Revenue Cycle Modeler om de fases in kaart te brengen.

   ![](assets/image2016-11-29-13-3a16-3a55.png)

## Configuratie van inkomstencyclusmodellen {#revenue-cycle-modeler-configuration}

1. Ga naar **Analyse**.

   ![](assets/image2016-11-29-13-3a29-3a23.png)

1. Selecteer uw model en klik op **Concept bewerken**.

   ![](assets/image2016-11-29-13-3a31-3a6.png)

   >[!NOTE]
   >
   >Er zijn momenteel 10 Facebook-gebeurtenissen waaraan u de omzetcyclusfasen kunt toewijzen:
   >
   >* Toevoegen van betalingsgegevens
   >* Toevoegen aan winkelwagentje
   >* Toevoegen aan lijst met wensen
   >* Registraties voltooid
   >* Afhandelingen gestart
   >* Persoon
   >* Anders
   >* Aanschaffen
   >* Zoekopdrachten
   >* Weergaven van inhoud

1. Selecteer het werkgebied dat u wilt toewijzen, en kies vervolgens in het menu **Facebook-conversie** selecteert u de Facebook-gebeurtenis waaraan u deze wilt toewijzen. Herhaal deze stap om alle stadia in uw RCM aan off-line omzettingsstadia op Facebook in kaart te brengen.

   ![](assets/1-1.png)

1. Als u klaar bent met toewijzen, sluit u het model.

   ![](assets/2.png)

1. Uw model goedkeuren en u bent klaar!

   ![](assets/image2016-11-29-15-3a6-3a30.png)

   Wanneer leads de door u toegewezen stappen bereiken, worden de conversies naar Facebook verzonden voor rapportage.

   >[!CAUTION]
   >
   >Controleer uw Facebook-account en zorg ervoor dat alles [advertenties zijn gekoppeld](https://www.facebook.com/business/url/?href=%2Fbusiness%2Fhelp%2Fwww%2F1776828022605281&amp;cmsid&amp;creative=link&amp;creative_detail=advertiser-help-center&amp;create_type&amp;destination_cms_id&amp;orig_http_referrer) naar de Marketo Offline conversiegebeurtenissenset. Als dat niet het geval is, werkt de toewijzing mogelijk niet.

   >[!NOTE]
   >
   >Offline conversiegegevens worden verschillende keren per dag van Marketo naar Facebook verzonden.

>[!MORELIKETHIS]
>
>[Facebook Offline conversies begrijpen](/help/marketo/product-docs/demand-generation/facebook/understanding-facebook-offline-conversions.md)
