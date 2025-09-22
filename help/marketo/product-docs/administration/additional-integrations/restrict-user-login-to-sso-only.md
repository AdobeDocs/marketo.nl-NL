---
unique-page-id: 2360358
description: Alleen aanmelding door gebruiker beperken tot SSO - Marketo Docs - Productdocumentatie
title: Alleen gebruikersaanmelding beperken tot SSO
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
feature: Administration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---

# Alleen gebruikersaanmelding beperken tot SSO {#restrict-user-login-to-sso-only}

Als u [ SSO ](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) gebruikt en gebruikers wilt verzekeren kan niet de veiligheid omzeilen SSO, deze instructies volgen.

>[!IMPORTANT]
>
>Dit artikel is niet op [ toe:laten 1} Marketo abonnementen van Adobe IMS {van toepassing.](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md)

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/restrict-user-login-to-sso-only-1.png)

1. Klik op **[!UICONTROL Login Settings]**.

   ![](assets/restrict-user-login-to-sso-only-2.png)

1. Klik op **[!UICONTROL Edit Security Settings]**.

   ![](assets/restrict-user-login-to-sso-only-3.png)

1. Vouw de **[!UICONTROL Advanced]** -instellingen uit, controleer **[!UICONTROL Require SSO]** en klik op **[!UICONTROL Save]** .

![](assets/restrict-user-login-to-sso-only-4.png)

>[!NOTE]
>
>De beste manier is om de gebruiker(s) uit te nodigen en de uitnodiging te accepteren. _nadat_ de uitnodiging wordt goedgekeurd, zouden Admins hen dan aan &quot;[!UICONTROL Require SSO]&quot; moeten plaatsen.

>[!TIP]
>
>Als u **[!UICONTROL Require SSO]** selecteert, kunt u a [ gebruikersrol ](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) van deze beperking uitsluiten door de **[!UICONTROL Bypass Single Sign-On]** optie te controleren terwijl vestiging de rol. Hierdoor kunnen gebruikers zich normaal aanmelden. Het is bijvoorbeeld mogelijk dat Admin-gebruikers zich nog steeds via het aanmeldingsscherm moeten aanmelden bij Marketo. Als zowel SSO als Universal ID zijn ingeschakeld, moet u de machtiging Enkelvoudige aanmelding omzeilen hebben ingesteld om te kunnen schakelen tussen abonnementen.

>[!CAUTION]
>
>Wanneer nieuwe gebruikers worden uitgenodigd, ontvangen zij uitnodigingse-mails. Als **[!UICONTROL Require SSO]** echter is geselecteerd, ontvangen deze geen e-mailberichten, tenzij ze zijn toegewezen aan een rol die is ingesteld op **[!UICONTROL Bypass Single Sign-On]** .

Dat is het! Nu zullen alle gebruikers (behalve gebruikers met toestemming om enig teken-op te mijden) worden beperkt tot het gebruiken van slechts login SSO.

>[!MORELIKETHIS]
>
>* [ voeg Enige Sign-On aan een Portaal ](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) toe
>* [ Gebruikend een Universele identiteitskaart voor de Login van het Abonnement ](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [ het Uitnodigen van de Gebruikers van Marketo aan Twee Instanties met Universele identiteitskaart ](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)
