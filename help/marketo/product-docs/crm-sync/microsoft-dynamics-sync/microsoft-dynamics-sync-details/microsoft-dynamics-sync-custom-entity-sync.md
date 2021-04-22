---
unique-page-id: 3571846
description: Microsoft Dynamics Sync - Custom Entity Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Custom Entity Sync
exl-id: 1e175bd4-509f-4c1f-a41d-456629e4a8fb
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '217'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Aangepaste entiteitssynchronisatie {#microsoft-dynamics-sync-custom-entity-sync}

Als u de aanvankelijke synchronisatie van de douaneentiteit moet toelaten om gegevens van Dynamica beschikbaar te maken in Marketo, is hier hoe te om het te doen.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!PREREQUISITES]
>
>Als u een aangepast object wilt gebruiken, moet het worden gekoppeld aan een [lead](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md), [contact](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md) of [account](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)object in Dynamics.

>[!CAUTION]
>
>Zorg ervoor dat de eerste synchronisatie is voltooid (u wordt via e-mail op de hoogte gesteld) voordat u de synchronisatie voor aangepaste entiteiten start.

1. Ga naar de sectie Beheer.

   ![](assets/image2014-10-20-14-3a32-3a16.png)

1. Klik **Schakel Sync** uit om de standaard algemene synchronisatie tijdelijk uit te schakelen.

   ![](assets/image2015-11-10-9-3a0-3a6.png)

1. Installeer een versie van de Dynamica van Microsoft die douanefunctionaliteit (na 2_0_0_2) steunt. Zie [Marketo Plugin-releases voor Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/marketo-plugin-releases-for-microsoft-dynamics.md).

1. Leestoegang tot alle entiteiten die u wilt synchroniseren door de Marketo Sync-gebruiker.

1. Klik onder Databasebeheer op de koppeling **Dynamics Entities Sync**.

   ![](assets/image2015-11-10-9-3a6-3a55.png)

1. Klik op de koppeling **Schema synchroniseren** om de lijst met beschikbare aangepaste entiteiten over te halen.

   ![](assets/image2015-11-10-9-3a41-3a37.png)

1. Nadat de lijst synchroniseert, selecteer de gebieden u en degenen wilt synchroniseren u als [beperkingen](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) en/of trekkers in slimme lijsten wilt gebruiken. Wanneer gedaan, klik **toelaten Synchronisatie**.

   ![](assets/image2014-10-20-14-3a32-3a55.png)

1. Schakel de globale synchronisatie opnieuw in.

   ![](assets/image2015-11-10-9-3a48-3a35.png)

   >[!NOTE]
   >
   >Marketo ondersteunt alleen aangepaste entiteiten die een of twee niveaus diep zijn gekoppeld aan standaardentiteiten.

   >[!NOTE]
   >
   >Entiteitsnamen mogen maximaal **33 tekens** bevatten.

Je bent goed!
