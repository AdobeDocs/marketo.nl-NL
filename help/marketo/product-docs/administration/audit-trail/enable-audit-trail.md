---
unique-page-id: 11382122
description: Audittrail inschakelen - Marketo Docs - Productdocumentatie
title: Audittrail inschakelen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 0%

---


# Audittrail inschakelen {#enable-audit-trail}

Audittrail is beschikbaar voor alle klanten en wordt beheerd door twee beheerdersmachtigingen.

>[!NOTE]
>
>Door gebrek, hebben alle systeem admin rollen beide toegelaten toestemmingen.

## Audittrail inschakelen voor een rol {#enable-audit-trail-for-a-role}

1. Klik op **Beheerder**.

   ![](assets/one-2.png)

1. Selecteer **Gebruikers en rollen** en klik op **Rollen**.

   ![](assets/two-2.png)

1. Selecteer de rol waarvoor u Audittrail wilt inschakelen en klik op Rol **** bewerken.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >U hebt hier ook de optie om een nieuwe rol te creëren en het toegang van het Spoor van de Controle te verlenen.

1. Vouw de machtiging **Toegangsbeheer** uit. Selecteer **Access Audit Trail** en/of **Access Login History**, afhankelijk van uw behoeften. Klik op **Opslaan**.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >**Definitie**
   >
   >
   >**Actie audittrail:** Biedt gebruikers toegang tot zowel Asset Audit Trail als Admin Audit Trail.
   >
   >
   >**Aanmeldingsgeschiedenis toegang:** Biedt gebruikers toegang tot de historie [van de](user-login-history.md)gebruikersaanmelding.

## Roll audittrail toewijzen aan een gebruiker {#assign-audit-trail-role-to-a-user}

>[!NOTE]
>
>**Vereisten**
>
>[Maak](http://docs.marketo.com/display/DOCS/Create,+Delete,+Edit+and+Change+a+User+Role#Create,Delete,EditandChangeaUserRole-CreateaRole) of [schakel](#Enable) een bestaande rol in en geef deze de machtigingen Audittrail.

1. Klik in **Gebruikers en rollen** op **Gebruikers**.

   ![](assets/five-1.png)

1. Selecteer de gebruiker u de toegang van het Spoor van de Controle wilt geven tot en de klik **geeft Gebruiker** uit.

   ![](assets/six-1.png)

   >[!NOTE]
   >
   >Dit proces is ook van toepassing wanneer u een nieuwe gebruiker creeert.

1. Selecteer de rollen van het Spoor van de Controle u creeerde. In dit voorbeeld hebben we &quot;Audit Trail - Asset en Admin&quot; en &quot;Audit Trail - With Login History&quot; gemaakt.

   ![](assets/seven-1.png)

   >[!CAUTION]
   >
   >Als u werkruimten hebt ingeschakeld, schakelt u het selectievakje voor de rol in, waarmee alle werkruimten worden geselecteerd. Als u de selectie van een afzonderlijke werkruimte opheft, wordt Audittrail verborgen. Dit betekent u de gegevens van het Spoor van de Controle voor elke werkruimte zult zien. U kunt werkruimten tijdens het [filteren](http://docs.marketo.com/display/DOCS/Filtering+in+Audit+Trail)wel verbergen.

1. Klik op **Opslaan**.

   ![](assets/eight-1.png)

