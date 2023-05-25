---
unique-page-id: 2360358
description: Alleen aanmelding door gebruiker beperken tot SSO - Marketo Docs - Productdocumentatie
title: Alleen gebruikersaanmelding beperken tot SSO
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
source-git-commit: 1f10e1fcdbd5cf91481f749236fd37050ade29f8
workflow-type: tm+mt
source-wordcount: '212'
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

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/restrict-user-login-to-sso-only-1.png)

1. Klikken **[!UICONTROL Login Setting]s**.

   ![](assets/restrict-user-login-to-sso-only-2.png)

1. Klik op **[!UICONTROL Edit Security Settings]**.

   ![](assets/restrict-user-login-to-sso-only-3.png)

1. Breid uit **[!UICONTROL Advanced]** instellingen, controleren **[!UICONTROL Require SSO]** en klik op **[!UICONTROL Save]**.

![](assets/restrict-user-login-to-sso-only-4.png)

>[!NOTE]
>
>De beste manier is om de gebruiker(s) uit te nodigen en de uitnodiging te accepteren. _Na_ de uitnodiging is geaccepteerd, dienen beheerders deze in te stellen op &quot;[!UICONTROL Require SSO].&quot;

>[!TIP]
>
>Als u **[!UICONTROL Require SSO]**, kunt u een [gebruikersrol](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) van deze beperking door **[!UICONTROL Bypass Single Sign-On]** tijdens het instellen van de rol. Hierdoor kunnen gebruikers zich normaal aanmelden. Admin-gebruikers moeten zich bijvoorbeeld nog steeds via het aanmeldingsscherm aanmelden bij Marketo.

>[!CAUTION]
>
>Als nieuwe gebruikers worden uitgenodigd, ontvangen ze e-mailuitnodigingen. Als **[!UICONTROL Require SSO]** is geselecteerd, ontvangen ze deze e-mailberichten niet, tenzij ze zijn toegewezen aan een rol die is ingesteld op **[!UICONTROL Bypass Single Sign-On]**.

Dat is het! Nu zullen alle gebruikers (behalve gebruikers met toestemming om enig teken-op te mijden) worden beperkt tot het gebruiken van slechts login SSO.

>[!MORELIKETHIS]
>
>* [Eén aanmelding toevoegen aan een portal](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [Een universele id gebruiken voor aanmelding bij een abonnement](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [Marketo-gebruikers uitnodigen voor twee instanties met Universal ID](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)

