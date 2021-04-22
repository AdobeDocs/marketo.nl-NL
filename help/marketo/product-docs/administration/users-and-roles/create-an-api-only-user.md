---
unique-page-id: 2360207
description: Een gebruiker met alleen een API maken - Marketo Docs - Productdocumentatie
title: Alleen een API-gebruiker maken
exl-id: 23c92255-07a8-41c2-b7b8-8e495d135671
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '163'
ht-degree: 0%

---

# Alleen een API-gebruiker maken {#create-an-api-only-user}

Als u met Marketo via [REST API](https://developers.marketo.com/documentation/rest/) wilt integreren, zult u een slechts gebruiker moeten creëren API. Zo gaat het.

>[!PREREQUISITES]
>
>[Een gebruikersrol maken die alleen een API is](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Klik onder **Admin** op **Gebruikers en rollen.**

   ![](assets/image2014-9-17-9-3a31-3a31.png)

1. Klik **Nieuwe gebruiker uitnodigen**.

   ![](assets/image2014-9-17-9-3a32-3a3.png)

1. Voer een e-mail, voornaam en achternaam in voor alleen de gebruiker van de API. Klik **Volgende**.

   ![](assets/image2016-5-24-10-3a53-3a7.png)

   >[!TIP]
   >
   >Voeg een optionele reden of een vervaldatum toe. De vervaldata van de toegang zijn handig voor kortetermijnwerknemers.

1. Selecteer de rol **Alleen API** en schakel het selectievakje **Alleen API** in. Klik **Volgende**.

   ![](assets/four.png)

1. Klik **Send**.

   ![](assets/image2016-5-24-11-3a8-3a20.png)

>[!NOTE]
>
>In de pop-up staat: &quot;Een uitnodiging is niet alleen vereist voor API,&quot; maar dat betekent niet dat je iets verkeerd hebt gedaan. Het betekent gewoon dat we de rol maken zonder dat er een uitnodigings-e-mail moet worden verzonden.

Aldus terecht! Laten we nu de aangepaste service maken.

>[!MORELIKETHIS]
>
>[Een aangepaste service maken voor gebruik met de ReST-API](/help/marketo/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api.md)
