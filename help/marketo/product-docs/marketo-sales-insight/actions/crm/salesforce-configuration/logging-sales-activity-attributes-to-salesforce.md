---
description: Logboekkenmerken van verkoopactiviteiten aan Salesforce - Marketo Docs - Productdocumentatie
title: Kenmerken verkoopactiviteit registreren voor Salesforce
exl-id: fdefe53b-eb99-48ce-a04e-3666be33fea4
source-git-commit: 222b0692998be1fd15dc6465af1da627e1c32683
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 1%

---

# Kenmerken verkoopactiviteit registreren voor Salesforce {#logging-sales-activity-attributes-to-salesforce}

Salesforce-beheerder kan handmatig aangepaste activiteitsvelden toevoegen aan Salesforce.

1. Klik in uw Salesforce-account op **Instellen**.

1. Zoek naar de &quot;Velden van de Douane van de Activiteit&quot;in het snelle onderzoeksgebied en klik op het.

1. Klikken **Nieuw**.

1. Selecteer Gegevenstype dat overeenkomt met het veld dat u wilt toevoegen op basis van de onderstaande tabel en klik op **Volgende**.

1. Voer de veldnaam en het label in die overeenkomen met het veld dat u wilt toevoegen.

Beschrijving van elke kolom in de onderstaande tabel:

* **Veldlabel**: Veldnaam weergegeven in de gebruikersinterface (deze naam kan worden aangepast om de leesbaarheid van het team te verbeteren)
* **Veldnaam**: Technische naam van het veld (zorg dat de ingevoerde veldnaam overeenkomt met de veldnaam in de onderstaande tabel)
* **API-naam**: Technische naam van veld voor API (zorg dat de ingevoerde API-naam overeenkomt met de API-naam in de onderstaande tabel)
* **Gegevenstype**: Type veld
* **Grootte**: Grootte van het tekstveld

<table>
 <tr>
  <th>Veldlabel</th>
  <th>Veldnaam</th>
  <th>API-naam</th>
  <th>Gegevenstype</th>
  <th>Grootte</th>
 </tr>
 <tr>
  <td>Lokale aanwezigheid-id van Marketo Sales Call</td>
  <td>MSE_Call_Local_Presence_ID</td>
  <td>MSE_Call_Local_Presence_ID__c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>Opname-URL Marketo-verkoopoproep</td>
  <td>MSE_Call_Recording</td>
  <td>MSE_Call_Recording_c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo-verkoopcampagne</td>
  <td>MSE_Campaign</td>
  <td>MSE_Campaign_c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>Huidige stap Marketo-verkoopcampagne</td>
  <td>MSE_Current_Campaign_Step</td>
  <td>MSE_Current_Campaign_Step__c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>Marketo Sales Campaign URL</td>
  <td>MSE_Campaign_Details_Link</td>
  <td>MSE_Campaign_Details_Link_c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Verkoop-e-mailbijlage weergegeven</td>
  <td>MSE_Presentation_Viewed</td>
  <td>MSE_Presentation_Viewed_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales-e-mail geklikt</td>
  <td>MSE_Clicked</td>
  <td>MSE_Clicked_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales-e-mail gereageerd</td>
  <td>MSE_Replied</td>
  <td>MSE_Replied_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Verkoop-e-mailstatus</td>
  <td>MSE_Email_Status</td>
  <td>MSE_Email_Status__c</td>
  <td>Tekst</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales-e-mailsjabloon</td>
  <td>MSE_Template</td>
  <td>MSE_Template__c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>URL Marketo-verkoopsjabloon</td>
  <td>MSE_Template_Details</td>
  <td>MSE_Template_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Verkoop-e-mailURL</td>
  <td>MSE_Details</td>
  <td>MSE_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Verkoop-e-mail weergegeven</td>
  <td>MSE_Viewed</td>
  <td>MSE_Viewed_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
</table>
