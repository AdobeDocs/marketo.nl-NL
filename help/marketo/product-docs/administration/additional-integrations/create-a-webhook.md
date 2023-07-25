---
unique-page-id: 2360360
description: Een [!DNL Webhook] - Marketo Docs - Productdocumentatie
title: Een [!DNL Webhook]
exl-id: 3e753d2d-6f33-4987-884e-8e13167cf3df
feature: Administration, Webhooks
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 1%

---

# Een [!DNL Webhook] {#create-a-webhook}

Gebruiken [!DNL Webhooks] om gebruik te maken van externe webservices voor het verzenden van tekstberichten, het uitbreiden van persoonlijke gegevens en meer.

>[!AVAILABILITY]
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/create-a-webhook-1.png)

1. Klik op **[!UICONTROL Webhooks]**.

   ![](assets/create-a-webhook-2.png)

1. Klik op **[!UICONTROL New Webhook]**.

   ![](assets/create-a-webhook-3.png)

1. Naam en vorm uw [!DNL Webhook].

   ![](assets/create-a-webhook-4.png)

   >[!NOTE]
   >
   >Dit omvat vaak het ingaan van uw derdedienstgeloofsbrieven als parameter URL, of in het malplaatje van de POST.

   * **[!UICONTROL URL]**: Voer de URL in die u in uw aanvraag voor de webservice gebruikt. Een token invoegen, zoals het e-mailadres van de persoon (**`{{lead.Email Address}}`**), klikt u in uw verzoek op **[!UICONTROL Insert Token]**.

   * **[!UICONTROL Template]**: Als u informatie in het lichaam van het verzoek wilt overbrengen, ga via het ladingsmalplaatje in. Sjablonen zijn toegestaan voor de volgende aanvraagtypen: POST, DELETE, PATCH of PUT. U kunt gegevensformaten zoals JSON of XML gebruiken. Als u een token wilt invoegen in uw sjabloon, klikt u op **[!UICONTROL Insert Token]**.

   * **[!UICONTROL Request Token Encoding]**: Als de tokenwaarden speciale tekens bevatten (zoals een en-teken &#39;&amp;&#39;), geeft u de indeling van uw verzoek op (**JSON** of **Formulier/URL**).

   * **[!UICONTROL Response type]**: Selecteer het formaat van de reactie u van de dienst ontvangt (**JSON** of **XML**).

   * **[!UICONTROL Request Type]**: Selecteer de te gebruiken methode van HTTP (DELETE, GET, PATCH, POST, PUT).

1. Klik op **[!UICONTROL Create]**.

   ![](assets/create-a-webhook-5.png)

>[!NOTE]
>
>Meer informatie in het dialoogvenster [[!DNL Webhooks]](https://developers.marketo.com/documentation/webhooks/){target="_blank"} diep duiken.
