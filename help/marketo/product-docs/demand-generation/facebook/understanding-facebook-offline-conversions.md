---
unique-page-id: 11383945
description: Facebook Offline conversies begrijpen - Marketo Docs - Productdocumentatie
title: Facebook Offline conversies begrijpen
exl-id: e0995ebc-47fb-4f10-b767-4fe9f572b2d2
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%

---

# Facebook Offline conversies begrijpen {#understanding-facebook-offline-conversions}

Met facebook Lead Ads-campagnes worden leads gegenereerd en naar Marketo verzonden voor gebruik in marketingcampagnes. Zonder zichtbaarheid in offline conversies kan de Facebook-adverteerder echter niet weten welke advertenties het meest effectief zijn. Hier is een voorbeeld.

>[!NOTE]
>
>**Voorbeeld**
>
>Facebook Lead Ads voert drie advertenties uit.
>
>* Advertentie 1 genereert 20 leads
>* Advertentie 2 genereert 30 leads
>* Advertentie 3 genereert 50 leads
>
>Alleen al op basis van deze cijfers lijkt Advertentie 3 het meest effectief.
>
>Als je echter kijkt naar gegevens aan de Marketo kant, dan ontstaat een ander verhaal.
>
>* Advertentie 1 genereert 10 verkopen
>* Advertentie 3 produceert 2 verkopen
>
>Dat betekent dat Advertentie 1, ondanks het genereren van minder leads, een succespercentage van 50 procent had, terwijl Advertentie 3 nauwelijks effectief was.
>
>Zonder offline conversies zou de adverteerder waarschijnlijk meer geld investeren in advertentie 3. Met offlineconversiegegevens zal de adverteerder waarschijnlijker investeren in advertentie 1.

U kunt [facebook Offline conversies instellen](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md) om offline en prestaties naar Facebook te verzenden.

1. Zorg ervoor dat u [Facebook LaunchPoint-integratie](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-facebook-custom-audiences-as-a-launchpoint-service.md) is bijgewerkt.
1. Stappen in uw inkomstencyclusmodel toewijzen aan offlineconversiefasen in Facebook.
1. Wanneer een Facebook-lead wordt gegenereerd vanuit een Facebook-advertentie en een toegewezen werkgebied bereikt, stuurt Marketo de gegevens voor offline conversie een aantal keer per dag terug naar Facebook via een beveiligde, geautomatiseerde API. De gegevens worden weergegeven in het rapport Facebook Ads Manager.

>[!MORELIKETHIS]
>
>[Facebook-offlineconversies instellen](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md)
