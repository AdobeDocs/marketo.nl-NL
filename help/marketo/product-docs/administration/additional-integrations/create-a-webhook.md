---
unique-page-id: 2360360
description: Webhaak maken - Marketo Docs - Productdocumentatie
title: Webhaak maken
exl-id: 3e753d2d-6f33-4987-884e-8e13167cf3df
source-git-commit: a498dcc5dc95bd7f732481d30db021485cf052c0
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# Webhaak maken {#create-a-webhook}

Gebruik websites om gebruik te maken van externe webservices voor het verzenden van tekstberichten, het uitbreiden van persoonlijke gegevens en nog veel meer.

>[!AVAILABILITY]
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

1. Ga naar de **Beheer** gebied.

   ![](assets/create-a-webhook-1.png)

1. Klikken **Webhaken**.

   ![](assets/create-a-webhook-2.png)

1. Klikken **Nieuwe webhaak**.

   ![](assets/create-a-webhook-3.png)

1. Geef uw webhaak een naam en configureer deze.

   ![](assets/create-a-webhook-4.png)

   >[!NOTE]
   >
   >Dit omvat vaak het ingaan van uw derdedienstgeloofsbrieven als parameter URL, of in het malplaatje van de POST.

   * **URL**: Voer de URL in die u in uw aanvraag voor de webservice gebruikt. Een token invoegen, zoals het e-mailadres van de persoon (**`{{lead.Email Address}}`**), klikt u in uw verzoek op **Token invoegen**.

   * **Sjabloon**: Als u informatie in het lichaam van het verzoek wilt overbrengen, ga via het ladingsmalplaatje in. Sjablonen zijn toegestaan voor de volgende aanvraagtypen: POST, DELETE, PATCH of PUT. U kunt gegevensformaten zoals JSON of XML gebruiken. Als u een token wilt invoegen in uw sjabloon, klikt u op **Token invoegen**.

   * **Tokencodering aanvragen**: Als de tokenwaarden speciale tekens bevatten (zoals een en-teken &#39;&amp;&#39;), geeft u de indeling van uw verzoek op (**JSON** of **Formulier/URL**).

   * **Type reactie**: Selecteer het formaat van de reactie u van de dienst ontvangt (**JSON** of **XML**).

   * **Type aanvraag**: Selecteer de te gebruiken methode van HTTP (DELETE, GET, PATCH, POST, PUT).

1. Klikken **Maken**.

   ![](assets/create-a-webhook-5.png)

>[!NOTE]
>
>Meer informatie in het dialoogvenster [webhaken](https://developers.marketo.com/documentation/webhooks/) diep duiken.
