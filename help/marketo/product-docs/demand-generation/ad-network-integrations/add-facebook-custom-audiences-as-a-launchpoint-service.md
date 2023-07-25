---
unique-page-id: 4720257
description: Aangepast publiek voor Facebook toevoegen als een opstartpuntservice - Marketo Docs - Productdocumentatie
title: Aangepast publiek voor Facebook toevoegen als een opstartpuntservice
exl-id: 5c5b5c80-fd0f-482a-8163-6eef3dbcb236
feature: Integrations
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '324'
ht-degree: 0%

---

# Aangepast publiek voor Facebook toevoegen als een opstartpuntservice {#add-facebook-custom-audiences-as-a-launchpoint-service}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Met deze integratie kunt u publieksgegevens van statische en slimme lijsten van Marketo naar Facebook verzenden voor gebruik als Aangepast publiek in Facebook Ad Campaigns. Hier is hoe je het instelt.

1. Ga naar Marketo **Beheer**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. Ga naar **LaunchPoint**, klikt u op **Nieuw** en selecteert u **Nieuwe service**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. Voer een **Weergavenaam** voor uw service en selecteer de **Aangepast publiek voor facebook** van de **Service** vervolgkeuzelijst.

   ![](assets/image2016-11-29-12-3a51-3a8.png)

1. Open een nieuw tabblad in dezelfde browser en ga naar [facebook.com](https://www.facebook.com/). Meld u aan bij Facebook met het account dat u voor de integratie wilt gebruiken.

   >[!CAUTION]
   >
   >Marketo kan alleen een publiek sturen via meerdere Advertentiebeheeraccounts als de Facebook-gebruiker die u in de volgende stappen autoriseert, toegang heeft tot *alles* van deze rekeningen.

   ![](assets/image2016-11-29-10-3a52-3a29.png)

1. Ga terug naar Marketo nadat u zich hebt aangemeld bij Facebook. Klikken **Autoriseren**.

   ![](assets/fb-custom-authorize-hand.png)

   >[!NOTE]
   >
   >U _moet_ gebruik een Facebook Business Manager-account zodat de integratie met het aangepaste publiek werkt. Raadpleeg voor meer informatie over het instellen van een Business Manager-account [Facebook Help](https://www.facebook.com/business/help/1710077379203657).

1. Klik desgevraagd op **OK** om de installatie van de Marketo-app in Facebook te accepteren.

   ![](assets/image2016-11-29-10-3a56-3a3.png)

1. U bent nu geautoriseerd! Selecteer een overeenkomende modus en klik op **Maken**.

   >[!NOTE]
   >
   >**Standaard overeenkomend** gebruikt alleen e-mailadressen. **Geavanceerde overeenkomsten** gebruikt zeven extra gebieden, die het gelijke tarief verhogen, voor meer omzetting. Nochtans, als het de privacybeleid van uw bedrijf het delen van extra gebieden niet toelaat, of als uw gegevens hen niet omvat, uitgezochte BasisGelijke.

   ![](assets/fb-custom-adv-matching-hands.png)

   Geweldig werk! U kunt nu naar elke statische of slimme lijst in Marketo gaan en de publieksgegevens naar Facebook verzenden.

   >[!CAUTION]
   >
   >Oh, voordat je gaat, zorg ervoor dat je [Voorwaarden voor aangepast publiek voor Facebook accepteren](https://www.facebook.com/ads/manage/customaudiences/tos.php) in je Facebook-account! Zonder dit te doen, zullen de publieksupdates ontbreken.

>[!MORELIKETHIS]
>
>* [Een aangepast publiek maken in Facebook](/help/marketo/product-docs/demand-generation/facebook/create-a-custom-audience-in-facebook.md)
>
>* [Facebook Lead Ads instellen](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md)
