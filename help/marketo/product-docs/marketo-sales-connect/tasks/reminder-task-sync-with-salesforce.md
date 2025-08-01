---
description: Herinnering taaksynchronisatie met Salesforce - Marketo Docs - Productdocumentatie
title: Taaksynchronisatie met Salesforce herinneren
exl-id: 4de933db-4626-4845-be70-8ad55d03a18e
feature: Marketo Sales Connect
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '483'
ht-degree: 0%

---

# Taaksynchronisatie herinnering met [!DNL Salesforce] {#reminder-task-sync-with-salesforce}

>[!NOTE]
>
>Leren hoe te om de controle van de Synchronisatie van de Taak uit [ te laten synchroniseren  [!DNL Sales Connect]  Taken/Herinneringen aan  [!DNL Salesforce]  Taken ](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md#sync-sales-connect-tasks-reminders-to-salesforce-tasks).

Als de instellingen voor taaksynchronisatie zijn ingeschakeld, worden de herinneringstaken bidirectioneel gesynchroniseerd met [!DNL Salesforce] . Dit betekent dat gebruikers taken vanuit [!DNL Salesforce] of [!DNL Sales Connect] kunnen beheren en erop kunnen vertrouwen dat de systemen op één lijn blijven staan.

## Herinnering taakveldsync {#reminder-task-field-sync}

![](assets/reminder-task-sync-with-salesforce-1.png)

Hieronder vindt u een lijst met de taakvelden voor herinneringen in [!DNL Sales Connect] en de bijbehorende [!DNL Salesforce] -velden die worden ondersteund via tweerichtingtaaksynchronisatie.

<table>
 <tr>
  <th>[!DNL Sales Connect] Taakveld</th>
  <th>[!DNL Salesforce] Taakveld</th>
  <th>[!DNL Salesforce] Taak</th>
 </tr>
 <tr>
  <td>[!UICONTROL Task Name]</td>
  <td>[!UICONTROL Subject Field]</td>
  <td>Een kort samenvattingsveld dat de titel van de taak moet weergeven.</td>
 </tr>
 <tr>
  <td>[!UICONTROL Status]</td>
  <td>[!UICONTROL Task Status]</td>
  <td><p>Hier wordt de status van de taak weergegeven. [!DNL Sales Connect] -taken hebben twee statussen die zijn toegewezen aan twee van de waarden in de [!DNL Salesforce] keuzelijst met taakstatus.</p>
  <p>Openen in [!DNL Sales Connect] = Niet gestart in [!DNL Salesforce] .</p>
  <p>Voltooien in [!DNL Sales Connect] = Voltooid in [!DNL Salesforce] .</p>
  <p>De andere statuswaarden in [!DNL Salesforce] worden niet gesynchroniseerd met [!DNL Sales Connect] .</p></td>
 </tr>
 <tr>
  <td>[!UICONTROL Priority]</td>
  <td>[!UICONTROL Priority]</td>
  <td><p>[!DNL Sales Connect] De prioriteit kan Normaal of Hoog zijn die aan de Normale en Hoge prioritaire waarden in [!DNL Salesforce] in kaart brengt.</p>
  <p>De waarde met lage prioriteit in [!DNL Salesforce] wordt niet gesynchroniseerd met [!DNL Sales Connect] .</p></td>
 </tr>
 <tr>
  <td>[!UICONTROL Due Date]</td>
  <td>[!UICONTROL Due Date]</td>
  <td>De datum waarop de taak moet worden uitgevoerd.</td>
 </tr>
 <tr>
  <td>[!UICONTROL Details]</td>
  <td>[!UICONTROL Comments]</td>
  <td>Toont gedetailleerdere informatie over wat bedoeld was om met de herinneringstaak te worden voltooid.</td>
 </tr>
</table>

## [!DNL Sales Connect] Taken synchroniseren met [!DNL Salesforce] voor het eerst {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Wanneer u de synchronisatie tussen [!DNL Sales Connect] - en [!DNL Salesforce] -taken voor het eerst inschakelt, importeren wij uw [!DNL Salesforce] -taken. Wij **zullen** niet over om het even welke huidige taken duwen u binnen [!DNL Sales Connect] aan [!DNL Salesforce] hebt. Om rommelige en duplicaten te verminderen, zijn de enige taken die van [!DNL Sales Connect] in [!DNL Salesforce] worden gesynchroniseerd taken gecreeerd *nadat* u [!DNL Sales Connect] met SFDC synchroniseert.

Hier volgt wat er gebeurt wanneer u [!DNL Sales Connect] - en SFDC-taken synchroniseert:

* Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

* Herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar [!DNL Sales Connect] opgehaald. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

* Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, worden alle taken die in de afgelopen 15 dagen zijn verwijderd, ook uit Command Center verwijderd.

* We synchroniseren taken voortdurend tussen [!DNL Sales Connect] en SFDC zolang de synchronisatie is ingeschakeld.

Na de eerste synchronisatie worden alle taken die u maakt, bewerkt, voltooit of verwijdert in [!DNL Sales Connect] , gesynchroniseerd met de takenlijst in [!DNL Salesforce] . En alles wat in [!DNL Salesforce] is gemaakt, bewerkt, voltooid of verwijderd, werkt uw takenlijst bij in [!DNL Sales Connect] .

Om deze synchronisatie aan te zetten, controleer enkel de synchronisatiedoos in uw [ pagina van Montages ](https://toutapp.com/login) in de Webtoepassing.

>[!NOTE]
>
>Het onderwerpgebied van een taak kan in [!DNL Sales Connect] worden bijgewerkt en die update zal op het [!DNL Salesforce] onderwerpgebied voor de overeenkomstige gesynchroniseerde taak worden gesynchroniseerd, als u het `{{activity_subject}}` dynamische gebied in uw [ montages van de Aanpassing van het Detail van de Activiteit ](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md) gebruikt. Omgekeerd, zullen om het even welke die updates aan het onderwerpgebied in [!DNL Salesforce] worden aangebracht _niet_ over aan het [!DNL Sales Connect] onderwerponderwerpgebied van de herinneringstaak synchroniseren.
