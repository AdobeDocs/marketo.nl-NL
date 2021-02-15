---
unique-page-id: 14352541
description: De Taken van de Verkoop verbinden met Salesforce voor het eerst synchroniseren - Marketo Docs - de Documentatie van het Product
title: De Taken van de Verbinding van de Verkoop met Salesforce voor de eerste keer synchroniseren
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---


# De Taken van de Verkoop verbinden met Salesforce voor de eerste keer {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time} synchroniseren

Wanneer u de synchronisatie tussen Sales Connect- en Salesforce-taken voor het eerst inschakelt, importeren wij uw Salesforce-taken. Wij zullen **niet** over om het even welke huidige taken duwen u in Verkoop verbindt met Salesforce hebt. Om rommelige en duplicaten te verminderen, zijn de enige taken die van Verkoop Connect in Salesforce worden gesynchroniseerd taken die *na* worden gecreeerd u Verkoop verbindt met SFDC synchroniseert.

Hieronder wordt beschreven wat er gebeurt wanneer u Sales Connect- en SFDC-taken synchroniseert:

- Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

- Alle herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar Sales Connect opgehaald. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

- Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, wordt alles dat in de afgelopen 15 dagen is verwijderd, uit Command Center verwijderd.

- We synchroniseren taken voortdurend tussen Sales Connect en SFDC zolang de synchronisatie is ingeschakeld.

Na de eerste synchronisatie worden alle taken die u in Sales Connect maakt, bewerkt, voltooit of verwijdert, gesynchroniseerd met de takenlijst in Salesforce. En alles wat in Salesforce is gemaakt, bewerkt, voltooid of verwijderd, werkt uw takenlijst bij in Sales Connect.

Als u deze synchronisatie wilt inschakelen, schakelt u gewoon het synchronisatievak in op de pagina [Instellingen](https://toutapp.com/login) in de webtoepassing.
