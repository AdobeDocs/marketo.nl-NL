---
description: Salesforce Classic-aanpassingspakket verwijderen - Marketo Docs - Productdocumentatie
title: Salesforce Classic-aanpassingspakket verwijderen
hide: true
hidefromtoc: true
exl-id: 1216d313-28b7-4505-8378-a16a475c707c
source-git-commit: 9186e15ea99052ef83a877ac336979acff5e692d
workflow-type: tm+mt
source-wordcount: '1187'
ht-degree: 0%

---

# Salesforce Classic-aanpassingspakket verwijderen {#uninstall-salesforce-classic-customization-package}

Verwijder het Marketo Sales Connect-pakket van uw Salesforce-account als u het MSI-handelingspakket gebruikt.

## Verkoop Connect-velden verwijderen uit paginalayout {#remove-sales-connect-fields-from-page-layout}

1. Klik in Salesforce Classic op **Instellen**.

   ![](assets/uninstall-salesforce-classic-customization-package-1.png)

1. Vouw in de linkernavigatiebalk onder Build (maar klik niet op) Aanpassen en Leads uit. Selecteer vervolgens **Pagina-indelingen**.

   ![](assets/uninstall-salesforce-classic-customization-package-2.png)

1. Klikken **Bewerken** naast Lay-out lead.

   ![](assets/uninstall-salesforce-classic-customization-package-3.png)

1. Selecteer in de console de optie **Velden**. Zoek in Snel zoeken naar &quot;MSC.&quot; Alle grijze velden zijn toegevoegd aan de pagina-indeling. U moet ze verwijderen.

   ![](assets/uninstall-salesforce-classic-customization-package-4.png)

   >[!NOTE]
   >
   >Als geen van de velden grijs wordt weergegeven, hebt u deze niet toegevoegd aan de pagina-indeling. U kunt deze sectie overslaan.

1. Blader naar de sectie met uw aangepaste verkoopvelden voor Connect.

   ![](assets/uninstall-salesforce-classic-customization-package-5.png)

1. Er zijn 10 types van gebieden MSC die aan deze sectie kunnen worden toegevoegd. Verwijder alle velden die u hebt toegevoegd of verwijder gewoon de volledige sectie.

1. Klikken **Snel opslaan** wanneer gereed.

   ![](assets/uninstall-salesforce-classic-customization-package-6.png)

## Knoppen Verkoop verbinden verwijderen uit pagina-indelingen {#remove-sales-connect-buttons-from-page-layouts}

1. Selecteer in de console (stap 4 hierboven) de optie **Knoppen**. Zoeken naar MSC. Alle grijze knoppen zijn toegevoegd aan de sectie Aangepaste knoppen. U moet ze verwijderen.

   ![](assets/uninstall-salesforce-classic-customization-package-7.png)

   >[!NOTE]
   >
   >Als geen van de knoppen grijs wordt weergegeven, betekent dit dat u ze niet hebt toegevoegd. U kunt deze sectie overslaan.

1. Sleep de knopen MSC van de sectie van de Knopen van de Douane aan de console.

   ![](assets/uninstall-salesforce-classic-customization-package-8.png)

1. Klikken **Snel opslaan** wanneer gereed.

   ![](assets/uninstall-salesforce-classic-customization-package-9.png)

## Verkoop Connect-velden verwijderen uit sectie Activiteitenoverzicht {#remove-sales-connect-fields-from-activity-history-section}

1. Blader naar de onderkant van de pagina en klik op het pictogram Sleutel.

   ![](assets/uninstall-salesforce-classic-customization-package-10.png)

1. Selecteer de velden Verkoop Connect in het gebied Geselecteerde velden en klik op de pijl Verwijderen. Klikken **OK** wanneer gereed.

   ![](assets/uninstall-salesforce-classic-customization-package-11.png)

   >[!NOTE]
   >
   >De afkorting MSE _is_ Sales Connect. Het is gewoon de vorige naam, &quot;Marketo Sales Engage&quot;.

1. Klikken **Opslaan** als u klaar bent met de pagina Leads.

## Knoppen Handeling bulksgewijs verkopen verwijderen uit de koplijstweergave {#remove-sales-connect-bulk-action-buttons-from-lead-list-view}

1. Vouw in de linkernavigatiebalk onder Build (maar klik niet op) Aanpassen en Leads uit. Selecteer vervolgens **Schermindelingen zoeken**.

   ![](assets/uninstall-salesforce-classic-customization-package-12.png)

1. Klik naast de weergave Lijst met leads op **Bewerken**.

   ![](assets/uninstall-salesforce-classic-customization-package-13.png)

