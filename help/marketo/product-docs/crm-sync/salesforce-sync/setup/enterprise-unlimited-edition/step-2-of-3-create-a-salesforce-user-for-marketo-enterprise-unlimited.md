---
unique-page-id: 2360364
description: Stap 2 van 3 - creeer een Gebruiker Salesforce voor Marketo (Onderneming/Onbeperkt) - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - creeer een Gebruiker Salesforce voor Marketo (Onderneming/Onbeperkt)
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '439'
ht-degree: 0%

---


# Stap 2 van 3: Een Salesforce-gebruiker voor markeren maken (Enterprise/Onbeperkt) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>Deze stappen moeten door een beheerder van Salesforce worden voltooid

>[!PREREQUISITES]
>
>* [Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt)](step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)

>



In dit artikel stelt u gebruikersmachtigingen in in het Salesforce-profiel en maakt u een Marketo-Salesforce-integratieaccount.

## Een profiel maken {#create-a-profile}

1. Klik op **Instellen**.

   ![](assets/image2015-6-11-16-3a15-3a27.png)

1. Typ &quot;profielen&quot; in de zoekbalk Nav en klik op de koppeling **Profielen** .

   ![](assets/sfdc-profiles-hands.png)

1. Klik op **Nieuw**.

   ![](assets/image2014-12-9-9-3a19-3a15.png)

1. Selecteer **Standaardgebruiker**, geef het profiel Marketo-Salesforce Sync een naam en klik op **Opslaan**.

   ![](assets/image2014-12-9-9-3a19-3a22.png)

## Profielmachtigingen instellen {#set-profile-permissions}

1. Klik op **Bewerken** om de beveiligingsmachtigingen in te stellen.

   ![](assets/image2014-12-9-9-3a19-3a30.png)

1. Controleer of onder de sectie **Administratieve machtigingen** de volgende vakken zijn ingeschakeld:

   * API ingeschakeld
   * HTML-sjablonen bewerken
   * Openbare documenten beheren
   * Openbare sjablonen beheren

   ![](assets/image2014-12-9-9-3a19-3a38.png)

   >[!TIP]
   >
   >Controleer of het vak **Wachtwoord nooit verlopen** is ingeschakeld.

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

1. Als u klaar bent, klikt u onder aan de pagina op **Opslaan** .

   ![](assets/image2014-12-9-9-3a20-3a5.png)

## Veldmachtigingen instellen {#set-field-permissions}

1. Bespreek met uw marketers welke aangepaste velden nodig zijn voor synchronisatie.

   >[!NOTE]
   >
   >Met deze stap voorkomt u dat velden die u niet nodig hebt, worden weergegeven in Marketo, waardoor de synchronisatie minder rommelig wordt en sneller verloopt.

1. Ga op de pagina met profieldetails naar de sectie **Veldbeveiliging** . Klik op **Weergave** om de toegankelijkheid voor de objecten te bewerken:

   * `Lead`
   * `Contact`
   * `Account`
   * `Opportunity`

   >[!TIP]
   >
   >U kunt andere voorwerpen op de behoeften van uw organisatie vormen.

   ![](assets/image2014-12-9-9-3a20-3a14.png)

1. Klik voor elk object op **Bewerken**.

   ![](assets/sfdc-sync-field-edit1.png)

1. Zoek de overbodige velden en zorg ervoor dat **Toegang lezen **en Toegang bewerken **** zijn uitgeschakeld. Klik op **Opslaan** als u klaar bent.

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Bewerk alleen de toegankelijkheid voor de aangepaste velden.

   ![](assets/sfdc-sync-field-edit2.png)

1. Nadat u alle onnodige velden hebt uitgeschakeld, moet u **Toegang lezen en Toegang **bewerken voor de volgende objectvelden inschakelen. Klik op **Opslaan** als u klaar bent.

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
>Een speciale Salesforce-account maken (bijvoorbeeld [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#89e4e8fbe2ecfde6c9f0e6fcfbeae6e4f9e8e7f0a7eae6e4)) om een onderscheid te maken tussen de wijzigingen die door Marketo en andere Salesforce-gebruikers zijn aangebracht.

1. Typ &quot;Gebruikers beheren&quot; in de zoekbalk van Nav en klik vervolgens op **Gebruikers**. Klik op **Nieuwe gebruiker**.

   ![](assets/sfdc-new-users.png)

1. Vul de vereiste velden in. Selecteer vervolgens de **gebruikerslicentie: Salesforce** en het profiel dat u eerder hebt gemaakt. Klik op **Opslaan** als u klaar bent.

   ![](assets/image2014-12-9-9-3a20-3a56.png)

Stap 2 van 2 is voltooid.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Stap 3 van 3: Connect Marketo en Salesforce (Enterprise/Onbeperkt)](step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)

>



