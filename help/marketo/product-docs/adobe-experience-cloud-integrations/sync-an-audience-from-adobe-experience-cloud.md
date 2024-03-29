---
description: Een publiek synchroniseren vanuit Adobe Experience Cloud - Marketo Docs - Productdocumentatie
title: Een publiek synchroniseren vanuit Adobe Experience Cloud
exl-id: 2288ee01-2c2e-4f33-b5c9-da3a431c1816
feature: Integrations
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '258'
ht-degree: 0%

---

# Een publiek synchroniseren vanuit Adobe Experience Cloud {#sync-an-audience-from-adobe-experience-cloud}

>[!NOTE]
>
>Een HIPAA-klaar plaatsing van een instantie van Marketo kan deze integratie niet gebruiken.

>[!PREREQUISITES]
>
>[Organisatietoewijzing Adobe instellen](/help/marketo/product-docs/adobe-experience-cloud-integrations/set-up-adobe-organization-mapping.md){target="_blank"}

## Een publiek synchroniseren {#how-to-sync-an-audience}

1. Klik in Mijn Marketo op de knop **[!UICONTROL Database]** tegel.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-1.png)

1. Klik op de knop **[!UICONTROL New]** vervolgkeuzelijst en selecteer **[!UICONTROL Sync from Experience Cloud Audience]**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-2.png)

1. Klik op de knop **[!UICONTROL Audience Library Folder]** en selecteert u de gewenste oorspronkelijke map.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-3.png)

1. Selecteer een **[!UICONTROL Audience Name]**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-4.png)

1. Voor de bestemming, kunt u een bestaande lijst selecteren, of de naam van nieuwe typen. In dit voorbeeld maken we een nieuwe. Klikken **[!UICONTROL Sync]** wanneer gereed.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-5.png)

1. Klik op **[!UICONTROL OK]**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-6.png)

## Veelgestelde vragen {#faq}

**Hoe werkt de cookiesync?**

Wanneer de cookiesync voor uw Abonnement van Marketo wordt toegelaten, zal Marketo munchkin.js proberen om Adobe ECIDs voor de orde van de Org van de IMS van Adobe te vangen en op te slaan u tijdens de integratieopstelling specificeerde en deze ECIDs aan het overeenkomstige koekjesherkenningsteken van Marketo aan te passen. Hierdoor kunnen anonieme gebruikersprofielen van Marketo worden verrijkt met Adobe-ECID&#39;s.

Een volgende stap is vereist om het anonieme gebruikersprofiel aan een Profiel van de Lood te associëren, dat gebruikend een gewone tekst e-mail wordt geïdentificeerd. Precies hoe dit werkt [wordt hier beschreven](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md){target="_blank"}.

**Waarom is de lijstgrootte in Marketo anders dan die in Adobe?**

Een persoon synchroniseert ook niet als we een ECID-cookie-id niet aan een bekende persoon in Marketo kunnen koppelen.

**Is dit een eenmalige synchronisatie?**

U hoeft de synchronisatie slechts eenmaal te starten. Daarna worden records automatisch gesynchroniseerd. De eerste synchronisatie kan tot 24 uur duren; Als u doorgaat, worden nieuwe records over 2 tot 3 uur gesynchroniseerd.
