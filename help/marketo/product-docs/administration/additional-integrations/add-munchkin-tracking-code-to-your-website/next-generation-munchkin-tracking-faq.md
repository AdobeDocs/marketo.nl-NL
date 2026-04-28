---
unique-page-id: 10096583
description: Veelgestelde vragen over volgende-generatie  [!DNL Munchkin]  het volgen rollout en is Anoniem filterverandering.
title: Volgende Generatie  [!DNL Munchkin]  het Volgen Veelgestelde vragen
exl-id: 283189ac-c817-479a-b896-91233980608c
feature: Administration, Munchkin Tracking Code
hide: true
hidefromtoc: true
source-git-commit: 40f06a5391f2f7263bea0c5b8cefc1f3a607c68c
workflow-type: tm+mt
source-wordcount: '705'
ht-degree: 0%

---

# Veelgestelde vragen over bijhouden van volgende generatie [!DNL Munchkin] {#next-generation-munchkin-tracking-faq}

Marketo is rolling out next-generation web tracking technology in phases.

Dit zijn de belangrijkste dingen die u moet weten:

* The &quot;Is Anonymous&quot; Smart List filter has been removed
* Het aantal webgebeurtenissen (Bezoek webpagina, Klikte koppeling op webpagina) dat Marketo kan toevoegen neemt toe
* Uw [!DNL Munchkin] -code wordt niet gewijzigd, dus er zijn geen updates voor uw website vereist

## Wanneer zal mijn Marketo-abonnement op [!DNL Munchkin] V2 zijn? {#when-will-my-marketo-subscription-be-on-munchkin-v}

Een exacte datum is nog niet beschikbaar. Controleer deze pagina voor updates.

## Moet ik wijzigingen aanbrengen in mijn [!DNL Munchkin] tracking op mijn website? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

Nee. De [!DNL Munchkin] -trackingcode blijft ongewijzigd. U hoeft geen wijzigingen in uw website aan te brengen.

>[!NOTE]
>
>Deze wijziging heeft geen invloed op Web Personalization (Real-Time Personalization). Het blijft anonieme en bekende webbezoekers identificeren en inhoud in real-time personaliseren voor deze bezoekers.

## Waarom heeft Marketo het filter &quot;Is Anoniem&quot;uit Slimme Lijsten verwijderd? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

Marketo veranderde de manier waarop anonieme mensen met slimme campagnes communiceren. Vroeger gingen ze door een slimme campagne, net als bekende mensen. Het filter &quot;Is Anoniem&quot;werd gebruikt om te specificeren dat slechts bekende of slechts anonieme mensen door de campagne stromen.

Met [!DNL Munchkin] V2 blijft Marketo alle anonieme activiteiten bijhouden, maar kunt u geen filters meer toepassen op anonieme personen. Op het moment van omzetting (wanneer de persoon in Marketo bekend wordt) worden alle activiteiten die plaatsvonden toen de persoon anoniem was, toegevoegd aan het activiteitenlogboek van de persoon en op dit moment stromen zij door de campagnes waarvoor zij in aanmerking komen.

Als u dit filter al in een Slimme Lijst (bijvoorbeeld, in een Slimme Campagne of een Rapport) gebruikt, wordt het niet automatisch verwijderd uit de Slimme Lijst. See below for more details.

>[!NOTE]
>
>**Trigger**: Visits Web Page, Web Page is Pricing Page >**Flow**: Change Score +10 and Interesting Moment >**Web**: Viewed Pricing Page
>
>With [!DNL Munchkin] V2, if an anonymous person visits the pricing page, they do not enter the campaign immediately. At the time the anonymous person becomes known, Marketo runs this campaign on them. They will:
>
>* Get a score of 10
>
>* Have the Web Page activity set to the right date (when they actually visited)
>
>* Have an Interesting Moment logged for them (with the date they actually visited the page, not when they became known)
>
>* Have a &quot;New Person&quot; activity logged, as it is today

## What happens to my Smart Lists that already have the &quot;Is Anonymous&quot; filter? {#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

After the Winter &#39;16 Release, if you have old Smart Campaigns with a Smart List that has the &quot;Is Anonymous&quot; filter in it, one of two things will happen:

1. If the Smart List has the filter &quot;Is Anonymous = False&quot;, then nothing will happen. It is ignored.
1. If the Smart List has the filter &quot;Is Anonymous = True&quot;, this campaign will fail and a notification is sent.

## I have been using Marketo for a while. How do I know which of my campaigns use the &quot;Is Anonymous&quot; filter? {#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

Before this change, Marketo sent several weekly notifications to your Notifications inbox with a list of Smart Lists, Smart Campaigns and Reports that use the &quot;Is Anonymous&quot; filter. These can help you identify where you are currently using this filter.

Review them and identify where you have &quot;Is Anonymous&quot; set to True, as these are the campaigns that are affected. Most times, this setting is used for some kind of scoring. See the example above to understand how these campaigns will work now.

## I would like more detailed documentation. Where can I find it? {#id-like-more-detailed-documentation-where-can-i-find-it}

Bekijk de volgende koppelingen:

[Overzicht van anonieme leads](https://nation.marketo.com/docs/DOC-2937){target="_blank"}

[Anonieme lead-upgrades - Wijzigingen in Marketo-gebruikersinterface](https://nation.marketo.com/docs/DOC-2938){target="_blank"}

[Anonieme hoofdupgrades - actie van de klant vereist](https://nation.marketo.com/docs/DOC-2939){target="_blank"}

[Anonieme lead-upgrades - analyserapporten](https://nation.marketo.com/docs/DOC-2940){target="_blank"}

[Anonieme hoofdupgrades - Releaseschema](https://nation.marketo.com/docs/DOC-2961){target="_blank"}

[Anonieme leads - onder de Hout](https://nation.marketo.com/docs/DOC-2962){target="_blank"}

[De anonieme Bevordering van de Lood aan Bekende Lood - [!DNL Munchkin]  V2 Gedrag](https://nation.marketo.com/docs/DOC-2963){target="_blank"}

## Ik heb nog meer vragen! Hoe krijg ik antwoord? {#i-have-more-questions-how-do-i-get-them-answered}

Bezoek de [&#x200B; Gemeenschap van Marketo &#x200B;](https://experienceleaguecommunities.adobe.com/?profile.language=nl){target="_blank"}. Je kunt ook contact opnemen met Marketo Support. Ze zijn blij uw vragen te beantwoorden.
