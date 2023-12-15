---
unique-page-id: 4720257
description: Aangepast publiek voor Facebook toevoegen als een opstartpuntservice - Marketo Docs - Productdocumentatie
title: Aangepast publiek voor Facebook toevoegen als een opstartpuntservice
exl-id: 5c5b5c80-fd0f-482a-8163-6eef3dbcb236
feature: Integrations
source-git-commit: bebf61037f37a06b40b4d9c1df872f1cf62a1403
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 0%

---

# Aangepast publiek voor Facebook toevoegen als een opstartpuntservice {#add-facebook-custom-audiences-as-a-launchpoint-service}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Met deze integratie kunt u publieksgegevens van statische en slimme lijsten van het Marketo Engage naar Facebook verzenden die als Aangepast publiek in de Campagnes van Facebook en van de Advertentie worden gebruikt. Hier is hoe u het kunt instellen.

1. Ga naar Marketo **[!UICONTROL Admin]**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. Ga naar **[!UICONTROL LaunchPoint]**, klikt u op **[!UICONTROL New]** en selecteert u **[!UICONTROL New Service]**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. Voer een **[!UICONTROL Display Name]** voor uw service en selecteer de **[!UICONTROL Facebook Custom Audiences]** van de **[!UICONTROL Service]** vervolgkeuzelijst.

   ![](assets/image2016-11-29-12-3a51-3a8.png)

1. Open een nieuw tabblad in dezelfde browser en ga naar [facebook.com](https://www.facebook.com/){target="_blank"}. Meld u aan bij Facebook met het account dat u voor de integratie wilt gebruiken.

   >[!CAUTION]
   >
   >Marketo kan alleen een publiek sturen via meerdere Advertentiebeheeraccounts als de Facebook-gebruiker die u in de volgende stappen autoriseert, toegang heeft tot *alles* van deze rekeningen.

   ![](assets/image2016-11-29-10-3a52-3a29.png)

1. Ga terug naar Marketo nadat u zich hebt aangemeld bij Facebook. Klik op **[!UICONTROL Authorize]**.

   ![](assets/fb-custom-authorize-hand.png)

   >[!NOTE]
   >
   >U _moet_ gebruik een Facebook Business Manager-account zodat uw aangepaste publiek kan integreren. Raadpleeg voor meer informatie over het instellen van een Business Manager-account [Facebook Help](https://www.facebook.com/business/help/1710077379203657){target="_blank"}.

1. Klik desgevraagd op **[!UICONTROL OK]** om de installatie van de Marketo-app in Facebook te accepteren.

   ![](assets/image2016-11-29-10-3a56-3a3.png)

1. U bent nu geautoriseerd! Selecteer een passende wijze en klik **[!UICONTROL Create]**.

   >[!NOTE]
   >
   >**Standaard overeenkomend** gebruikt alleen e-mailadressen. **Geavanceerde overeenkomsten** gebruikt zeven extra gebieden, die het gelijke tarief verhogen, voor meer omzetting. Nochtans, als het de privacybeleid van uw bedrijf het delen van extra gebieden niet toelaat, of als uw gegevens hen niet omvat, uitgezochte BasisGelijke.

   ![](assets/fb-custom-adv-matching-hands.png)

   Geweldig werk! U kunt nu naar elke statische of slimme lijst in Marketo gaan en de publieksgegevens naar Facebook verzenden.

   >[!CAUTION]
   >
   >Oh, voordat je gaat, zorg ervoor dat je [Voorwaarden voor aangepast publiek voor Facebook accepteren](https://www.facebook.com/ads/manage/customaudiences/tos.php){target="_blank"} in je Facebook-account! Zonder dit te doen, zullen de publieksupdates ontbreken.

>[!MORELIKETHIS]
>
>* [Een aangepast publiek maken in Facebook](/help/marketo/product-docs/demand-generation/facebook/create-a-custom-audience-in-facebook.md){target="_blank"}
>
>* [Facebook Lead Ads instellen](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md){target="_blank"}
