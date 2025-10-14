---
unique-page-id: 2360364
description: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Enterprise/Unlimited) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)
exl-id: 871f335c-7b1e-47e1-8320-a18fbf21a970
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '351'
ht-degree: 0%

---

# Stap 2 van 3: Een [!DNL Salesforce] gebruiker voor Marketo maken (Enterprise/Onbeperkt) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>Deze stappen moeten worden uitgevoerd door een [!DNL Salesforce] beheerder

>[!PREREQUISITES]
>
>[&#x200B; Stap 1 van 3: Voeg de Gebieden van Marketo aan  [!DNL Salesforce]  toe (Onderneming/Onbeperkt) &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)

In dit artikel stelt u gebruikersmachtigingen in in het [!DNL Salesforce] -profiel en maakt u een Marketo- [!DNL Salesforce] -integratieaccount.

## Een profiel maken {#create-a-profile}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-6-11-16-3a15-3a27.png)

1. Typ &quot;profielen&quot; in de zoekbalk Nav en klik op de koppeling **[!UICONTROL Profiles]** .

   ![](assets/sfdc-profiles-hands.png)

1. Klik op **[!UICONTROL New]** .

   ![](assets/image2014-12-9-9-3a19-3a15.png)

1. Selecteer **[!UICONTROL Standard User]** , geef het profiel &quot;Marketo-Salesforce Sync&quot; een naam en klik op **[!UICONTROL Save]** .

   ![](assets/image2014-12-9-9-3a19-3a22.png)

## Profielmachtigingen instellen {#set-profile-permissions}

1. Klik op **[!UICONTROL Edit]** om de beveiligingsmachtigingen in te stellen.

   ![](assets/image2014-12-9-9-3a19-3a30.png)

1. Controleer of onder de sectie **[!UICONTROL Administrative Permissions]** de volgende vakken zijn ingeschakeld:

   * [!UICONTROL API Enabled]
   * [!UICONTROL Edit HTML Templates]
   * [!UICONTROL Manage Public Documents]
   * [!UICONTROL Manage Public Templates]

   ![](assets/image2014-12-9-9-3a19-3a38.png)

   >[!TIP]
   >
   >Controleer het vakje **[!UICONTROL Password Never Expires]** .

1. Controleer of onder de sectie [!UICONTROL General User Permissions] de volgende vakken zijn ingeschakeld:

   * [!UICONTROL Convert Leads]
   * [!UICONTROL Edit Events]
   * [!UICONTROL Edit Tasks]

   ![](assets/image2014-12-9-9-3a19-3a47.png)

1. Controleer in de sectie [!UICONTROL Standard Object Permissions] of [!UICONTROL Read, Create, Edit, and Delete] -machtigingen zijn gecontroleerd op:

   * [!UICONTROL Accounts]
   * [!UICONTROL Campaigns]
   * [!UICONTROL Contacts]
   * [!UICONTROL Leads]
   * [!UICONTROL Opportunities]

   >[!NOTE]
   >
   >Rechten verlenen aan de [!UICONTROL Campaigns] als u Campagne Sync wilt gebruiken.

   ![](assets/image2014-12-9-9-3a19-3a57.png)

1. Als u klaar bent, klikt u op **[!UICONTROL Save]** onder aan de pagina.

   ![](assets/image2014-12-9-9-3a20-3a5.png)

## Veldmachtigingen instellen {#set-field-permissions}

1. Bespreek met uw marketers welke aangepaste velden nodig zijn voor synchronisatie.

   >[!NOTE]
   >
   >Met deze stap voorkomt u dat velden die u niet nodig hebt, worden weergegeven in Marketo, waardoor de synchronisatie minder rommelig wordt en sneller verloopt.

1. Ga naar de sectie **[!UICONTROL Field-Level Security]** in de pagina met profieldetails. Klik op **[!UICONTROL View]** om de toegankelijkheid voor de objecten te bewerken:

   * [!UICONTROL Lead]
   * [!UICONTROL Contact]
   * [!UICONTROL Account]
   * [!UICONTROL Opportunity]

   >[!TIP]
   >
   >U kunt andere voorwerpen op de behoeften van uw organisatie vormen.

   ![](assets/image2014-12-9-9-3a20-3a14.png)

1. Klik voor elk object op **[!UICONTROL Edit]** .

   ![](assets/sfdc-sync-field-edit1.png)

1. Zoek de overbodige velden. Controleer of **[!UICONTROL Read Access]** en **[!UICONTROL Edit Access]** zijn uitgeschakeld. Klik op **[!UICONTROL Save]** wanneer u klaar bent.

   >[!NOTE]
   >
   >Bewerk alleen de toegankelijkheid voor de aangepaste velden.

   ![](assets/sfdc-sync-field-edit2.png)

1. Nadat u alle overbodige velden hebt uitgeschakeld, moet u **[!UICONTROL Read Access and Edit Access]** controleren op de volgende objectvelden. Klik op **[!UICONTROL Save]** wanneer u klaar bent.

<table>
 <tbody>
  <tr>
   <th>Object</th>
   <th>Velden</th>
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

![](assets/sfdc-check-the-boxes.png)

## Marketo-Salesforce-synchronisatieaccount maken {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>Maak een toegewijde [!DNL Salesforce] -account (bijvoorbeeld <marketo@yourcompany.com> ) om onderscheid te maken tussen de wijzigingen die door Marketo en andere [!DNL Salesforce] -gebruikers zijn aangebracht.

1. Typ &quot;Gebruikers beheren&quot; in de zoekbalk Nav en klik op **[!UICONTROL Users]** . Klik op **[!UICONTROL New User]** .

   ![](assets/sfdc-new-users.png)

1. Vul de vereiste velden in. Selecteer vervolgens de **[!UICONTROL User License: Salesforce]** en het profiel die u eerder hebt gemaakt. Klik op **[!UICONTROL Save]** wanneer u klaar bent.

   ![](assets/image2014-12-9-9-3a20-3a56.png)

Stap 2 van 3 is voltooid.

>[!NOTE]
>
>[&#x200B; Stap 3 van 3: Verbind Marketo en  [!DNL Salesforce]  (Onderneming/Onbeperkt) &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)
