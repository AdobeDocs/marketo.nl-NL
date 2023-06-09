---
unique-page-id: 2360207
description: Een gebruiker met alleen een API maken - Marketo Docs - Productdocumentatie
title: Alleen een API-gebruiker maken
exl-id: 23c92255-07a8-41c2-b7b8-8e495d135671
source-git-commit: 2d28d4b473815952231356691b1e9310c61a20f1
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 3%

---

# Alleen een API-gebruiker maken {#create-an-api-only-user}

Als u met Marketo wilt integreren via de [REST API](https://developers.marketo.com/documentation/rest/){target="_blank"}, moet u een gebruiker met alleen de API maken. Zo gaat het.

>[!PREREQUISITES]
>
>[Een gebruikersrol maken die alleen een API is](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target="_blank"}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/create-an-api-only-user-1.png)

1. Klik op **[!UICONTROL Users & Roles]**.

   ![](assets/create-an-api-only-user-2.png)

1. Klik op **[!UICONTROL Invite New User]**.

   ![](assets/create-an-api-only-user-3.png)

1. Voer een e-mail, voornaam en achternaam in voor alleen de gebruiker van de API. Klik op **[!UICONTROL Next]**.

   ![](assets/create-an-api-only-user-4.png)

   >[!TIP]
   >
   >Voeg een optionele reden of een vervaldatum toe. De vervaldata van de toegang zijn handig voor kortetermijnwerknemers.

1. Selecteer **[!UICONTROL API Only]** en controleert de **[!UICONTROL API Only]** selectievakje. Klik op **[!UICONTROL Next]**.

   ![](assets/create-an-api-only-user-5.png)

1. Klik op **[!UICONTROL Send]**.

   ![](assets/create-an-api-only-user-6.png)

>[!NOTE]
>
>In de pop-up staat: &quot;Een uitnodiging is niet alleen vereist voor API,&quot; maar dat betekent niet dat je iets verkeerd hebt gedaan. Het betekent gewoon dat we de rol zullen creëren zonder dat er een uitnodigings-e-mail moet worden verzonden.

Aldus terecht! Laten we nu de aangepaste service maken.

>[!MORELIKETHIS]
>
>[Een aangepaste service maken voor gebruik met de ReST-API](/help/marketo/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api.md){target="_blank"}
