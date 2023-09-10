---
description: Overzicht Dynamic Chat - Marketo Docs - Productdocumentatie
title: Overzicht van Dynamic Chat
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: 3fc84a0e679b0b27aaf4ee251668a3ba0a62f9ef
workflow-type: tm+mt
source-wordcount: '873'
ht-degree: 1%

---

# Overzicht van Dynamic Chat {#dynamic-chat-overview}

Met Dynamic Chat kunt u een gebruiksvriendelijke interface gebruiken om gebruikers en accounts die uw website bezoeken, als doel in te stellen. Verzamel relevante inhoud, zoals naam, contactgegevens en vrije tekst. De bezoekers van de plaats kunnen vergaderingen met uw Team van de Verkoop ook boeken. Gegevens over activiteiten en betrokkenheid van Dynamics Chat kunnen worden gebruikt om leden toe te voegen aan Marketo-programma&#39;s en kanaalactiviteiten te activeren.

>[!NOTE]
>
>Dynamic Chat wordt geleidelijk ingevoerd en is momenteel in beperkte mate beschikbaar. Deze pagina zal met algemene beschikbaarheidsdetails (GA) worden bijgewerkt aangezien zij beschikbaar worden.

>[!TIP]
>
>Bezoek [deze pagina](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dynamic-chat-overview.html) om zelfstudievideo&#39;s van Dynamic Chat weer te geven.

## Integraties {#integrations}

Een belangrijke component van Dynamic Chat is zijn capaciteit om met uw abonnement van Marketo te communiceren. Als u de volledige mogelijkheden van deze integratie wilt benutten, moet u eerst de gegevenssynchronisatie starten. Afhankelijk van de grootte van uw Marketo-database kan het maximaal 24 uur duren voordat gegevens voor de eerste database zijn opgeslagen, [eenmalige synchronisatie](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/connect-dynamic-chat-to-marketo.md) in.

Het volgende wordt gesynchroniseerd:

* Persoonsveldgegevens
* Bedrijfsveldgegevens
* Activiteitsgegevens

## Dialoogvensters {#dialogues}

