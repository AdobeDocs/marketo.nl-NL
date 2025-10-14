---
unique-page-id: 1147066
description: Persoonlijke beperkingen in een slimme campagne negeren - Marketo Docs - Productdocumentatie
title: Persoonlijke beperkingen in een slimme campagne negeren
exl-id: 45ff3e36-01fd-42ea-ba74-efd98867a58a
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '132'
ht-degree: 0%

---

# Persoonlijke beperkingen in een slimme campagne negeren {#override-person-restrictions-in-a-smart-campaign}

Met Marketo Engage kunt u het maximumaantal personen instellen dat in aanmerking komt voor een slimme campagne. Zo voorkomt u dat per ongeluk uw gehele database wordt gemaild. Als u __ deze grens wilt met voeten treden, is hier hoe.

>[!PREREQUISITES]
>
>Ben zeker om [&#x200B; persoonlijke beperkingen voor Slimme Campagnes &#x200B;](/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md){target="_blank"} in Marketo toe te laten Admin.

1. Ga in **[!UICONTROL Marketing Activities]** naar uw slimme campagne en klik op **[!UICONTROL Schedule]** .

   ![](assets/override-person-restrictions-in-a-smart-campaign-1.png)

1. Klik op **[!UICONTROL Edit]** bij Instellingen voor slimme campagne.

   ![](assets/override-person-restrictions-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >De standaardlimiet is de limiet die is ingesteld in Beheer.

1. Voer een nieuwe limiet in en klik op **[!UICONTROL Save]** .

   ![](assets/override-person-restrictions-in-a-smart-campaign-3.png)

   De slimme campagne wordt niet uitgevoerd als het aantal personen dat in aanmerking komt, de ingestelde limiet overschrijdt.

   >[!CAUTION]
   >
   >Wees voorzichtig met deze functie, zodat u niet per ongeluk te veel mensen opneemt.
