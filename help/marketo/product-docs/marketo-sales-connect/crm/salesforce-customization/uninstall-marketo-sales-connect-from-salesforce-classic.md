---
description: Marketo Sales Connect verwijderen uit Salesforce Classic - Marketo Docs - Productdocumentatie
title: Marketo Sales Connect verwijderen uit Salesforce Classic
exl-id: 17078054-a615-4f2f-bfde-f28fd3ff6f48
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '1025'
ht-degree: 0%

---

# Marketo Sales Connect verwijderen uit Salesforce Classic {#uninstall-marketo-sales-connect-from-salesforce-classic}

Hieronder wordt beschreven hoe u het Marketo Sales Connect-pakket verwijdert van uw Salesforce-account wanneer u de Handelingen van Sales Insight gaat gebruiken.

## [!DNL Sales Connect] velden verwijderen uit paginalayout {#remove-sales-connect-fields-from-page-layout}

1. Klik in [!DNL Salesforce] Klassiek op **[!UICONTROL Setup]** .

   ![](assets/uninstall-salesforce-classic-customization-package-1.png)

1. Vouw in de linkernav onder [!UICONTROL Build] uit (maar klik niet op) [!UICONTROL Customize] en vervolgens [!UICONTROL Leads] . Selecteer vervolgens **[!UICONTROL Page Layouts]** .

   ![](assets/uninstall-salesforce-classic-customization-package-2.png)

1. Klik op **[!UICONTROL Edit]** naast Lay-out lead.

   ![](assets/uninstall-salesforce-classic-customization-package-3.png)

1. Selecteer **[!UICONTROL Fields]** in de console. Zoek in Snel zoeken naar &quot;MSC.&quot; Alle grijze velden zijn toegevoegd aan de pagina-indeling. U moet ze verwijderen.

   ![](assets/uninstall-salesforce-classic-customization-package-4.png)

   >[!NOTE]
   >
   >Als geen van de velden grijs wordt weergegeven, hebt u deze niet toegevoegd aan de pagina-indeling. U kunt deze sectie overslaan.

1. Blader naar de sectie met de aangepaste velden van [!DNL Sales Connect] .

   ![](assets/uninstall-salesforce-classic-customization-package-5.png)

1. Er zijn 10 types van gebieden MSC die aan deze sectie kunnen worden toegevoegd. Verwijder alle velden die u hebt toegevoegd of verwijder gewoon de volledige sectie.

1. Klik op **[!UICONTROL Quick Save]** als u klaar bent.

   ![](assets/uninstall-salesforce-classic-customization-package-6.png)

## Knoppen [!DNL Sales Connect] verwijderen uit pagina-indelingen {#remove-sales-connect-buttons-from-page-layouts}

1. Selecteer **[!UICONTROL Buttons]** in de console (stap 4 hierboven). Zoeken naar MSC. Alle grijze knoppen zijn toegevoegd aan de sectie Aangepaste knoppen. U moet ze verwijderen.

   ![](assets/uninstall-salesforce-classic-customization-package-7.png)

   >[!NOTE]
   >
   >Als geen van de knoppen grijs wordt weergegeven, betekent dit dat u ze niet hebt toegevoegd. U kunt deze sectie overslaan.

1. Sleep de MSC-knoppen van de sectie [!UICONTROL Custom Buttons] naar de console.

   ![](assets/uninstall-salesforce-classic-customization-package-8.png)

1. Klik op **[!UICONTROL Quick Save]** als u klaar bent.

   ![](assets/uninstall-salesforce-classic-customization-package-9.png)

## [!DNL Sales Connect] Velden verwijderen uit [!UICONTROL Activity History] sectie {#remove-sales-connect-fields-from-activity-history-section}

1. Blader naar de onderzijde van de pagina naar de sectie met de [!UICONTROL Activity History] -lijst en klik op het pictogram Sleutel.

   ![](assets/uninstall-salesforce-classic-customization-package-10.png)

1. Selecteer de velden [!DNL Sales Connect] in het [!UICONTROL Selected Fields] -gebied en klik op de pijl [!UICONTROL Remove] . Klik op **[!UICONTROL OK]** als u klaar bent.

   ![](assets/uninstall-salesforce-classic-customization-package-11.png)

   >[!NOTE]
   >
   >De afkorting MSE _is_ [!DNL Sales Connect]. Het is gewoon de vorige naam, &quot;Marketo Sales Engage&quot;.

