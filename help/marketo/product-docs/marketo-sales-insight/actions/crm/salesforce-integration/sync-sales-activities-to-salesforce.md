---
description: Verkoopactiviteiten synchroniseren met Salesforce - Marketo Docs - Productdocumentatie
title: Verkoopactiviteiten synchroniseren met Salesforce
exl-id: fa13ced2-6184-485f-a0ef-813ccab4f0fe
source-git-commit: 02354356949aef7aa8836d4753ec538b7819a65a
workflow-type: tm+mt
source-wordcount: '759'
ht-degree: 0%

---

# Verkoopactiviteiten synchroniseren met Salesforce {#sync-sales-activities-to-salesforce}

U kunt de Acties vormen Salesforce synchroniseren Montages om e-mail en vraagactiviteiten aan Salesforce te registreren. Dit verstrekt betere zichtbaarheid aan teams die uit uw CRM werken en staat managers toe om deze activiteiten te gebruiken om de rapporten van de douaneSalesforce te bouwen om uw teamprestaties te volgen.

## E-mailactiviteiten aanmelden bij Salesforce via API {#logging-email-activity-to-salesforce-via-api}

Deze functionaliteit vereist dat u zich op de Enterprise/Unlimited editie van Salesforce bevindt, of de Professional-editie als u Integratie via de Web Services API hebt aangeschaft.

>[!PREREQUISITES]
>
>Handelingen Salesforce en Sales Insight moeten zijn verbonden.

1. Klik in Handelingen in het venster Verkoopinzicht op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/sync-sales-activities-to-salesforce-1.png)

1. Klik onder Beheerinstellingen (of Mijn account als u geen beheerder bent) op **Salesforce**.

   ![](assets/sync-sales-activities-to-salesforce-2.png)

1. Klik op de knop **Instellingen synchroniseren** tab.

   ![](assets/sync-sales-activities-to-salesforce-3.png)

1. Klik op de pijl naast E-mailactiviteiten in log opnemen op Salesforce.

   ![](assets/sync-sales-activities-to-salesforce-4.png)

1. Klik op de knop **Salesforce-API** tab. Op deze kaart kunt u uw voorkeur instellen voor het registreren van gegevens bij Salesforce. Klikken **Opslaan** wanneer gereed.

   ![](assets/sync-sales-activities-to-salesforce-5.png)

## E-mailactiviteiten registreren bij Salesforce via e-mail naar Salesforce (BCC) {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

Zodra u &quot;E-mail aan Salesforce (BCC)&quot;activeert, zult u een BCC van uw verkoop e-mails ontvangen en uw e-mails zullen als activiteiten op kansen, lood en contacten worden geregistreerd.

>[!PREREQUISITES]
>
>Handelingen Salesforce en Sales Insight moeten zijn verbonden.

**Je e-mails via e-mail (BCC) in Salesforce aanmelden**

1. Klik in Marketo Sales op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/sync-sales-activities-to-salesforce-6.png)

1. Klik onder Beheerinstellingen (of Mijn account als u geen beheerder bent) op **Salesforce**.

   ![](assets/sync-sales-activities-to-salesforce-7.png)

1. Klik op de knop **Instellingen synchroniseren** tab.

   ![](assets/sync-sales-activities-to-salesforce-8.png)

1. Klik op de knop **E-mail naar Salesforce (BCC)** en klik op **Activeren**.

   ![](assets/sync-sales-activities-to-salesforce-9.png)

Als uw e-mail naar het Salesforce-adres om een of andere reden niet wordt binnengehaald, voert u de volgende stappen uit om de BCC-functie in uw Salesforce-account te activeren:

