---
unique-page-id: 2360350
description: Een aangepaste service maken voor gebruik met de ReST API - Marketo Docs - Productdocumentatie
title: Een aangepaste service maken voor gebruik met de ReST-API
exl-id: d94f723b-2e98-4350-a9e5-bd57aff2303b
feature: Administration
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 1%

---

# Een aangepaste service maken voor gebruik met de ReST-API {#create-a-custom-service-for-use-with-rest-api}

Als u met Marketo wilt integreren via de ReST API, zult u een douanedienst willen tot stand brengen. Zo gaat het.

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
>Raadpleeg de documentatie van onze ontwikkelaars voor meer informatie over de [ReST-API](https://developers.marketo.com/documentation/rest/). We hebben ook de [SOAP API](https://developers.marketo.com/documentation/soap/) als dat is wat je nodig hebt.

## Aangepaste service maken {#create-custom-service}

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/create-a-custom-service-for-use-with-rest-api-1.png)

1. Klikken **LaunchPoint**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-2.png)

1. Selecteren **[!UICONTROL New]** en vervolgens **[!UICONTROL New Service]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-3.png)

1. Voer een **[!UICONTROL Display Name]** voor de dienst. Selecteer **[!UICONTROL API Only User]** [eerder gemaakt](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md).

   ![](assets/create-a-custom-service-for-use-with-rest-api-4.png)

   >[!NOTE]
   >
   >Merk op dat wij reeds inheemse integratie voor populaire webinardiensten hebben.

1. Klik op **[!UICONTROL Create]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-5.png)

   O ja! De dienst wordt nu gecreeerd, gaan vooruit en krijgen alle geloofsbrieven om voor toegang te verstrekken.

## Referenties voor API-toegang {#credentials-for-api-access}

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/create-a-custom-service-for-use-with-rest-api-6.png)

1. Klik op **[!UICONTROL LaunchPoint]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-7.png)

1. Klikken **[!UICONTROL View Details]** voor de aangepaste [!UICONTROL LaunchPoint] hierboven gemaakte service.

   ![](assets/create-a-custom-service-for-use-with-rest-api-8.png)

1. Klik op **[!UICONTROL Get Token]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-9.png)

1. Geef de **[!UICONTROL Client Id]**, **[!UICONTROL Client Secret]**, **[!UICONTROL Authorized User]**, en **[!UICONTROL Token]** aan de persoon die verantwoordelijk is voor het tot stand brengen van de verbinding.

   ![](assets/create-a-custom-service-for-use-with-rest-api-10.png)

>[!CAUTION]
>
>Deze gegevens niet delen; het is de achterdeur naar je data . Houd het veilig!
