---
unique-page-id: 2360350
description: Een aangepaste service maken voor gebruik met de ReST API - Marketo Docs - Productdocumentatie
title: Een aangepaste service maken voor gebruik met de ReST-API
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 0%

---


# Een aangepaste service maken voor gebruik met de ReST-API {#create-a-custom-service-for-use-with-rest-api}

Als u met Marketo via de ReST API wilt integreren, zult u een douanedienst willen tot stand brengen. Zo gaat het.

>[!PREREQUISITES]
>
>* [Een gebruikersrol maken die alleen een API is](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [Alleen een API-gebruiker maken](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md)

>



>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!TIP]
>
>Raadpleeg de documentatie van onze ontwikkelaars voor meer informatie over de [ReST API](https://developers.marketo.com/documentation/rest/). We hebben ook de [SOAP API](https://developers.marketo.com/documentation/soap/) als dat is wat u nodig hebt.

>[!NOTE]
>
>U kunt geen douanedienst tot stand brengen als u het niveau van de Vonk van Marketo hebt.

## Aangepaste service maken {#create-custom-service}

1. Ga naar **Admin** en klik **LaunchPoint**.

   ![](assets/image2014-9-19-10-3a38-3a15.png)

1. Klik onder **Nieuw** op **Nieuwe service**.

   ![](assets/image2014-9-19-10-3a38-3a22.png)

1. Voer een **Weergavenaam** voor de service in. Selecteer **Alleen API Gebruiker** [eerder gemaakt](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md).

   >[!NOTE]
   >
   >Merk op dat wij reeds inheemse integratie voor populaire webinardiensten hebben.

   ![](assets/image2014-9-19-10-3a38-3a32.png)

1. Klik **Maken**.

   ![](assets/image2014-9-19-10-3a39-3a28.png)

   O ja! De dienst wordt nu gecreeerd, gaan vooruit en krijgen alle geloofsbrieven om voor toegang te verstrekken.

## Referenties voor API-toegang {#credentials-for-api-access}

1. Ga naar **Admin** en klik **LaunchPoint**.

   ![](assets/image2014-9-19-10-3a42-3a11.png)

1. Klik **Details weergeven** voor de aangepaste LaunchPoint-service die hierboven is gemaakt.

   ![](assets/image2014-9-19-10-3a42-3a16.png)

1. Klik **Token ophalen**.

   ![](assets/image2014-9-19-10-3a42-3a24.png)

1. Geef **Client ID**, **Client Secret**, **Authorized User** en **Token** op aan de persoon die verantwoordelijk is voor het tot stand brengen van de verbinding.

   ![](assets/image2014-9-19-10-3a42-3a38.png)

>[!CAUTION]
>
>Deze gegevens niet delen; het is de achterdeur naar je data . Houd het veilig!