1. Klik **sparen** wanneer u met de pagina van Leads wordt gedaan.

## Knoppen voor [!DNL Sales Connect] bulkacties verwijderen uit de weergave voor de lijst met leads {#remove-sales-connect-bulk-action-buttons-from-lead-list-view}

1. Vouw in de linkernav onder [!UICONTROL Build] uit (maar klik niet op) [!UICONTROL Customize] en vervolgens [!UICONTROL Leads] . Selecteer vervolgens **[!UICONTROL Search Layouts]** .

   ![](assets/uninstall-salesforce-classic-customization-package-12.png)

1. Klik op **[!UICONTROL Edit]** naast de lijstweergave voor leads.

   ![](assets/uninstall-salesforce-classic-customization-package-13.png)

1. Selecteer **[!UICONTROL Add to MSC Campaign (Classic)]** , **[!UICONTROL Email with MSC (Classic)]** en **[!UICONTROL Push to MSC (Classic)]** en klik op de pijl [!UICONTROL Remove] . Klik vervolgens op **[!UICONTROL Save]** .

   ![](assets/uninstall-salesforce-classic-customization-package-14.png)

De knoppen in de weergave voor de lijst met leads worden niet meer weergegeven.

## MSC-configuratie verwijderen voor contactpersonen {#remove-msc-configuration-for-contacts}

1. Klik in [!DNL Salesforce] op **[!UICONTROL Setup]** .

1. Vouw in de linkernav onder [!UICONTROL Build] uit (maar klik niet op) [!UICONTROL Customize] en vervolgens [!UICONTROL Contacts] . Selecteer vervolgens **[!UICONTROL Page Layouts]** .

1. Klik op **[!UICONTROL Edit]** naast Contactlay-out.

1. Herhaal de stappen van alle drie de secties.

## MSC-configuratie voor opportunity verwijderen {#remove-msc-configuration-for-opportunity}

1. Klik in [!DNL Salesforce] op **[!UICONTROL Setup]** .

1. Vouw in de linkernav onder [!UICONTROL Build] uit (maar klik niet op) [!UICONTROL Customize] en vervolgens [!UICONTROL Opportunities] . Selecteer vervolgens **[!UICONTROL Page Layouts]** .

1. Klik op **[!UICONTROL Edit]** naast Opportunity Layout.

1. Herhaal de stappen van alle drie de secties.

De opportuniteitsweergave heeft slechts één knop - &quot;MSE-mail verzenden&quot; en de volgende velden:

![](assets/uninstall-salesforce-classic-customization-package-15.png)

## MSC-configuratie voor account verwijderen {#remove-msc-configuration-for-account}

1. Klik in [!DNL Salesforce] op **[!UICONTROL Setup]** .

1. Vouw in de linkernav onder [!UICONTROL Build] uit (maar klik niet op) [!UICONTROL Customize] en vervolgens [!UICONTROL Account] . Selecteer vervolgens **[!UICONTROL Page Layouts]** .

1. Klik op **[!UICONTROL Edit]** naast Account Layout.

1. Herhaal de stappen van alle drie de secties.

De accountweergave heeft slechts één knop - &quot;MSE-mail verzenden&quot; en de volgende velden:

![](assets/uninstall-salesforce-classic-customization-package-16.png)

## Postvak UIT Marketo-verkoop verwijderen {#remove-marketo-sales-outbox}

1. Klik in [!DNL Salesforce] op de tab **+** boven aan het scherm.

1. Klik op **[!UICONTROL Customize My Tabs]**.

1. Selecteer aan de rechterkant de optie Postvak UIT verkopen van Marketo. Klik op de pijl [!UICONTROL Remove] en klik vervolgens op **[!UICONTROL Save]** .

## [!DNL Sales Connect] Pakket verwijderen {#delete-sales-connect-package}

Nadat u alle objecten van uw Salesforce-account hebt verwijderd, volgt u de onderstaande stappen.

1. Klik in [!DNL Salesforce] op **[!UICONTROL Setup]** .

1. Typ &quot;Apex-klassen&quot; in het vak Snel zoeken.

1. Klik **Schrapping** naast alle &quot;MarketoSalesConnectionCustomization&quot;of &quot;MarketoSalesEngageCustomization&quot;ingangen op uw lijst.

U bent klaar!

