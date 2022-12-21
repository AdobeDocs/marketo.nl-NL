---
unique-page-id: 14352541
description: De Taken van de Verbinding van de Verkoop met Salesforce voor het eerst synchroniseren - de Documenten van Marketo - de Documentatie van het Product
title: De Taken van de Verbinding van de Verkoop met Salesforce voor de eerste keer synchroniseren
exl-id: 42ac6b4f-76ac-40d7-9e10-7e0d3886a638
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---

# De Taken van de Verbinding van de Verkoop met Salesforce voor de eerste keer synchroniseren {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Wanneer u de synchronisatie tussen Sales Connect- en Salesforce-taken voor het eerst inschakelt, importeren wij uw Salesforce-taken. Wij zullen **niet** Houd de huidige taken die u hebt in Sales Connect aan Salesforce over. Om rommelige en dubbele taken te voorkomen, zijn de enige taken die van Sales Connect in Salesforce worden gesynchroniseerd, taken die zijn gemaakt *na* u synchroniseert Sales Connect met SFDC.

Hieronder wordt beschreven wat er gebeurt wanneer u Sales Connect- en SFDC-taken synchroniseert:

- Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

- Alle herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar Sales Connect opgehaald. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

- Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, wordt alles dat in de afgelopen 15 dagen is verwijderd, uit Command Center verwijderd.

- We synchroniseren taken voortdurend tussen Sales Connect en SFDC zolang de synchronisatie is ingeschakeld.

Na de eerste synchronisatie worden alle taken die u in Sales Connect maakt, bewerkt, voltooit of verwijdert, gesynchroniseerd met de takenlijst in Salesforce. En alles wat in Salesforce is gemaakt, bewerkt, voltooid of verwijderd, werkt uw takenlijst bij in Sales Connect.

Als u deze synchronisatie wilt inschakelen, schakelt u gewoon het synchronisatievak in [Instellingen, pagina](https://toutapp.com/login) in de webtoepassing.
