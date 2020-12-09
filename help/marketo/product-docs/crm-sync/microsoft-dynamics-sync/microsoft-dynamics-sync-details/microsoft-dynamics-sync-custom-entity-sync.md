---
unique-page-id: 3571846
description: Microsoft Dynamics Sync - Custom Entity Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Custom Entity Sync
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '217'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Aangepaste entiteitssynchronisatie {#microsoft-dynamics-sync-custom-entity-sync}

Als u de aanvankelijke synchronisatie van de douaneentiteit moet toelaten om gegevens van Dynamiek beschikbaar te maken in Marketo, is hier hoe te om het te doen.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!PREREQUISITES]
>
>Als u een aangepast object wilt gebruiken, moet het worden gekoppeld aan een [lead](microsoft-dynamics-sync-lead-sync.md), [contact](microsoft-dynamics-sync-contact-sync.md)of [](microsoft-dynamics-sync-account-sync.md)accountobject in Dynamics.

>[!CAUTION]
>
>Zorg ervoor dat de eerste synchronisatie is voltooid (u wordt via e-mail op de hoogte gesteld) voordat u de synchronisatie voor aangepaste entiteiten start.

1. Ga naar de sectie Beheer.

   ![](assets/image2014-10-20-14-3a32-3a16.png)

1. Klik op Sync **uitschakelen** om de standaard algemene synchronisatie tijdelijk uit te schakelen.

   ![](assets/image2015-11-10-9-3a0-3a6.png)

1. Installeer een versie van de Dynamica van Microsoft die douanefunctionaliteit (na 2_0_0_2) steunt. Zie [Marketo Plugin-releases voor Microsoft Dynamics](../../../../product-docs/crm-sync/microsoft-dynamics-sync/marketo-plugin-releases-for-microsoft-dynamics.md).
1. Geef de gebruiker van het Marketo synchroon toegang tot om het even welke entiteiten u van plan bent te synchroniseren.
1. Klik onder Databasebeheer op de koppeling* Dynamische entiteiten synchroniseren**.

   ![](assets/image2015-11-10-9-3a6-3a55.png)

1. Klik op de koppeling Schema **** synchroniseren om de lijst met beschikbare aangepaste entiteiten te doorlopen.

   ![](assets/image2015-11-10-9-3a41-3a37.png)

1. Nadat de lijst is gesynchroniseerd, selecteert u de velden die u wilt synchroniseren en de velden die u wilt gebruiken als [beperkingen](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) en/of triggers in slimme lijsten. Klik op Sync **inschakelen als u klaar bent**.

   ![](assets/image2014-10-20-14-3a32-3a55.png)

1. Schakel de globale synchronisatie opnieuw in.

   ![](assets/image2015-11-10-9-3a48-3a35.png)

   >[!NOTE]
   >
   >Marketo ondersteunt alleen aangepaste entiteiten die een of twee niveaus diep zijn gekoppeld aan standaardentiteiten.

   >[!NOTE]
   >
   >Entiteitsnamen mogen maximaal** 33 tekens** hebben.

Je bent goed!