Hier volgt een lijst met alle objecten die uit uw Salesforce-exemplaar moeten worden verwijderd:

## [!DNL Sales Connect] Aanpassingsdetails {#sales-connect-customization-details}

<table>
 <tr>
  <th>Aangepaste activiteitsvelden</th>
  <th>Beschrijving</th>
  <th>Type</th>
  <th>Gegevenstype</th>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Call Local Presence ID]</td>
  <td>Als gebruiker, kan ik Lokale Aanwezigheid als optie kiezen wanneer ik vraag van Telefoon MSC. De inkomende vraag zal een lokaal aantal voor de ontvanger tonen</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Call Recording URL]</td>
  <td>De vraag kan worden geregistreerd en een verbinding voor de opname zal hier worden geregistreerd </td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Campaign]</td>
  <td>Logs naam van de MSC campagne de contact/lood is op</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Campaign URL]</td>
  <td>Logs URL aan de campagne die in MSC werd gecreeerd. Als u hierop klikt, wordt de campagne geopend in de MSC-webtoepassing</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Campaign Current Step]</td>
  <td>Als een contact/lood op een campagne is, zal dit gebied de naam van de stap registreren zij momenteel op zijn</td>
  <td>Activiteit</td>
  <td>Selectievakje</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Attachment Viewed]</td>
  <td>Hiermee worden gegevens geregistreerd wanneer een e-mailbericht wordt verzonden met een bijlage die door de ontvanger wordt weergegeven</td>
  <td>Activiteit</td>
  <td>Selectievakje</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Clicked]</td>
  <td>Hiermee wordt een vinkje geregistreerd wanneer de ontvanger op een koppeling in de e-mail klikt</td>
  <td>Activiteit</td>
  <td>Selectievakje</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Replied]</td>
  <td>Logt een vinkje in wanneer de ontvanger op e-mail antwoordt</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Status]</td>
  <td>Geeft aan of een e-mail is verzonden/bezig/teruggestuurd (het bijhouden van teruggestuurde e-mails is afhankelijk van het gebruikte leveringskanaal)</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Template]</td>
  <td>Logs naam van het malplaatje MSC dat in e-mail werd gebruikt die naar de lood/de contact wordt verzonden</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Template URL]</td>
  <td>Logs URL aan het malplaatje dat in MSC werd gecreeerd. Als u hierop klikt, wordt de sjabloon geopend in de MSC-webtoepassing</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email URL]</td>
  <td>Als u op deze URL klikt, wordt het opdrachtcentrum in MSC geopend en wordt het tabblad Historie van Personendetails weergegeven, waar de gebruiker de verzonden e-mail kan zien</td>
  <td>Activiteit</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Viewed]</td>
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
  <td>MSC - Last Marketing Engagement Source</td>
  <td>Source van marketingovereenkomst</td>
  <td>
  <p>Account
  <p>Contact
  <p>Lood
  <p>Opportunity</td>
  <td>Tekst</td>
 </tr>
 <tr>
  <td>MSC - Last Marketing Engagement Type</td>
  <td>Soort betrokkenheid (bijv. webactiviteit)</td>
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
  <td>[!UICONTROL Send MSC Email]</td>
  <td>E-mails over verkopen verzenden van [!DNL Salesforce]</td>
  <td>
  <p>Account
  <p>Contact
  <p>Lood
  <p>Opportunity</td>
 </tr>
 <tr>
  <td>[!UICONTROL Add to MSC Campaign]</td>
  <td>Toevoegen aan MSC-campagnes vanuit [!DNL Salesforce]</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>[!UICONTROL Push to MSC]</td>
  <td>Contact van [!DNL Salesforce] naar MSC verplaatsen</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>[!UICONTROL Call with MSC]</td>
  <td>Maak verkoopvraag van [!DNL Salesforce]</td>
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
  <td>[!UICONTROL Add to MSC Campaign (Classic)]</td>
  <td>Toevoegen aan MSC-campagnes vanuit [!DNL Salesforce]</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>[!UICONTROL Push to MSC (Classic)]</td>
  <td>Contact van [!DNL Salesforce] naar MSC verplaatsen</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
 <tr>
  <td>[!UICONTROL Email with MSC (Classic)]</td>
  <td>E-mailen met MSC van [!DNL Salesforce]</td>
  <td>
  <p>Contact
  <p>Lood</td>
 </tr>
</table>
