---
description: Herinnering taaksynchronisatie met Salesforce - Marketo Docs - Productdocumentatie
title: Herinnering taaksynchronisatie met Salesforce
exl-id: 11aa6ab5-5489-4c20-a64d-2fd6fe29506f
source-git-commit: 02354356949aef7aa8836d4753ec538b7819a65a
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---

# Herinnering taaksynchronisatie met Salesforce {#reminder-task-sync-with-salesforce}

>[!NOTE]
>
>Meer informatie over het inschakelen van het uitchecken van taaksynchronisatie [De Taken/Herinneringen van de Acties van het Inzicht van de Verkoop van de Synchronisatie aan Taken Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md#sync-sales-insight-actions-tasks-reminders-to-salesforce-tasks).

Zodra de instellingen voor taaksynchronisatie zijn ingeschakeld, zien gebruikers hun herinneringstaken bidirectioneel gesynchroniseerd met Salesforce. Dit betekent gebruikers taken van of Salesforce of de Acties van het Inzicht van de Verkoop kunnen beheren en zeker voelen dat de systemen zullen blijven gericht.

## Herinnering taakveldsync {#reminder-task-field-sync}

![](assets/reminder-task-sync-with-salesforce-1.png)

Hieronder volgt een lijst van de gebieden van de herinneringstaak in de Acties van het Inzicht van de Verkoop en hun overeenkomstige gebieden van Salesforce die door bidirectionele taaksynchronisatie worden gesteund.

<table>
 <tr>
  <th>Taakveld Handelingen Handelingen verkoopinzicht</th>
  <th>Salesforce-taakveld</th>
  <th>Salesforce-taak</th>
 </tr>
 <tr>
  <td>Taaknaam</td>
  <td>Onderwerpveld</td>
  <td>Een kort samenvattingsveld dat de titel van de taak moet weergeven.</td>
 </tr>
 <tr>
  <td>Status</td>
  <td>Taakstatus</td>
  <td><p>Geeft de status van de taak weer. De taken van de Acties van het Inzicht van de verkoop hebben twee statussen die aan twee van de waarden in de de taakstatuspicklist van Salesforce in kaart brengen.</p>
  <p>Openen in Handelingen van het Inzicht van de Verkoop = Niet begonnen in Salesforce.</p>
  <p>Voltooien in Handelingen van het Inzicht van de Verkoop = Voltooid in Salesforce.</p>
  <p>De andere statuswaarden in Salesforce worden niet gesynchroniseerd met Handelingen voor Verkoopcontrole.</p></td>
 </tr>
 <tr>
  <td>Prioriteit</td>
  <td>Prioriteit</td>
  <td><p>De prioriteit van Handelingen van het Inzicht van de verkoop kan of Normaal of Hoog zijn die aan de Normale en Hoge prioritaire waarden in Salesforce in kaart brengt.</p>
  <p>De lage prioritaire waarde in Salesforce zal niet aan de Acties van het Inzicht van de Verkoop synchroniseren.</p></td>
 </tr>
 <tr>
  <td>Vervaldatum</td>
  <td>Vervaldatum</td>
  <td>De datum waarop de taak moet worden uitgevoerd.</td>
 </tr>
 <tr>
  <td>Details</td>
  <td>Opmerkingen</td>
  <td>Toont gedetailleerdere informatie over wat bedoeld was om met de herinneringstaak te worden voltooid.</td>
 </tr>
</table>

## De Taken van de Acties van het Inzicht van de Verkoop met Salesforce voor de eerste keer synchroniseren {#syncing-sales-insight-actions-tasks-with-salesforce-for-the-first-time}

Wanneer u eerst de synchronisatie tussen de Acties van het Inzicht van de Verkoop en de taken van Salesforce aanzet, voeren wij uw taken van Salesforce in. Wij zullen **niet** duw over om het even welke huidige taken u in de Acties van het Inzicht van de Verkoop aan Salesforce hebt. Om rommelige en duplicaten te verminderen, zijn de enige taken die van de Acties van het Inzicht van de Verkoop in Salesforce worden gesynchroniseerd gemaakte taken *na* u synchroniseert Handelingen van het Inzicht van de Verkoop met SFDC.

Hier is wat gebeurt wanneer u de Acties van het Inzicht van de Verkoop en taken SFDC synchroniseert:

* Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

* Herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar Handelingen in het verkoopinzicht geactiveerd. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

* Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, wordt alles dat in de afgelopen 15 dagen is verwijderd, uit Command Center verwijderd.

* Wij zullen taken tussen de Acties van het Inzicht van de Verkoop en SFDC constant synchroniseren zolang de synchronisatie wordt toegelaten.

Na de eerste synchronisatie worden alle taken die u maakt, bewerkt, voltooit of verwijdert in Handelingen voor Verkoopcontrole gesynchroniseerd met de takenlijst in Salesforce. En om het even wat gecreeerd, uitgegeven, voltooid, of geschrapt in Salesforce zal uw takenlijst in de Acties van het Inzicht van de Verkoop bijwerken.

Als u deze synchronisatie wilt inschakelen, schakelt u gewoon het synchronisatievak in [Instellingen, pagina](https://toutapp.com/login) in de webtoepassing.

>[!NOTE]
>
>Het onderwerpgebied van een taak kan in de Acties van het Inzicht van de Verkoop worden bijgewerkt en die update zal in het Salesforce onderwerpgebied voor de overeenkomstige gesynchroniseerde taak, als u gebruikt `{{activity_subject}}` dynamisch veld in uw [Aanpassing activiteitsgegevens](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md) instellingen. Omgekeerd worden eventuele updates van het onderwerpveld in Salesforce _niet_ sync over aan het gebied van het de taakonderwerp van de Herinnering van Acties van het Inzicht van de Verkoop.
