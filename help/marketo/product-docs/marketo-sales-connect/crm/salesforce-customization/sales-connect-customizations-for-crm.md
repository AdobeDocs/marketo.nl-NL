---
unique-page-id: 14745793
description: Aanpassingen voor verkoop Connect voor CRM - Marketo Docs - Productdocumentatie
title: Aanpassingen voor verkoop Connect voor CRM
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '626'
ht-degree: 0%

---


# Aanpassingen voor verkoop Connect voor CRM {#sales-connect-customizations-for-crm}

De onderstaande velden en knoppen worden gemaakt met de metagegevens-API in Salesforce CRM. Zodra de gebieden worden gecreeerd, moeten de beheerders de paginalay-outs in hun CRM vormen om hen bloot te stellen. Instructies vindt u [hier](https://docs.marketo.com/display/docs/assets/marketo-sales-engage-for-salesforce-installation-and-success-guide.pdf).

>[!NOTE]
>
>Dit is van invloed op zowel ToutApp- als Sales Connect-klanten.

## Hoe te om Aanpassingen in Salesforce {#how-to-install-customizations-in-salesforce} te installeren

1. Klik in Sales Connect op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/one.png)

1. Selecteer **Salesforce** onder Beheerinstellingen.

   ![](assets/two.png)

1. Klik **Aanpassingen van de Verkoop van Marketo verbinden**.

   ![](assets/three.png)

1. Klik **Verbinding maken met Salesforce**.

   ![](assets/four.png)

1. Log in bij Salesforce.

   ![](assets/five.png)

## Aangepaste activiteitsvelden {#custom-activity-fields}

Marketo detecteert het maken van de nieuwe velden en voert vervolgens een eenmalige back-up van gegevens uit, wijst een nieuwe toewijzing toe en synchroniseert waarden voortdurend alleen in de velden **new**. Oude velden worden niet bijgewerkt.

| **Veldnaam** | **Beschrijving** |
|---|---|
| Lokale aanwezigheid-id voor MSE-aanroep | Als gebruiker kunt u Lokale Aanwezigheid als optie kiezen wanneer u vraag van de Telefoon MSE maakt. De inkomende vraag zal een lokaal aantal voor de ontvanger tonen. |
| URL opnameoproep MSE | De vraag kan worden geregistreerd en een verbinding voor de opname zal hier worden geregistreerd. |
| MSE-campagne | Logs name van de campagne MSE de Contact/Lead een lid van is. |
| URL MSE-campagne | Logs URL aan de campagne die in MSE werd gecreeerd. Als u hierop klikt, wordt de campagne geopend in de MSE-webapp. |
| Huidige stap van MSE-campagne | Als een contactpersoon/lead deel uitmaakt van een campagne, registreert dit veld de naam van de stap waarop de lead/contactpersoon momenteel is ingeschakeld. |
| MSE-e-mailbijlage weergegeven | Hiermee worden gegevens geregistreerd wanneer een e-mailbericht met een bijlage wordt verzonden en de bijlage door de ontvanger wordt bekeken. |
| MSE-e-mail geklikt | Logs a checkmark wanneer de ontvanger een verbinding in een e-mail klikt. |
| MSE-e-mail gereageerd | Logs a checkmark wanneer de ontvanger op een e-mail antwoordt. |
| E-mailstatus MSE | Geeft aan of een e-mail is verzonden/bezig is/wordt teruggestuurd (het bijhouden van teruggestuurde e-mails is afhankelijk van het gebruikte leveringskanaal). |
| MSE-e-mailsjabloon | Logs name van het malplaatje MSE dat in e-mail werd gebruikt die naar het lood/de contact wordt verzonden. |
| URL E-mailsjabloon MSE | Logs URL aan het malplaatje dat in MSE werd gecreeerd. Als u hierop klikt, wordt de sjabloon geopend in de MSE-webapp. |
| URL MSE-e-mail | Als u op deze URL klikt, wordt Command Center in MSE geopend en wordt het tabblad Historie van Personendetails weergegeven waarop u het verzonden e-mailbericht kunt zien. |
| MSE-e-mail weergegeven | Logs a checkmark wanneer de ontvanger een e-mail bekijkt. |

## Logboekvelden opheffen {#roll-up-logging-fields}

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Veldnaam</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>MSE - Laatste marketingservice</td> 
   <td>Laatste inkomende betrokkenheid van Marketing. </td> 
  </tr> 
  <tr> 
   <td>MSE - Datum laatste marketingovereenkomst</td> 
   <td>Tijdstempel van de service van Marketing.</td> 
  </tr> 
  <tr> 
   <td>MSE - Laatste marketingservicebureau</td> 
   <td>Beschrijving van de service.</td> 
  </tr> 
  <tr> 
   <td>MSE - Laatste bron voor marketingbetrokkenheid</td> 
   <td>Bron van marketingovereenkomst.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - Laatste type marketingservice</td> 
   <td colspan="1">Type betrokkenheid.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - Laatste activiteit door verkoop<br></td> 
   <td colspan="1">Laatste uitgaande activiteit uitgevoerd door het verkoopteam.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - Laatste reactie</td> 
   <td colspan="1">Laatste e-mailantwoord op e-mail over verkoop.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - Huidige verkoopcampagne</td> 
   <td colspan="1">Logs name van de campagne MSE de lood/het contact een lid van is.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - Laatste verkoopbetrokkenheid</td> 
   <td colspan="1">Laatste inkomende service van Sales. </td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - Weigeren</td> 
   <td colspan="1">Veld voor uitschakelen.</td> 
  </tr> 
 </tbody> 
</table>

## Knoppen {#buttons}

| **Knopnaam** | **Beschrijving** |
|---|---|
| MSE-e-mail verzenden | Verkoop e-mails van Salesforce. |
| Toevoegen aan MSE-campagne | Toevoegen aan MSE-campagnes van Salesforce. |
| Naar MSE duwen | Zet contact op van Salesforce naar MSE. |
| Vraag met MSE | Maak de vraag van de Verkoop van Salesforce. |

## Knoppen voor handelingen met opsommingstekens {#bulk-action-buttons}

| **Knopnaam** | **Beschrijving** |
|---|---|
| Toevoegen aan MSE-campagne | Toevoegen aan MSE-campagnes van Salesforce. |
| Naar MSE duwen | Zet contact op van Salesforce naar MSE. |

## Gebruikershandleidingen {#user-guides}

[Aangepaste MSE-rapporten in Salesforce](https://docs.marketo.com/display/docs/assets/mse-custom-reports-in-sf.docx)

[MSE voor Salesforce](https://docs.marketo.com/display/docs/assets/mse-for-sf-classic.pdf)

[MSE voor Salesforce Lightning](https://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf)