Dialoogvensters vertegenwoordigen één chatgesprek. Beschouw het als een container met alle informatie die u nodig hebt om een aansprekende chatdialoog met uw websitebezoekers te voeren. In elk dialoogvenster kunt u opgeven op welke pagina(&#39;s) u het dialoogvenster wilt weergeven, aan wie u het dialoogvenster wilt laten weergeven, en kunt u de inhoud en de stroom van het dialoogvenster zelf opgeven. Bovendien kunt u metriek vinden om te zien hoe goed uw Dialoog presteert. [Meer informatie over dialoogvensters](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/dialogue-overview.md){target="_blank"}.

## Configuratie {#configuration}

In het lusje van de Configuratie, pas de blik en het gevoel van uw diverse Dialogen aan. Wijzig lettertype, kleuren, responstijd en meer! [Meer informatie over Configuratie](/help/marketo/product-docs/demand-generation/dynamic-chat/configuration.md){target="_blank"}.

## Kalender {#calendar}

Verbind uw Vooruitzichten of Gmail kalender voor gebruik in benoeming die in het praatje plant. [Meer informatie over Kalender](/help/marketo/product-docs/demand-generation/dynamic-chat/appointment-scheduling/calendar.md){target="_blank"}

## Vergaderingen {#meetings}

Hier ziet u alle afspraken die door websitebezoekers zijn gepland via uw verschillende dialoogvensters. [Meer informatie over vergaderingen](/help/marketo/product-docs/demand-generation/dynamic-chat/appointment-scheduling/meetings.md){target="_blank"}

## Routering {#routing}

Dit is waar u een lijst van alle agenten kunt zien die hun kalenders hebben aangesloten, welke orde zij aan websitebezoekers zullen worden voorgesteld, en douane het verpletteren regels tot stand brengen. [Meer informatie over routeren](/help/marketo/product-docs/demand-generation/dynamic-chat/appointment-scheduling/routing.md){target="_blank"}

## Live Chat {#live-chat}

Bied uw gekwalificeerde webbezoekers via [live chat](/help/marketo/product-docs/demand-generation/dynamic-chat-two/live-chat/agent-inbox.md){target="_blank"}.

## Veelgestelde vragen {#faq}

**Kan ik Dynamic Chat ergens op mijn bedrijfswebsite installeren of werkt het alleen op Marketo landingspagina&#39;s?**

Het JavaScript-fragment voor Dynamics Chat kan op elke website en op elke bestemmingspagina van Marketo worden geïnstalleerd.

**Hoe lang worden gegevens voor rapportage opgeslagen?**

90 dagen (zie de volledige lijst van limieten) [onder](#limits-in-dynamic-chat)).

**Staat Dynamic Chat live chatten toe?**

Neen, het gebruikt slechts vooraf bepaalde reacties.

**Steunt de Dynamic Chat om het even welke talen behalve Engels?**

Ja. Dynamic Chat ondersteunt de volgende talen: Frans, Duits, Japans, Spaans, Italiaans, Braziliaans Portugees, Koreaans, Vereenvoudigd Chinees en Traditioneel Chinees. Meer informatie in het dialoogvenster [sectie hieronder](#changing-the-language).

**Ondersteunt u de AI/NLP-functionaliteit?**

AI/NLP-functionaliteit wordt niet ondersteund.

**Hoe kan ik mij richten op anonieme mensen?**

In uw dialoogvenster moet u de opdracht _Persoonsbericht is leeg_ kenmerk.

## De taal wijzigen {#changing-the-language}

Ga als volgt te werk om de taal van uw Dynamic Chat te wijzigen.

>[!IMPORTANT]
>
>Als u de taal op profielniveau wijzigt, wordt de taal voor _alles_ Experience Cloud toepassingen, niet alleen Dynamic Chat.

1. Klik in uw Experience Cloud-account op het instellingenpictogram en kies **Voorkeuren**.

   ![](assets/dynamic-chat-overview-1.png)

1. Klik op de huidige taal onder uw e-mailadres.

   ![](assets/dynamic-chat-overview-2.png)

1. Kies de nieuwe taal (de tweede taal is optioneel) en klik op **Opslaan**.

   ![](assets/dynamic-chat-overview-3.png)

   >[!NOTE]
   >
   >Er zijn een paar dozijn talen om uit te kiezen, echter, steunt slechts het volgende: Engels, Frans, Duits, Japans, Spaans, Italiaans, Braziliaans Portugees, Koreaans, Vereenvoudigd Chinees, en Traditioneel Chinees.

Wanneer u de taal bijwerkt, verandert alles in de app zelf, behalve de woorden die u persoonlijk hebt ingevuld (bijvoorbeeld reacties op de stream).

## Limieten in Dynamic Chat {#limits-in-dynamic-chat}

<table>
  <th>Parameter</th>
  <th>Beschrijving</th>
  <th>Limiet</th>
 <tr>
  <td>Totaal aantal dialoogvensters</td>
  <td>Aantal dialoogvensters (gepubliceerd en concept)</td>
  <td>500</td>
 </tr>
 <tr>
  <td>Totaal aantal kalenders</td>
  <td>Aantal verbonden kalenders</td>
  <td>25</td>
 </tr>
 <tr>
  <td>Totaal aantal gebruikers (beheerders en marketinggebruikers)</td>
  <td>Aantal gecombineerde gebruikers toegestaan per instantie van de Dynamic Chat</td>
  <td>50</td>
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
  <td>Het aantal kaarten dat per dialoogvenster aan het canvas kan worden toegevoegd</td>
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
  <td>Bewaarperiode van boekingsactiviteit van vergadering</td>
  <td>De hoeveelheid tijd die vergadering het boeken activiteit zal in Dynamic Chat worden opgeslagen</td>
  <td>24 maanden</td>
 </tr>
 <tr>
  <td>Gesprek</td>
  <td>Aantal chatgesprekken waarmee webbezoekers per maand kunnen werken</td>
  <td>250</td>
 </tr>
 <tr>
  <td>Gesprek geactiveerd</td>
  <td>Aantal chatgesprekken dat per maand aan webbezoekers kan worden getoond</td>
  <td>25,000</td>
 </tr>
</table>
