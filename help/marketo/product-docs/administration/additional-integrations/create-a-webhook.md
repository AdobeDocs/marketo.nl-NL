---
unique-page-id: 2360360
description: Een  [!DNL Webhook]  - Marketo-document maken - Productdocumentatie
title: Maken a [!DNL Webhook]
exl-id: 3e753d2d-6f33-4987-884e-8e13167cf3df
feature: Administration, Webhooks
source-git-commit: 23a7b8cb1cd07c0194c08d30218602a52d03df5b
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 1%

---

# Een [!DNL Webhook] maken {#create-a-webhook}

Gebruik [!DNL Webhooks] om gebruik te maken van externe webservices voor het verzenden van tekstberichten, het uitbreiden van persoonlijke gegevens en nog veel meer.

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/create-a-webhook-1.png)

1. Klik op **[!UICONTROL Webhooks]**.

   ![](assets/create-a-webhook-2.png)

1. Klik op **[!UICONTROL New Webhook]**.

   ![](assets/create-a-webhook-3.png)

1. Geef uw [!DNL Webhook] een naam en configureer deze.

   ![](assets/create-a-webhook-4.png)

   >[!NOTE]
   >
   >Dit omvat vaak het ingaan van uw derdedienstgeloofsbrieven als parameter URL, of in het malplaatje van de POST.

   * **[!UICONTROL URL]**: voer de URL in die u in uw aanvraag voor de webservice gebruikt. Als u een token, zoals het e-mailadres van de persoon (**`{{lead.Email Address}}`**), wilt invoegen in uw verzoek, klikt u op **[!UICONTROL Insert Token]** .

   * **[!UICONTROL Template]**: Als u informatie in de tekst van de aanvraag wilt verzenden, voert u deze in via de payload-sjabloon. Sjablonen zijn toegestaan voor de volgende aanvraagtypen: POST, DELETE, PATCH of PUT. U kunt gegevensindelingen gebruiken, zoals JSON of XML. Klik op **[!UICONTROL Insert Token]** om een token in de sjabloon in te voegen.

   * **[!UICONTROL Request Token Encoding]**: Als de symbolische waarden speciale karakters (zoals ampersand, &quot;&amp;&quot;) omvatten, wijs op het formaat van uw verzoek (**JSON** of **Vorm/Url**).

   * **[!UICONTROL Response type]**: Selecteer het formaat van de reactie u van de dienst (**JSON** of **XML**) ontvangt.

   * **[!UICONTROL Request Type]**: selecteer de te gebruiken methode van HTTP (DELETE, GET, PATCH, POST, PUT).

1. Klik op **[!UICONTROL Create]**.

   ![](assets/create-a-webhook-5.png)

>[!NOTE]
>
>Leer meer in [[!DNL Webhooks] ](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/webhooks/webhooks){target="_blank"}  diepe duik.
