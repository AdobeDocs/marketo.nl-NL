---
description: Herinnering taaksynchronisatie met Salesforce - Marketo Docs - Productdocumentatie
title: Herinnering taaksynchronisatie met Salesforce
exl-id: 4de933db-4626-4845-be70-8ad55d03a18e
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '564'
ht-degree: 0%

---

# Herinnering taaksynchronisatie met Salesforce {#reminder-task-sync-with-salesforce}

>[!NOTE]
>
>Meer informatie over het inschakelen van het uitchecken van taaksynchronisatie [De Taken van de Verkoop verbindt/Herinneringen van de synchronisatie aan Taken Salesforce](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md#sync-sales-connect-tasks-reminders-to-salesforce-tasks).

Zodra de instellingen voor taaksynchronisatie zijn ingeschakeld, zien gebruikers hun herinneringstaken bidirectioneel gesynchroniseerd met Salesforce. Dit betekent dat gebruikers taken kunnen beheren vanuit Salesforce of Sales Connect en erop kunnen vertrouwen dat de systemen op één lijn blijven staan.

## Herinnering taakveldsync {#reminder-task-field-sync}

![](assets/reminder-task-sync-with-salesforce-1.png)

Hieronder vindt u een lijst met de taakvelden voor herinneringen in Sales Connect en de bijbehorende Salesforce-velden die worden ondersteund via de tweerichtingtaaksynchronisatie.

<table>
 <tr>
  <th>Taakveld voor verbinding met verkoop</th>
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
  <td><p>Geeft de status van de taak weer. Sales Connect-taken hebben twee statussen die worden toegewezen aan twee van de waarden in de statuskeuzelijst voor Salesforce-taken.</p>
  <p>Openen in Sales Connect = Niet gestart in Salesforce.</p>
  <p>Voltooid in Sales Connect = voltooid in Salesforce.</p>
  <p>De andere statuswaarden in Salesforce worden niet gesynchroniseerd met Sales Connect.</p></td>
 </tr>
 <tr>
  <td>Prioriteit</td>
  <td>Prioriteit</td>
  <td><p>De prioriteit voor Sales Connect kan Normaal of Hoog zijn. Deze waarden worden toegewezen aan de waarden voor Normaal en Hoge prioriteit in Salesforce.</p>
  <p>De waarde met lage prioriteit in Salesforce synchroniseert niet met Sales Connect.</p></td>
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

## De Taken van de Verbinding van de Verkoop met Salesforce voor de eerste keer synchroniseren {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Wanneer u de synchronisatie tussen Sales Connect- en Salesforce-taken voor het eerst inschakelt, importeren wij uw Salesforce-taken. Wij zullen **niet** Houd de huidige taken die u hebt in Sales Connect aan Salesforce over. Om rommelige en dubbele taken te voorkomen, zijn de enige taken die van Sales Connect in Salesforce worden gesynchroniseerd, taken die zijn gemaakt *na* u synchroniseert Sales Connect met SFDC.

Hieronder wordt beschreven wat er gebeurt wanneer u Sales Connect- en SFDC-taken synchroniseert:

* Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

* Alle herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar Sales Connect opgehaald. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

* Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, wordt alles dat in de afgelopen 15 dagen is verwijderd, uit Command Center verwijderd.

* We synchroniseren taken voortdurend tussen Sales Connect en SFDC zolang de synchronisatie is ingeschakeld.

Na de eerste synchronisatie worden alle taken die u in Sales Connect maakt, bewerkt, voltooit of verwijdert, gesynchroniseerd met de takenlijst in Salesforce. En alles wat in Salesforce is gemaakt, bewerkt, voltooid of verwijderd, werkt uw takenlijst bij in Sales Connect.

Als u deze synchronisatie wilt inschakelen, schakelt u gewoon het synchronisatievak in [Instellingen, pagina](https://toutapp.com/login) in de webtoepassing.

>[!NOTE]
>
>Het onderwerpveld van een taak kan worden bijgewerkt in Sales Connect en die update wordt gesynchroniseerd in het Salesforce-onderwerpveld voor de corresponderende gesynchroniseerde taak als u de `{{activity_subject}}` dynamisch veld in uw [Aanpassing activiteitsgegevens](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md) instellingen. Omgekeerd worden eventuele updates van het onderwerpveld in Salesforce _niet_ synchroniseren naar het onderwerpveld voor de taak van Sales Connect-herinnering.
