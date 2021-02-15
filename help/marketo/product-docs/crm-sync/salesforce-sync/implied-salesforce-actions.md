---
unique-page-id: 4719304
description: Impliciete Salesforce-acties - Marketo Docs - Productdocumentatie
title: Impliciete Salesforce-acties
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 0%

---


# Impliciete Salesforce-handelingen {#implied-salesforce-actions}

Wanneer een salesforce-specifieke stroomstap wordt uitgevoerd, worden soms extra stappen automatisch uitgevoerd. Hier zijn de regels, dus weet u:

Deze regels zijn van toepassing _wanneer de persoon momenteel niet in [Salesforce.com](https://Salesforce.com)_ als contact of lood is.

<table> 
 <thead> 
  <tr> 
   <th>Stap Markeren naar stroom</th> 
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
   <td>Persoon synchroniseren naar SFDC<br>Toevoegen aan SFDC-campagne</td> 
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

U kunt SFDC-records in een slimme lijst uitfilteren met het filter **SFDC Type** met de operator ingesteld op &quot;is niet leeg&quot;. Alle SFDC-records hebben een waarde in dit veld.

Onthoud dat deze automatische handelingen alleen plaatsvinden als de lead zich momenteel niet in [Salesforce.com](https://salesforce.com) bevindt
