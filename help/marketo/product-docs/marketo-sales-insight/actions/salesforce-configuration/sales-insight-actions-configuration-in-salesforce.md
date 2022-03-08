---
description: Configuratie van verkooponderzoeken in Salesforce - Marketo-documenten - Productdocumentatie
title: Configuratie van de Acties van het Inzicht van de verkoop in Salesforce
hide: true
hidefromtoc: true
exl-id: 2d842886-3501-4aca-96fb-0d6763ab2b01
source-git-commit: ba1357e6970ba4e3dc496d27272d067ac87c5e6d
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 0%

---

# Configuratie van de Acties van het Inzicht van de verkoop in Salesforce {#sales-insight-actions-configuration-in-salesforce}

>[!PREREQUISITES]
>
>* [Installeren](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md) of [Upgrade](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md) Verkooppakket in uw Salesforce-exemplaar
>* [Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)


## Nieuwe externe site toevoegen in Salesforce {#add-new-remote-site-in-salesforce}

1. Klik in Salesforce op **Instellen**.

   ![](assets/msi-actions-configuration-in-salesforce-1.png)

1. Zoeken naar &quot;externe site&quot; en selecteren **Instellingen voor externe site**.
   ![](assets/msi-actions-configuration-in-salesforce-2.png)

1. Klikken **Nieuwe externe site**.

   ![](assets/msi-actions-configuration-in-salesforce-3.png)

1. Ga de Verre Naam van de Plaats in (het kan iets als &quot;MarketoSalesInsight&quot; zijn). Voer de URL van de externe site in (https://ims-na1-stg1.adobelogin.com) en klik op **Opslaan**.

   ![](assets/msi-actions-configuration-in-salesforce-4.png)

## Het toelaten van de Acties van het Inzicht van de Verkoop over CRM {#enabling-sales-insight-actions-across-the-crm}

1. Klik in Salesforce op de knop **Marketo Sales Insight Config** tab.

   ![](assets/msi-actions-configuration-in-salesforce-5.png)

   >[!NOTE]
   >
   >Als u &quot;Marketo Sales Insight Config&quot; niet ziet in de bovenste balk, klikt u op de knop **+** ondertekenen en zoeken onder All Tabs.

1. Selecteer **MSI-handelingen inschakelen** selectievakje.

   ![](assets/msi-actions-configuration-in-salesforce-6.png)

1. Voer de geheime API-sleutel in.

   ![](assets/msi-actions-configuration-in-salesforce-7.png)

   >[!NOTE]
   >
   >Als u niet over uw API Secrey Key handig beschikt, kunt u het vinden door de stappen in [dit artikel](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md).

1. Klikken **Opslaan** wanneer gereed.

Hierdoor worden automatisch alle functies van MSI-handelingen ingeschakeld die in het artikel met het overzicht van functies worden beschreven.

>[!NOTE]
>
>U kunt alle functies van MSI-acties uitschakelen door het selectievakje MSI-acties inschakelen uit te schakelen.

## Beheer van MSI-acties {#msi-actions-governance}

1. U kunt verkoopcampagnes en/of het lusje van de Taak in de aanstaande sectie onbruikbaar maken. Dit is van toepassing op de deelvensters lood, contact, account en opportunity.

   ![](assets/msi-actions-configuration-in-salesforce-8.png)

1. U kunt MSI-handelingen uitschakelen door de bijbehorende functies onder Handelingen uit te schakelen.

   ![](assets/msi-actions-configuration-in-salesforce-9.png)

>[!NOTE]
>
>De montages van de governance zijn van toepassing op alle gebruikers MSI.
