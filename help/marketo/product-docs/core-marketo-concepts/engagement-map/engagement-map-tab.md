---
description: Tabblad Betrokkenheid - Marketo-documenten - Productdocumentatie
title: Tabblad Betrokkenheid
hide: true
hidefromtoc: true
exl-id: f54b9258-451b-4607-b5a9-f8627c6f420a
source-git-commit: f88704f03a757f117fbb997eff13843cad637315
workflow-type: tm+mt
source-wordcount: '965'
ht-degree: 0%

---

# Tabblad Betrokkenheid {#engagement-map-tab}

De Kaart van de betrokkenheid wordt vertegenwoordigd door een reeks trekker, filter, en debietkaarten. Als u op elke kaart klikt, worden aanvullende gegevens weergegeven.

Overzicht van trigger: Deze kaart geeft het aantal triggers in uw campagne weer. Als u erop klikt, wordt een kaart voor elke trigger en een uitschuifvenster weergegeven met de volgende informatie:

* Campagne voeren waarbij de trigger hoort
* Lijst met triggernamen
* Knop Trigger bewerken

  ![](assets/engagement-map-tab-1.png)

Triggergegevens: op deze kaart wordt de naam van de trigger weergegeven. Als u erop klikt, wordt een uitschuifvenster weergegeven met de volgende informatie:

* Campagne voeren waarbij de trigger hoort
* Lijst met beperkingen die zijn gekoppeld aan de trigger
* Knop Trigger bewerken

  ![](assets/engagement-map-tab-2.png)

Filter: als u op deze kaart klikt, wordt een venster weergegeven met de volgende informatie:

* Campagne voeren waarbij de trigger hoort
* Geschat aantal personen dat voor het filter in aanmerking komt
* Lijst van filters en hun respectieve beperkingen
* De knop Filter bewerken

  ![](assets/engagement-map-tab-3.png)

Stappen voor stroom: als een stap voor stroom keuzen bevat, wordt op deze kaart de naam van de stap voor stroom weergegeven. Als u erop klikt, wordt een uitschuifvenster weergegeven met de volgende informatie:

* Campagne voeren voor de stap Stroom behoort tot
* Lijst met keuzevoorwaarden die aan de flowstap zijn gekoppeld
* De knop Stroom bewerken

  ![](assets/engagement-map-tab-4.png)

Stappen voor stroom: als een stap voor stroom _niet_ Deze kaart bevat alle opties die aan de flowstap zijn gekoppeld. Als u erop klikt, wordt een uitschuifvenster weergegeven met de volgende informatie:

* Campagne voeren voor de stap Stroom behoort tot
* Lijst met kenmerken die aan de flowstap zijn gekoppeld
* De knop Stroom bewerken

  ![](assets/engagement-map-tab-5.png)

## De Stap van de stroom voor Uitvoeren en vraagt Campagnes {#flow-step-for-execute-and-request-campaigns}

* Als de de stroomstap van de Campagne van de Uitvoeren of van het Verzoek geen keuzen omvat, zal de kaart de naam van de campagne tonen. Als u op de kaart klikt, wordt een venster met de volgende informatie weergegeven:

   * Campagne voeren voor de flowstap behoort tot
   * De knop Stroom bewerken
   * Lijst met kenmerken die aan de flowstap zijn gekoppeld
   * De knop Lijst weergeven, waarmee u een lijst opent met campagnes die de specifieke campagne Verzoek/Uitvoeren gebruiken

>[!NOTE]
>
>U kunt de flowstap(en) vanuit een primaire campagne bewerken. Als u geneste campagnes wilt bewerken, moet u naar de campagne navigeren via de koppeling in het deelvenster Uitschuiven.

![](assets/engagement-map-tab-6.png)

![](assets/engagement-map-tab-7.png)

* Als de de stroomstap van de Campagne van de Uitvoeren of van het Verzoek keuzen omvat, zal de kaart de naam van de campagne tonen. Als u op de kaart klikt, wordt een venster met de volgende informatie weergegeven:

   * Campagne voeren voor de flowstap behoort tot
   * Lijst met keuzevoorwaarden die aan de flowstap zijn gekoppeld
   * De knop Stroom bewerken

  ![](assets/engagement-map-tab-8.png)

  ![](assets/engagement-map-tab-9.png)

* Als een campagne voor uitvoeren of aanvragen opties bevat, wordt het klikken op de stroomkaart uitgebreid en worden alle opties in de afzonderlijke kaarten weergegeven. Als u op de keuzevaart klikt, wordt de campagne voor de specifieke keuze uitgebreid en wordt een venster met de volgende informatie weergegeven:

   * Campagne van de keuze behoort tot
   * Knop Keuze bewerken
   * Lijst met keuzevoorwaarden die aan de flowstap zijn gekoppeld
   * De knop Lijst weergeven, waarmee u een lijst opent met campagnes die de specifieke campagne Verzoek/Uitvoeren gebruiken

  ![](assets/engagement-map-tab-10.png)

