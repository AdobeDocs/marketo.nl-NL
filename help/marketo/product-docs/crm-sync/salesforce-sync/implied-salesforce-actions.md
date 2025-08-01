---
unique-page-id: 4719304
description: Impliciete Salesforce-acties - Marketo Docs - Productdocumentatie
title: Impliciete Salesforce-handelingen
exl-id: 88533588-77f2-465e-9644-a4f95b87f99d
feature: Salesforce Integration
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '136'
ht-degree: 0%

---

# Impliciete Salesforce-handelingen {#implied-salesforce-actions}

Wanneer een [!DNL Salesforce]-specifieke stroomstap wordt uitgevoerd, worden soms extra stappen automatisch uitgevoerd. Hier zijn de regels, dus weet u:

Deze regels zullen van toepassing zijn wanneer de persoon momenteel niet in [ Salesforce.com ](https://Salesforce.com){target="_blank"} als contact of lood is.

<table>
 <thead>
  <tr>
   <th>Marketo Flow-stap</th>
   <th>Automatische actie</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>Toevoegen aan SFDC-campagne</td>
   <td>Persoon synchroniseren naar SFDC</td>
  </tr>
  <tr>
   <td>Status wijzigen in SFDC-campagne</td>
   <td>De Persoon van de synchronisatie aan SFDC <br> voegt aan de Campagne van SFDC toe</td>
  </tr>
  <tr>
   <td>Eigenaar wijzigen</td>
   <td><p>Persoon synchroniseren naar SFDC</p></td>
  </tr>
  <tr>
   <td>Persoon omzetten</td>
   <td><p>Persoon synchroniseren naar SFDC</p></td>
  </tr>
  <tr>
   <td>Taak maken</td>
   <td>Persoon synchroniseren naar SFDC</td>
  </tr>
 </tbody>
</table>

U kunt SFDC-records in een slimme lijst uitfilteren met het filter **[!UICONTROL SFDC Type]** en de operator &quot;[!UICONTROL is not empty]&quot;. Alle SFDC-records hebben een waarde in dit veld.

Herinner me, gebeuren deze automatische acties slechts als het lood niet momenteel in [ Salesforce.com ](https://salesforce.com){target="_blank"} is
