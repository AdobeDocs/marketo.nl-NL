---
unique-page-id: 10096583
description: Volgende Generatie  [!DNL Munchkin]  het Volgen Veelgestelde Veelgestelde vragen - de Documenten van Marketo - de Documentatie van het Product
title: Volgende Generatie  [!DNL Munchkin]  het Volgen Veelgestelde vragen
exl-id: 283189ac-c817-479a-b896-91233980608c
feature: Administration, Munchkin Tracking Code
hide: true
hidefromtoc: true
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '698'
ht-degree: 0%

---

# Veelgestelde vragen over bijhouden van volgende generatie [!DNL Munchkin] {#next-generation-munchkin-tracking-faq}

We zijn blij om te kunnen aankondigen dat we binnenkort een gefaseerde introductie van onze webtrackingtechnologie van de volgende generatie zullen starten.

Dit zijn de belangrijkste dingen die u moet weten:

* We verwijderen het filter &quot;Is Anoniem&quot; slimme lijst met onze Q1-versie (al klaar)
* We verhogen het aantal webgebeurtenissen (Bezoek webpagina, Klik op Koppeling op webpagina) dat we kunnen invoeren
* Uw [!DNL Munchkin] -code wordt niet gewijzigd, dus er zijn geen updates voor uw website vereist

## Wanneer zal mijn Marketo-abonnement op [!DNL Munchkin] V2 zijn? {#when-will-my-marketo-subscription-be-on-munchkin-v}

We hebben nog geen exacte datum, maar kom hier terug voor updates.

## Moet ik wijzigingen aanbrengen in mijn [!DNL Munchkin] tracking op mijn website? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

Nee. De [!DNL Munchkin] -trackingcode blijft ongewijzigd. U hoeft geen wijzigingen in uw website aan te brengen.

>[!NOTE]
>
>Deze wijziging heeft geen invloed op Web Personalization (Real-Time Personalization). Het blijft anonieme en bekende webbezoekers identificeren en inhoud in real-time personaliseren voor deze bezoekers.

## Waarom heeft Marketo het filter &quot;Is Anoniem&quot;uit Slimme Lijsten verwijderd? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

We veranderden hoe anonieme mensen interageren met slimme campagnes. Vroeger gingen ze door een slimme campagne, net als bekende mensen. Het filter &quot;Is Anoniem&quot;werd gebruikt om te specificeren dat slechts bekende of slechts anonieme mensen door de campagne stromen.

Met [!DNL Munchkin] V2 blijven we alle anonieme activiteiten volgen, maar u kunt geen filters meer toepassen op anonieme personen. Op het moment van omzetting (wanneer de persoon in Marketo bekend wordt) worden alle activiteiten die plaatsvonden toen de persoon anoniem was, toegevoegd aan het activiteitenlogboek van de persoon en op dit moment stromen zij door de campagnes waarvoor zij in aanmerking komen.

Als u dit filter al in een Slimme Lijst (bijvoorbeeld, in een Slimme Campagne of een Rapport) gebruikt, wordt het niet automatisch verwijderd uit de Slimme Lijst. Zie hieronder voor meer informatie.

>[!NOTE]
>
>**Trekker**: Bezoekt Web-pagina, de Pagina van het Web Prijsingspagina
>>**Stroom**: Score +10 en Interessant moment wijzigen
>>**Web**: Bekeken Prijspagina
>
>Met [!DNL Munchkin] V2 voert een anonieme persoon die de prijspagina bezoekt, niet onmiddellijk de campagne in. Op het moment dat de anonieme persoon bekend wordt, voeren we deze campagne op haar. Ze zal:
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

[ Anonieme Lood verbetert Overzicht ](https://nation.marketo.com/docs/DOC-2937){target="_blank"}

[ anonieme loodverbeteringen - Veranderingen binnen Marketo UI ](https://nation.marketo.com/docs/DOC-2938){target="_blank"}

[ anonieme loodverbeteringen - de Actie van de Klant Nodig ](https://nation.marketo.com/docs/DOC-2939){target="_blank"}

[ anonieme loodverbeteringen - de Rapporten van Analytics ](https://nation.marketo.com/docs/DOC-2940){target="_blank"}

[ Anonieme verbeteringen van de Lood - de Lijst van de Versie ](https://nation.marketo.com/docs/DOC-2961){target="_blank"}

[ anonieme loodverbeteringen - onder het Hood ](https://nation.marketo.com/docs/DOC-2962){target="_blank"}

[ Anonieme Loodbevordering aan Bekende Lood -  [!DNL Munchkin]  V2 Gedrag ](https://nation.marketo.com/docs/DOC-2963){target="_blank"}

## Ik heb nog meer vragen! Hoe krijg ik antwoord? {#i-have-more-questions-how-do-i-get-them-answered}

Gelieve te bereiken uit op de [ gemeenschap ](https://nation.marketo.com/){target="_blank"}. U kunt [ Steun van Marketo ](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"} ook contacteren. Ze zullen graag je vragen beantwoorden.