## Een geneste campagne voor uitvoeren visualiseren {#visualizing-a-nested-execute-campaign}

Voer campagnes in serie met de oudercampagne uit. De mensen die voor een uitvoerbare campagne kwalificeren voltooien alle stroomstappen van de campagne en keren aan de primaire campagne terug om door de stroomstappen van deze campagne verder te gaan.

Hieronder ziet u een voorbeeld van een slimme campagne, Campagne A, die een stap bevat voor het uitvoeren van de campagnestroom. Beschouw &#39;Campagne A&#39; als uw primaire campagne.

![](assets/engagement-map-tab-11.png)

1. Klik op de campagnestrookaart uitvoeren om de details van &quot;Campagne B&quot; te tonen.
1. &quot;Campagne B&quot; omvat een filter dat het publiek in twee groepen splitst: gekwalificeerd en niet gekwalificeerd.
1. Gekwalificeerd publiek doorloopt de aan &quot;Campagne B.&quot; gekoppelde stroomstappen.
1. Alle (gekwalificeerde en niet-gekwalificeerde) doelgroepen keren terug naar &quot;Campagne A&quot; en gaan door naar de volgende flowstap.

   ![](assets/engagement-map-tab-12.png)

U kunt op de Uitvoeren de stroomstap van de Campagne in &quot;Campagne B&quot;klikken die zal uitbreiden om de keuzevakaarten en de campagne te tonen verbonden aan elke keus.

![](assets/engagement-map-tab-13.png)

## Bezig met visualiseren aanvraagcampagne {#visualizing-request-campaign}

Aanvraagcampagnes worden parallel met de bovenliggende campagne uitgevoerd. De mensen die voor een verzoekcampagne in aanmerking komen voltooien alle stroomstappen van de campagne en gaan dan de campagne weg. Tegelijk, gaat de zelfde reeks mensen door de stroomstappen van de primaire campagne.

Hier is een voorbeeld van een Slimme Campagne, &quot;Campagne A,&quot;die een stap van de verzoekcampagnestroom omvat. Beschouw &#39;Campagne A&#39; als uw primaire campagne.

![](assets/engagement-map-tab-14.png)

1. Klik op de de stroomkaart van de verzoekcampagne zal uitbreiden om de details van &quot;Campagne B&quot; te tonen
1. &quot;Campagne B&quot; omvat een filter dat het publiek in twee groepen splitst: gekwalificeerd en niet gekwalificeerd.
1. Gekwalificeerd publiek doorloopt de aan &quot;Campagne B.&quot; gekoppelde stroomstappen.
1. Tezelfdertijd beweegt alle publiek zich aan de volgende stroomstappen in &quot;Campagne A.&quot;

   ![](assets/engagement-map-tab-15.png)

U kunt dieper in uw genestelde campagnes duiken als om het even welke stroomstappen een andere verzoekcampagne omvatten door op de stroomkaart te klikken om de details van de campagne te bekijken.

![](assets/engagement-map-tab-16.png)

Hier is een voorbeeld van een aanvraagcampagne met keuzes.

![](assets/engagement-map-tab-17.png)

## Foutafhandeling {#error-handling}

Fouten in slimme lijsten en stroomstappen worden gemarkeerd met een foutpictogram op de kaart. Bovendien wordt een bijbehorende foutmelding weergegeven in het deelvenster Uitschuiven.

Hieronder ziet u een voorbeeld van een fout in een trigger die wordt weergegeven in de overzichtkaart van de trigger, het deelvenster Uitschuiven en de gedetailleerde triggerkaart.

![](assets/engagement-map-tab-18.png)

![](assets/engagement-map-tab-19.png)

**Fouten in filterkaarten kunnen het volgende omvatten:**

* Een fout in de slimme lijst die ertoe zal leiden dat gekwalificeerd publiek niet wordt getoond

* Een fout in de filterlogica

* Een fout in beperkingen (of het ontbreken daarvan) in een of meer filters

  ![](assets/engagement-map-tab-20.png)

Als u geen waarden (kenmerken) invoert, treedt er geen fout op. De ingevoerde waarde werkt ook als op het tabblad Stroom. Bestaande campagnes zullen daarom niet worden verstoord. Als de stroomstappen echter geen kenmerken bevatten, worden deze weergegeven als waarschuwingen.

^^^ DIT ECHT NODIG, ZULLEN DE KLANT GEEN WAARSCHUWING ZIEN?

![](assets/engagement-map-tab-21.png)

>[!NOTE]
>
>Fouten in een geneste campagne zijn pas zichtbaar nadat u hebt geklikt om de geneste campagne uit te breiden.
