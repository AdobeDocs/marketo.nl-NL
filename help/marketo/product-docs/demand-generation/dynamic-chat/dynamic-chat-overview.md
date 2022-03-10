---
description: Dynamisch chatoverzicht - Marketo Docs - Productdocumentatie
title: Dynamisch chatoverzicht
exl-id: 73ab651e-bb11-459d-aa6a-39d9e208d512
source-git-commit: c386d5ae542f4f19ba2acf6d2472a0c9d79c20a3
workflow-type: tm+mt
source-wordcount: '735'
ht-degree: 0%

---

# Dynamisch chatoverzicht {#dynamic-chat-overview}

Met Dynamic Chat kunt u een gebruiksvriendelijke interface gebruiken om gebruikers en accounts die uw website bezoeken, als doel in te stellen. Verzamel relevante inhoud, zoals naam, contactgegevens en vrije tekst. De bezoekers van de plaats kunnen vergaderingen met uw Team van de Verkoop ook boeken. Dynamische chatactiviteiten en betrokkenheidsgegevens kunnen worden gebruikt om leden toe te voegen aan Marketo-programma&#39;s en om kanaalactiviteiten te activeren.

>[!NOTE]
>
>Dynamic Chat wordt momenteel geleidelijk ingevoerd en is momenteel in beperkte beschikbaarheid. Deze pagina zal met algemene beschikbaarheidsdetails (GA) worden bijgewerkt aangezien zij beschikbaar worden.

>[!TIP]
>
>Bezoek [deze pagina](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dynamic-chat-overview.html) om zelfstudievideo&#39;s van Dynamic Chat weer te geven.

## Integraties {#integrations}

Een belangrijk onderdeel van Dynamic Chat is de mogelijkheid om native verbinding te maken met uw Marketo-abonnement. Als u deze integratie volledig wilt benutten, moet u eerst de gegevenssynchronisatie starten. Afhankelijk van de grootte van uw Marketo-database kan het maximaal 24 uur duren voordat gegevens voor de eerste database zijn opgeslagen, [eenmalig synchroniseren](/help/marketo/product-docs/demand-generation/dynamic-chat/connect-dynamic-chat-to-marketo.md) om te voltooien.

Het volgende wordt gesynchroniseerd:

* Persoonsveldgegevens
* Bedrijfsveldgegevens
* Activiteitsgegevens

## Dialoogvensters {#dialogues}

