---
description: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Enterprise/Unlimited) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)
hide: true
hidefromtoc: true
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '421'
ht-degree: 0%

---

# Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>Deze stappen moeten worden uitgevoerd door een Salesforce-beheerder

>[!PREREQUISITES]
>
>[ Stap 1 van 3: Voeg de Gebieden van Marketo aan Salesforce (Onderneming/Onbeperkt) toe ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}

In dit artikel stelt u gebruikersmachtigingen in in het Salesforce-profiel en maakt u een Marketo-Salesforce-integratieaccount.

## Een profiel maken {#create-a-profile}

1. Klik op **[!UICONTROL Setup]**.

   SCREENSHOT

1. Typ &quot;profielen&quot; in de zoekbalk Nav en klik op de koppeling Profielen.

   SCREENSHOT

1. Klik op Nieuw profiel.

   SCREENSHOT

1. Selecteer Standaardgebruiker, geef het profiel &quot;Marketo-Salesforce Sync&quot; een naam en klik op Opslaan.

   SCREENSHOT

## Profielmachtigingen instellen {#set-profile-permissions}

1. Klik op Bewerken om de beveiligingsmachtigingen in te stellen.

   SCREENSHOT

1. Controleer of onder het gedeelte Administratieve machtigingen de volgende vakken zijn ingeschakeld:

   * API ingeschakeld
   * HTML-sjablonen bewerken
   * Openbare documenten beheren
   * Openbare sjablonen beheren

   >[!TIP]
   >
   >Controleer of het vak Wachtwoord nooit verlopen is ingeschakeld.

1. Controleer of onder de sectie Algemene gebruikersmachtigingen de volgende vakken zijn ingeschakeld:

   * Leads omzetten
   * Gebeurtenissen bewerken
   * Taken bewerken

1. Controleer in de sectie Standaardobjectmachtigingen of de machtigingen Lezen, Maken, Bewerken en Verwijderen zijn ingeschakeld:

   * Accounts
   * Campagnes
   * Contactpersonen
   * Leads
   * Kansen

   >[!NOTE]
   >
   >Verleen toestemmingen aan de Campagnes, als u van plan bent te gebruiken de Synchronisatie van de Campagne.

   SCREENSHOT

1. Klik op Opslaan onder aan de pagina als u klaar bent.

   SCREENSHOT

## Veldmachtigingen instellen {#set-field-permissions}

1. Bespreek met uw marketers welke aangepaste velden nodig zijn voor synchronisatie.

   >[!NOTE]
   >
   >Met deze stap voorkomt u dat velden die u niet nodig hebt, worden weergegeven in Marketo, waardoor de synchronisatie minder rommelig wordt en sneller verloopt.

1. Ga op de pagina met profieldetails naar de sectie Beveiliging op veldniveau. Klik op Weergave om de toegankelijkheid voor de objecten te bewerken:

   * Lood
   * Contact
   * Account
   * Kans

   >[!TIP]
   >
   >U kunt andere voorwerpen op de behoeften van uw organisatie vormen.

1. Klik voor elk object op Bewerken.

   SCREENSHOT

1. Zoek de overbodige velden en zorg ervoor dat de optie Toegang lezen en Toegang bewerken is uitgeschakeld. Klik op Opslaan als u klaar bent.

   >[!NOTE]
   >
   >Bewerk alleen de toegankelijkheid voor de aangepaste velden.

   SCREENSHOT

1. Nadat u alle overbodige velden hebt uitgeschakeld, moet u de optie Toegang lezen en Toegang bewerken inschakelen voor de volgende objectvelden. Klik op Opslaan als u klaar bent.

   TABEL

   SCREENSHOT

## Marketo-Salesforce-synchronisatieaccount maken {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>Maak een toegewijde Salesforce-account (bijvoorbeeld `marketo@yourcompany.com` ) om onderscheid te maken tussen de wijzigingen die Marketo aanbrengt en andere Salesforce-gebruikers.

1. Typ &quot;Gebruikers beheren&quot; in de zoekbalk Nav en klik vervolgens op Gebruikers. Klik op Nieuwe gebruiker.

   SCREENSHOT

   SCREENSHOT

1. Vul de vereiste velden in. Selecteer vervolgens Gebruikerslicentie: Salesforce en het profiel dat u eerder hebt gemaakt. Klik op Opslaan als u klaar bent.

   SCREENSHOT

Stap 2 van 3 is voltooid.
