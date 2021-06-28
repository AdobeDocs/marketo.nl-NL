---
unique-page-id: 2360368
description: Marketo Sales Insight in Salesforce Enterprise/Unlimited - Marketo Docs - Productdocumentatie configureren
title: Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt
exl-id: a33ed396-8d26-403f-b6d8-fe7c55ce76ba
source-git-commit: fbd8640d55a9a38936d060086f361b2281add47f
workflow-type: tm+mt
source-wordcount: '898'
ht-degree: 0%

---

# Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt {#configure-marketo-sales-insight-in-salesforce-enterprise-unlimited}

Hier volgen de stappen die u moet uitvoeren om Marketo Sales Insight in Salesforce Enterprise/Unlimited Editions te configureren. Laten we beginnen.

>[!PREREQUISITES]
>
>* [Marketo Sales Insight Package installeren in Salesforce AppExchange](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)


>[!NOTE]
**Beheerdersmachtigingen vereist**

## Verkoopinzicht configureren in Marketo {#configure-sales-insight-in-marketo}

1. Open een nieuw browservenster om de gegevens voor Marketo Sales Insight van uw Marketo-account op te halen.

1. Ga naar het gebied Admin en selecteer **Sales Insight**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-1.png)

1. Klik **API-configuratie bewerken**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-2.png)

1. Voer een API-beveiligingssleutel van uw keuze in en klik op **Opslaan**. Gebruik geen en-teken (&amp;) in de API-beveiligingssleutel.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-3.png)

   >[!NOTE]
   De geheime sleutel van uw API is als een wachtwoord voor uw organisatie en zou veilig moeten zijn.

1. Klik **Weergave** in het deelvenster Configuratie van de rest-API om de referenties te vullen.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-4.png)

1. Er verschijnt een bevestigingspop-up. Klik **OK**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-5.png)

## Verkoopinzicht configureren in Salesforce {#configure-sales-insight-in-salesforce}

1. Klik in Salesforce op **Setup**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-6.png)

1. Zoek naar &quot;verre plaats&quot;en selecteer **Verre Montages van de Plaats**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-7.png)

1. Klik **Nieuwe verre Plaats**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-8.png)

1. Voer de naam van de externe site in (dit kan bijvoorbeeld &quot;MarketoSoapAPI&quot; zijn). Voer de URL voor de externe site in. Dit is de URL van de Marketo-host in het configuratievenster voor de Soap API in Marketo. Klik **Opslaan**. U hebt nu externe site-instellingen voor de Soap API gemaakt.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-9.png)

1. Klik nogmaals **Nieuwe externe site**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-10.png)

1. Voer de naam van de externe site in (dit kan bijvoorbeeld &quot;MarketoRestAPI&quot; zijn). Voer de URL van de externe site in. Dit is de API-URL van het configuratievenster voor de rest van de API in Marketo. Klik **Opslaan**. U hebt nu externe site-instellingen voor de rest-API gemaakt.

## Marketo Sales Insight instellen {#set-up-marketo-sales-insight}

1. Meld u aan bij uw Marketo-exemplaar en klik op **Admin**.

   ![](assets/login-admin.png)

1. Klik **Sales Insight**.

   ![](assets/image2015-5-22-15-3a12-3a33.png)

1. Klik **API-configuratie bewerken**.

   ![](assets/image2015-5-22-15-3a15-3a0.png)

1. Voer een **API-beveiligingssleutel** in en klik op **Opslaan**.

   >[!CAUTION]
   Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2015-5-27-16-3a36-3a56.png)

   >[!TIP]
   Laat dit venster open. U hebt deze informatie later nodig in Salesforce.

1. Ga terug naar Salesforce, klik **Opstelling**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. Zoek naar &quot;verre plaats&quot;en klik **Verre Plaats** onder **Controles van de Veiligheid**.

   ![](assets/image2014-9-24-17-3a25-3a52.png)

1. Klik **Nieuwe verre Plaats**.

   ![](assets/image2014-9-24-17-3a26-3a6.png)

1. Typ **Naam externe site** en **URL externe site** en klik vervolgens op **Opslaan**.

   ![](assets/remote-site.png)

   >[!NOTE]
   U kiest uw **Naam externe site** (MarketoAPI wordt hier gebruikt). De **Remote Site URL** vindt u in het veld Marketo-host van het dialoogvenster API-configuratie bewerken in stap 4.

## Paginalay-outs aanpassen {#customize-page-layouts}

1. Klik **Setup**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. Zoek naar &quot;paginalay-out&quot;en selecteer **Pagina Layout** onder **Leads**.

   ![](assets/image2015-5-28-14-3a58-3a39.png)

