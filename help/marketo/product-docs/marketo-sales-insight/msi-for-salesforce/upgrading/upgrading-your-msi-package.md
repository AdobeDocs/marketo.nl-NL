---
unique-page-id: 37357050
description: Een upgrade uitvoeren van uw MSI-pakket - Marketo Docs - Productdocumentatie
title: Een upgrade uitvoeren van uw MSI-pakket
exl-id: 45004990-8452-4824-a9b2-89cd8302fe43
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 0%

---

# Een upgrade uitvoeren van uw MSI-pakket {#upgrading-your-msi-package}

>[!IMPORTANT]
>
>Vanwege beveiligingsverbeteringen die zijn aangebracht door Salesforce, kan het verkooppakket Insight geen toestemming meer verlenen voor standaardobjecten. In de toekomst moet het Salesforce-profiel van Insight-gebruikers lees-toegang hebben tot de volgende standaardobjecten: lead, contact, account en opportunity. [ Leer hoe te om dat te vormen hier ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#grant-sales-insight-users-profile-access){target="_blank"}.

1. Navigeer aan [ deze pagina in appexchange ](https://appexchange.salesforce.com/listingDetail?listingId=a0N30000001SVZmEAO){target="_blank"}.

1. Meld u aan bij de instantie [!DNL Salesforce] (de instantie die is verbonden met uw Marketo-instantie, kan een sandbox of productie zijn) in de rechterbovenhoek van de pagina vanuit Stap 1. U moet beheerdersrechten hebben om een beheerd pakket in [!DNL Salesforce] te installeren/upgraden.

1. Klik **krijgen het** knoop. U wordt gevraagd te kiezen waar u wilt installeren. U zult de optie worden gegeven om te bevorderen aangezien u reeds een vorige versie van MSI hebt. Kies een optie op basis van de account waarin u zich hebt aangemeld tijdens Stap 1.

   >[!TIP]
   >
   >We raden u aan dit op uw sandbox-instantie te testen voordat u de productie-instantie upgradet.

1. U kunt het pakket upgraden met de optie &quot;Alleen installeren voor beheerders&quot; (en later MSI-toegang tot specifieke profielen verschaffen), &quot;Installeren voor alle gebruikers&quot; of &quot;Installeren voor specifieke profielen&quot;. In dit voorbeeld kiezen we Alleen beheerders. Wanneer u uw selectie hebt gemaakt, klik **Verbetering**.

   ![](assets/four.png)

>[!NOTE]
>
>Het wordt geadviseerd u het pakket voor slechts Admins bijwerkt en dan [ toegang tot specifieke gebruikers ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"} verleent die op het aantal gekochte plaatsen MSI wordt gebaseerd. U kunt ook een specifiek Salesforce-profiel maken voor MSI-gebruikers en het pakket installeren of upgraden voor alleen die gebruikers.
