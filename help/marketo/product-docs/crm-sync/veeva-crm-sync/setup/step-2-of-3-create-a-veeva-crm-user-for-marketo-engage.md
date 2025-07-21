---
description: Stap 2 van 3 - creeer a [!DNL Veeva]  Gebruiker van CRM voor Marketo Engage - de Documenten van Marketo - de Documentatie van het Product
title: Stap 2 van 3 - Een Veeva CRM-gebruiker voor Marketo Engage maken
exl-id: 78945192-36b0-4e0b-830a-f37eb0b83484
feature: Veeva CRM
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '545'
ht-degree: 1%

---

# Stap 2 van 3: Een [!DNL Veeva] CRM-gebruiker voor Marketo Engage maken {#step-2-of-3-create-a-veeva-crm-user-for-marketo-engage}

>[!NOTE]
>
>De stappen in dit artikel moeten worden uitgevoerd door een [!DNL Veeva] CRM-beheerder.

>[!PREREQUISITES]
>
>[ Stap 1 van 3: Voeg de Gebieden van Marketo aan  [!DNL Salesforce]  toe (Beroeps) ](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target="_blank"}

In dit artikel past u veldmachtigingen aan met een [!DNL Veeva] CRM-paginalay-out en maakt u een [!DNL Marketo-Veeva] CRM-synchronisatiegebruiker.

## Paginalay-outs instellen {#set-page-layouts}

Als u deze stappen uitvoert, kan de Marketo-synchronisatiegebruiker de aangepaste velden bijwerken.

1. Klik op de pagina-indelingen **[!UICONTROL Account]** (Person account) in de zoekbalk Nav zonder op Enter te drukken en klik **[!UICONTROL Page Layout]** onder [!UICONTROL Contacts] .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-1.png)

1. Klik op **[!UICONTROL Page Layouts]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-2.png)

1. Klik op **[!UICONTROL HCP - Professional]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-3.png)

1. Klik en sleep een nieuwe **[!UICONTROL Section]** in de paginalay-out.

1. Voer &quot;Marketo&quot; voor **[!UICONTROL Section Name]** in en klik op **[!UICONTROL OK]** .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-4.png)

1. Klik en sleep het veld **[!UICONTROL Score]** naar de sectie Marketo.

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

1. Klik op [!UICONTROL HCP-Professional] als u klaar bent met de **[!UICONTROL Save]** -layout.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-6.png)

>[!NOTE]
>
>Herhaal dit voor andere [!UICONTROL Account] pagina-indelingen.

## Een profiel maken {#create-a-profile}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-7.png)

1. Typ &quot;profielen&quot; in de zoekbalk Nav en klik op de koppeling **[!UICONTROL Profiles]** .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-8.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-9.png)

1. Selecteer **[!UICONTROL Standard User]** , geef het profiel de naam &quot;[!UICONTROL Marketo-Salesforce Sync]&quot; en klik op **[!UICONTROL Save]** .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-10.png)

## Profielmachtigingen instellen {#set-profile-permissions}

1. Klik op **[!UICONTROL Edit]** om de beveiligingsmachtigingen in te stellen.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-11.png)

1. Controleer of onder de sectie [!UICONTROL Administrative Permissions] de optie [!UICONTROL API Enabled] is geselecteerd.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-12.png)

   >[!TIP]
   >
   >Controleer het vakje [!UICONTROL Password Never Expires] .

1. Controleer of onder de sectie [!UICONTROL General User Permissions] de opties [!UICONTROL Edit Events] en [!UICONTROL Edit Tasks] zijn geselecteerd.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-13.png)

1. Controleer onder de sectie [!UICONTROL Standard Object Permissions] of de machtigingen [!UICONTROL Read] , [!UICONTROL Create] , [!UICONTROL Edit] en [!UICONTROL Delete] zijn ingeschakeld voor [!UICONTROL Accounts] en [!UICONTROL Contacts] .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-14.png)

1. Controleer onder de sectie [!UICONTROL Custom Object Permissions] of [!UICONTROL Read] -machtigingen zijn ingeschakeld voor [!UICONTROL Call] , [!UICONTROL Call Key Message] en andere gewenste aangepaste objecten.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-15.png)

1. Als u klaar bent, klikt u op **[!UICONTROL Save]** onder aan de pagina.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-16.png)

## Veldmachtigingen instellen {#set-field-permissions}

1. Bespreek met uw marketers welke aangepaste velden nodig zijn voor synchronisatie.

   >[!NOTE]
   >
   >Met deze stap voorkomt u dat velden die u niet nodig hebt, worden weergegeven in Marketo, waardoor de synchronisatie minder rommelig wordt en sneller verloopt.

1. Ga in de pagina [!UICONTROL profile detail] naar de sectie **[!UICONTROL Field-Level Security]** . Klik op **[!UICONTROL View]** om de toegankelijkheid voor de objecten [!UICONTROL Contact] en [!UICONTROL Account] te bewerken.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-17.png)

   >[!TIP]
   >
   >U kunt andere voorwerpen op de behoeften van uw organisatie vormen.

1. Klik voor elk object op **[!UICONTROL Edit]** .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-18.png)

Bepaal de plaats van de onnodige gebieden, zorg ervoor dat [!UICONTROL Read Access] en [!UICONTROL Edit Access] **niet** gecontroleerd zijn. Klik op **[!UICONTROL Save]** als u klaar bent.

![](assets/step-2-of-3-create-a-veeva-crm-user-19.png)

>[!NOTE]
>
>Bewerk alleen de toegankelijkheid voor de aangepaste velden.

1. Nadat u alle overbodige velden hebt uitgeschakeld, controleert u [!UICONTROL Read Access] en [!UICONTROL Edit Access] voor de volgende objectvelden. Klik op **[!UICONTROL Save]** als u klaar bent.

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

Marketo heeft aanmeldingsgegevens nodig voor toegang tot [!DNL Veeva] CRM. Dit kunt u het beste doen met een toegewijde gebruiker die is gemaakt met de onderstaande stappen.

>[!NOTE]
>
>Als uw organisatie geen extra [!DNL Veeva] CRM-licenties heeft, kunt u een bestaande marketinggebruiker gebruiken met het profiel Systeembeheerder.

1. Voer &quot;gebruikers&quot; in op de zoekbalk Nav en klik op **[!UICONTROL Users]** onder [!UICONTROL Manage Users] .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-20.png)

1. Klik op **[!UICONTROL New User]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-21.png)

1. Vul de vereiste velden in, selecteer **[!UICONTROL User License]**: **[!UICONTROL Salesforce]** , stel **[!UICONTROL Profile]** in: **[!UICONTROL Marketo Sync]** Gebruiker en klik **[!UICONTROL Save]** .

   ![](assets/step-2-of-3-create-a-veeva-crm-user-22.png)

>[!TIP]
>
>Controleer of het e-mailadres dat u invoert, geldig is. U moet zich aanmelden als de synchronisatiegebruiker om het wachtwoord opnieuw in te stellen.

Uitstekend! Nu hebt u een account waarmee Marketo Engage verbinding kan maken met [!DNL Veeva] CRM. Laten we het doen.

>[!MORELIKETHIS]
>
>[ Stap 3 van 3: Verbind Marketo en  [!DNL Veeva]  CRM ](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-3-of-3-connect-marketo-engage-and-veeva-crm.md){target="_blank"}