1. Selecteren **Toevoegen aan MSC-campagne (klassiek)**, **E-mail met MSC (Klassiek)**, en **Verschuiven naar MSC (klassiek)** en klikt u op de pijl Verwijderen. Klik vervolgens op **Opslaan**.

   ![](assets/uninstall-salesforce-classic-customization-package-14.png)

De knoppen in de weergave voor de lijst met leads worden niet meer weergegeven.

## MSC-configuratie verwijderen voor contactpersonen {#remove-msc-configuration-for-contacts}

1. Klik in Salesforce op **Instellen**.

1. In linkernav, onder Bouwstijl, breid uit (maar klik niet op) aanpassen, toen Contacten. Selecteer vervolgens **Pagina-indelingen**.

1. Klik naast Contactlay-out op **Bewerken**.

1. Herhaal de stappen van alle drie de secties.

## MSC-configuratie voor opportunity verwijderen {#remove-msc-configuration-for-opportunity}

1. Klik in Salesforce op **Instellen**.

1. Vouw in de linkernavigatiebalk onder Build (maar klik niet op) Aanpassen en vervolgens Opportunity uit. Selecteer vervolgens **Pagina-indelingen**.

1. Klik naast Opportunity Layout op **Bewerken**.

1. Herhaal de stappen van alle drie de secties.

De opportuniteitsweergave heeft slechts één knop - &quot;MSE-mail verzenden&quot; en de volgende velden:

![](assets/uninstall-salesforce-classic-customization-package-15.png)

## MSC-configuratie voor account verwijderen {#remove-msc-configuration-for-account}

1. Klik in Salesforce op **Instellen**.

1. Vouw in de linkernavigatiebalk onder Build (maar klik niet op) Aanpassen en vervolgens Account. Selecteer vervolgens **Pagina-indelingen**.

1. Klik naast Account Layout op **Bewerken**.

1. Herhaal de stappen van alle drie de secties.

De accountweergave heeft slechts één knop - &quot;MSE-mail verzenden&quot; en de volgende velden:

![](assets/uninstall-salesforce-classic-customization-package-16.png)

## Postvak UIT Marketo-verkoop verwijderen {#remove-marketo-sales-outbox}

1. Klik in Salesforce op de knop **+** boven aan het scherm.

1. Klikken **Mijn tabbladen aanpassen**.

1. Selecteer aan de rechterkant de optie Postvak UIT verkopen van Marketo. Klik op de pijl Verwijderen en klik vervolgens op **Opslaan**.

## Sales Connect-pakket verwijderen {#delete-sales-connect-package}

Nadat u alle objecten van uw Salesforce-account hebt verwijderd, voert u de onderstaande stappen uit.

1. Klik in Salesforce op **Instellen**.

1. Typ &quot;Apex-klassen&quot; in het vak Snel zoeken.

1. Klikken **Verwijderen** naast alle vermeldingen &quot;MarketoSalesConnectionCustomization&quot; of &quot;MarketoSalesEngageCustomization&quot; in uw lijst.

U bent klaar!

Hier volgt een lijst met alle objecten die uit uw Salesforce-instantie moeten worden verwijderd:

## Aanpassingsgegevens van Sales Connect {#sales-connect-customization-details}