1. Klik **Visuale Pagina&#39;s** op de linkerzijde. Sleep **Sectie** naar de layout onder de sectie Aangepaste koppelingen.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. Voer &quot;Marketo Sales Insight&quot; in als de **Sectienaam**. Selecteer **1-Kolom** en klik **OK**.

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. Sleep **Lead** naar de nieuwe sectie.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   De naam van dit vak wordt gewijzigd op basis van het objecttype. Als u bijvoorbeeld de paginalay-out voor Contactpersonen wijzigt, wordt Contactpersoon weergegeven.

1. Dubbelklik op het **Lead** blok dat u net hebt toegevoegd.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. Bewerk de hoogte tot **450** pixels en klik op **OK**.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!TIP]
   We raden een hoogte van 410 pixels aan voor de objecten Accounts en Opportunity.

1. Klik op **Fields** op de linkerzijde. Zoek en sleep vervolgens het label **Betrokkenheid** naar de indeling **Marketo Sales Insight**.

   ![](assets/image2015-5-22-16-3a32-3a46.png)

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

1. Klik **Opslaan** wanneer u klaar bent.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. Herhaal dit proces om pagina secties Visualforce en de gebieden van het Inzicht van de Verkoop voor **Contact**, **Account** en **Opportunity** toe te voegen.

1. Herhaal stap 5-7 om Visualforce-paginagedeelten toe te voegen voor Contactpersoon, Account en Opportunity. Herhaal vervolgens stap 8-10 om de velden Verkoopinzicht toe te voegen voor **Contact**. Sla het bestand op nadat u wijzigingen hebt aangebracht.

## Aangepaste persoonlijke velden toewijzen {#map-custom-person-fields}

Marketo-persoonvelden moeten worden toegewezen aan Salesforce-contactvelden om ervoor te zorgen dat de conversie goed werkt. Zo gaat het.

1. Klik **Setup**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. Zoek naar &quot;gebieden&quot;in de onderzoeksbar en klik **Gebieden** onder **Leads**.

   ![](assets/image2015-6-1-9-3a54-3a50.png)

1. Klik **Velden voor regelafstand toewijzen**.

   ![](assets/image2015-6-1-9-3a58-3a48.png)

1. Klik op het vervolgkeuzemenu rechts voor **Betrokkenheid**.

   ![](assets/image2015-6-1-10-3a9-3a53.png)

1. Selecteer **Contact.Engagement** in de lijst.

   ![](assets/image2015-6-1-10-3a12-3a11.png)

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

1. Klik **Opslaan** wanneer u klaar bent.

## Marketo Sales Insight Config {#marketo-sales-insight-config}

1. Klik **+** en selecteer **Marketo Sales Insight Config**.

   ![](assets/image2014-9-24-17-3a37-3a45.png)

1. Schakel **Marketo API inschakelen**. Vul vervolgens de [API Configuration info in Marketo Admin](#set-up-marketo-sales-insight) in. Klik **Wijzigingen opslaan** wanneer u klaar bent.

   ![](assets/image2014-9-24-17-3a38-3a0.png)

   >[!NOTE]
   Als de diagnostische test mislukt, moet u mogelijk meer velden toevoegen aan uw paginalay-out](https://nation.marketo.com/docs/DOC-1115).[

En dat is het! Je moet de velden Marketo Sales Insight voor leads, Contacts, Accounts en Opportunity kunnen bekijken.

![](assets/twenty-six.png)

>[!NOTE]
Voor accounts omvat Verkoopinzicht alle e-mailberichten, maar alleen de meest recente interessante momenten, webactiviteit en scorewijzigingen.

## Marketo Sales Insight openen {#access-marketo-sales-insight}

1. Klik in Salesforce op **+** aan het einde van de tabbalk en klik op **Marketo Sales Insight Config**.

1. Schakel het selectievakje **Marketo API inschakelen** in.

1. Kopieer de gegevens vanuit het deelvenster Soap API in de pagina Sales Insight Admin van Marketo en plak ze in de sectie Soap API van de pagina Salesforce Sales Insight Configuration.

1. Kopieer de gegevens vanuit het venster Rest API in de pagina Sales Insight Admin van Marketo en plak ze in de sectie Rest API van de pagina Salesforce Sales Insight Configuration.

   ![](assets/access-msi.png)

>[!MORELIKETHIS]
* [Prioriteit, Urgentie, Relatieve Score en Beste Bets](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
* [Het tabblad Marketo Sales Insight en de knoppen aan Salesforce toevoegen](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/bulk-actions/add-marketo-sales-insight-tab-and-buttons-to-salesforce.md)
* [Het Inzicht van de Verkoop van de Opstelling voor uw Team](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/setting-up-sales-insight-for-your-team.md)

