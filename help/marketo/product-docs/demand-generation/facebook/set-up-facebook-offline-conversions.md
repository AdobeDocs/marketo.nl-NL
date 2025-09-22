---
unique-page-id: 11383953
description: Offlineconversies voor Facebook instellen - Marketo Docs - Productdocumentatie
title: Offlineconversies van Facebook instellen
exl-id: e1974943-8fc8-41f6-be7e-1b594de13db6
feature: Integrations
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '281'
ht-degree: 1%

---

# [!DNL Facebook] Offlineconversies instellen {#set-up-facebook-offline-conversions}

Door offline conversiegegevens terug te sturen naar [!DNL Facebook] voor mensen die zijn gemaakt via advertenties, kan uw advertentieteam hun advertentie beter dan ooit optimaliseren. Hier is hoe u het kunt instellen.

>[!PREREQUISITES]
>
>* U moet [ opstelling de Advertentie van de Lood van Facebook ](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md).
>* U moet een goedgekeurd model in [ Cyclus van de Opbrengst Modeler ](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/understanding-revenue-models.md) hebben.

## Beheerdersconfiguratie {#admin-configuration}

1. Ga naar Marketo **[!UICONTROL Admin]** .

   ![](assets/image2016-11-29-13-3a8-3a45.png)

1. Ga naar **[!UICONTROL LaunchPoint]** en dubbelklik op de Facebook Lead Ads-service die u eerder hebt gemaakt.

   >[!NOTE]
   >
   >Als u dat niet hebt gedaan, ga en [ Opstelling [!UICONTROL Facebook Lead Ads]](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md), dan kom hier terug.

   ![](assets/image2016-11-29-13-3a10-3a43.png)

1. Bewerk desgewenst de **[!UICONTROL Display Name]** om Offlineconversies op te nemen. Klik op **[!UICONTROL Next]**.

   ![](assets/image2016-11-29-13-3a12-3a19.png)

1. Controleer **[!UICONTROL Enable Offline Conversions]** en klik op **[!UICONTROL Next]** .

   ![](assets/image2016-11-29-13-3a13-3a32.png)

1. Klik op **[!UICONTROL Next]**.

   ![](assets/image2016-11-29-13-3a14-3a17.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-11-29-13-3a14-3a52.png)

   Zoet! U bent bijna klaar met het inschakelen van [!DNL Facebook] Offlineconversies. Laten we naar de Revenue Cycle Modeler gaan om de fases in kaart te brengen.

   ![](assets/image2016-11-29-13-3a16-3a55.png)

## Opbrengstcyclus Modeler-configuratie {#revenue-cycle-modeler-configuration}

1. Ga naar **[!UICONTROL Analytics]** .

   ![](assets/image2016-11-29-13-3a29-3a23.png)

1. Selecteer het model en klik op **[!UICONTROL Edit Draft]** .

   ![](assets/image2016-11-29-13-3a31-3a6.png)

   >[!NOTE]
   >
   >Er zijn momenteel 10 [!DNL Facebook] -gebeurtenissen die u kunt toewijzen aan:
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

1. Selecteer het werkgebied dat u wilt toewijzen en selecteer vervolgens in de vervolgkeuzelijst **[!UICONTROL Facebook Conversion]** de gebeurtenis [!DNL Facebook] waaraan u de gebeurtenis wilt toewijzen. Herhaal deze stap om alle stadia in uw RCM aan off-line omzettingsstadia op [!DNL Facebook] in kaart te brengen.

   ![](assets/1-1.png)

1. Als u klaar bent met toewijzen, sluit u het model.

   ![](assets/2.png)

1. Uw model goedkeuren en u bent klaar!

   ![](assets/image2016-11-29-15-3a6-3a30.png)

   Wanneer de regelafstand en de regelafstand de door u toegewezen stappen bereiken, worden de conversies naar [!DNL Facebook] verzonden voor rapportage.

   >[!CAUTION]
   >
   >Controleer uw [!DNL Facebook] rekening en zorg ervoor dat alle [ advertenties ](https://www.facebook.com/business/url/?href=%2Fbusiness%2Fhelp%2Fwww%2F1776828022605281&cmsid&creative=link&creative_detail=advertiser-help-center&create_type&destination_cms_id&orig_http_referrer) aan de Offline Reeks van de Gebeurtenis van Conversies van Marketo worden geassocieerd. Als dat niet het geval is, werkt de toewijzing mogelijk niet.

   >[!NOTE]
   >
   >Offline conversiegegevens worden verschillende keren per dag van Marketo naar [!DNL Facebook] verzonden.

>[!MORELIKETHIS]
>
>[ Begrijpend  [!DNL Facebook]  Offline Omzettingen ](/help/marketo/product-docs/demand-generation/facebook/understanding-facebook-offline-conversions.md)
