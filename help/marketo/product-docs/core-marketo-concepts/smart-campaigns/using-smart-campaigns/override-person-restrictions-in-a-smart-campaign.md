---
unique-page-id: 1147066
description: Persoonlijke beperkingen in een slimme campagne negeren - Marketo Docs - Productdocumentatie
title: Persoonlijke beperkingen in een slimme campagne negeren
exl-id: 45ff3e36-01fd-42ea-ba74-efd98867a58a
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '138'
ht-degree: 0%

---

# Persoonlijke beperkingen in een slimme campagne negeren {#override-person-restrictions-in-a-smart-campaign}

Met Marketo kunt u het maximumaantal personen instellen dat in aanmerking komt voor een slimme campagne. dit helpt u te voorkomen dat u per ongeluk uw gehele database per e-mail verzendt. Als u wilt _override_ deze limiet is hoe.

>[!PREREQUISITES]
>
>Zorg ervoor dat u [persoonlijke beperkingen voor slimme campagnes inschakelen](/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md) in Marketo Admin.

1. Ga bij marketingactiviteiten naar uw slimme campagne en klik op **Schema**.

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
