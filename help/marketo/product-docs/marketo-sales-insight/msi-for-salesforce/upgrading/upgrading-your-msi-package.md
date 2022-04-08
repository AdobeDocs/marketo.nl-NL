---
unique-page-id: 37357050
description: Een upgrade uitvoeren van uw MSI-pakket - Marketo Docs - Productdocumentatie
title: Een upgrade uitvoeren van uw MSI-pakket
exl-id: 45004990-8452-4824-a9b2-89cd8302fe43
source-git-commit: 5c4bce6ab6801b861f70722b6782df34f96fed10
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%

---

# Een upgrade uitvoeren van uw MSI-pakket {#upgrading-your-msi-package}

1. Navigeren naar [deze pagina in de app](https://appexchange.salesforce.com/listingDetail?listingId=a0N30000001SVZmEAO){target=&quot;_blank&quot;}.

1. Meld u aan bij de Salesforce-instantie (de instantie die is verbonden met uw Marketo-instantie, kan een sandbox of productie zijn) in de rechterbovenhoek van de pagina vanuit Stap 1. U moet beheerdersrechten hebben om een beheerd pakket in Salesforce te installeren/upgraden.

1. Klik op de knop **Nu ophalen** knop. U wordt gevraagd te kiezen waar u wilt installeren. U zult de optie worden gegeven om te bevorderen aangezien u reeds een vorige versie van MSI hebt. Kies een optie op basis van de account waarin u zich hebt aangemeld tijdens Stap 1.

   >[!TIP]
   >
   >We raden u aan dit op uw sandbox-instantie te testen voordat u de productie-instantie upgradet.

1. U kunt het pakket upgraden door &quot;Alleen installeren voor beheerders&quot; te kiezen (en later MSI-toegang tot specifieke profielen te verlenen), &quot;Installeren voor alle gebruikers&quot; of &quot;Installeren voor specifieke profielen&quot; te kiezen. In dit voorbeeld kiezen we Alleen beheerders. Wanneer u uw selectie hebt gemaakt, klikt u op **Upgrade**.

   ![](assets/four.png)

>[!NOTE]
>
>U wordt aangeraden het pakket alleen voor Admins bij te werken en vervolgens [toegang verlenen aan specifieke gebruikers](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target=&quot;_blank&quot;} op basis van het aantal gekochte MSI-licenties. U kunt ook een specifiek Salesforce-profiel maken voor MSI-gebruikers en het pakket alleen voor die gebruikers installeren of upgraden.
