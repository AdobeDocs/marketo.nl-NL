---
description: Campagne uitvoeren - Marketo Docs - Productdocumentatie
title: Campagne uitvoeren
source-git-commit: b491f476c4facc6343559a0acf5d5527e9afc618
workflow-type: tm+mt
source-wordcount: '711'
ht-degree: 0%

---

# Campagne {#execute-campaign} uitvoeren

Een uitvoerbare Campagne, zoals andere campagnes, bevat een Slimme Lijst, Stroom, en Programma. In tegenstelling tot andere campagnes, plant of activeert u het eigenlijk niet. Het kan slechts door een andere campagne via de Uitvoeren de debietstap van de Campagne worden geroepen. De stroomstappen in de Uitvoerbare Campagne worden in serie in werking gesteld met de oudercampagne (in tegenstelling tot de Campagne van het Verzoek, die parallel in een afzonderlijke Campagne van de Trekker loopt).

>[!NOTE]
>
>Uitvoerbare Campagnes zijn altijd kinderen van de (ouder) campagne die hen roept.

## Wanneer gebruikt u Campagne uitvoeren {#when-to-use-execute-campaign}

Er zijn veel dingen die je kunt doen met een uitvoerbare campagne. Zij worden ontworpen om gemeenschappelijke operationele taken, zoals lood het verpletteren, levenscyclusbeheer, en het scoring (onder anderen) te vergemakkelijken, en kunnen worden gebruikt om het zelfde werkschema van binnen Partij of teweeggebrachte Campagnes uit te voeren.

U kunt ze ook gebruiken wanneer u een aparte flow moet uitvoeren, maar u moet afhangen van de resultaten van die flow in de volgende keuzemogelijkheden voor de stap Stroom (als dit het geval is, moet u dat doen).

Uitvoeren Campagne is een verbetering op [Verzoek Campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/request-campaign.md), aangezien het in-series of parallel kan lopen, terwijl laatstgenoemde slechts parallel loopt.

>[!NOTE]
>
>De Stappen en Webhooks van de wachttijd zullen nooit compatibel met Uitvoerbare Campagnes zijn. Voor die, zult u de Campagne van het Verzoek in plaats daarvan moeten gebruiken.

## Een uitvoerbare campagne maken {#how-to-create-an-executable-campaign}

1. Klik met de rechtermuisknop op het gewenste programma en selecteer **Nieuwe slimme campagne**.

   ![](assets/execute-campaign-1.png)

1. Geef het een naam, selecteer **Uitvoerbaar** checkbox, en klik **creëren**.

   ![](assets/execute-campaign-2.png)

1. Definieer de slimme lijst en stroom, net als elke andere slimme campagne.

U kunt ook een bestaande slimme campagne klonen. Als u een bestaande Uitvoerbare Campagne kloont, zult u nog het **Uitvoerbare** checkbox na het noemen van het moeten selecteren.

>[!NOTE]
>
>U kunt geen campagne klonen die triggers bevat.

## Context {#use-parent-campaign-token-context} van token voor bovenliggende campagne gebruiken

Wanneer ingesteld op true, worden de volgende token-contexten verzonden naar de onderliggende campagne (de campagne die wordt uitgevoerd):

* Mijn tokens
* Campagne Tokens
* Programmatokens
* Member Tokens
* [Tokens](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/trigger-tokens-for-interesting-moments.md)  activeren (indien opgeroepen vanuit een geactiveerde campagne)

**API-interactie**

Wanneer het gebruiken van Programma of Campagne [in API](https://developers.marketo.com/rest-api/assets/smart-campaigns/#batch), allebei laat u waarden voor Mijn Tokens overgaan, die de waarden met voeten treedt die voor die tokens in de campagne worden geplaatst u roept. Als die Campagne dan een andere campagne uitvoert en &quot;de Context van de Ouder van het Gebruik aan Waar plaatst,&quot;zal het de waarden gebruiken die door API worden overgegaan, eerder dan de waarden die in de toepassing worden geplaatst.

## Notities {#things-to-note}

* De slimme lijst filtert iedereen uit die niet in aanmerking komt. Als een persoon kwalificeert, zal het resulterende Uitvoerde activiteitenverslag van de Campagne hen als &quot;Gekwalificeerd vermelden: TRUE&quot; (en FALSE indien niet)
* De kwalificatieregels van de Campagne van het programma zijn van toepassing (de Slimme Montages van de Campagne onder het lusje van het Programma)
* Uitvoerbare campagnes kunnen niet worden aangeroepen in verschillende werkruimten
* Als u [Remove uit Stroom](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/remove-from-flow.md) stroomactie gebruikt die zich richt op een Uitvoerbare Campagne, zal het zowel het kind als het ouder richten
* Gebruikend uit symbolische overerving - bijvoorbeeld, als u één enkele gemeenschappelijke het scoren stroom hebt die door veelvoudige verschillende activa teweeggebracht, kunt u een gebrek Mijn Symbolische score in de kindcampagne en in de oudercampagne bepalen zodat u de waarde van de kindscore campagnecampagne voor uw oudercampagnes (zie hieronder voor visueel voorbeeld) kunt met voeten treden
* Het nesten van Uitvoerbare Campagnes is niet beschikbaar op dit ogenblik, maar zal in een aanstaande versie zijn

>[!CAUTION]
>
>Laat uw slimme lijsten voor uitvoerbare campagnes nooit ongeldig, anders **zal niemand** voor het kwalificeren. De beste praktijken moeten afzonderlijke slimme lijstactiva tot stand brengen, hen volledig bepalen, en ervoor zorgen zij geldig zijn. Dan, gebruik het &quot;Lid van Slimme filter van de Lijst&quot;in de Uitvoerbare Campagne zodat kunt u uw slimme lijstdefinitie ruilen.

## Voorbeeld van symbolische overerving {#token-inheritance-example}

Hieronder ziet u een visueel voorbeeld van Symbolische Overerving in één Uitvoerbare Campagne en twee oudercampagnes: één met symbolische context die aan **Waar** wordt geplaatst, andere aan **Onwaar**.

Onderliggende campagne met een verkapte Change Score.

![](assets/execute-campaign-3.png)

De onderliggende campagne is Mijn Tokens.

![](assets/execute-campaign-4.png)

**Voorbeeld één - waar**

In de Uitgevoerde de debietstap van de Campagne van de Uitvoeren van de eerste oudercampagne, wordt &quot;de TokenContext van de Campagne van de Ouder van het Gebruik&quot;geplaatst aan **True**.

![](assets/execute-campaign-5.png)

De bovenliggende campagne is My Tokens.

![](assets/execute-campaign-6.png)

De resultaten: de score is gewijzigd met +10.

![](assets/execute-campaign-7.png)

**Voorbeeld twee: Onwaar**

In het filter Campagne uitvoeren van de tweede oudercampagne, wordt de &quot;Context van de Token van de Campagne van de Ouder van het Gebruik&quot;geplaatst aan **False**.

![](assets/execute-campaign-8.png)

De bovenliggende campagne is My Tokens.

![](assets/execute-campaign-9.png)

De resultaten: de score ongewijzigd blijft, omdat de score van de onderliggende campagne, +0, is gebruikt.

![](assets/execute-campaign-10.png)
