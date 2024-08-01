---
description: Handelingen Admin Setup-handleiding voor het toezicht op de verkoop - Marketo Docs - Productdocumentatie
title: Handleiding voor installatie van Admin Setup voor het inzicht in verkoop
exl-id: 339d518d-445b-4634-ab81-92c9d5541927
feature: Sales Insight Actions
source-git-commit: 1f228323c18204149630a7cb77d6ae0a88b425e3
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

---

# Handleiding voor installatie van Admin Setup voor het inzicht in verkoop {#sales-insight-actions-admin-setup-guide}

>[!NOTE]
>
>De Acties van het Inzicht van de Verkoop van Marketo is een web-based toepassing die exclusief met Salesforce CRM via het [ pakket van het Inzicht van de Verkoop van Marketo ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"} integreert. Het wordt soms bedoeld als &quot;Verkoop van Marketo,&quot;of eenvoudig &quot;Acties.&quot;

>[!PREREQUISITES]
>
>* Bevestig met het Team van de Rekening van de Adobe (uw Manager van de Rekening) dat de Acties MSI voor uw Rekening van het Marketo Engage zijn toegelaten (als u geen Manager van de Rekening hebt, contacteer [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support) {target="_blank"}).
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
  <td>Marketo Admin of <br/> Salesforce Admin</td>
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

1. In Marketo, klik **Admin**.

   ![](assets/msi-actions-admin-guide-1.png)

   >[!NOTE]
   >
   >Als u geen identiteitskaart van de Cliënt en Geheim van de Cliënt op de kaart van de Informatie van de Integratie ziet, activeer uw instantie van Acties door de eerste gebruiker uit te nodigen, en u zult Cliënt ID en Geheim verschijnen Cliënt zien.

1. Klik **Inzicht van de Verkoop**, toen **Config van Acties**. Selecteer van een lijst van beheerders van Marketo om uit te nodigen en te klikken **verzendt Uitnodiging**.

   ![](assets/msi-actions-admin-guide-2.png)

De gebruiker zal een e-mail met stappen ontvangen om toegang tot de rekening te krijgen.

>[!NOTE]
>
>Extra gebruikers worden niet toegevoegd via Marketo en worden toegevoegd via de pagina Gebruikersbeheer van verkoopaccount. [ klik hier ](/help/marketo/product-docs/marketo-sales-connect/admin/invite-users.md){target="_blank"} om meer over het toevoegen van extra gebruikers te leren.

## Marketo-verkoopaccount verbinden met Salesforce {#connect-marketo-sales-account-to-salesforce}

1. In uw rekening van de Verkoop van Marketo, klik het tandwielpictogram en selecteer **Montages**.

   ![](assets/msi-actions-admin-guide-3.png)

1. Onder Montages Admin, klik **Salesforce**.

   ![](assets/msi-actions-admin-guide-4.png)

1. In het lusje van Verbindingen &amp; van Aanpassingen, klik **verbinden**.

   ![](assets/msi-actions-admin-guide-5.png)

1. Klik **OK**.

   ![](assets/msi-actions-admin-guide-6.png)

Als u al bij Salesforce bent aangemeld, hebt u verbinding. Als je dat niet bent, wordt je gevraagd je aan te melden.

## Marketo verbinden met uw account voor verkoopapps {#connect-marketo-to-your-sales-apps-account}

1. In uw rekening van de Verkoop van Marketo, klik het tandwielpictogram en selecteer **Montages**.

   ![](assets/msi-actions-admin-guide-7.png)

1. Onder Montages Admin, klik **Marketo**.

   ![](assets/msi-actions-admin-guide-8.png)

1. Klik **verbinden**. Uw account wordt dan verbonden.

   ![](assets/msi-actions-admin-guide-9.png)

>[!NOTE]
>
>Als er geen verbinding wordt gemaakt, kopieert u de gegevens van het Marketo Sales Insight-tabblad &quot;Actions Config&quot; en plakt u deze op het tabblad Set-up.

## Gegevenssynchronisatie starten {#initiate-data-sync}

De het gebiedssynchronisatie van de gegevenseenmaking voor de Acties van het Inzicht van de Verkoop laat het systeem toe om persooninformatie van uw gegevensbestand van het Marketo Engage in uw gegevensbestand van de Acties van het Inzicht van de Verkoop te trekken, die uw gegevens van uw mensen bijgewerkt houden en ervoor zorgen de activiteiten aan de juiste verslagen over Marketo en Salesforce worden geregistreerd.

>[!CAUTION]
>
>Zodra u gegevenssynchronisatie in werking stelt, zou u **** niet de originele gebruiker op uw instantie van de Acties van het Inzicht van de Verkoop moeten verwijderen. Dit is de gebruiker waarnaar de eerste uitnodiging is verzonden.

1. In Marketo, klik **Admin**.

   ![](assets/msi-actions-admin-guide-10.png)

1. Klik **Inzicht van de Verkoop**.

   ![](assets/msi-actions-admin-guide-11.png)

1. Klik **Config van Acties** tabel. In de kaart van de Synchronisatie van het Gebied van de Actie, klik **Synchronisatie**.

   ![](assets/msi-actions-admin-guide-12.png)

1. U ziet een voorvertoning van de velden die worden gesynchroniseerd. Klik **Synchronisatie van het Begin**.

   ![](assets/msi-actions-admin-guide-13.png)

Persoonsgegevens die in Marketo en Salesforce bestaan, worden gesynchroniseerd met je Marketo Sales Apps-account.

>[!NOTE]
>
>Om meer over te leren hoe de mensen en activiteitengegevens tussen de Acties van het Inzicht van de Verkoop, Marketo, en Salesforce synchroniseren, [ klik hier ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/sync-sales-action-data-with-marketo-and-salesforce.md){target="_blank"}.

## Individuele gebruikers uitnodigen voor MSI-handelingen {#invite-individual-users-to-msi-actions}

1. In uw rekening van de Verkoop van Marketo, klik het tandwielpictogram en selecteer **Montages**.

   ![](assets/msi-actions-admin-guide-14.png)

1. Onder Montages Admin, uitgezochte **Beheer van de Gebruiker**.

   ![](assets/msi-actions-admin-guide-15.png)

1. Klik **Acties** en selecteer **Uitnodigen Gebruikers**.

   ![](assets/msi-actions-admin-guide-16.png)

1. Ga het e-mailadres(sen) in en klik **Uitnodiging**.

   ![](assets/msi-actions-admin-guide-17.png)

>[!NOTE]
>
>Door gebrek, zullen alle nieuwe leden aan het Iedereen team worden toegevoegd.

Je ontvangt een bevestigingsbericht.

## Gebruikers via CSV uitnodigen voor MSI-handelingen {#invite-users-via-csv-to-msi-actions}

1. In uw rekening van de Verkoop van Marketo, klik het tandwielpictogram en selecteer **Montages**.

   ![](assets/msi-actions-admin-guide-18.png)

1. Onder Montages Admin, uitgezochte **Beheer van de Gebruiker**.

   ![](assets/msi-actions-admin-guide-19.png)

1. Klik **Acties** en selecteer **Gebruikers via CSV** uitnodigen.

   ![](assets/msi-actions-admin-guide-20.png)

1. Blader naar CSV op uw computer, selecteer het, en klik **daarna**.

   ![](assets/msi-actions-admin-guide-21.png)

1. Bevestig dat de gebieden behoorlijk in kaart worden gebracht en klik **uitnodigen**.

   ![](assets/msi-actions-admin-guide-22.png)

U zult een bevestigingsbericht ontvangen zodra de uitnodigingen worden verzonden.

>[!NOTE]
>
>Zodra dit wordt gedaan, kunt u of uw bestaand pakket bevorderen MSI of nieuwe installeren en zich op [ het vormen acties MSI in Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/sales-insight-actions-configuration-in-salesforce.md){target="_blank"} bewegen.
