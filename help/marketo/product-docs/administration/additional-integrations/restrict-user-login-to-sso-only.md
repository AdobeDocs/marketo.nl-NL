---
unique-page-id: 2360358
description: Gebruikeraanmelding beperken tot SSO - Marketo Docs - Productdocumentatie
title: Alleen gebruikersaanmelding beperken tot SSO
translation-type: tm+mt
source-git-commit: a7c90193e5c934119fa3b6bdf864d1458d1aad7c
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%

---


# Alleen gebruikersaanmelding beperken tot SSO {#restrict-user-login-to-sso-only}

Als u [SSO](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) gebruikt en gebruikers niet de veiligheid van SSO kunt omzeilen, volg deze instructies.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar **Admin** en klik **Aanmeldingsinstellingen**.

   ![](assets/image2014-9-24-14-3a44-3a40.png)

1. Klik **Beveiligingsinstellingen bewerken**.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. Vouw de geavanceerde instellingen uit, schakel **SSO** vereisen in en klik op **Opslaan**.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!NOTE]
>
>De beste manier is om de gebruiker(s) uit te nodigen en de uitnodiging te accepteren. __ Nadat de uitnodiging is geaccepteerd, moeten beheerders deze instellen op &quot;SSO vereisen&quot;.

>[!TIP]
>
>Als u **SSO** vereist selecteert, kunt u [gebruikersrol](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) van deze beperking uitsluiten door **Enkelvoudige Sign-On** te omzeilen terwijl het plaatsen van de rol. Hierdoor kunnen gebruikers zich normaal aanmelden. Het is bijvoorbeeld mogelijk dat Admin-gebruikers zich nog steeds moeten aanmelden bij Marketo via het aanmeldingsscherm.

>[!CAUTION]
>
>Wanneer nieuwe gebruikers worden uitgenodigd, ontvangen zij uitnodigingse-mails. Nochtans, als **vereist SSO** wordt geselecteerd, zullen zij deze e-mail niet ontvangen, tenzij zij aan een rol worden toegewezen die aan **Enkelvoudige Sign-On** wordt geplaatst om te mijden.

Dat is het! Nu zullen alle gebruikers (behalve gebruikers met toestemming om enig teken-op te mijden) worden beperkt tot het gebruiken van slechts login SSO.

>[!MORELIKETHIS]
>
>* [Eén aanmelding toevoegen aan een portal](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [Een universele id gebruiken voor aanmelding bij een abonnement](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [Marketo-gebruikers uitnodigen voor twee instanties met Universal ID](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)

