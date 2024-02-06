---
unique-page-id: 2360297
description: Marketo-aanmeldingen beperken op basis van IP - Marketo Docs - Productdocumentatie
title: Marketo-aanmeldingen beperken op basis van IP
exl-id: 5d9d0b88-b4bc-4e1b-b70c-2c2e7b4269f5
feature: Administration
source-git-commit: b4bd06d3e5ee205744478e0f5556f490f9f5abe4
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 1%

---

# Marketo-aanmeldingen beperken op basis van IP {#restrict-marketo-logins-based-on-ip}

U kunt gebruikers beperken of toestaan om tot Marketo toegang te hebben die op hun IP adressen wordt gebaseerd. Zo gaat het.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!IMPORTANT]
>
>De informatie in dit artikel is bedoeld voor gebruikers die zich rechtstreeks aanmelden op login.marketo.com en is niet van toepassing op gebruikers die zich verifiëren met Adobe ID. Het is niet mogelijk om IP beperkingen op enige sign-on (SSO) logins op dit ogenblik af te dwingen.

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/restrict-marketo-logins-based-on-ip-1.png)

1. Klik op **[!UICONTROL Login Settings]**.

   ![](assets/restrict-marketo-logins-based-on-ip-2.png)

1. Klik op **[!UICONTROL Edit IP Restrictions]**.

   ![](assets/restrict-marketo-logins-based-on-ip-3.png)

1. Kies of u wilt **Toestaan** of **Blok** specifieke adressen, ga het adres(sen) in, dan klik **[!UICONTROL Save]**.

   >[!NOTE]
   >
   >**Definitie**
   >
   >* **[!UICONTROL Allowed IP addresses]**: Het toevoegen van toegestane IP-adressen is inclusief. Het zal alle IP gespecificeerde adressen omvatten en zal alles anders uitsluiten.
   >* **[!UICONTROL Block IP addresses]**: Voorkomt dat specifieke IP&#39;s toegang krijgen tot Marketo.
   >* **[!UICONTROL Disable IP Restrictions]**: Als u dit inschakelt, werken er geen/alle beperkingsregels meer. Gebruik dit voor testdoeleinden.

   >[!NOTE]
   >
   >U kunt meerdere beperkingen toevoegen, maar deze kunnen ALLES zijn toegestaan of ALLES geblokkeerd. Je kunt niet mixen en overeenkomen met toegestaan en geblokkeerd.

   ![](assets/restrict-marketo-logins-based-on-ip-4.png)

   Je marketinggegevens zijn nu veiliger dan ooit!
