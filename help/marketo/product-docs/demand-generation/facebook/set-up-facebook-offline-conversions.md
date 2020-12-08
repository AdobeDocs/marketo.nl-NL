---
unique-page-id: 11383953
description: Offlineconversies van Facebook instellen - Marketo Docs - Productdocumentatie
title: Offlineconversies van Facebook instellen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---


# Offlineconversies van Facebook instellen {#set-up-facebook-offline-conversions}

Door offline conversiegegevens terug te sturen naar Facebook voor mensen die zijn gemaakt via Advertenties voor advertenties, kan uw advertentieteam hun advertentie beter dan ooit optimaliseren. Hier is hoe je het instelt.

>[!NOTE]
>
>**Vereisten**
>
>* U moet Facebook Lead Ads [instellen](set-up-facebook-lead-ads.md).
>* U moet een goedgekeurd model in de Modellen van de [Cyclus van de Opbrengst](http://docs.marketo.com/display/docs/revenue+cycle+models)hebben.

>



## Beheerdersconfiguratie {#admin-configuration}

1. Ga naar Marketo **Admin**.

   ![](assets/image2016-11-29-13-3a8-3a45.png)

1. Ga naar **LaunchPoint** en dubbelklik op de Facebook Lead Ads-service die u eerder hebt gemaakt.

   >[!NOTE]
   >
   >Als je dat nog niet hebt gedaan, ga dan door en [stel Facebook Lead Ads](set-up-facebook-lead-ads.md)in en kom dan terug hier.

   ![](assets/image2016-11-29-13-3a10-3a43.png)

1. Bewerk desgewenst de **weergavenaam** om Offlineconversies op te nemen. Klik op **Volgende**.

   ![](assets/image2016-11-29-13-3a12-3a19.png)

1. Schakel Offlineconversies **** inschakelen in en klik op **Volgende**.

   ![](assets/image2016-11-29-13-3a13-3a32.png)

1. Klik op **Volgende**.

   ![](assets/image2016-11-29-13-3a14-3a17.png)

1. Klik op **Opslaan**.

   ![](assets/image2016-11-29-13-3a14-3a52.png)

   Zoet! U bent bijna klaar met het inschakelen van Facebook Offline Conversies. Laten we verder gaan naar de Revenue Cycle Modeler om de fases in kaart te brengen.

   ![](assets/image2016-11-29-13-3a16-3a55.png)

## Configuratie van inkomstencyclusmodellen {#revenue-cycle-modeler-configuration}

1. Ga naar **Analytics**.

   ![](assets/image2016-11-29-13-3a29-3a23.png)

1. Selecteer uw model en klik op Concept **** bewerken.

   ![](assets/image2016-11-29-13-3a31-3a6.png)

   >[!NOTE]
   >
   >Momenteel zijn er 10 Facebook-gebeurtenissen waaraan u de Fase-cyclusfasen kunt toewijzen:
   >
   >    
   >    
   >    * Toevoegen van betalingsgegevens
   >    * Toevoegen aan winkelwagentje
   >    * Toevoegen aan lijst met wensen
   >    * Registraties voltooid
   >    * Afhandelingen gestart
   >    * Persoon
   >    * Overige
   >    * Aanschaffen
   >    * Zoekopdrachten
   >    * Weergaven van inhoud


1. Selecteer het werkgebied dat u wilt toewijzen en selecteer vervolgens in het vervolgkeuzemenu **Facebook-conversie** de Facebook-gebeurtenis waaraan u de gebeurtenis wilt toewijzen. Herhaal deze stap om alle stadia in uw RCM aan off-line omzettingsstadia op Facebook in kaart te brengen.

   ![](assets/1-1.png)

1. Als u klaar bent met toewijzen, sluit u het model.

   ![](assets/2.png)

1. Uw model goedkeuren en u bent klaar!

   ![](assets/image2016-11-29-15-3a6-3a30.png)

   Wanneer leads de door u toegewezen stappen bereiken, worden de conversies naar Facebook verzonden voor rapportage.

   >[!CAUTION]
   >
   >Controleer uw Facebook-account en controleer of alle [advertenties zijn gekoppeld](https://www.facebook.com/business/url/?href=%2Fbusiness%2Fhelp%2Fwww%2F1776828022605281&amp;cmsid&amp;creative=link&amp;creative_detail=advertiser-help-center&amp;create_type&amp;destination_cms_id&amp;orig_http_referrer) aan de set Marketo Offline conversies-gebeurtenissen. Als dat niet het geval is, werkt de toewijzing mogelijk niet.

   >[!NOTE]
   >
   >Offline conversiegegevens worden verschillende keren per dag van Marketo naar Facebook verzonden.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Offlineconversies van Facebook](understanding-facebook-offline-conversions.md)

>



