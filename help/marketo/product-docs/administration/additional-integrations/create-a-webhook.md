---
unique-page-id: 2360360
description: Een webhaak maken - Marketo Docs - Productdocumentatie
title: Webhaak maken
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 0%

---


# Webhaak {#create-a-webhook} maken

Gebruik websites om gebruik te maken van externe webservices voor het verzenden van tekstberichten, het uitbreiden van persoonlijke gegevens en nog veel meer.

>[!AVAILABILITY]
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

1. Ga naar **Admin** en klik **Webhooks**.

   ![](assets/image2014-9-24-14-3a52-3a57.png)

1. Klik **Nieuwe Webhaak**.

   ![](assets/image2014-9-24-14-3a53-3a9.png)

1. Geef uw webhaak een naam en configureer deze.

   ![](assets/image2014-9-24-14-3a53-3a19.png)

   >[!NOTE]
   >
   >Dit omvat vaak het ingaan van uw derdedienstgeloofsbrieven als parameter URL, of in het malplaatje van de POST.

   * **URL**: Voer de URL in die u gebruikt om uw aanvraag naar de webservice te POSTEN. Als u een token, zoals het e-mailadres van de persoon (**`{{lead.Email Address}}`**), wilt invoegen in uw verzoek, klikt u op **Token invoegen**.

   * **Sjabloon**: Als u informatie in het lichaam van de POST wilt overbrengen, ga het malplaatje in. Gebruik om het even welk gegevensformaat dat de POST van HTTP, met inbegrip van XML, JSON, of ZEEP steunt. Als u een token wilt invoegen in uw sjabloon, klikt u op **Token invoegen**.

   * **Tokencodering** aanvragen: Als de tokenwaarden speciale tekens bevatten (zoals een en-teken &#39;&amp;&#39;), geeft u de indeling van uw verzoek aan (**** JSONof  **Form/Url**).

   * **Type** reactie: Selecteer het formaat van de reactie u van de dienst (**** JSONof  **XML**) ontvangt.

   Klik op Maken.

   ![](assets/image2014-9-24-14-3a53-3a35.png)

>[!NOTE]
>
>Leer meer in de [grote duik](https://developers.marketo.com/documentation/webhooks/).
