---
unique-page-id: 4719304
description: Impliciete Salesforce-acties - Marketo Docs - Productdocumentatie
title: Impliciete Salesforce-acties
exl-id: 88533588-77f2-465e-9644-a4f95b87f99d
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 0%

---

# Impliciete Salesforce-acties {#implied-salesforce-actions}

Wanneer een salesforce-specifieke stroomstap wordt uitgevoerd, worden soms extra stappen automatisch uitgevoerd. Hier zijn de regels, dus weet u:

Deze regels zijn van toepassing _wanneer de persoon zich momenteel niet in [Salesforce.com](https://Salesforce.com)_ als contact of lood.

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

U kunt SFDC-records in een slimme lijst filteren met de opdracht **SFDC-type** Filter met de operator ingesteld op &quot;is niet leeg&quot;. Alle SFDC-records hebben een waarde in dit veld.

Deze automatische handelingen worden alleen uitgevoerd als de lead zich momenteel niet in [Salesforce.com](https://salesforce.com)
