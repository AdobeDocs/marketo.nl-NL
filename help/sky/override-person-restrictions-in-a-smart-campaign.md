---
title: override-person-constraints-in-a-smart-campagne
description: Persoonlijke beperkingen in een slimme campagne negeren
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '130'
ht-degree: 0%

---


# Persoonlijke beperkingen in een slimme campagne negeren

<br> 

Marketo stelt het maximumaantal personen in dat in aanmerking komt voor een slimme campagne. dit helpt u te voorkomen dat u per ongeluk uw gehele database per e-mail verzendt. Als je deze limiet wilt overschrijven, is dit hoe.

>[!IMPORTANT]
>
>Zorg ervoor dat u persoonlijke beperkingen [inschakelt voor slimme campagnes](https://docs.marketo.com/display/DOCS/Enable+Person+Restrictions+for+Smart+Campaigns) in Marketo [!UICONTROL Admin].

1. Zoek uw slimme campagne en klik op **[!UICONTROL Schedule]**.

   ![Afbeelding één](/help/sky/assets/smart-campaigns/override-person-restrictions-in-a-smart-campaign/override-person-restrictions-in-a-smart-campaign-1.png)

1. Klik **[!UICONTROL Qualification Rules]**.

   ![Afbeelding twee](/help/sky/assets/smart-campaigns/override-person-restrictions-in-a-smart-campaign/override-person-restrictions-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >De standaardlimiet is de limiet die is ingesteld in Beheer.

1. Voer naast **[!UICONTROL Abort campaign if qualified leads exceed]** een nieuwe limiet in.

   ![Afbeelding drie](/help/sky/assets/smart-campaigns/override-person-restrictions-in-a-smart-campaign/override-person-restrictions-in-a-smart-campaign-3.png)

>[!NOTE]
>
>De slimme campagne wordt niet uitgevoerd als het aantal personen dat in aanmerking komt de ingestelde limiet overschrijdt.

>[!CAUTION]
>
>Wees voorzichtig met deze functie, zodat u niet per ongeluk te veel mensen opneemt.
