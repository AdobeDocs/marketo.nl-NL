---
unique-page-id: 2360350
description: Een aangepaste service maken voor gebruik met de ReST API - Marketo Docs - Productdocumentatie
title: Een aangepaste service maken voor gebruik met ReST API
exl-id: d94f723b-2e98-4350-a9e5-bd57aff2303b
feature: Administration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '182'
ht-degree: 2%

---

# Een aangepaste service maken voor gebruik met ReST API {#create-a-custom-service-for-use-with-rest-api}

Als u met Marketo wilt integreren via de ReST API, zult u een douanedienst willen tot stand brengen. Zo gaat het.

>[!PREREQUISITES]
>
>* [&#x200B; creeer een slechtsAPI Rol van de Gebruiker &#x200B;](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [&#x200B; creeer een slechts Gebruiker API &#x200B;](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md)
>

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!TIP]
>
>Controle uit onze ontwikkelaarsdocumentatie voor details op [&#x200B; REST API &#x200B;](https://developer.adobe.com/marketo-apis/). Wij hebben ook [&#x200B; SOAP API &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/soap/soap-api) als dat is wat u nodig hebt.

## Aangepaste service maken {#create-custom-service}

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/create-a-custom-service-for-use-with-rest-api-1.png)

1. Klik op **[!UICONTROL LaunchPoint]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-2.png)

1. Selecteer **[!UICONTROL New]** en vervolgens **[!UICONTROL New Service]** .

   ![](assets/create-a-custom-service-for-use-with-rest-api-3.png)

1. Voer een **[!UICONTROL Display Name]** in voor de service. Selecteer **[!UICONTROL API Only User]** [&#x200B; eerder gecreeerd &#x200B;](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md).

   ![](assets/create-a-custom-service-for-use-with-rest-api-4.png)

   >[!NOTE]
   >
   >Merk op dat wij reeds inheemse integratie voor populaire webinardiensten hebben.

1. Klik op **[!UICONTROL Create]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-5.png)

   O ja! De dienst wordt nu gecreeerd, gaan vooruit en krijgen alle geloofsbrieven om voor toegang te verstrekken.

## Referenties voor API-toegang {#credentials-for-api-access}

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/create-a-custom-service-for-use-with-rest-api-6.png)

1. Klik op **[!UICONTROL LaunchPoint]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-7.png)

1. Klik op **[!UICONTROL View Details]** voor de aangepaste [!UICONTROL LaunchPoint] -service die hierboven is gemaakt.

   ![](assets/create-a-custom-service-for-use-with-rest-api-8.png)

1. Klik op **[!UICONTROL Get Token]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-9.png)

1. Geef **[!UICONTROL Client Id]**, **[!UICONTROL Client Secret]**, **[!UICONTROL Authorized User]** en **[!UICONTROL Token]** door aan de persoon die verantwoordelijk is voor het tot stand brengen van de verbinding.

   ![](assets/create-a-custom-service-for-use-with-rest-api-10.png)

>[!CAUTION]
>
>Deel deze informatie niet; het is de achterdeur naar je gegevens. Houd het veilig!
