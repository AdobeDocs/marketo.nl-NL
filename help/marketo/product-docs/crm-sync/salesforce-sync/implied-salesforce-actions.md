---
unique-page-id: 4719304
description: Impliciete Salesforce-acties - Marketo Docs - Productdocumentatie
title: Impliciete Salesforce-acties
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '149'
ht-degree: 0%

---


# Impliciete Salesforce-acties {#implied-salesforce-actions}

Wanneer een salesforce-specifieke stroomstap wordt uitgevoerd, worden soms extra stappen automatisch uitgevoerd. Hier zijn de regels, dus weet u:

Deze regels zijn van toepassing *wanneer de persoon zich momenteel niet in [Salesforce.com](http://Salesforce.com)* bevindt als contactpersoon of lead.

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
   <td>Persoon synchroniseren naar<br>SFDCAdd naar SFDC-campagne</td> 
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

U kunt SFDC-records in een slimme lijst uitfilteren met behulp van het **SFDC Type** -filter en de operator ingesteld op &quot;is niet leeg&quot;. Alle SFDC-records hebben een waarde in dit veld.

Deze automatische handelingen worden alleen uitgevoerd als de lead zich momenteel niet op [Salesforce.com bevindt.](http://Salesforce.com)

De Salesforce-synchronisatie is cool, toch?
