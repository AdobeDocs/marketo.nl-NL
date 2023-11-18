---
unique-page-id: 4719304
description: Impliciete Salesforce-acties - Marketo Docs - Productdocumentatie
title: Impliciete Salesforce-acties
exl-id: 88533588-77f2-465e-9644-a4f95b87f99d
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# Impliciete Salesforce-acties {#implied-salesforce-actions}

Wanneer een salesforce-specifieke stroomstap wordt uitgevoerd, worden soms extra stappen automatisch uitgevoerd. Hier zijn de regels, dus weet u:

Deze regels zijn van toepassing wanneer de persoon zich momenteel niet in [Salesforce.com](https://Salesforce.com){target="_blank"} als contact of lood.

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

U kunt SFDC-records in een slimme lijst filteren met de opdracht **[!UICONTROL SFDC Type]** Filter met de operator ingesteld op &quot;is niet leeg&quot;. Alle SFDC-records hebben een waarde in dit veld.

Deze automatische handelingen worden alleen uitgevoerd als de lead zich momenteel niet in [Salesforce.com](https://salesforce.com){target="_blank"}
