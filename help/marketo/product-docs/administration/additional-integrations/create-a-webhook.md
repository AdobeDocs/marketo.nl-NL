---
unique-page-id: 2360360
description: Een webhaak maken - Marketo Docs - Productdocumentatie
title: Webhaak maken
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '251'
ht-degree: 0%

---


# Webhaak maken {#create-a-webhook}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

Gebruik websites om gebruik te maken van externe webservices voor het verzenden van tekstberichten, het uitbreiden van persoonlijke gegevens en nog veel meer.

>[!NOTE]
>
>**Beschikbaarheid**
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

1. Ga naar **Admin **en klik **Webhooks**.

   ![](assets/image2014-9-24-14-3a52-3a57.png)

1. Klik op **Nieuwe webhaak**.

   ![](assets/image2014-9-24-14-3a53-3a9.png)

1. Geef uw webhaak een naam en configureer deze.

   ![](assets/image2014-9-24-14-3a53-3a19.png)

   >[!NOTE]
   >
   >Dit omvat vaak het ingaan van uw derdedienstgeloofsbrieven als parameter URL, of in het malplaatje van de POST.

   * **URL**: Voer de URL in die u gebruikt om uw aanvraag naar de webservice te POSTEN. Als u een token, zoals het e-mailadres (**`{{lead.Email Address}}`**) van de persoon, wilt invoegen in uw verzoek, klikt u op Token **** invoegen.

   * **Sjabloon**: Als u informatie in het lichaam van de POST wilt overbrengen, ga het malplaatje in. Gebruik om het even welk gegevensformaat dat de POST van HTTP, met inbegrip van XML, JSON, of ZEEP steunt. Als u een token wilt invoegen in uw sjabloon, klikt u op **Token** invoegen.

   * **Tokencodering** aanvragen: Als de tokenwaarden speciale tekens bevatten (zoals een en-teken &#39;&amp;&#39;), geeft u de indeling van uw verzoek aan (**JSON** of **Form/Url**).

   * **Type** reactie: Selecteer het formaat van de reactie u van de dienst (**JSON** of **XML**) ontvangt.

   Klik op Maken.

   ![](assets/image2014-9-24-14-3a53-3a35.png)

>[!NOTE]
>
>**Diep duiken**
>
>Meer weten over de [webhooks](http://developers.marketo.com/documentation/webhooks/) in de diepe duik?

