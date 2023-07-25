---
unique-page-id: 10096583
description: "Volgende generatie [!DNL Munchkin] Veelgestelde vragen over bijhouden - Marketo-documenten - productdocumentatie"
title: "Volgende generatie [!DNL Munchkin] Veelgestelde vragen over bijhouden"
exl-id: 283189ac-c817-479a-b896-91233980608c
feature: Administration, Munchkin Tracking Code
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '716'
ht-degree: 0%

---

# Volgende generatie [!DNL Munchkin] Veelgestelde vragen over bijhouden {#next-generation-munchkin-tracking-faq}

We zijn blij om te kunnen aankondigen dat we binnenkort een gefaseerde introductie van onze webtrackingtechnologie van de volgende generatie zullen starten.

Dit zijn de belangrijkste dingen die u moet weten:

* We verwijderen het filter &quot;Is Anoniem&quot; slimme lijst met onze Q1-versie (al klaar)
* We verhogen het aantal webgebeurtenissen (Bezoek webpagina, Klik op Koppeling op webpagina) dat we kunnen invoeren
* Uw [!DNL Munchkin] code wordt niet gewijzigd, dus er zijn geen updates voor uw website vereist

## Wanneer is mijn Marketo-abonnement ingeschakeld [!DNL Munchkin] V2? {#when-will-my-marketo-subscription-be-on-munchkin-v}

We hebben nog geen exacte datum, maar kom hier terug voor updates.

## Moet ik mijn [!DNL Munchkin] volgen op mijn website? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

Nee. De [!DNL Munchkin] de volgende code blijft hetzelfde. U hoeft geen wijzigingen in uw website aan te brengen.

>[!NOTE]
>
>Deze verandering beïnvloedt geen Personalisatie van het Web (Echt - tijd Personalisatie). Het blijft anonieme en bekende webbezoekers identificeren en inhoud in real-time personaliseren voor deze bezoekers.

## Waarom heeft Marketo het filter &quot;Is Anoniem&quot;uit Slimme Lijsten verwijderd? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

We veranderden hoe anonieme mensen interageren met slimme campagnes. Vroeger gingen ze door een slimme campagne, net als bekende mensen. Het filter &quot;Is Anoniem&quot;werd gebruikt om te specificeren dat slechts bekende of slechts anonieme mensen door de campagne stromen.

Met [!DNL Munchkin] V2, we zullen alle anonieme activiteiten blijven volgen; u kunt echter geen filters meer toepassen op anonieme personen . Op het moment van omzetting (wanneer de persoon in Marketo bekend wordt) worden alle activiteiten die plaatsvonden toen de persoon anoniem was, toegevoegd aan het activiteitenlogboek van de persoon en op dit moment stromen zij door de campagnes waarvoor zij in aanmerking komen.

Als u dit filter al in een Slimme Lijst (bijvoorbeeld, in een Slimme Campagne of een Rapport) gebruikt, wordt het niet automatisch verwijderd uit de Slimme Lijst. Zie hieronder voor meer informatie.

>[!NOTE]
>
>**Trigger**: Bezoekt de Web-pagina, de Web-pagina is Prijspagina\
>**Stroom**: Score +10 en interessant moment wijzigen
>**Web**: Weergegeven prijspagina
>
>Met [!DNL Munchkin] V2, als een anonieme persoon de prijspagina bezoekt, gaat zij niet onmiddellijk de campagne binnen. Op het moment dat de anonieme persoon bekend wordt, voeren we deze campagne op haar. Ze zal:
>
>* Een score van 10 halen
>
>* De activiteit van de Web-pagina hebben aan de juiste datum wordt geplaatst (toen zij eigenlijk bezocht)
>
>* Heb een Interessant Moment voor haar het programma wordt geopend (met de datum zij daadwerkelijk de pagina bezocht, niet toen zij gekend werd)
>
>* Heb een &quot;Nieuwe Persoon&quot;activiteit het programma wordt geopend aangezien het vandaag is

## Wat gebeurt er met mijn slimme lijsten die al het filter &quot;Is Anoniem&quot; hebben? {#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

Na onze Winter &#39;16 Versie, als u oude Slimme Campagnes met een Slimme Lijst hebt die het &quot;Is Anoniem&quot;filter in het heeft, zal één van twee dingen gebeuren:

1. Als de slimme lijst het filter &quot;is Anoniem = Onwaar&quot;heeft, dan zal niets gebeuren. We zullen het gewoon negeren.
1. Als de Slimme Lijst de filter &quot;is Anoniem = Waar&quot;heeft, dan zal deze campagne ontbreken en u zult een bericht worden verzonden.

## Ik gebruik Marketo al een tijdje. Hoe weet ik welke van mijn campagnes het filter &quot;Is Anoniem&quot;gebruiken? {#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

Voordat we deze wijziging aanbrachten, stuurden we een aantal wekelijkse meldingen naar het Postvak IN met een lijst met slimme lijsten, slimme campagnes en rapporten die gebruikmaken van het filter &quot;Is Anoniem&quot;. Deze kunnen u helpen identificeren waar u momenteel dit filter gebruikt.

Controleer deze en geef aan waar u &quot;Is anoniem&quot; hebt ingesteld op Waar, aangezien dit de betrokken campagnes zijn. Meestal gebruiken klanten deze instelling voor een bepaald type scoring. Zie het bovenstaande voorbeeld om te begrijpen hoe deze campagnes nu werken.

## Ik wil graag meer gedetailleerde documentatie. Waar kan ik het vinden? {#id-like-more-detailed-documentation-where-can-i-find-it}

Bekijk de volgende koppelingen:

[Overzicht van anonieme leads](https://nation.marketo.com/docs/DOC-2937){target="_blank"}

[Anonieme lead-upgrades - Wijzigingen in Marketo-gebruikersinterface](https://nation.marketo.com/docs/DOC-2938){target="_blank"}

[Anonieme hoofdupgrades - actie van de klant vereist](https://nation.marketo.com/docs/DOC-2939){target="_blank"}

[Anonieme lead-upgrades - analyserapporten](https://nation.marketo.com/docs/DOC-2940){target="_blank"}

[Anonieme hoofdupgrades - Releaseschema](https://nation.marketo.com/docs/DOC-2961){target="_blank"}

[Anonieme leads - onder de Hout](https://nation.marketo.com/docs/DOC-2962){target="_blank"}

[Anonieme lead-promotie voor bekende lead - [!DNL Munchkin] Gedrag V2](https://nation.marketo.com/docs/DOC-2963){target="_blank"}

## Ik heb nog meer vragen! Hoe krijg ik antwoord? {#i-have-more-questions-how-do-i-get-them-answered}

Neem contact op met de [gemeenschap](https://nation.marketo.com/){target="_blank"}. You can also contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}. Ze zullen graag je vragen beantwoorden.
