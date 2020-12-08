---
unique-page-id: 2360350
description: Een aangepaste service maken voor gebruik met de ReST API - Marketo Docs - Productdocumentatie
title: Een aangepaste service maken voor gebruik met de ReST-API
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---


# Een aangepaste service maken voor gebruik met de ReST-API {#create-a-custom-service-for-use-with-rest-api}

Als u met Marketo via de ReST API wilt integreren, zult u een douanedienst willen tot stand brengen. Zo gaat het.

>[!NOTE]
>
>**Vereisten**
>
>* [Een gebruikersrol maken die alleen een API is](../../../product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [Alleen een API-gebruiker maken](../../../product-docs/administration/users-and-roles/create-an-api-only-user.md)

>



>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!NOTE]
>
>**Diep duiken**
>
>Raadpleeg de documentatie van onze ontwikkelaars voor meer informatie over de [ReST API](http://developers.marketo.com/documentation/rest/). We hebben ook de [SOAP API](http://developers.marketo.com/documentation/soap/) als dat is wat u nodig hebt.

>[!NOTE]
>
>U kunt geen douanedienst tot stand brengen als u het niveau van de Vonk van Marketo hebt.

## Aangepaste service maken {#create-custom-service}

1. Ga naar **Admin** en klik **LaunchPoint**.

   ![](assets/image2014-9-19-10-3a38-3a15.png)

1. Klik onder **Nieuw** op **Nieuwe service**.

   ![](assets/image2014-9-19-10-3a38-3a22.png)

1. Voer een **weergavenaam** voor de service in. Selecteer de Gebruiker **van Alleen** API [eerder gecreeerd](../../../product-docs/administration/users-and-roles/create-an-api-only-user.md).

   >[!NOTE]
   >
   >**Herinnering**
   >
   >Merk op dat wij reeds inheemse integratie voor populaire webinardiensten hebben.

   ![](assets/image2014-9-19-10-3a38-3a32.png)

1. Klik op **Maken**.

   ![](assets/image2014-9-19-10-3a39-3a28.png)

   O ja! De dienst wordt nu gecreeerd, gaan vooruit en krijgen alle geloofsbrieven om voor toegang te verstrekken.

## Referenties voor API-toegang {#credentials-for-api-access}

1. Ga naar **Admin** en klik **LaunchPoint**.

   ![](assets/image2014-9-19-10-3a42-3a11.png)

1. Klik op Details **van** weergave voor de hierboven gemaakte aangepaste LaunchPoint-service.

   ![](assets/image2014-9-19-10-3a42-3a16.png)

1. Klik op Token **ophalen**.

   ![](assets/image2014-9-19-10-3a42-3a24.png)

1. Geef de** Client ID**, **Client Secret**, **Authorized User** en **Token** door aan de persoon die verantwoordelijk is voor het tot stand brengen van de verbinding.

   ![](assets/image2014-9-19-10-3a42-3a38.png)

>[!CAUTION]
>
>Deze gegevens niet delen; het is de achterdeur naar je data . Houd het veilig!

