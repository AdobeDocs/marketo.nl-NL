---
unique-page-id: 2360358
description: Gebruikeraanmelding beperken tot SSO - Marketo Docs - Productdocumentatie
title: Alleen gebruikersaanmelding beperken tot SSO
translation-type: tm+mt
source-git-commit: 78961a3e163ce903facf955a9dda6909b5e85bad
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---


# Alleen gebruikersaanmelding beperken tot SSO {#restrict-user-login-to-sso-only}

Als u [SSO](add-single-sign-on-to-a-portal.md) gebruikt en gebruikers niet de veiligheid van SSO kunt omzeilen, volg deze instructies.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar **Admin** en klik **Aanmeldingsinstellingen**.

![](assets/image2014-9-24-14-3a44-3a40.png)

1. Klik **Beveiligingsinstellingen bewerken**.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. Vouw de geavanceerde instellingen uit, schakel **SSO** vereisen in en klik op **Opslaan**.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!TIP]
>
>Als u **SSO** vereist selecteert, kunt u [gebruikersrol](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) van deze beperking uitsluiten door **Enkelvoudige Sign-On** te omzeilen terwijl het plaatsen van de rol. Hierdoor kunnen gebruikers zich normaal aanmelden. Het is bijvoorbeeld mogelijk dat Admin-gebruikers zich nog steeds moeten aanmelden bij Marketo via het aanmeldingsscherm.

>[!CAUTION]
>
>Wanneer nieuwe gebruikers worden uitgenodigd, ontvangen zij uitnodigingse-mails. Nochtans, als **vereist SSO** wordt geselecteerd, zullen zij deze e-mail niet ontvangen, tenzij zij aan een rol worden toegewezen die aan **Enkelvoudige Sign-On** wordt geplaatst om te mijden.

Dat is het! Nu zullen alle gebruikers (behalve gebruikers met toestemming om enig teken-op te mijden) worden beperkt tot het gebruiken van slechts login SSO.
