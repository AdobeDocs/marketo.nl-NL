---
unique-page-id: 2360364
description: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt) - Marketo Docs - Productdocumentatie
title: Stap 2 van 3 - Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)
exl-id: 871f335c-7b1e-47e1-8320-a18fbf21a970
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 0%

---

# Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>Deze stappen moeten door een beheerder van Salesforce worden voltooid

>[!PREREQUISITES]
>
>[Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)

In dit artikel stelt u gebruikersmachtigingen in in het Salesforce-profiel en maakt u een Marketo-Salesforce-integratieaccount.

## Een profiel maken {#create-a-profile}

1. Klikken **Instellen**.

   ![](assets/image2015-6-11-16-3a15-3a27.png)

1. Typ &quot;profielen&quot; in de navigatiebalk en klik op de knop **Profielen** koppeling.

   ![](assets/sfdc-profiles-hands.png)

1. Klikken op **Nieuw**.

   ![](assets/image2014-12-9-9-3a19-3a15.png)

1. Selecteren **Standaardgebruiker**, geef het profiel &quot;Marketo-Salesforce Sync&quot; een naam en klik op **Opslaan**.

   ![](assets/image2014-12-9-9-3a19-3a22.png)

## Profielmachtigingen instellen {#set-profile-permissions}

1. Klikken **Bewerken** om de beveiligingsmachtigingen in te stellen.

   ![](assets/image2014-12-9-9-3a19-3a30.png)

1. Onder de **Administratieve machtigingen** , controleert u of de volgende vakken zijn ingeschakeld:

   * API ingeschakeld
   * HTML-sjablonen bewerken
   * Openbare documenten beheren
   * Openbare sjablonen beheren

   ![](assets/image2014-12-9-9-3a19-3a38.png)

   >[!TIP]
   >
   >Controleer de **Wachtwoord verloopt nooit** doos.

1. Controleer of onder de sectie Algemene gebruikersmachtigingen de volgende vakken zijn ingeschakeld:

   * Leads omzetten
   * Gebeurtenissen bewerken
   * Taken bewerken

   ![](assets/image2014-12-9-9-3a19-3a47.png)

1. Controleer in de sectie Standaardobjectmachtigingen of de machtigingen Lezen, Maken, Bewerken en Verwijderen zijn ingeschakeld voor:

   * Accounts
   * Campagnes
   * Contactpersonen
   * Leads
   * Kansen

   >[!NOTE]
   >
   >Verleen toestemmingen aan de Campagnes, als u van plan bent om de Synchronisatie van de Campagne te gebruiken.

   ![](assets/image2014-12-9-9-3a19-3a57.png)

1. Als u klaar bent, klikt u op **Opslaan** onder aan de pagina.

   ![](assets/image2014-12-9-9-3a20-3a5.png)

## Veldmachtigingen instellen {#set-field-permissions}

1. Bespreek met uw marketers welke aangepaste velden nodig zijn voor synchronisatie.

   >[!NOTE]
   >
   >Met deze stap voorkomt u dat velden die u niet nodig hebt, worden weergegeven in Marketo, waardoor de synchronisatie minder rommelig wordt en sneller verloopt.

1. Ga op de pagina met profieldetails naar **Beveiliging op veldniveau** sectie. Klikken **Weergave** om de toegankelijkheid voor de objecten te bewerken:

   * Lood
   * Contact
   * Account
   * Opportunity

   >[!TIP]
   >
   >U kunt andere voorwerpen op de behoeften van uw organisatie vormen.

   ![](assets/image2014-12-9-9-3a20-3a14.png)

1. Voor elk object klikt u op **Bewerken**.

   ![](assets/sfdc-sync-field-edit1.png)

1. Zoek de overbodige velden en zorg ervoor dat **Leestoegang** en **Toegang bewerken** zijn uitgeschakeld. Klikken **Opslaan** als u klaar bent.

   >[!NOTE]
   >
   >Bewerk alleen de toegankelijkheid voor de aangepaste velden.

   ![](assets/sfdc-sync-field-edit2.png)

1. Nadat u alle overbodige velden hebt uitgeschakeld, moet u **Toegang lezen en bewerken** voor de volgende objectvelden. Klikken **Opslaan** als u klaar bent.

<table> 
 <tbody> 
  <tr> 
   <th colspan="1" rowspan="1"><p>Object</p></th> 
   <th colspan="1" rowspan="1"><p>Velden</p></th> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Account</p></td> 
   <td colspan="1" rowspan="1"><p>Tekstveld</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Gebeurtenis</p></td> 
   <td colspan="1" rowspan="1"><p>Alle velden</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Taak</p></td> 
   <td colspan="1" rowspan="1"><p>Alle velden</p></td> 
  </tr> 
 </tbody> 
</table>

![](assets/sfdc-check-the-boxes.png)

## Marketo-Salesforce-synchronisatieaccount maken {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>Maak een speciale Salesforce-account (bijv. marketo@yourcompany.com) om onderscheid te maken tussen de wijzigingen die door Marketo en andere Salesforce-gebruikers zijn aangebracht.

1. Typ &quot;Gebruikers beheren&quot; in de zoekbalk Nav en klik op **Gebruikers**. Klikken op **Nieuwe gebruiker**.

   ![](assets/sfdc-new-users.png)

1. Vul de vereiste velden in. Selecteer vervolgens de **Gebruikerslicentie: Salesforce** en het profiel dat u eerder hebt gemaakt. Klikken **Opslaan** als u klaar bent.

   ![](assets/image2014-12-9-9-3a20-3a56.png)

Stap 2 van 2 is voltooid.

>[!NOTE]
>
>[Stap 3 van 3: Connect Marketo en Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)
