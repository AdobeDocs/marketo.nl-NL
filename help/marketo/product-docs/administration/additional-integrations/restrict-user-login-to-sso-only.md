---
unique-page-id: 2360358
description: Alleen aanmelding door gebruiker beperken tot SSO - Marketo Docs - Productdocumentatie
title: Alleen gebruikersaanmelding beperken tot SSO
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
source-git-commit: 5dcaf886c488e5e1b7fd1c4caa5f869e70c6fb18
workflow-type: tm+mt
source-wordcount: '232'
ht-degree: 0%

---

# Alleen gebruikersaanmelding beperken tot SSO {#restrict-user-login-to-sso-only}

Als je [SSO gebruiken](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) en willen ervoor zorgen dat gebruikers de SSO-beveiliging niet kunnen omzeilen, volgt u deze instructies.

>[!IMPORTANT]
>
>Dit artikel is niet van toepassing op [Adobe IMS ingeschakeld](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md) Marketo-abonnementen.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar **Beheer** en klik op **Aanmeldingsinstellingen**.

   ![](assets/image2014-9-24-14-3a44-3a40.png)

1. Klikken **Beveiligingsinstellingen bewerken**.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. Vouw de geavanceerde instellingen uit, schakel **SSO vereist** en klik op **Opslaan**.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!NOTE]
>
>De beste manier is om de gebruiker(s) uit te nodigen en de uitnodiging te accepteren. _Na_ Als de uitnodiging is geaccepteerd, dienen beheerders deze in te stellen op &quot;SSO vereisen&quot;.

>[!TIP]
>
>Als u **SSO vereist**, kunt u een [gebruikersrol](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) van deze beperking door **Single Sign-On omzeilen** tijdens het instellen van de rol. Hierdoor kunnen gebruikers zich normaal aanmelden. Admin-gebruikers moeten zich bijvoorbeeld nog steeds via het aanmeldingsscherm aanmelden bij Marketo.

>[!CAUTION]
>
>Als nieuwe gebruikers worden uitgenodigd, ontvangen ze e-mailuitnodigingen. Als **SSO vereist** is geselecteerd, ontvangen ze deze e-mailberichten niet, tenzij ze zijn toegewezen aan een rol die is ingesteld op **Single Sign-On omzeilen**.

Dat is het! Nu zullen alle gebruikers (behalve gebruikers met toestemming om enig teken-op te mijden) worden beperkt tot het gebruiken van slechts login SSO.

>[!MORELIKETHIS]
>
>* [Eén aanmelding toevoegen aan een portal](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [Een universele id gebruiken voor aanmelding bij een abonnement](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [Marketo-gebruikers uitnodigen voor twee instanties met Universal ID](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)

