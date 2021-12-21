---
description: Beheerdershandleiding voor MSI-handelingen - Marketo Docs - Productdocumentatie
title: Beheerdershandleiding voor MSI-handelingen
hide: true
hidefromtoc: true
source-git-commit: 9ee07611ffae25fea4bffa3124927083bf187ddd
workflow-type: tm+mt
source-wordcount: '509'
ht-degree: 0%

---

# Beheerdershandleiding voor MSI-handelingen {#msi-actions-admin-guide}

>[!PREREQUISITES]
>
>* Bevestig met uw manager van het Succes van de Klant dat de Acties MSI voor uw Marketo- Rekening is toegelaten (als u geen CSM hebt) [contactondersteuning](https://nation.marketo.com/t5/support/ct-p/Support)).
>* Uw Marketo/Salesforce-synchronisatie moet zijn ingesteld.


<table>
 <tr>
  <th>Persona</th>
  <th>Stap</th>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Marketo-verkoopaccount instellen</td>
 </tr>
 <tr>
  <td>Marketo Admin of <br/>Salesforce Admin</td>
  <td>Marketo-verkoopaccount verbinden met Salesforce</td>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Marketo-verkoopaccount verbinden met Marketo</td>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Gegevenssynchronisatie starten van Marketo naar Marketo Sales Account</td>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Gebruikers uitnodigen voor MSI-handelingen</td>
 </tr>
 <tr>
  <td>Salesforce Admin</td>
  <td>MSI-pakket installeren/upgraden in Salesforce</td>
 </tr>
 <tr>
  <td>Salesforce Admin</td>
  <td>MSI-acties configureren in Salesforce</td>
 </tr>
</table>

## Marketo-verkoopaccount instellen {#set-up-marketo-sales-account}

1. Klik in Marketo op **Beheer**.

PICC

1. Klikken **Verkoopoverzicht** vervolgens **Handelingen configureren**. Kiezen uit een lijst met Marketo-beheerders die u wilt uitnodigen en klikken **Uitnodiging verzenden**.

PICC

De gebruiker zal een e-mail met stappen ontvangen om toegang tot de rekening te krijgen.

>[!NOTE]
>
>Extra gebruikers worden niet toegevoegd via Marketo en worden toegevoegd via de pagina Gebruikersbeheer van verkoopaccount. [Klik hier](/help/marketo/product-docs/marketo-sales-connect/admin/invite-users.md) voor meer informatie over het toevoegen van extra gebruikers.

## Marketo-verkoopaccount verbinden met Salesforce {#connect-marketo-sales-account-to-salesforce}

1. Klik in je Marketo Sales-account op het tandwielpictogram en selecteer **Instellingen**.

PICC

1. Klik onder Beheerinstellingen op **Salesforce**.

PICC

1. Klik op het tabblad Verbindingen en aanpassingen op **Verbinden**.

PICC

1. Klikken **OK**.

PICC

Als u al bent aangemeld bij Salesforce, hebt u verbinding. Als dat niet het geval is, wordt u gevraagd u aan te melden.

## Marketo verbinden met uw account voor verkoopapps {#connect-marketo-to-your-sales-apps-account}

1. Klik in je Marketo Sales-account op het tandwielpictogram en selecteer **Instellingen**.

PICC

1. Klik onder Beheerinstellingen op **Marketo**.

PICC

1. Klikken **verbinden**. Uw account wordt dan verbonden.

>[!NOTE]
>
>Als er geen verbinding wordt gemaakt, kopieert u de gegevens van het Marketo Sales Insight-tabblad &quot;Actions Config&quot; en plakt u deze op het tabblad Set-up.

## Gegevenssynchronisatie starten {#initiate-data-sync}

1. Klik in Marketo op Beheer.

PICC

1. Klik het Inzicht van de Verkoop, dan Config van Acties.

PICC

1. Klik op de synchronisatiekaart van het veld Handeling op **Synchroniseren**.

PICC

1. U ziet een voorvertoning van de velden die worden gesynchroniseerd. Klikken **Synchronisatie starten**.

PICC

Persoonlijke gegevens die in Marketo en Salesforce bestaan, worden gesynchroniseerd met je Marketo Sales Apps-account.

## Individuele gebruikers uitnodigen voor MSI-handelingen {#invite-individual-users-to-msi-actions}

1. Klik in je Marketo Sales-account op het tandwielpictogram en selecteer **Instellingen**.

PICC

1. Selecteer onder Beheerinstellingen de optie **Gebruikersbeheer**.

PICC

1. Klikken **Handelingen** en selecteert u **Gebruikers uitnodigen**.

PICC

1. Voer het e-mailadres of de e-mailadressen in en klik op **Uitnodigen**.

>[!NOTE]
>
>Door gebrek, zullen alle nieuwe leden aan het Iedereen team worden toegevoegd.

Je ontvangt een bevestigingsbericht.

## Gebruikers via CSV uitnodigen voor MSI-handelingen {#invite-users-via-csv-to-msi-actions}

1. Klik in je Marketo Sales-account op het tandwielpictogram en selecteer **Instellingen**.

PICC

1. Selecteer onder Beheerinstellingen de optie **Gebruikersbeheer**.

PICC

1. Klikken **Handelingen** en selecteert u **Gebruikers uitnodigen via CSV**.

PICC

1. Blader naar de CSV op uw computer, selecteer deze en klik op **Volgende**.

PICC

1. Controleer of de velden correct zijn toegewezen en klik op **Uitnodigen**.

PICC

U zult een bevestigingsbericht ontvangen zodra de uitnodigingen worden verzonden.

>[!NOTE]
>
>Als dit is gebeurd, kunt u een upgrade uitvoeren van het bestaande MSI-pakket of een nieuw MSI-pakket installeren en doorgaan naar [MSI-handelingen configureren in Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/salesforce-configuration/msi-actions-configuration-in-salesforce.md).
