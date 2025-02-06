---
title: Document voor Connect Experience Manager
description: Leer hoe u Adobe Experience Manager-Cloud Servicen met Adobe Marketo Engage kunt verbinden zodat u uw AEM kunt gebruiken.
source-git-commit: 92404e10771920862cd147c09e2ada37484e6118
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 0%

---

# Connect Adobe Experience Manager-Cloud Servicen {#connect-adobe-experience-manager-cloud-services}

Leer hoe u uw AEM Assets Cloud Servicen-account koppelt aan uw Adobe Marketo Engage-exemplaar zodat u de AEM Asset-opslagplaats in de Marketo Engage-e-mail Designer kunt gebruiken.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. In Marketo Engage, ga naar het **Admin** gebied en selecteer **Adobe Experience Manager** in de linkernavigatieboom.

   ![ Uitgezochte Adobe Experience Manager in de Admin sectie ](assets/connect-adobe-experience-manager-cloud-services-1.png){width="800"}

1. Klik **uitgeven** naast _Cloud Servicen van Adobe Experience Manager_.

   ![ klik uitgeven ](assets/connect-adobe-experience-manager-cloud-services-2.png){width="400"}

1. Selecteer een of meer opslagruimten.

   ![ selecteer een bewaarplaats ](assets/connect-adobe-experience-manager-cloud-services-3.png){width="800"}

   >[!NOTE]
   >
   >Alleen opslagruimten die zijn gekoppeld in dezelfde IMS-org als uw abonnement op een Marketo Engage, worden weergegeven.

1. U moet het certificaat van de a [ dienstcredentie ](https://experienceleague.adobe.com/nl/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials) toevoegen om de bewaarplaats te vormen. Klik op de knop **+ Certificaat toevoegen** .

   ![ voeg een certificaat toe ](assets/connect-adobe-experience-manager-cloud-services-4.png){width="800"}

1. Sleep het certificaat (alleen JSON-bestand) en zet het neer of selecteer het op uw computer. Klik **toevoegen** wanneer gedaan.

   ![ plaats van het certificaat op uw machine ](assets/connect-adobe-experience-manager-cloud-services-5.png){width="600"}

1. De geconfigureerde opslagplaats wordt hieronder samen met de status en de vervaldatum weergegeven. Klik op de knop voor weglatingsteken (**...** ) om het certificaat weer te geven. Anders ben je klaar.

   ![ het certificaat is toegevoegd ](assets/connect-adobe-experience-manager-cloud-services-5.png){width="600"}

Alle afbeeldingen uit de bibliotheek voor digitaal middelenbeheer in die opslagplaats zijn nu toegankelijk via de Marketo Engage-e-mail Designer.

>[!MORELIKETHIS]
>
>[ Werk met de activa van de Experience Manager ](/help/marketo/product-docs/email-marketing/email-designer/aem-assets.md)