1. Meld u aan bij uw Salesforce-exemplaar.
1. Zoek de gebruikersnaam in de rechterbovenhoek en selecteer de vervolgkeuzelijst.
1. Selecteren **Mijn instellingen**.
1. Selecteren **E-mail**.
1. Selecteren **Mijn e-mail naar Salesforce**.
1. Op deze pagina ziet u een veld met het label &quot;E-mail naar Salesforce-adres&quot;. Als er niets naast het is bevolkt, scrol neer aan &quot;Mijn Acceptabele E-mailadressen.&quot;
1. Voer het e-mailadres of de e-mailadressen in die u voor BCC wilt gebruiken.
1. Klikken **Wijzigingen opslaan**.

**Kan mijn e-mail naar Salesforce niet vinden in Mijn instellingen**

Als Mijn e-mail naar Salesforce niet wordt weergegeven onder de instellingen, is het mogelijk dat uw beheerder dit niet heeft ingeschakeld. Dit kan gebeuren als uw team nieuw aan Salesforce is, of uw team heeft nooit het adres BCC gebruikt dat Salesforce verstrekt.

>[!NOTE]
>
>U hebt beheerdersrechten nodig om dit in te stellen.

1. Klikken **Instellen**.
1. Klikken **E-mailbeheer**.
1. Klikken **E-mail naar Salesforce**.
1. Klikken **Bewerken**.
1. Schakel het selectievakje naast Actief in.
1. Klikken **Opslaan**.

## De Taken/Herinneringen van de Acties van het Inzicht van de Verkoop van de Synchronisatie aan Taken Salesforce {#sync-sales-insight-actions-tasks-reminders-to-salesforce-tasks}

1. Klik in Handelingen in het venster Verkoopinzicht op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/sync-sales-activities-to-salesforce-10.png)

1. Klik onder Beheerinstellingen (of Mijn account als u geen beheerder bent) op **Salesforce**.

   ![](assets/sync-sales-activities-to-salesforce-11.png)

1. Klik op de knop **Instellingen synchroniseren** tab.

   ![](assets/sync-sales-activities-to-salesforce-12.png)

1. Klik op de pijl naast Marketo Sales Tasks/Reminders synchroniseren met Salesforce Tasks.

   ![](assets/sync-sales-activities-to-salesforce-13.png)

1. Kies de gewenste optie (Synchroniseren met Salesforce-taken is standaard ingeschakeld).

   ![](assets/sync-sales-activities-to-salesforce-14.png)

## De Taken van de Acties van het Inzicht van de Verkoop met Salesforce voor de eerste keer synchroniseren {#syncing-sales-insight-ations-tasks-with-salesforce-for-the-first-time}

Wanneer u eerst de synchronisatie tussen de Acties van het Inzicht van de Verkoop en de taken van Salesforce aanzet, voeren wij uw taken van Salesforce in. Wij zullen niet over om het even welke huidige taken duwen u in de Acties van het Inzicht van de Verkoop aan Salesforce hebt. Om rommelige en duplicaten te verminderen, zijn de enige taken die van de Acties van het Inzicht van de Verkoop in Salesforce worden gesynchroniseerd taken die worden gecreeerd nadat u de Acties van het Inzicht van de Verkoop met SFDC synchroniseert.

Hier is wat gebeurt wanneer u de Acties van het Inzicht van de Verkoop en taken SFDC synchroniseert:

* Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

* Herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar Handelingen in het verkoopinzicht geactiveerd. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

* Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, wordt alles dat in de afgelopen 15 dagen is verwijderd, uit Command Center verwijderd.

* Wij zullen taken tussen de Acties van het Inzicht van de Verkoop en SFDC constant synchroniseren zolang de synchronisatie wordt toegelaten.

* Na de eerste synchronisatie worden alle taken die u maakt, bewerkt, voltooit of verwijdert in Handelingen voor Verkoopcontrole gesynchroniseerd met de takenlijst in Salesforce. En om het even wat gecreeerd, uitgegeven, voltooid, of geschrapt in Salesforce zal uw takenlijst in de Acties van het Inzicht van de Verkoop bijwerken.

* Als u deze synchronisatie wilt inschakelen, schakelt u gewoon het synchronisatievak in op de pagina Instellingen in de webtoepassing.
