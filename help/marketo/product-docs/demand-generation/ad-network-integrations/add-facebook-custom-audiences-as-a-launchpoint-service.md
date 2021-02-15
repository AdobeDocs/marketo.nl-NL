---
unique-page-id: 4720257
description: Aangepast publiek voor Facebook toevoegen als een opstartpuntservice - Marketo Docs - Productdocumentatie
title: Aangepast publiek voor Facebook toevoegen als een opstartpuntservice
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '324'
ht-degree: 0%

---


# Aangepast publiek voor Facebook toevoegen als een opstartpuntservice {#add-facebook-custom-audiences-as-a-launchpoint-service}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Met deze integratie kunt u publieksgegevens van de statische en slimme lijsten van Marketo naar Facebook verzenden voor gebruik als aangepast publiek in Facebook en campagnes. Hier is hoe je het instelt.

1. Ga naar Marketo **Admin**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. Ga naar **LaunchPoint**, klik op **New** en selecteer **New Service**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. Voer een **Weergavenaam** voor uw service in en selecteer de **Aangepaste doelgroep voor Facebook**-service in de vervolgkeuzelijst **Service**.

   ![](assets/image2016-11-29-12-3a51-3a8.png)

1. Open een nieuw tabblad in dezelfde browser en ga naar [facebook.com](https://www.facebook.com/). Meld u aan bij Facebook met het account dat u voor de integratie wilt gebruiken.

   >[!CAUTION]
   >
   >Als u wilt dat Marketo een publiek verstuurt via meerdere Advertentiebeheeraccounts, moet de Facebook-gebruiker die u in de volgende stappen autoriseert toegang hebben tot *all* van deze accounts.

   ![](assets/image2016-11-29-10-3a52-3a29.png)

1. Ga terug naar Marketo nadat u zich hebt aangemeld bij Facebook. Klik **Autoriseren**.

   ![](assets/fb-custom-authorize-hand.png)

   >[!NOTE]
   >
   >U _moet_ een Facebook Business Manager-account gebruiken om de integratie van Aangepast publiek te laten werken. Raadpleeg [Facebook Help](https://www.facebook.com/business/help/1710077379203657) voor meer informatie over het instellen van een Business Manager-account.

1. Klik desgevraagd op **OK** om de installatie van de Marketo-app in Facebook te accepteren.

   ![](assets/image2016-11-29-10-3a56-3a3.png)

1. U bent nu geautoriseerd! Selecteer een aanpassingsmodus en klik op **Maken**.

   >[!NOTE]
   >
   >**Standaard** afstemming gebruikt alleen e-mailadressen. **Bij Geavanceerde** overeenkomsten worden zeven extra velden gebruikt, waardoor de overeenkomende snelheid toeneemt, voor meer conversie. Nochtans, als het de privacybeleid van uw bedrijf het delen van extra gebieden niet toelaat, of als uw gegevens hen niet omvat, uitgezochte BasisGelijke.

   ![](assets/fb-custom-adv-matching-hands.png)

   Geweldig werk! U kunt nu naar elke statische of slimme lijst in Marketo gaan en publieksgegevens naar Facebook verzenden.

   >[!CAUTION]
   >
   >Oh, voordat u gaat, moet u [Aangepaste voorwaarden voor soorten publiek van Facebook accepteren](https://www.facebook.com/ads/manage/customaudiences/tos.php) in uw Facebook-account! Zonder dit te doen, zullen de publieksupdates ontbreken.

>[!MORELIKETHIS]
>
>* [Een aangepast publiek maken op Facebook](/help/marketo/product-docs/demand-generation/facebook/create-a-custom-audience-in-facebook.md)
   >
   >
* [Advertenties voor Facebook-leads instellen](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md)

