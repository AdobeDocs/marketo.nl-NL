---
unique-page-id: 14352541
description: De Taken van de Verkoop verbinden met Salesforce voor het eerst synchroniseren - Marketo Docs - de Documentatie van het Product
title: De Taken van de Verbinding van de Verkoop met Salesforce voor de eerste keer synchroniseren
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---


# De Taken van de Verbinding van de Verkoop met Salesforce voor de eerste keer synchroniseren {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Wanneer u de synchronisatie tussen Sales Connect- en Salesforce-taken voor het eerst inschakelt, importeren wij uw Salesforce-taken. We gaan **niet** over de huidige taken die u hebt in Sales Connect aan Salesforce. Om rommelige en dubbele taken te voorkomen, zijn de enige taken die van Sales Connect in Salesforce worden gesynchroniseerd taken die worden gemaakt *nadat* u Sales Connect synchroniseert met SFDC.

Hieronder wordt beschreven wat er gebeurt wanneer u Sales Connect- en SFDC-taken synchroniseert:

- Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

- Herinneringen die in de map zijn bijgewerkt of gemaakt, `last 24 hours` worden van SFDC naar Sales Connect opgehaald. De synchronisatie is gebaseerd op `due date` en al deze taken worden gesynchroniseerd op het achterste gedeelte, maar in Command Center ziet u alleen taken die vandaag en morgen verschuldigd zijn.

- Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, wordt alles dat in de afgelopen 15 dagen is verwijderd, uit Command Center verwijderd.

- We synchroniseren taken voortdurend tussen Sales Connect en SFDC zolang de synchronisatie is ingeschakeld.

Na de eerste synchronisatie worden alle taken die u in Sales Connect maakt, bewerkt, voltooit of verwijdert, gesynchroniseerd met de takenlijst in Salesforce. En alles wat in Salesforce is gemaakt, bewerkt, voltooid of verwijderd, werkt uw takenlijst bij in Sales Connect.

Als u deze synchronisatie wilt inschakelen, schakelt u gewoon het synchronisatievak in op de pagina [](http://toutapp.com/next#settings/crm/salesforce/configure) Instellingen in de webtoepassing.

