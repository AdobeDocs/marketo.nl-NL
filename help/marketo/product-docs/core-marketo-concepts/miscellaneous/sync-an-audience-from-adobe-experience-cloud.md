---
description: Een publiek synchroniseren vanuit Adobe Experience Cloud - Marketo Docs - Productdocumentatie
title: Een publiek synchroniseren vanuit Adobe Experience Cloud
translation-type: tm+mt
source-git-commit: 05c2e89222f9316241a3929642998bddb02ff7a5
workflow-type: tm+mt
source-wordcount: '274'
ht-degree: 0%

---


# Een publiek synchroniseren vanuit Adobe Experience Cloud {#sync-an-audience-from-adobe-experience-cloud}

>[!NOTE]
>
>Een plaatsing HIPAA-klaar van een instantie van Marketo kan deze integratie niet gebruiken.

>[!PREREQUISITES]
>
>[Adobe Experience Cloud-publiek delen instellen](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/set-up-adobe-experience-cloud-audience-sharing.md)

## Een publiek synchroniseren {#how-to-sync-an-audience}

1. Klik in Mijn markeerteken op de tegel **Database**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-1.png)

1. Klik op de vervolgkeuzelijst **Nieuw** en selecteer **Synchroniseren vanuit Experience Cloud Publiek**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-2.png)

1. Klik op de vervolgkeuzelijst **Audience Library Folder** en selecteer de gewenste oorspronkelijke map.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-3.png)

1. Selecteer een **Audience Name**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-4.png)

1. Voor de bestemming, kunt u een bestaande lijst selecteren, of de naam van nieuwe typen. In dit voorbeeld maken we een nieuwe. Klik **Sync** wanneer gereed.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-5.png)

1. Klik **OK**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-6.png)

## Veelgestelde vragen {#faq}

**Hoe werkt de cookiesync?**

Wanneer de cookiesync voor uw Abonnement van het Marketo wordt toegelaten, zal Marketo&#39;s munchkin.js proberen om Adobe ECIDs voor de Adobe IMS van de Org te vangen en op te slaan u tijdens de integratieopstelling specificeerde en deze ECIDs aan het overeenkomstige koekjesherkenningsteken van het Marketo aanpas. Hierdoor kunnen de anonieme gebruikersprofielen van Marketo worden verrijkt met Adobe ECID&#39;s.

Een volgende stap is vereist om het anonieme gebruikersprofiel aan een Profiel van de Lood te associëren, dat gebruikend een gewone tekst e-mail wordt geïdentificeerd. Precies hoe dit [werkt wordt hier beschreven](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md).

**Waarom verschilt de lijstgrootte in Marketo van die in Adobe?**

Een persoon synchroniseert ook niet als we een ECID cookie ID niet aan een bekende persoon in Marketo kunnen koppelen.

**Is dit een eenmalige synchronisatie?**

U hoeft de synchronisatie slechts eenmaal te starten. Daarna worden records automatisch gesynchroniseerd. De eerste synchronisatie kan tot 24 uur duren; Als u doorgaat, worden nieuwe records over 2 tot 3 uur gesynchroniseerd.
