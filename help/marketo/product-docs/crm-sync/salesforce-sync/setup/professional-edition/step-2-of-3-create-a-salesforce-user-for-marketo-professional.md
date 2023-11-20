---
unique-page-id: 3571797
description: Stap 2 van 3 - een Salesforce-gebruiker voor Marketo maken (Professional) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Professional)
exl-id: 7eb4bf89-b6e4-45e0-adee-e2976cb01dd3
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '383'
ht-degree: 1%

---

# Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Professional) {#step-of-create-a-salesforce-user-for-marketo-professional}

>[!NOTE]
>
>Deze stappen moeten door een beheerder van Salesforce worden voltooid.

>[!PREREQUISITES]
>
>[Stap 1 van 3: Voeg Marketo-velden toe aan Salesforce (Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md){target="_blank"}

In dit artikel past u veldmachtigingen aan met een Salesforce Page Layout en maakt u een Marketo-Salesforce synchronisatiegebruiker.

## Paginalay-outs instellen {#set-page-layouts}

Salesforce Professional stelt toegankelijkheid op veldniveau in met paginalay-outs, in tegenstelling tot de profielen van Salesforce Enterprise/Unlimited. Als u deze stappen uitvoert, kan de Marketo-synchronisatiegebruiker de aangepaste velden bijwerken.

1. Typ &quot;[!UICONTROL page layouts]&quot; in de zoekbalk van Nav zonder op **[!UICONTROL Enter]** en klik op **[!UICONTROL Page Layout]** krachtens **[!UICONTROL Leads]**.

   ![](assets/image2016-2-26-12-3a58-3a32.png)

1. Klikken **[!UICONTROL Edit]** naast Lay-out lead.

   ![](assets/image2016-2-26-13-3a2-3a46.png)

1. Klik en sleep een nieuwe **[!UICONTROL Section]** in de pagina-indeling.

   ![](assets/image2014-12-9-12-3a56-3a40.png)

1. Voer &quot;Marketo&quot; in voor **[!UICONTROL Section Name]** en klik op **[!UICONTROL OK]**.

   ![](assets/image2014-12-9-12-3a56-3a52.png)

1. Klik en sleep het veld **[!UICONTROL Acquisition Date]** in de **Marketo** sectie.

   ![](assets/image2014-12-9-12-3a57-3a0.png)

1. Herhaal bovenstaande stap voor de volgende velden:

   * Overnameprogramma
   * Id van overnameprogramma
   * E-mail uitschakelen
   * Overgenomen stad
   * Afgeleid bedrijf
   * Afgeleid land
   * Overgenomen metropolitaans gebied
   * Gebiedscode afgeleide telefoon
   * Postcode
   * Gebied van de betrokken staat
   * Leadscore
   * Oorspronkelijke verwijzing
   * Originele zoekengine
   * Oorspronkelijke zoekterm
   * Originele broninformatie
   * Oorspronkelijk brontype

   >[!NOTE]
   >
   >Deze velden moeten in de paginalay-out staan, zodat Marketo ze kan lezen/schrijven.

   >[!TIP]
   >
   >Maak twee kolommen voor de velden door naar de rechterkant van de pagina te slepen. U kunt velden van de ene naar de andere zijde verplaatsen om de kolomlengte in evenwicht te brengen.

1. Klikken **[!UICONTROL Save]** als u klaar bent met het toevoegen van velden.

   ![](assets/image2014-12-9-12-3a57-3a10.png)

1. Herhaal alle bovenstaande stappen voor de Salesforce **[!UICONTROL Contact Page Layout]**.

   ![](assets/image2016-2-26-13-3a10-3a1.png)

1. Vergeet niet te klikken **[!UICONTROL Save]** als u klaar bent met de **[!UICONTROL Contact Page Layout]**.

   ![](assets/image2014-12-9-12-3a57-3a30.png)

   >[!NOTE]
   >
   >Zorg ervoor dat de **[!UICONTROL All-Day Event]** veld is toegevoegd aan de **[!UICONTROL Event Page Layout]**.

## Synchronisatiegebruiker maken {#create-sync-user}

Marketo heeft aanmeldingsgegevens nodig om toegang te krijgen tot Salesforce. Dit kunt u het beste doen met een toegewijde gebruiker die is gemaakt met de onderstaande stappen.

>[!NOTE]
>
>Als uw organisatie geen extra licenties voor Salesforce heeft, kunt u een bestaande marketinggebruiker gebruiken met het profiel Systeembeheerder.

1. Voer &quot;gebruikers&quot; in op de zoekbalk Nav en klik op **[!UICONTROL Users]** krachtens **[!UICONTROL Manage Users]**.

   ![](assets/image2014-12-9-12-3a57-3a42.png)

1. Klik op **[!UICONTROL New User]**.

   ![](assets/image2014-12-9-12-3a58-3a1.png)

1. Vul de vereiste gebieden in, selecteer **[!UICONTROL User License: Salesforce]**, stelt u de **[!UICONTROL Profile: System Administrator]**, controle **[!UICONTROL Marketing User]** en klik op **[!UICONTROL Save]**.

   ![](assets/image2014-12-9-12-3a58-3a11.png)

   >[!TIP]
   >
   >Controleer of het e-mailadres dat u invoert, geldig is. U moet zich aanmelden als de synchronisatiegebruiker om het wachtwoord opnieuw in te stellen.

Uitstekend! Nu hebt u een account dat Marketo kan gebruiken om verbinding te maken met Salesforce. Laten we het doen.

>[!MORELIKETHIS]
>
>[Stap 3 van 3: Connect Marketo en Salesforce (Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-3-of-3-connect-marketo-and-salesforce-professional.md){target="_blank"}
