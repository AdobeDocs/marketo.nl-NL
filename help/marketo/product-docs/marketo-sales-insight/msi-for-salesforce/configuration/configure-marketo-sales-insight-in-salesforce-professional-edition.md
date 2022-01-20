---
unique-page-id: 3571743
description: Marketo Sales Insight configureren in Salesforce Professional Edition - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight configureren in Salesforce Professional Edition
exl-id: fae63560-0bb3-46a9-94a3-cc27c1aa363e
source-git-commit: 84ac037a041398bdb1a056c3ab2fcf0d516f0097
workflow-type: tm+mt
source-wordcount: '901'
ht-degree: 0%

---

# Marketo Sales Insight configureren in Salesforce Professional Edition {#configure-marketo-sales-insight-in-salesforce-professional-edition}

Hier volgen de stappen die u moet uitvoeren om Marketo Sales Insight in Salesforce Professional Edition te configureren. Laten we beginnen.

>[!PREREQUISITES]
>
>* Installeer Marketo in uw Salesforce Professional Edition.
>
>* [Marketo Sales Insight Package installeren in Salesforce AppExchange](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)


>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Verkoopinzicht configureren in Marketo {#configure-sales-insight-in-marketo}

1. Open een nieuw browservenster om de gegevens voor Marketo Sales Insight van uw Marketo-account op te halen.
1. Ga naar het gebied Beheer en selecteer **Verkoopoverzicht**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-1-1.png)

1. Klikken **API-configuratie bewerken**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-2-1.png)

1. Voer een door u gekozen API-beveiligingssleutel in en klik op **Opslaan**. Gebruik geen en-teken (&amp;) in de API-beveiligingssleutel.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-3-1.png)

   >[!NOTE]
   >
   >De geheime sleutel van uw API is als een wachtwoord voor uw organisatie en zou veilig moeten zijn.

1. Klikken **Weergave** in het configuratievenster voor de rest-API om de referenties in te vullen.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-4-1.png)

1. Er verschijnt een bevestigingspop-up. Klikken **OK**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-5-1.png)

## Verkoopinzicht configureren in Salesforce {#configure-sales-insight-in-salesforce}

1. Klik in Salesforce op **Instellen**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-6-1.png)

1. Zoeken naar &quot;externe site&quot; en selecteren **Instellingen voor externe site**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-7-1.png)

1. Klikken **Nieuwe externe site**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-8-1.png)

1. Voer de naam van de externe site in (dit kan bijvoorbeeld &quot;MarketoSoapAPI&quot; zijn). Voer de URL voor de externe site in. Dit is de URL van de Marketo-host in het configuratievenster voor de Soap API in Marketo. Klikken **Opslaan**. U hebt nu externe site-instellingen voor de Soap API gemaakt.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-9-1.png)

1. Klikken **Nieuwe externe site** opnieuw.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-10-1.png)

1. Voer de naam van de externe site in (dit kan bijvoorbeeld &quot;MarketoRestAPI&quot; zijn). Voer de URL van de externe site in. Dit is de API-URL van het configuratievenster voor de rest van de API in Marketo. Klikken **Opslaan**. U hebt nu externe site-instellingen voor de rest-API gemaakt.

## Marketo Sales Insight instellen {#set-up-marketo-sales-insight}

1. Meld u aan bij uw Marketo-exemplaar en klik op **Beheer**.

   ![](assets/login-admin-1.png)

1. Klikken **Verkoopoverzicht**.

   ![](assets/image2015-5-22-15-3a12-3a33-1.png)

1. Klikken **API-configuratie bewerken**.

   ![](assets/image2015-5-22-15-3a15-3a0-1.png)

1. Voer een **API-beveiligingssleutel** en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2015-5-27-16-3a36-3a56-1.png)

   >[!TIP]
   >
   >Laat dit venster open. U hebt deze informatie later nodig in Salesforce.

1. Ga terug naar Salesforce en klik op **Instellen**.

   ![](assets/image2015-5-22-14-3a40-3a39-1.png)

1. Zoek naar &quot;verre plaats&quot; en klik **Externe site-instelling** krachtens **Beveiligingscontroles**.

   ![](assets/image2014-9-24-17-3a25-3a52.png)

1. Klikken **Nieuwe externe site**.

   ![](assets/image2014-9-24-17-3a26-3a6.png)

1. Enter **Externe sitenaam** en **URL externe site** en klik vervolgens op **Opslaan**.

   ![](assets/remote-site-1.png)

   >[!NOTE]
   >
   >U kiest uw **Externe sitenaam** (MarketoAPI wordt hier gebruikt). De **URL externe site** U vindt deze in stap 4 in het veld Marketo-host van het dialoogvenster API-configuratie bewerken.

## Paginalay-outs aanpassen {#customize-page-layouts}

1. Klikken **Instellen**.

   ![](assets/image2015-5-22-14-3a40-3a39-1.png)

1. Zoek naar &quot;paginalay-out&quot;en selecteer **Pagina-indeling** krachtens **Leads**.

   ![](assets/image2015-5-28-14-3a58-3a39-1.png)

1. Klikken **Visuale pagina&#39;s** links. Slepen **Sectie** naar de lay-out onder de sectie Aangepaste koppelingen.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. Voer &quot;Marketo Sales Insight&quot; in als de **Sectienaam**. Selecteren **1 kolom** en klik op **OK**.

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. Slepen en neerzetten **Lood** in de nieuwe sectie.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   >
   >De naam van dit vak wordt gewijzigd op basis van het objecttype. Als u bijvoorbeeld de paginalay-out voor Contactpersonen wijzigt, wordt Contactpersoon weergegeven.

