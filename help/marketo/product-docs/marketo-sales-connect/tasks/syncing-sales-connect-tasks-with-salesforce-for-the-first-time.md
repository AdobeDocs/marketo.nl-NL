---
unique-page-id: 14352541
description: Sales Connect-taken voor het eerst synchroniseren met Salesforce - Marketo Docs - Productdocumentatie
title: Sales Connect-taken voor het eerst synchroniseren met Salesforce
exl-id: 42ac6b4f-76ac-40d7-9e10-7e0d3886a638
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '256'
ht-degree: 0%

---

# [!DNL Sales Connect] Taken synchroniseren met [!DNL Salesforce] voor het eerst {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Wanneer u de synchronisatie tussen [!DNL Sales Connect] - en [!DNL Salesforce] -taken voor het eerst inschakelt, importeren wij uw [!DNL Salesforce] -taken. Wij **zullen** niet over om het even welke huidige taken duwen u binnen [!DNL Sales Connect] aan [!DNL Salesforce] hebt. Om rommelige en duplicaten te verminderen, zijn de enige taken die van [!DNL Sales Connect] in [!DNL Salesforce] worden gesynchroniseerd taken gecreeerd *nadat* u [!DNL Sales Connect] met SFDC synchroniseert.

Hier volgt wat er gebeurt wanneer u [!DNL Sales Connect] - en SFDC-taken synchroniseert:

- Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

- Herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar [!DNL Sales Connect] opgehaald. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

- Als synchronisatie eerder is ingeschakeld en u taken in SFDC verwijdert, worden alle taken die in de afgelopen 15 dagen zijn verwijderd, ook uit Command Center verwijderd.

- We synchroniseren taken voortdurend tussen [!DNL Sales Connect] en SFDC zolang de synchronisatie is ingeschakeld.

Na de eerste synchronisatie worden alle taken die u maakt, bewerkt, voltooit of verwijdert in [!DNL Sales Connect] , gesynchroniseerd met de takenlijst in [!DNL Salesforce] . En alles wat in [!DNL Salesforce] is gemaakt, bewerkt, voltooid of verwijderd, werkt uw takenlijst bij in [!DNL Sales Connect] .

Om deze synchronisatie aan te zetten, controleer enkel de synchronisatiedoos in uw [ pagina van Montages ](https://toutapp.com/login) in de Webtoepassing.
