---
description: Logboekregistratie van kenmerken van verkoopactiviteiten aan Salesforce - Marketo-documenten - Productdocumentatie
title: Kenmerken verkoopactiviteit registreren voor Salesforce
exl-id: fdefe53b-eb99-48ce-a04e-3666be33fea4
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 3%

---

# Kenmerken verkoopactiviteit registreren voor [!DNL Salesforce] {#logging-sales-activity-attributes-to-salesforce}

Salesforce-beheerders kunnen handmatig aangepaste activiteitsvelden toevoegen aan [!DNL Salesforce] .

1. Klik op [!DNL Salesforce] in uw **[!UICONTROL Setup]** -account.

1. Zoek naar de &quot;Velden van de Douane van de Activiteit&quot;in het snelle onderzoeksgebied en klik op het.

1. Klik op **[!UICONTROL New]**.

1. Selecteer Gegevenstype dat overeenkomt met het veld dat u wilt toevoegen op basis van de onderstaande tabel en klik op **[!UICONTROL Next]** .

1. Voer de veldnaam en het label in die overeenkomen met het veld dat u wilt toevoegen.

Beschrijving van elke kolom in de onderstaande tabel:

* **Etiket van het Gebied**: De naam van het Gebied die in UI wordt getoond (deze naam kan worden aangepast om leesbaarheid door uw team te verbeteren)
* **Naam van het Gebied**: De technische naam van het gebied (zorg ervoor de Naam van het Gebied u ingaat past de Naam van het Gebied in de lijst hieronder aan)
* **API Naam**: De technische naam van het gebied voor API (zorg ervoor API naam u ingaat past de API naam in de lijst hieronder aan)
* **Type van Gegevens**: Type van gebied
* **Grootte**: Grootte van het tekstgebied

<table>
 <tr>
  <th>Veldlabel</th>
  <th>Veldnaam</th>
  <th>API-naam</th>
  <th>Gegevenstype</th>
  <th>Grootte</th>
 </tr>
  <tr>
  <td>[!UICONTROL Call Outcomes]</td>
  <td>mktosales_call_result</td>
  <td>mktosales_call_result_c</td>
  <td>Tekst</td>
  <td>50</td>
 </tr>
 <tr>
  <td>[!UICONTROL Call Reasons]</td>
  <td>mktosales_call_reason</td>
  <td>mktosales_call_reason_c</td>
  <td>Tekst</td>
  <td>50</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Call Local Presence ID]</td>
  <td>MSE_Call_Local_Presence_ID</td>
  <td>MSE_Call_Local_Presence_ID__c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Call Recording URL]</td>
  <td>MSE_Call_Recording</td>
  <td>MSE_Call_Recording_c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Campaign]</td>
  <td>MSE_Campaign</td>
  <td>MSE_Campaign_c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Campaign Current Step]</td>
  <td>MSE_Current_Campaign_Step</td>
  <td>MSE_Current_Campaign_Step__c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Campaign URL]</td>
  <td>MSE_Campaign_Details_Link</td>
  <td>MSE_Campaign_Details_Link_c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Attachment Viewed]</td>
  <td>MSE_Presentation_Viewed</td>
  <td>MSE_Presentation_Viewed_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Clicked]</td>
  <td>MSE_Clicked</td>
  <td>MSE_Clicked_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Replied]</td>
  <td>MSE_Replied</td>
  <td>MSE_Replied_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Status]</td>
  <td>MSE_Email_Status</td>
  <td>MSE_Email_Status__c</td>
  <td>Tekst</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Template]</td>
  <td>MSE_Template</td>
  <td>MSE_Template__c</td>
  <td>Tekst</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Template URL]</td>
  <td>MSE_Template_Details</td>
  <td>MSE_Template_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email URL]</td>
  <td>MSE_Details</td>
  <td>MSE_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Viewed]</td>
  <td>MSE_Viewed</td>
  <td>MSE_Viewed_c</td>
  <td>Selectievakje</td>
  <td></td>
 </tr>
</table>
