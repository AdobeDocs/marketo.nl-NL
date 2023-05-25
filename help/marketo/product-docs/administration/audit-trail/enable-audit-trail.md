---
unique-page-id: 11382122
description: Audittrail inschakelen - Marketo Docs - Productdocumentatie
title: Audittrail inschakelen
exl-id: 3ab2d7b2-1be1-4b3f-a9cc-d3edfa963679
source-git-commit: 81ee349dbbe48c70b040751cae750c3684b71c78
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 1%

---

# Audittrail inschakelen {#enable-audit-trail}

Audittrail is beschikbaar voor alle klanten en wordt beheerd door twee beheerdersmachtigingen.

>[!NOTE]
>
>Door gebrek, hebben alle systeem admin rollen beide toegelaten toestemmingen.

## Audittrail inschakelen voor een rol {#enable-audit-trail-for-a-role}

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/enable-audit-trail-1.png)

1. Selecteren **[!UICONTROL Users & Roles]** en klik op **[!UICONTROL Roles]**.

   ![](assets/enable-audit-trail-2.png)

1. Selecteer de rol waarvoor u Audittrail wilt inschakelen en klik op **[!UICONTROL Edit Role]**.

   ![](assets/enable-audit-trail-3.png)

   >[!NOTE]
   >
   >U hebt hier ook de optie om een nieuwe rol te creëren en het toegang van het Spoor van de Controle te verlenen.

1. Breid uit **[!UICONTROL Access Admin]** toestemming. Selecteren **[!UICONTROL Access Audit Trail]** en/of **[!UICONTROL Access Login History]**, afhankelijk van uw behoeften. Klik op **[!UICONTROL Save]**.

   ![](assets/enable-audit-trail-4.png)

   >[!NOTE]
   >
   >**Definitie**
   >
   >**[!UICONTROL Access Audit Trail]**: Biedt gebruikers toegang tot beide [!UICONTROL Asset Audit Trail] en [!UICONTROL Admin Audit Trail].
   >
   >**[!UICONTROL Access Login History]**: Biedt gebruikers toegang tot [Aanmeldingsgeschiedenis gebruiker](/help/marketo/product-docs/administration/audit-trail/user-login-history.md).

## Roll audittrail toewijzen aan een gebruiker {#assign-audit-trail-role-to-a-user}

>[!PREREQUISITES]
>
>[Maken](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md#create-a-role) of [enable](#enable-audit-trail) een bestaande rol, die het toestemmingen van het Trail van de Controle geeft.

1. In **[!UICONTROL Users & Roles]**, klikt u op **[!UICONTROL Users]**.

   ![](assets/enable-audit-trail-5.png)

1. Selecteer de gebruiker tot u de toegang van het Spoor van de Controle wilt geven en klikken **[!UICONTROL Edit User]**.

   ![](assets/enable-audit-trail-6.png)

   >[!NOTE]
   >
   >Dit proces is ook van toepassing wanneer u een nieuwe gebruiker creeert.

1. Selecteer de rollen van het Spoor van de Controle u creeerde. In dit voorbeeld hebben we &quot;Audit Trail - Asset en Admin&quot; en &quot;Audit Trail - With Login History&quot; gemaakt.

   ![](assets/enable-audit-trail-7.png)

   >[!CAUTION]
   >
   >Als u werkruimten hebt ingeschakeld, schakelt u het selectievakje voor de rol in, waarmee alle werkruimten worden geselecteerd. Als u de selectie van een afzonderlijke werkruimte opheft, wordt Audittrail verborgen. Dit betekent u de gegevens van het Spoor van de Controle voor elke werkruimte zult zien. U kunt werkruimten desgewenst verbergen wanneer [filteren](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md).

1. Klik op **[!UICONTROL Save]**.

   ![](assets/enable-audit-trail-8.png)
