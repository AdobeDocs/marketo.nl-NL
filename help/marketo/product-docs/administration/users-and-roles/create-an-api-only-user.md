---
unique-page-id: 2360207
description: Een gebruiker met alleen een API maken - Marketo Docs - Productdocumentatie
title: Alleen een API-gebruiker maken
exl-id: 23c92255-07a8-41c2-b7b8-8e495d135671
feature: Users and Roles
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 2%

---

# Alleen een API-gebruiker maken {#create-an-api-only-user}

Als u met Marketo via [ REST API ](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api){target="_blank"} wilt integreren, zult u een slechts gebruiker API moeten creëren. Zo gaat het.

>[!IMPORTANT]
>
>Als u API slechts gebruikers in een abonnement creeert dat aan de Identiteit van Adobe is bezet, zijn uw stappen verschillend en [ kan hier ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-api-only-user-for-adobe-ims-enabled-subscriptions.md){target="_blank"} worden gevonden.

>[!PREREQUISITES]
>
>[ creeer een slechtsAPI Rol van de Gebruiker ](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target="_blank"}

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/create-an-api-only-user-1.png)

1. Klik op **[!UICONTROL Users & Roles]**.

   ![](assets/create-an-api-only-user-2.png)

1. Klik op **[!UICONTROL Invite New User]**.

   ![](assets/create-an-api-only-user-3.png)

1. Voer een e-mail, voornaam en achternaam in voor alleen de gebruiker van de API. Klik op **[!UICONTROL Next]**.

   ![](assets/create-an-api-only-user-4.png)

   >[!TIP]
   >
   >Voeg een optionele [!UICONTROL Reason] of een [!UICONTROL Access Expiration] datum toe. De vervaldata van de toegang zijn handig voor kortetermijnwerknemers.

1. Selecteer de **[!UICONTROL API Only]** rol en schakel het selectievakje **[!UICONTROL API Only]** in. Klik op **[!UICONTROL Next]**.

   ![](assets/create-an-api-only-user-5.png)

1. Klik op **[!UICONTROL Send]**.

   ![](assets/create-an-api-only-user-6.png)

>[!NOTE]
>
>In de pop-up staat: &quot;Een uitnodiging is niet alleen vereist voor API,&quot; maar dat betekent niet dat je iets verkeerd hebt gedaan. Het betekent gewoon dat we de rol zullen creëren zonder dat er een uitnodigings-e-mail moet worden verzonden.

Aldus terecht! Laten we nu de aangepaste service maken.

>[!MORELIKETHIS]
>
>[ creeer een Dienst van de Douane voor Gebruik met REST API ](/help/marketo/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api.md){target="_blank"}