Dialoogvensters vertegenwoordigen één chatgesprek. Beschouw het als een container met alle informatie die u nodig hebt om een aansprekende chatdialoog met uw websitebezoekers te voeren. In elk dialoogvenster kunt u opgeven op welke pagina(&#39;s) u het dialoogvenster wilt weergeven, aan wie u het dialoogvenster wilt laten weergeven, en kunt u de inhoud en de stroom van het dialoogvenster zelf opgeven. Bovendien kunt u metriek vinden om te zien hoe goed uw Dialoog presteert. [Meer informatie over dialoogvensters](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues.md).

## Configuratie {#configuration}

In het lusje van de Configuratie, pas de blik en het gevoel van uw diverse Dialogen aan. Wijzig lettertype, kleuren, responstijd en meer! [Meer informatie over Configuratie](/help/marketo/product-docs/demand-generation/dynamic-chat/configuration.md).

## Kalender {#calendar}

In het lusje van de Kalender, verbind uw (Vooruitzichten of Gmail) kalender voor gebruik in afspraak die in het praatje plant. Zodra de kalender van een gebruiker met Dynamisch Praatje wordt verbonden, zal die gebruiker aan de rij worden toegevoegd en hun kalender zal voor websitebezoekers beschikbaar zijn om benoemingen te plannen op.

U kunt ook de hoofdtekst van de uitnodiging aanpassen die naar de bezoeker wordt verzonden wanneer deze een afspraak in de agenda van de gebruiker plant.

## Vergaderingen {#meetings}

Hier ziet u alle afspraken die door websitebezoekers zijn gepland via uw verschillende dialoogvensters. Hier vindt u het e-mailadres van de persoon die de afspraak heeft geboekt, met welke agent de afspraak is geboekt, wanneer de afspraak gepland is en of de vergadering al dan niet heeft plaatsgevonden.

## Routering {#routing}

Hier kunt u een lijst zien van alle agenten die hun kalenders hebben aangesloten evenals welke orde zij aan websitebezoekers zullen worden voorgesteld. De vergaderingen gaan rond robin stijl, zodat als u vijf agenten hebt en agent drie nam de laatste vergadering, agent vier volgende krijgt, gevolgd door agent vijf, dan terug naar agent één.

## Veelgestelde vragen {#faq}

**Staat Dynamic Chat live chatten toe?**

Neen, het gebruikt slechts vooraf bepaalde reacties.

**Hoe kan ik mij richten op anonieme mensen?**

In uw dialoogvenster moet u de opdracht _Persoonsbericht is leeg_ kenmerk.

**Ondersteunt u de AI/NLP-functionaliteit?**

AI/NLP-functionaliteit wordt niet ondersteund.

**Hoe lang worden gegevens voor rapportage opgeslagen?**

90 dagen.

**Biedt Dynamic Chat naast Engels ook talen?**

Op dit moment niet.

## Limieten in dynamische chat {#limits-in-dynamic-chat}

<table>
  <th>Parameter</th>
  <th>Beschrijving</th>
  <th>Limiet</th>
 <tr>
  <td>Totaal aantal dialoogvensters</td>
  <td>Totaal aantal dialoogvensters (gepubliceerd en concept)</td>
  <td>500</td>
 </tr>
 <tr>
  <td>Gepubliceerde dialoogvensters</td>
  <td>Aantal gepubliceerde dialoogvensters dat is opgeslagen</td>
  <td>100</td>
 </tr>
 <tr>
  <td>Doel-URL's per dialoogvenster</td>
  <td>Aantal doel-URL's dat kan worden toegevoegd aan één dialoogvenster</td>
  <td>20</td>
 </tr>
 <tr>
  <td>Kenmerken per dialoogvenster</td>
  <td>Aantal kenmerken dat kan worden toegevoegd aan publiekscriteria voor één dialoogvenster</td>
  <td>100</td>
 </tr>
 <tr>
  <td>Groepen</td>
  <td>Aantal groepen dat kan worden toegevoegd aan één dialoogvenster</td>
  <td>10</td>
 </tr>
 <tr>
  <td>Attributen per groep</td>
  <td>Aantal kenmerken dat aan een groep kan worden toegevoegd</td>
  <td>10</td>
 </tr>
 <tr>
  <td>Kaarten</td>
  <td>Aantal kaarten dat per Dialoogvenster aan het canvas kan worden toegevoegd</td>
  <td>500</td>
 </tr>
 <tr>
  <td>Bewaarperiode anonieme gegevens lead</td>
  <td>Duur van de periode waarin informatie over een anonieme lead zonder enige betrokkenheid bewaard blijft</td>
  <td>90 dagen</td>
 </tr>
 <tr>
  <td>Aanhoudingsperiode van de reële activiteit</td>
  <td>De hoeveelheid tijd die de activiteitengegevens van het doel worden behouden</td>
  <td>24 maanden</td>
 </tr>
 <tr>
  <td>Bewaarperiode documentactiviteit</td>
  <td>De hoeveelheid tijd die nodig is om de activiteitengegevens van het document te behouden</td>
  <td>24 maanden</td>
 </tr>
 <tr>
  <td>Interactie met periode van activiteit in het dialoogvenster</td>
  <td>De hoeveelheid tijd die interactie heeft met de gegevens over dialoogactiviteiten blijft behouden</td>
  <td>90 dagen</td>
 </tr>
 <tr>
  <td>Bewaarperiode van boekingsactiviteit vergadering</td>
  <td>De hoeveelheid tijd die vergadering het boeken activiteit zal worden opgeslagen in Dynamisch Praatje</td>
  <td>24 maanden</td>
 </tr>
</table>
