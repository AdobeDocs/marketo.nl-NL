---
description: Een publiek synchroniseren vanuit Adobe Experience Cloud - Marketo Docs - Productdocumentatie
title: Een publiek synchroniseren vanuit Adobe Experience Cloud
exl-id: 2288ee01-2c2e-4f33-b5c9-da3a431c1816
source-git-commit: c396c205d3cececc752f9b563c0d2ab41ff92b6a
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# Een publiek synchroniseren vanuit Adobe Experience Cloud {#sync-an-audience-from-adobe-experience-cloud}

>[!NOTE]
>
>Een HIPAA-klaar plaatsing van een instantie van Marketo kan deze integratie niet gebruiken.

>[!PREREQUISITES]
>
>[Organisatietoewijzing Adobe instellen](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/set-up-adobe-organization-mapping.md)

## Een publiek synchroniseren {#how-to-sync-an-audience}

1. Klik in Mijn Marketo op de knop **Database** tegel.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-1.png)

1. Klik op de knop **Nieuw** vervolgkeuzelijst en selecteer **Synchroniseren vanaf publiek Experience Cloud**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-2.png)

1. Klik op de knop **Poortbibliotheekmap** en selecteert u de gewenste oorspronkelijke map.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-3.png)

1. Selecteer een **Auditienaam**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-4.png)

1. Voor de bestemming, kunt u een bestaande lijst selecteren, of de naam van nieuwe typen. In dit voorbeeld maken we een nieuwe. Klikken **Synchroniseren** wanneer gereed.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-5.png)

1. Klikken **OK**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-6.png)

## Veelgestelde vragen {#faq}

**Hoe werkt de cookiesync?**

Wanneer de cookiesynchronisatie is ingeschakeld voor uw Marketo-abonnement, probeert Marketo&#39;s munchkin.js Adobe ECID&#39;s vast te leggen en op te slaan voor de Adobe IMS Org die u tijdens de integratie-instellingen hebt opgegeven en deze ECID&#39;s overeen te laten komen met de overeenkomstige Marketo cookie-id. Hierdoor kunnen de anonieme gebruikersprofielen van Marketo worden verrijkt met Adobe-ECID&#39;s.

Een volgende stap is vereist om het anonieme gebruikersprofiel aan een Profiel van de Lood te associëren, dat gebruikend een gewone tekst e-mail wordt geïdentificeerd. Precies hoe dit werkt [wordt hier beschreven](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md).

**Waarom is de lijstgrootte in Marketo anders dan die in Adobe?**

Een persoon synchroniseert ook niet als we een ECID-cookie-id niet aan een bekende persoon in Marketo kunnen koppelen.

**Is dit een eenmalige synchronisatie?**

U hoeft de synchronisatie slechts eenmaal te starten. Daarna worden records automatisch gesynchroniseerd. De eerste synchronisatie kan tot 24 uur duren; Als u doorgaat, worden nieuwe records over 2 tot 3 uur gesynchroniseerd.
