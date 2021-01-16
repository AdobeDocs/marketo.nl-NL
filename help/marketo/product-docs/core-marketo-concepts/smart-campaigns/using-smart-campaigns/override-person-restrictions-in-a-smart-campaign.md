---
unique-page-id: 1147066
description: De Beperkingen van de Persoon in een Slimme Campagne met voeten treden - Marketo Docs - de Documentatie van het Product
title: Persoonlijke beperkingen in een slimme campagne negeren
translation-type: tm+mt
source-git-commit: 4a0bd2efe99284807a46d07ffef0070d9a303631
workflow-type: tm+mt
source-wordcount: '138'
ht-degree: 0%

---


# Persoonlijke beperkingen in een slimme campagne {#override-person-restrictions-in-a-smart-campaign} overschrijven

Marketo stelt het maximumaantal personen in dat in aanmerking komt voor een slimme campagne. dit helpt u te voorkomen dat u per ongeluk uw gehele database per e-mail verzendt. Als u _override_ deze limiet wilt, is dit hoe.

>[!PREREQUISITES]
>
>Zorg ervoor dat u de beperkingen voor personen [inschakelt voor slimme campagnes](/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md) in Marketo Admin.

1. Ga in de Activiteiten van de Marketing, naar uw slimme campagne en klik **Programma**.

   ![](assets/one.png)

1. Klik in Instellingen voor slimme campagne op **Bewerken**.

   ![](assets/two.png)

   >[!NOTE]
   >
   >De standaardlimiet is de limiet die is ingesteld in Beheer.

1. Voer een nieuwe limiet in en klik op **Opslaan.**

   ![](assets/three.png)

   De slimme campagne wordt niet uitgevoerd als het aantal personen dat in aanmerking komt de ingestelde limiet overschrijdt.

   >[!CAUTION]
   >
   >Wees voorzichtig met deze functie, zodat u niet per ongeluk te veel personen opneemt.