1. Dubbelklik op de knop **Lood** blokkeren die u zojuist hebt toegevoegd.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. Hoogte bewerken tot **450** pixels en klik op **OK**.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!TIP]
   >
   >We raden een hoogte van 410 pixels aan voor de objecten Accounts en Opportunity.

1. Klikken op **Velden** links. Zoek en sleep vervolgens het gereedschap **Betrokkenheid** in de **Marketo Sales Insight** layout.

   ![](assets/image2015-5-22-16-3a32-3a46-1.png)

1. Herhaal de bovenstaande stap ook voor deze velden.

<table> 
 <tbody> 
  <tr> 
   <td colspan="1">Betrokkenheid</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Relatieve score</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Urgentiewaarde</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Datum laatste interessant moment</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Laatste interessante momentele beschrijving</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Laatste interessante mompbron</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Type laatst interessant moment</p></td> 
  </tr> 
 </tbody> 
</table>

1. likken **Opslaan** wanneer gereed.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. Herhaal dit proces om secties van de Visualforce-pagina en velden van het Inzicht van de Verkoop toe te voegen voor **Contact**, **Account** en **Opportunity**.
1. Herhaal stap 5-7 om Visualforce-paginagedeelten toe te voegen voor Contactpersoon, Account en Opportunity. Herhaal dan stap 8-10 om de gebieden van het Inzicht van de Verkoop voor toe te voegen **Contact**. Sla het bestand op nadat u wijzigingen hebt aangebracht.

## Aangepaste persoonlijke velden toewijzen {#map-custom-person-fields}

Marketo-persoonvelden moeten worden toegewezen aan Salesforce-contactvelden om ervoor te zorgen dat de conversie goed werkt. Zo gaat het.

1. Klikken **Instellen**.

   ![](assets/image2015-5-22-14-3a40-3a39-1.png)

1. Zoek naar &quot;gebieden&quot;in de onderzoeksbar en klik **Velden** krachtens **Leads**.

   ![](assets/image2015-6-1-9-3a54-3a50-1.png)

1. Klikken **Velden met regelafstand toewijzen**.

   ![](assets/image2015-6-1-9-3a58-3a48-1.png)

1. Klik op het vervolgkeuzemenu rechts voor **Betrokkenheid**.

   ![](assets/image2015-6-1-10-3a9-3a53-1.png)

1. Selecteren **Contact.Betrokkenheid** in de lijst.

   ![](assets/image2015-6-1-10-3a12-3a11-1.png)

1. U kunt deze velden ook herhalen en toewijzen.

<table> 
 <tbody> 
  <tr> 
   <th colspan="1" rowspan="1">Aangepast veld voor Marketo-persoon</th> 
   <th colspan="1" rowspan="1">Aangepast veld voor Salesforce-contact</th> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Betrokkenheid</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Engagement</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Relatieve score</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Relatieve score</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Urgentiewaarde</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Urence-waarde</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Datum laatste interessant moment</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Laatste interessante momentdatum</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Laatste interessante momentele beschrijving</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Laatste interessante momentele beschrijving</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Laatste interessante mompbron</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Laatste interessante momentele bron</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Type laatst interessant moment</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Laatste interessante momentype</p></td> 
  </tr> 
 </tbody> 
</table>

1. Klikken **Opslaan** als u klaar bent.

   ![](assets/image2014-9-24-17-3a37-3a17.png)

## Marketo Sales Insight Config {#marketo-sales-insight-config}

1. Klikken **+** en selecteer vervolgens **Marketo Sales Insight Config**.

   ![](assets/image2014-9-24-17-3a37-3a45.png)

1. Controleren **Marketo API inschakelen**. Vul vervolgens de [API-configuratiegegevens in Marketo Admin](#set-up-marketo-sales-insight). Klikken **Wijzigingen opslaan** als u klaar bent.

   ![](assets/image2014-9-24-17-3a38-3a0.png)

   >[!NOTE]
   >
   >Als de diagnostische test mislukt, moet u mogelijk [meer velden toevoegen aan uw pagina-indeling](https://nation.marketo.com/docs/DOC-1115).

En dat is het! Je moet de velden Marketo Sales Insight voor leads, Contacts, Accounts en Opportunity kunnen bekijken.

![](assets/twenty-six-1.png)

>[!NOTE]
>
>Voor accounts omvat Verkoopinzicht alle e-mailberichten, maar alleen de meest recente interessante momenten, webactiviteit en scorewijzigingen.

## Marketo Sales Insight openen {#access-marketo-sales-insight}

1. Klik in Salesforce op de knop **+** aan het einde van de tabbalk en klik op **Marketo Sales Insight Config**.

1. Selecteer **Marketo API inschakelen** selectievakje.

1. Kopieer de gegevens vanuit het deelvenster Soap API in de pagina Sales Insight Admin van Marketo en plak ze in de sectie Soap API van de pagina Salesforce Sales Insight Configuration.

1. Kopieer de gegevens vanuit het venster Rest API in de pagina Sales Insight Admin van Marketo en plak ze in de sectie Rest API van de pagina Salesforce Sales Insight Configuration.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-27.png)

>[!MORELIKETHIS]
>
>* [Prioriteit, Urgentie, Relatieve Score en Beste Bets](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
>* [Marketo Tab toevoegen aan Salesforce](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-marketo-tab-to-salesforce.md)
>* [Het Inzicht van de Verkoop van de Opstelling voor uw Team](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/setting-up-sales-insight-for-your-team.md)

