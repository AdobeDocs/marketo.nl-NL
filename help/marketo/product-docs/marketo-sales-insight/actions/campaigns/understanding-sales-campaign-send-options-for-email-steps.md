---
description: Een goed begrip van de verzendopties voor verkoopcampagne voor e-mailstappen - Marketo Docs - Productdocumentatie
title: Verzendopties voor verkoopcampagne voor e-mailstappen
feature: Sales Insight Actions
exl-id: 775c6401-efb2-4940-a81c-be5d2759c7bd
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '740'
ht-degree: 0%

---

# Verzendopties voor verkoopcampagne voor e-mailstappen {#understanding-sales-campaign-send-options-for-email-steps}

Wanneer u een verkoopcampagne maakt, hebt u verschillende opties voor het maken van uw e-mailstappen in [!DNL Sales Insight Actions] . En afhankelijk van waar je e-mailadres in je verkoopcampagne valt, verschillen je opties ook.

## Verzendopties eerste stap {#first-step-send-options}

Als het uw eerste stap en de eerste dag in uw Verkoop Campagne is, zult u de volgende opties hebben:

![](assets/understanding-sales-campaign-send-options-for-email-steps-1.png)

### Ik kies wanneer ik deze e-mail verstuur {#first-step-i-will-choose}

* Met deze optie kunt u de optie &quot;verzenden op&quot;-tijd kiezen voor de eerste e-mail in uw verkoopcampagne wanneer u de verkoopcampagne start door mensen toe te voegen.

### Deze e-mail op het volgende moment verzenden {#first-step-following-time}

* Wanneer je je verkoopcampagne start door er mensen aan toe te voegen, plannen we de e-mail voor deze keer.
* Je hebt altijd de mogelijkheid om een nieuwe verzenddatum te kiezen wanneer je je verkoopcampagne afsluit.

### Een taak maken; ik stuur deze e-mail zelf {#first-step-create-a-task}

* Met deze optie maakt u een e-mailtaak (en synchroniseert u deze met [!DNL Salesforce] ) die u naar wens kunt verzenden.
* Zodra u deze selectie hebt gemaakt, wanneer u uw verkoopcampagne start, zullen wij deze taken voor u in de rij zetten in het Opdrachtcentrum en Live feed. Vervolgens kunt u elke e-mail personaliseren en verzenden (of plannen) voordat deze wordt verzonden.

   * Als u deze taak in onze webtoepassing opent, wordt een samenstellingsvenster geopend met het e-mailadres van uw contactpersoon, de onderwerpregel van uw e-mail en de gekozen sjabloon.
   * Als u deze taak opent in Gmail of [!DNL Outlook] , wordt er een native samenstellingsvenster geopend waarin het e-mailadres van uw contactpersoon, de onderwerpregel van uw e-mail en de sjabloon die u hebt gekozen, dynamisch worden ingevuld.

## Verzendopties volgende stap {#subsequent-step-send-options}

Voor alle volgende dagen/stappen in uw verkoopcampagne hebt u de volgende opties:

### Deze e-mail verzenden op hetzelfde moment als de vorige e-mail in deze verkoopcampagne {#subsequent-send-at-same-time}

* Met deze optie wordt het e-mailbericht tegelijk met het e-mailbericht direct vóór het bericht verzonden.
* Het zal nog verzenden op de dag het met wordt geassocieerd.

>[!IMPORTANT]
>
>Het verzenden van een e-mailbericht tegelijk met het vorige e-mailbericht wordt niet ondersteund voor e-mails die op dezelfde dag worden verzonden. In plaats daarvan wordt het e-mailbericht verzonden op het moment dat het van de vorige dag is verzonden. Als deze optie is geselecteerd voor een e-mail op de eerste dag van de campagne (niet aanbevolen), wordt die e-mail direct verzonden aan het begin van de campagne.

### Deze e-mail op het volgende moment verzenden {#subsequent-send-at-following-time}

* Wanneer je je verkoopcampagne start door er mensen aan toe te voegen, plannen we de e-mail voor deze keer.
* Je hebt altijd de mogelijkheid om een nieuwe verzenddatum te kiezen wanneer je je verkoopcampagne afsluit.

### Een taak maken; ik stuur deze e-mail zelf {#subsequent-create-a-task}

* Met deze optie maakt u een e-mailtaak (en synchroniseert u deze met [!DNL Salesforce] ) die u naar wens kunt verzenden.
* Zodra u deze selectie hebt gemaakt, wanneer u uw verkoopcampagne start, plaatst [!DNL Sales Insight Actions] deze taken in de wachtrij voor u in Opdrachtcentrum en Live feed. Vervolgens kunt u elke e-mail personaliseren en verzenden (of plannen) voordat deze wordt verzonden.

   * Als u deze taak in onze webtoepassing opent, wordt een samenstellingsvenster geopend met het e-mailadres van uw contactpersoon, de onderwerpregel van uw e-mail en de gekozen sjabloon.
   * Als u deze taak opent in Gmail of [!DNL Outlook] , wordt er een native samenstellingsvenster geopend waarin het e-mailadres van uw contactpersoon, de onderwerpregel van uw e-mail en de sjabloon die u hebt gekozen, dynamisch worden ingevuld.

### Deze e-mail maken als vervolg op de vorige e-mail in deze campagne {#subsequent-create-this-email}

* Schakel dit selectievakje in als u het vorige e-mailbericht in uw verkoopcampagne wilt toevoegen aan de volgende e-mail die door uw verkoopcampagne wordt verzonden.
* Voor de toegevoegde kopie van het e-mailbericht wordt de e-mailsjabloon in uw verkoopcampagne altijd verzonden. Eventuele bewerkingen die de gebruiker heeft aangebracht voordat deze werd verzonden, worden niet in de verzending opgenomen.

>[!NOTE]
>
>Deze optie voor het maken van een e-mailbericht als follow-up is alleen beschikbaar in een e-mailstap als de vorige stap ook een e-mail is. Als de vorige stap Vraag, InMail, of Douane is, zal de optie om een follow-up tot stand te brengen niet verschijnen.

>[!MORELIKETHIS]
>
>[ creeer een Campagne van de Verkoop ](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/create-a-sales-campaign.md){target="_blank"}
>>[De Types van Stap van de Campagne van de verkoop en de Taken van de Herinnering ](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/sales-campaign-step-types-and-reminder-tasks.md){target="_blank"}
>>[De Montages van de Campagne van de verkoop ](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/sales-campaign-settings.md){target="_blank"}

