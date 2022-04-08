---
description: Toegang tot verkoopinzicht verwijderen - Marketo-documenten - productdocumentatie
title: Toegang tot verkoopinzicht verwijderen
exl-id: 3cda112a-524e-469b-a222-c0192b2f5301
source-git-commit: 5c4bce6ab6801b861f70722b6782df34f96fed10
workflow-type: tm+mt
source-wordcount: '411'
ht-degree: 0%

---

# Toegang tot verkoopinzicht verwijderen {#remove-sales-insight-access}

Gebruik de volgende stappen om toegang tot de eigenschappen van het Inzicht van de Verkoop in Salesforce te verwijderen. Van toepassing op Salesforce Classic en Lightning.

## Overzicht {#overview}

Toestemming tot de hieronder vermelde voorwerpen, apex klassen, en visualforce pagina&#39;s wordt vereist om tot alle eigenschappen van het Inzicht van de Verkoop toegang te hebben. Als u deze instellingen verwijdert, wordt de toegang tot Sales Insight verwijderd.

**Objectinstellingen**

<table> 
 <tbody> 
 <tr> 
   <td>BestBetsCache</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>Gegevens beste biets</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>Weergaven beste ets</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>EmailActivityCache</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>GetMethodArgus</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>GroupedWebActivityCache</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>InterestingMomentsCache</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>Marketo Sales Insight Config</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>ScoringCache</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>Waarden</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
  <tr> 
   <td>WebActivityCache</td> 
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td> 
  </tr> 
 </tbody> 
</table>

* Toegang tot Apex-klasse: 159 Apex-klassen die met &quot;mkto_si&quot; zijn
* Toegang tot visuale pagina: 64 Visuale pagina&#39;s met &quot;mkto_si&quot;
* Definities aangepaste instelling: mkto_si.Marketo Settings &amp; mkto_si.User Preferences

## Het verwijderen van Toegang tot het Inzicht van de Verkoop {#removing-access-to-sales-insight}

1. Meld u aan bij uw Salesforce-account.

1. Klikken **Instellen**.

   ![](assets/remove-sales-insight-access-1.png)

1. Klik onder Beheerder op **Gebruikers beheren** vervolgens **Profielen**.

1. Klik op het profiel dat u wilt bijwerken en klik vervolgens op **Bewerken**.

1. Blader omlaag naar &quot;Aangepaste tabinstellingen&quot; onder Tabinstellingen.

1. Selecteer de optie &quot;Tab Hidden&quot; in de vervolgkeuzelijst voor Marketo Sales Insight Config en MSI Marketo Sales Outbox.

   ![](assets/remove-sales-insight-access-2.png)

   ![](assets/remove-sales-insight-access-3.png)

1. Schuif omlaag naar &quot;Aangepaste objectmachtigingen&quot;.

1. Verwijder de toegang &quot;Lezen, Maken, Bewerken, Verwijderen&quot; uit de volgende objecten:

   * BestBetsCache
   * Gegevens beste biets
   * Weergaven beste ets
   * EmailActivityCache
   * GetMethodArgus
   * GroupedWebActivityCache
   * InterestingMomentsCache
   * Marketo Sales Insight Config
   * ScoringCache
   * Waarden
   * WebActivityCache

1. Blader omlaag naar de sectie &quot;Enabled Apex Class Access&quot;. Klikken **Bewerken**.

1. Selecteer in de sectie &quot;Ingeschakelde Apex-klassen&quot; alle klassen die met &quot;mkto_si&quot; beginnen. Dit zou tot 159 klassen moeten toevoegen.

1. Klikken **Verwijderen** vervolgens **Opslaan**.

   ![](assets/remove-sales-insight-access-4.png)

1. Schuif omlaag naar de sectie &#39;Ingeschakelde visuale paginatoegang&#39;. Klikken **Bewerken**.

1. Selecteer in de sectie &quot;Ingeschakelde visuele pagina&#39;s&quot; alle pagina&#39;s die met &quot;mkto_si&quot; beginnen. Dit zou tot 64 pagina&#39;s moeten optellen.

1. Klikken **Verwijderen** vervolgens **Opslaan**.

   ![](assets/remove-sales-insight-access-5.png)

1. Blader omlaag naar de sectie &quot;Enabled Custom Setting Definitions Access&quot;. Klikken **Bewerken**.

1. Selecteer &quot;Marketo Sales Insight.mkto_si.Marketo Settings&quot; en &quot;Marketo Sales Insight.mkto_si.User Preferences&quot;.

1. Klikken **Verwijderen** vervolgens **Opslaan**.

   ![](assets/remove-sales-insight-access-6.png)

Dat is het! Je hebt de toegang tot Verkoopinzicht verwijderd. Herhaal dezelfde stappen voor elk ander profiel waarvoor u toegang wilt verwijderen.
