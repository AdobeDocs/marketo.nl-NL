---
unique-page-id: 2360207
description: Een gebruiker met alleen een API maken - Marketo Docs - Productdocumentatie
title: Alleen een API-gebruiker maken
exl-id: 23c92255-07a8-41c2-b7b8-8e495d135671
feature: Users and Roles
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 2%

---

# Alleen een API-gebruiker maken {#create-an-api-only-user}

Als u met Marketo wilt integreren via de [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}, moet u een gebruiker met alleen de API maken. Zo gaat het.

>[!IMPORTANT]
>
>Als u alleen API-gebruikers maakt in een abonnement dat is aangemeld bij Identiteit Adobe, zijn de stappen anders en [hier te vinden](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-api-only-user-for-adobe-ims-enabled-subscriptions.md){target="_blank"}.

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

1. Selecteer de **[!UICONTROL API Only]** en controleert de **[!UICONTROL API Only]** selectievakje. Klik op **[!UICONTROL Next]**.

   ![](assets/create-an-api-only-user-5.png)

1. Klik op **[!UICONTROL Send]**.

   ![](assets/create-an-api-only-user-6.png)

>[!NOTE]
>
>In de pop-up staat: &quot;Een uitnodiging is niet alleen vereist voor API,&quot; maar dat betekent niet dat je iets verkeerd hebt gedaan. Het betekent gewoon dat we de rol zullen creëren zonder dat er een uitnodigings-e-mail moet worden verzonden.

Aldus terecht! Laten we nu de aangepaste service maken.

>[!MORELIKETHIS]
>
>[Een aangepaste service maken voor gebruik met REST API](/help/marketo/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api.md){target="_blank"}
