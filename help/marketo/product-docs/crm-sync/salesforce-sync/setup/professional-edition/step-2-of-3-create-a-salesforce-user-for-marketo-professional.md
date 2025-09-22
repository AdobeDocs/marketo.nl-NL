---
unique-page-id: 3571797
description: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Professional) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Professional)
exl-id: 7eb4bf89-b6e4-45e0-adee-e2976cb01dd3
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 0%

---

# Stap 2 van 3: Een [!DNL Salesforce] gebruiker voor Marketo (Professional) maken {#step-of-create-a-salesforce-user-for-marketo-professional}

>[!NOTE]
>
>Deze stappen moeten worden uitgevoerd door een Salesforce-beheerder.

>[!PREREQUISITES]
>
>[ Stap 1 van 3: Voeg de Gebieden van Marketo aan Salesforce (Beroeps) toe ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md){target="_blank"}

In dit artikel past u veldmachtigingen aan met een [!DNL Salesforce] pagina-indeling en maakt u een Marketo- [!DNL Salesforce] -synchronisatiegebruiker.

## Paginalay-outs instellen {#set-page-layouts}

[!DNL Salesforce] Professional stelt toegankelijkheid op veldniveau in met paginalay-outs, in tegenstelling tot [!DNL Salesforce] Profielen van Enterprise/Unlimited. Als u deze stappen uitvoert, kan de Marketo-synchronisatiegebruiker de aangepaste velden bijwerken.

1. Typ &quot;[!UICONTROL page layouts]&quot; in de zoekbalk Nav zonder op **[!UICONTROL Enter]** te drukken en klik op **[!UICONTROL Page Layout]** onder **[!UICONTROL Leads]** .

   ![](assets/image2016-2-26-12-3a58-3a32.png)

1. Klik op **[!UICONTROL Edit]** naast Lay-out lead.

   ![](assets/image2016-2-26-13-3a2-3a46.png)

1. Klik en sleep een nieuwe **[!UICONTROL Section]** in de paginalay-out.

   ![](assets/image2014-12-9-12-3a56-3a40.png)

1. Voer &quot;Marketo&quot; voor **[!UICONTROL Section Name]** in en klik op **[!UICONTROL OK]** .

   ![](assets/image2014-12-9-12-3a56-3a52.png)

1. Klik en sleep het gebied **[!UICONTROL Acquisition Date]** in de **Marketo** sectie.

   ![](assets/image2014-12-9-12-3a57-3a0.png)

1. Herhaal bovenstaande stap voor de volgende velden:

   * [!UICONTROL Acquisition Program]
   * [!UICONTROL Acquisition Program Id]
   * [!UICONTROL Email Opt Out]
   * [!UICONTROL Inferred City]
   * [!UICONTROL Inferred Company]
   * [!UICONTROL Inferred Country]
   * [!UICONTROL Inferred Metropolitan Area]
   * [!UICONTROL Inferred Phone Area Code]
   * [!UICONTROL Inferred Postal Code]
   * [!UICONTROL Inferred State Region]
   * [!UICONTROL Lead Score]
   * [!UICONTROL Original Referrer]
   * [!UICONTROL Original Search Engine]
   * [!UICONTROL Original Search Phrase]
   * [!UICONTROL Original Source Info]
   * [!UICONTROL Original Source Type]

   >[!NOTE]
   >
   >Deze velden moeten in de paginalay-out staan, zodat Marketo ze kan lezen/schrijven.

   >[!TIP]
   >
   >Maak twee kolommen voor de velden door naar de rechterkant van de pagina te slepen. U kunt velden van de ene naar de andere zijde verplaatsen om de kolomlengte in evenwicht te brengen.

1. Klik op **[!UICONTROL Save]** wanneer u klaar bent met het toevoegen van velden.

   ![](assets/image2014-12-9-12-3a57-3a10.png)

1. Herhaal alle bovenstaande stappen voor de Salesforce **[!UICONTROL Contact Page Layout]** .

   ![](assets/image2016-2-26-13-3a10-3a1.png)

1. Vergeet niet op **[!UICONTROL Save]** te klikken wanneer u klaar bent met de **[!UICONTROL Contact Page Layout]** .

   ![](assets/image2014-12-9-12-3a57-3a30.png)

   >[!NOTE]
   >
   >Controleer of het veld **[!UICONTROL All-Day Event]** is toegevoegd aan **[!UICONTROL Event Page Layout]** .

## Synchronisatiegebruiker maken {#create-sync-user}

Marketo heeft referenties nodig om toegang te krijgen tot [!DNL Salesforce] . Dit kunt u het beste doen met een toegewijde gebruiker die is gemaakt met de onderstaande stappen.

>[!NOTE]
>
>Als uw organisatie geen extra Salesforce-licenties heeft, kunt u een bestaande marketinggebruiker gebruiken met het profiel Systeembeheerder.

1. Voer &quot;gebruikers&quot; in op de zoekbalk Nav en klik op **[!UICONTROL Users]** onder **[!UICONTROL Manage Users]** .

   ![](assets/image2014-12-9-12-3a57-3a42.png)

1. Klik op **[!UICONTROL New User]**.

   ![](assets/image2014-12-9-12-3a58-3a1.png)

1. Vul de vereiste velden in, selecteer de **[!UICONTROL User License: Salesforce]** , stel de **[!UICONTROL Profile: System Administrator]** , check **[!UICONTROL Marketing User]** in en klik op **[!UICONTROL Save]** .

   ![](assets/image2014-12-9-12-3a58-3a11.png)

   >[!TIP]
   >
   >Controleer of het e-mailadres dat u invoert, geldig is. U moet zich aanmelden als de synchronisatiegebruiker om het wachtwoord opnieuw in te stellen.

Uitstekend! Nu hebt u een account waarmee Marketo verbinding kan maken met [!DNL Salesforce] . Laten we het doen.

>[!MORELIKETHIS]
>
>[ Stap 3 van 3: Verbind Marketo en Salesforce (Beroeps) ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-3-of-3-connect-marketo-and-salesforce-professional.md){target="_blank"}
