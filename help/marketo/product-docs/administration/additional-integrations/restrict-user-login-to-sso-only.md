---
unique-page-id: 2360358
description: Gebruikeraanmelding beperken tot SSO - Marketo Docs - Productdocumentatie
title: Alleen gebruikersaanmelding beperken tot SSO
translation-type: tm+mt
source-git-commit: c33b7ab59e612f37d3f64bb954579700dc574068
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---


# Alleen gebruikersaanmelding beperken tot SSO {#restrict-user-login-to-sso-only}

Als u SSO [](add-single-sign-on-to-a-portal.md) gebruikt en gebruikers niet de veiligheid van SSO wilt omzeilen, volg deze instructies.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar Beheer en klik op Aanmeldingsinstellingen.

![](assets/image2014-9-24-14-3a44-3a40.png)

1. Klik op Beveiligingsinstellingen bewerken.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. Vouw de geavanceerde instellingen uit, schakel SSO vereisen in en klik op Opslaan.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!TIP]
>
>Als u SSO **** vereisen selecteert, kunt u een [gebruikersrol](../../../product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) van deze beperking uitsluiten door de **optie Afmelden bij** enkele aanmelding omzeilen tijdens het instellen van de rol te controleren. Hierdoor kunnen gebruikers zich normaal aanmelden. Het is bijvoorbeeld mogelijk dat Admin-gebruikers zich nog steeds moeten aanmelden bij Marketo via het aanmeldingsscherm.

>[!CAUTION]
>
>Wanneer nieuwe gebruikers worden uitgenodigd, ontvangen zij uitnodigingse-mails. Als SSO **** vereisen is geselecteerd, ontvangen ze deze e-mails echter niet, tenzij ze zijn toegewezen aan een rol die is ingesteld op Single Sign-On **** omzeilen.

Dat is het! Nu zullen alle gebruikers (behalve gebruikers met toestemming om enig teken-op te mijden) worden beperkt tot het gebruiken van slechts login SSO.