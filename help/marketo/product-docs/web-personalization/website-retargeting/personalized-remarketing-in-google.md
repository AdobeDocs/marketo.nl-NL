---
unique-page-id: 4720810
description: Persoonlijke opmerkingen in Google - Marketo Docs - Productdocumentatie
title: Persoonlijke opmerkingen in Google
exl-id: cc733f43-161d-41e4-afdf-8b5217700810
feature: Web Personalization
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 2%

---

# Persoonlijke opmerkingen in Google {#personalized-remarketing-in-google}

De gepersonaliseerde Markeringen laat u met uw gebruikers opnieuw in dienst nemen gebruikend gegevens RTP en de macht van Google Analytics met het bereik van het Netwerk van de Vertoning van Google.

>[!PREREQUISITES]
>
>* Voltooi [ het Opnieuw richten met  [!DNL Web Personalization]  Configuratie van Gegevens ](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* Het overzicht [ Opmerking met de documentatie van de Hulp van Google Analytics ](https://support.google.com/analytics/topic/2611283?hl=en&ref_topic=3413645).

## Een opmerkingspubliek maken in Google {#creating-a-remarketing-audience-in-google}

1. Meld u aan bij uw Google Analytics. Klik op **[!UICONTROL Admin]** , **[!UICONTROL Account]** , **[!UICONTROL Property]** . Klik op **[!UICONTROL Audience Definitions]** en **[!UICONTROL Audiences]** .

   ![](assets/remarketing-ga-screenshots.jpg)

1. Klik op **[!UICONTROL +New Audience]**.

   ![](assets/image2015-1-15-17-3a26-3a40.png)

1. **[!UICONTROL Link Configuration]**: Koppeling maken naar uw [!DNL Google Adwords] -account. **[!UICONTROL Define Audience]**: klik op **[!UICONTROL Create New]** .

   ![](assets/image2015-1-15-17-3a32-3a4.png)

1. Klik in de Audience Builder op **[!UICONTROL Sequences]** en **[!UICONTROL Find the RTP Data]** onder [!UICONTROL Custom Dimensions] , [!UICONTROL UICONTROL [ !] Custom Variables] , [!UICONTROL Events] .

>[!TIP]
>
>Hoe te om de gegevens RTP in Analytics te vinden om uw publiek te bouwen?
>
>In Google Analytics:
>
>* Aangepaste variabelen: organisatie, industrie
>* Gebeurteniscategorie: Segment, Insightera-CTA, RTP-Remarketing
>* Gebeurtenislabel: segmentnaam, naam van campagne, segmentnaam publiek
>
>In Google Universal Analytics:
>
>* Aangepaste afmetingen: organisatie, industrie, categorie (Fortune 500,1000, Global 2000), groep (Enterprise, SMB), ABM-lijst (benoemde accountlijst)
>* Gebeurteniscategorie: RTP-Segment, RTP-Campagne RTP-Remarketing
>* Gebeurtenislabel: segmentnaam, naam van campagne, segmentnaam publiek

**Voorbeeld van de Audience van de Nota&#39;s van de Nota&#39;s van de Opmerking van RTP Gesegmenteerde Gegevens van het Publiek**

1. Klik op **[!UICONTROL Sequences].**
1. Selecteren **[!UICONTROL Event Label].**
1. Voer **[!UICONTROL Name of Segmented Audience]** in (zoals deze wordt weergegeven in RTP).
1. Klik op **[!UICONTROL Apply]**.

![](assets/image2015-2-10-14-3a51-3a43.png)

**Voorbeeld van Publiek van de Gegevens van de Industrie RTP**

![](assets/image2015-1-15-17-3a36-3a5.png)

1. Klik op **[!UICONTROL Sequences]**.
1. Selecteer **[!UICONTROL RTP-Industry]** .
1. Ga **Naam van de Industrie** in (b.v. [!UICONTROL Financial Services], [!UICONTROL Education]...).
1. Klik op **[!UICONTROL Apply]**.
1. Voer een **[!UICONTROL Audience Name]** in. Klik op **[!UICONTROL Save]**.

![](assets/image2015-1-15-18-3a29-3a16.png)

## Een campagne voor opmerkingen en advertenties maken in [!DNL Google Adwords] {#create-a-remarketing-ad-campaign-in-google-adwords}

1. Meld u aan bij **[!DNL Google Adwords]** . Klik op **[!UICONTROL Campaigns]** en selecteer **[!UICONTROL Display Network only]** .

   ![](assets/image2015-1-15-18-3a31-3a58.png)

1. Enter **[!UICONTROL Campaign Name]**, Select **[!UICONTROL Type Remarketing].**

   ![](assets/image2015-1-15-18-3a35-3a7.png)

1. Voer **[!UICONTROL Ad Group Name],** enter **[!UICONTROL Enhanced CPC]**, Select **[!UICONTROL Remarketing List]** in.

   ![](assets/image2015-1-15-18-3a51-3a57.png)

1. Klik op **[!UICONTROL Save]** en ga verder.
1. Voeg uw afbeelding of tekstadvertentie toe en start uw campagne voor het opnieuw op de markt brengen van tekst.

   ![](assets/image2015-1-15-18-3a47-3a21.png)

>[!MORELIKETHIS]
>
>* [ het opnieuw richten met  [!DNL Web Personalization]  Gegevens ](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [ Gepersonaliseerde het Merken in  [!DNL Facebook]](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)
