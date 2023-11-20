---
description: Stap 2 van 3 - creeer een gebruiker van de CRM van Veeva voor Marketo Engage - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - creeer een Gebruiker van Veeva CRM voor Marketo Engage
exl-id: 78945192-36b0-4e0b-830a-f37eb0b83484
feature: Veeva CRM
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '592'
ht-degree: 1%

---

# Stap 2 van 3: Een Veeva CRM-gebruiker voor Marketo Engage maken {#step-2-of-3-create-a-veeva-crm-user-for-marketo-engage}

>[!NOTE]
>
>De stappen in dit artikel moeten door een beheerder van Veeva CRM worden voltooid.

>[!PREREQUISITES]
>
>[Stap 1 van 3: Voeg Marketo-velden toe aan Salesforce (Professional)](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target="_blank"}

In dit artikel past u de veldmachtigingen aan met een Veeva CRM-paginalay-out en maakt u een Marketo-Veeva CRM-synchronisatiegebruiker.

## Paginalay-outs instellen {#set-page-layouts}

Als u deze stappen uitvoert, kan de Marketo-synchronisatiegebruiker de aangepaste velden bijwerken.

1. Klik op de pagina-indelingen Account (persoonlijk account) in de zoekbalk Nav zonder op Enter te drukken en klik op **[!UICONTROL Page Layout]** onder Contacten.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-1.png)

1. Klik op **[!UICONTROL Page Layouts]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-2.png)

1. Klik op **[!UICONTROL HCP - Professional]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-3.png)

1. Klik en sleep een nieuwe **[!UICONTROL Section]** in de pagina-indeling.

1. Voer Marketo in voor Sectienaam en klik op **[!UICONTROL OK]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-4.png)

1. Klik en sleep het gebied van de Score in de sectie van Marketo.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-5.png)

1. Herhaal bovenstaande stap voor de volgende velden:

   * Overgenomen stad
   * Afgeleid bedrijf
   * Afgeleid land
   * Overgenomen metropolitaans gebied
   * Gebiedscode afgeleide telefoon
   * Postcode
   * Gebied van de betrokken staat

   >[!NOTE]
   >
   >Deze velden moeten in de paginalay-out staan, zodat Marketo ze kan lezen/schrijven.

   >[!TIP]
   >
   >Maak twee kolommen voor de velden door naar de rechterkant van de pagina te slepen. U kunt velden van de ene naar de andere zijde verplaatsen om de kolomlengte in evenwicht te brengen.

1. Als u klaar bent met de HCP-Professional-indeling, klikt u op **[!UICONTROL Save]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-6.png)

   >[!NOTE]
   >
   >Herhaal dit voor andere pagina-indelingen voor accounts.

## Een profiel maken {#create-a-profile}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-7.png)

1. Typ &quot;profielen&quot; in de navigatiebalk en klik op de knop **[!UICONTROL Profiles]** koppeling.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-8.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-9.png)

1. Selecteer Standaardgebruiker, geef het profiel &quot;Marketo-Salesforce Sync&quot; een naam en klik op **[!UICONTROL Save]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-10.png)

## Profielmachtigingen instellen {#set-profile-permissions}

1. Klikken **[!UICONTROL Edit]** om de beveiligingsmachtigingen in te stellen.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-11.png)

1. Controleer onder de sectie Administratieve machtigingen of **[!UICONTROL API Enabled]** is geselecteerd.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-12.png)

   >[!TIP]
   >
   >Controleer of het vak Wachtwoord nooit verlopen is ingeschakeld.

1. Controleer of onder de sectie Algemene gebruikersmachtigingen **[!UICONTROL Edit Events]** en **[!UICONTROL Edit Tasks]** zijn geselecteerd.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-13.png)

1. Controleer in de sectie Standaardobjectmachtigingen of **[!UICONTROL Read]**, **[!UICONTROL Create]**, **[!UICONTROL Edit]**, en **[!UICONTROL Delete]** de machtigingen worden gecontroleerd op accounts en contactpersonen.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-14.png)

1. Controleer in de sectie Aangepaste objectmachtigingen of Leesmachtigingen zijn ingeschakeld **[!UICONTROL Call]**, **[!UICONTROL Call Key Message]** en andere gewenste aangepaste objecten.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-15.png)

1. Klik op **[!UICONTROL Save]** onder aan de pagina.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-16.png)

## Veldmachtigingen instellen {#set-field-permissions}

1. Bespreek met uw marketers welke aangepaste velden nodig zijn voor synchronisatie.

   >[!NOTE]
   >
   >Met deze stap voorkomt u dat velden die u niet nodig hebt, worden weergegeven in Marketo, waardoor de synchronisatie minder rommelig wordt en sneller verloopt.

1. Ga op de pagina met profieldetails naar [!UICONTROL Field-Level Security] sectie. Klikken **[!UICONTROL View]** om de toegankelijkheid voor de objecten Contact en Account te bewerken.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-17.png)

   >[!TIP]
   >
   >U kunt andere voorwerpen op de behoeften van uw organisatie vormen.

1. Voor elk object klikt u op **[!UICONTROL Edit]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-18.png)

1. Zoek de overbodige velden, zorg ervoor dat Toegang lezen en Toegang bewerken zijn _ongecontroleerd_. Klikken **[!UICONTROL Save]** wanneer gereed.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-19.png)

   >[!NOTE]
   >
   >Bewerk alleen de toegankelijkheid voor de aangepaste velden.

1. Nadat u alle onnodige velden hebt uitgeschakeld, schakelt u Toegang lezen en Toegang bewerken in voor de volgende objectvelden. Klikken **[!UICONTROL Save]** wanneer gereed.

<table>
 <tbody>
  <tr>
   <th>Object
   <th>Velden
  </tr>
  <tr>
   <td>Account</td>
   <td>Tekstveld</td>
  </tr>
  <tr>
   <td>Gebeurtenis</td>
   <td>Alle velden</td>
  </tr>
  <tr>
   <td>Taak</td>
   <td>Alle velden</td>
  </tr>
 </tbody>
</table>

## Synchronisatiegebruiker maken {#create-sync-user}

Marketo heeft aanmeldingsgegevens nodig voor toegang tot Veeva CRM. Dit kunt u het beste doen met een toegewijde gebruiker die is gemaakt met de onderstaande stappen.

>[!NOTE]
>
>Als uw organisatie geen extra Veeva CRM-licenties heeft, kunt u een bestaande marketinggebruiker gebruiken met het profiel Systeembeheerder.

1. Voer &quot;gebruikers&quot; in op de zoekbalk Nav en klik op **[!UICONTROL Users]** onder Gebruikers beheren.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-20.png)

1. Klik op **[!UICONTROL New User]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-21.png)

1. Vul de vereiste gebieden in, selecteer de Vergunning van de Gebruiker: Salesforce, plaats het Profiel: de Gebruiker van de Synchronisatie van Marketo en klik **[!UICONTROL Save]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-22.png)

>[!TIP]
>
>Controleer of het e-mailadres dat u invoert, geldig is. U moet zich aanmelden als de synchronisatiegebruiker om het wachtwoord opnieuw in te stellen.

Uitstekend! Nu hebt u een account die Marketo Engage kan gebruiken om verbinding te maken met Veeva CRM. Laten we het doen.

>[!MORELIKETHIS]
>
>[Stap 3 van 3: Connect Marketo en Veeva CRM](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-3-of-3-connect-marketo-engage-and-veeva-crm.md){target="_blank"}
