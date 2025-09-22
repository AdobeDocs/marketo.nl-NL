---
unique-page-id: 11383945
description: Facebook Offline conversies - Marketo Docs - Productdocumentatie
title: Offlineconversies van Facebook
exl-id: e0995ebc-47fb-4f10-b767-4fe9f572b2d2
feature: Integrations
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 0%

---

# [!DNL Facebook] Offlineconversies begrijpen {#understanding-facebook-offline-conversions}

Facebook-campagnes voor advertenties genereren leads en sturen deze naar Marketo voor gebruik in marketingcampagnes. Zonder zichtbaarheid in offline conversies kan de [!DNL Facebook] -adverteerder echter niet weten welke advertenties het meest effectief zijn. Hier is een voorbeeld.

>[!NOTE]
>
>**Voorbeeld**
>
>[!UICONTROL Facebook Lead Ads] voert drie advertenties uit.
>
>* Advertentie 1 genereert 20 leads
>* Advertentie 2 genereert 30 leads
>* Advertentie 3 genereert 50 leads
>
>Alleen al op basis van deze cijfers lijkt Advertentie 3 het meest effectief.
>
>Als je echter kijkt naar gegevens aan de Marketo kant, dan ontstaat er een ander verhaal.
>
>* Advertentie 1 genereert 10 verkopen
>* Advertentie 3 produceert 2 verkopen
>
>Dat betekent dat Advertentie 1, ondanks het genereren van minder leads, een succespercentage van 50 procent had, terwijl Advertentie 3 nauwelijks effectief was.
>
>Zonder offline conversies zou de adverteerder waarschijnlijk meer geld investeren in advertentie 3. Met offlineconversiegegevens zal de adverteerder waarschijnlijker investeren in advertentie 1.

U kunt [ opstelling Offline Conversies van Facebook ](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md) offline en prestaties naar [!DNL Facebook] verzenden.

1. Zorg ervoor dat de [[!DNL Facebook] [!UICONTROL LaunchPoint] integratie ](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-facebook-custom-audiences-as-a-launchpoint-service.md) up-to-date is.
1. Wijs fasen in uw model van de conjunctuurcyclus aan off-line omzettingsstadia op [!DNL Facebook] toe.
1. Wanneer een [!DNL Facebook] -lead wordt gegenereerd vanuit een [!DNL Facebook] lead-advertentie en een toegewezen werkgebied bereikt, stuurt Marketo offline conversiegegevens een aantal keren per dag terug naar [!DNL Facebook] via een beveiligde, geautomatiseerde API. De gegevens worden weergegeven in het rapport [!DNL Facebook] Advertentiebeheer.

>[!MORELIKETHIS]
>
>[ Offlineconversies van de opstelling  [!DNL Facebook]  ](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md)
