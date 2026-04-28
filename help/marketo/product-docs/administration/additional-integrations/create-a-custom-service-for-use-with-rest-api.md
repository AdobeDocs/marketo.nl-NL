---
unique-page-id: 2360350
description: Maak een aangepaste LaunchPoint-service die is gekoppeld aan een gebruiker met alleen een API voor integratie met de ReST API.
title: Een aangepaste service maken voor gebruik met ReST API
exl-id: d94f723b-2e98-4350-a9e5-bd57aff2303b
feature: Administration
source-git-commit: 40f06a5391f2f7263bea0c5b8cefc1f3a607c68c
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 2%

---

# Een aangepaste service maken voor gebruik met ReST API {#create-a-custom-service-for-use-with-rest-api}

Als u met Marketo wilt integreren via de ReST-API, maakt u een aangepaste service.

>[!PREREQUISITES]
>
>* [ creeer een slechtsAPI Rol van de Gebruiker ](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [ creeer een slechts Gebruiker API ](/help/marketo/product-docs/administration/users-and-roles/create-api-only-user.md)
>

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!TIP]
>
>Zie de documentatie van Ontwikkelaars voor details op [ REST API ](https://developer.adobe.com/marketo-apis/).

## Aangepaste service maken {#create-custom-service}

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/create-a-custom-service-for-use-with-rest-api-1.png)

1. Klik op **[!UICONTROL LaunchPoint]** .

   ![](assets/create-a-custom-service-for-use-with-rest-api-2.png)

1. Selecteer **[!UICONTROL New]** en vervolgens **[!UICONTROL New Service]** .

   ![](assets/create-a-custom-service-for-use-with-rest-api-3.png)

1. Voer een **[!UICONTROL Display Name]** in voor de service. Selecteer **[!UICONTROL API Only User]** [ eerder gecreeerd ](/help/marketo/product-docs/administration/users-and-roles/create-api-only-user.md).

   ![](assets/create-a-custom-service-for-use-with-rest-api-4.png)

1. Klik op **[!UICONTROL Create]** .

   ![](assets/create-a-custom-service-for-use-with-rest-api-5.png)

   De service wordt nu gemaakt. Haal de referenties op om toegang te verlenen.

## Referenties voor API-toegang {#credentials-for-api-access}

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/create-a-custom-service-for-use-with-rest-api-6.png)

1. Klik op **[!UICONTROL LaunchPoint]** .

   ![](assets/create-a-custom-service-for-use-with-rest-api-7.png)

1. Klik op **[!UICONTROL View Details]** voor de aangepaste [!UICONTROL LaunchPoint] -service die hierboven is gemaakt.

   ![](assets/create-a-custom-service-for-use-with-rest-api-8.png)

1. Klik op **[!UICONTROL Get Token]** .

   ![](assets/create-a-custom-service-for-use-with-rest-api-9.png)

1. Geef **[!UICONTROL Client Id]**, **[!UICONTROL Client Secret]**, **[!UICONTROL Authorized User]** en **[!UICONTROL Token]** door aan de persoon die verantwoordelijk is voor het tot stand brengen van de verbinding.

   ![](assets/create-a-custom-service-for-use-with-rest-api-10.png)

>[!CAUTION]
>
>Deel deze informatie niet, omdat deze toegang biedt tot uw gegevens.