<table>
 <tr>
  <th>Aangepaste activiteitsvelden</th>
  <th>Beschrijving</th>
  <th>Type</th>
  <th>Gegevenstype</th>
 </tr>
 <tr>
  <td>Lokale Aanwezigheidsidentiteitskaart van de Vraag MSC</td>
  <td>Als gebruiker, kan ik Lokale Aanwezigheid als optie kiezen wanneer ik vraag van Telefoon MSC. De inkomende vraag zal een lokaal aantal voor de ontvanger tonen</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC-URL voor opnamen van oproepen</td>
  <td>De vraag kan worden geregistreerd en een verbinding voor de opname zal hier worden geregistreerd </td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC-campagne</td>
  <td>Logs naam van de MSC campagne de contact/lood is op</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>URL voor MSC-campagne</td>
  <td>Logs URL aan de campagne die in MSC werd gecreeerd. Als u hierop klikt, wordt de campagne geopend in de MSC-webtoepassing</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>Huidige stap MSC-campagne</td>
  <td>Als een contact/lood op een campagne is, zal dit gebied de naam van de stap registreren zij momenteel op zijn</td>
  <td>Activiteit</td>
  <td>Selectievakje</td>
 </tr>
 <tr>
  <td>MSC-e-mailbijlage weergegeven</td>
  <td>Hiermee worden gegevens geregistreerd wanneer een e-mailbericht wordt verzonden met een bijlage die door de ontvanger wordt weergegeven</td>
  <td>Activiteit</td>
  <td>Selectievakje</td>
 </tr>
 <tr>
  <td>MSC-e-mail geklikt</td>
  <td>Hiermee wordt een vinkje geregistreerd wanneer de ontvanger op een koppeling in de e-mail klikt</td>
  <td>Activiteit</td>
  <td>Selectievakje</td>
 </tr>
 <tr>
  <td>MSC-e-mail gereageerd</td>
  <td>Logt een vinkje in wanneer de ontvanger op e-mail antwoordt</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC-e-mailstatus</td>
  <td>Geeft aan of een e-mail is verzonden/bezig/teruggestuurd (het bijhouden van teruggestuurde e-mails is afhankelijk van het gebruikte leveringskanaal)</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC-e-mailsjabloon</td>
  <td>Logs naam van het malplaatje MSC dat in e-mail werd gebruikt die naar de lood/de contact wordt verzonden</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>URL MSC-e-mailsjabloon</td>
  <td>Logs URL aan het malplaatje dat in MSC werd gecreeerd. Als u hierop klikt, wordt de sjabloon geopend in de MSC-webtoepassing</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC-e-mailURL</td>
  <td>Als u op deze URL klikt, wordt het opdrachtcentrum in MSC geopend en wordt het tabblad Historie van Personendetails weergegeven, waar de gebruiker de verzonden e-mail kan zien</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC-e-mail weergegeven</td>
  <td>Logt een vinkje in wanneer de ontvanger een e-mail bekijkt</td>
  <td>Activiteit</td>
  <td>Selectievakje</td>
 </tr>
</table>

<table>
 <tr>
  <th>MSC Logboekveld voor oprollen</th>
  <th>Beschrijving</th>
  <th>Type</th>
  <th>Gegevenstype</th>
 </tr>
 <tr>
  <td>MSC - Laatste marketingservice</td>
  <td>Laatste inkomende betrokkenheid van Marketing</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Gegevens en tijd</td>
 </tr>
 <tr>
  <td>MSC - Datum laatste marketingservice</td>
  <td>Tijdstempel voor betrokkenheid bij marketing</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Gegevens en tijd</td>
 </tr>
 <tr>
  <td>MSC - Laatste marketingservice</td>
  <td>Beschrijving van de betrokkenheid</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC - Laatste bron voor marketingservice</td>
  <td>Bron van marketingovereenkomst</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC - Laatste type marketingservice</td>
  <td>Soort betrokkenheid (bijv.: Webactiviteit)</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC - Laatste activiteit door verkoop</td>
  <td>Laatste uitgaande activiteit uitgevoerd door het verkoopteam</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Gegevens en tijd</td>
 </tr>
 <tr>
  <td>MSC - Laatste reactie</td>
  <td>Laatste e-mailantwoord op e-mail over verkoop</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Gegevens en tijd</td>
 </tr>
 <tr>
  <td>MSC - Huidige verkoopcampagne</td>
  <td>Logs naam van de MSC campagne de contact/lood is op</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC - Laatste verkoopservice</td>
  <td>Laatste inkomende betrokkenheid van Sales</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Gegevens en tijd</td>
 </tr>
 <tr>
  <td>MSC - Weigeren</td>
  <td>Veld Weigeren</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
  <td>Selectievakje</td>
 </tr>
</table>

<table>
 <tr>
  <th>MSC-knoppen</th>
  <th>Beschrijving</th>
  <th>Type</th>
 </tr>
 <tr>
  <td>MSC-e-mail verzenden</td>
  <td>E-mails over verkopen verzenden vanuit Salesforce</td>
  <td>
  <p>Account 
  <p>Contact 
  <p>Lood 
  <p>Opportunity</td>
 </tr>
 <tr>
  <td>Toevoegen aan MSC-campagne</td>
  <td>Toevoegen aan MSC-campagnes van Salesforce</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>Naar MSC duwen</td>
  <td>Zet contact op van Salesforce naar MSC</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>Vraag met MSC</td>
  <td>Maak verkoopvraag van Salesforce</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
</table>

<table>
 <tr>
  <th>MSC Bulk Action Buttons</th>
  <th>Beschrijving</th>
  <th>Type</th>
 </tr>
 <tr>
  <td>Toevoegen aan MSC-campagne (klassiek)</td>
  <td>Toevoegen aan MSC-campagnes van Salesforce</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>Verschuiven naar MSC (klassiek)</td>
  <td>Zet contact op van Salesforce naar MSC</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>E-mail met MSC (Klassiek)</td>
  <td>E-mail met MSC van Salesforce</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
</table>
