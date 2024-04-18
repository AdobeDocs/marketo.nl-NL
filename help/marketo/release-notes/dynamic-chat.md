---
description: Opmerkingen bij de release Dynamic Chat - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release Dynamic Chat
hide: true
hidefromtoc: true
feature: Release Information, Dynamic Chat
exl-id: 0447dc47-b9c5-42e1-8f66-73bf67c7871d
source-git-commit: 9f442b64f2e6d012207f79d06298583655db86b7
workflow-type: tm+mt
source-wordcount: '1203'
ht-degree: 0%

---

# Opmerkingen bij de release Dynamic Chat {#dynamic-chat-release}

De versies van de Adobe Dynamic Chat werken op een ononderbroken leveringsmodel dat voor een scalable benadering van eigenschapplaatsing toestaat. Soms zijn er meerdere releases per maand, dus raadpleeg je regelmatig voor de meest actuele informatie.

De standaardpagina Opmerkingen bij de release voor Marketo Engage [hier te vinden](/help/marketo/release-notes/current.md){target="_blank"}.

## Release van april 2024 {#april-release}

**Releasedatum: 22 april 2024**

### Conversatiestromen zijn nu beschikbaar voor alle gebruikers {#conversational-flows-available-to-all-users}

Maak uw formulieren en bestemmingspagina&#39;s conversatiever en verkort de verkooptrechter door gekwalificeerde leads de mogelijkheid te geven een vergadering of chat met verkoop te boeken direct na een formulierverzending met Conversational Forms, nu volledig beschikbaar&#42; voor alle gebruikers van de Dynamic Chat.

_&#42;Eerder beschikbaar als proeffunctie met 100 levenscycluscontracten. Conversational Flow-services tellen nu mee voor de maandelijkse limiet van 250 gesprekken die gebruikers in het Select-pakket moeten voeren._

### Callback-functies {#callback-functions}

Met callback-functies kunt u analytische gebeurtenissen voor Dynamics Chat verzamelen in externe systemen, zoals Adobe Analytics of Googles Analytics, terwijl bezoekers gesprekken met Dynamics Chat voeren. U schakelt Dynamic Chat analytics-gebeurtenissen in door een callback met de API te registreren om naar de gebeurtenissen te luisteren. Hierdoor kunt u een meer holistische weergave van de betrokkenheid van uw Dynamic Chat hebben, aangezien deze betrekking heeft op andere belangrijke gegevens, zoals webverkeer.

### Beschikbaarheidsvoorwaarden voor actieve agent toegevoegd aan voorwaardelijke vertakking {#live-agent-availability-conditional-branching}

Naast native velden en aangepaste velden voor Marketo&#39;s Engage kunt u nu voorwaardelijke vertakking gebruiken om vertakkingen te maken op basis van de beschikbaarheid van agents. Dit is handig als u bezoekers alleen de optie wilt geven om met een actieve agent te spreken als er live agents beschikbaar zijn.

![](assets/dynamic-chat-release-1.png)

### Voorwaarde voor slimme lijst toegevoegd aan voorwaardelijke vertakking {#smart-list-condition}

Met de toevoeging van de nieuwe voorwaarde van de Lijst van het Marketo Engage Slimme in voorwaardelijk vertakking, kunt u takken tot stand brengen die op reeds bestaand publiek worden gebaseerd u reeds in Marketo Engage eerder dan het bepalen van publiek vertakkende voorwaarden in Dynamic Chat hebt gecreeerd.

![](assets/dynamic-chat-release-2.png)

### Voorwaardelijke vertakking voor conversie-stromen {#conditional-branching-for-conversational-flows}

Eerder dit jaar hebben we voorwaardelijke vertakking voor Dialogen uitgebracht en nu kunt u ook profiteren van voorwaardelijke vertakking in Conversationele Stroom! Met voorwaardelijke vertakking kunt u vertakkingen in uw flow maken op basis van verschillende voorwaarden.

### Live chatten over conversatiestromen {#live-chat-for-conversational-flows}

We hebben in 2023 live chatfunctionaliteit voor dialoogvensters uitgebracht en nu kunt u ook live chatsopdrachten toevoegen aan uw conversatiestromen. Als u de Stroom van het Gesprek met uw vormen van het Marketo Engage gebruikt, kunt u gekwalificeerde bezoekers nu toestaan om met een levende agent onmiddellijk na de vormverzending te chatten!

### Recente activiteiten van het Marketo Engage in Agent Inbox {#recent-marketo-engage-activities-in-agent-inbox}

Wij hebben recente activiteiten van het Marketo Engage aan de Recente sectie van Activiteiten van de Agent Inbox toegevoegd, zodat wanneer een bezoeker van de plaats om met een agent verzoekt te chatten, de agent snel kan zien of de bezoeker onlangs aan om het even welke volgende activiteiten van het Marketo Engage betrokken was (laatste 25 activiteiten):

* E-mail geopend
* Bezochte webpagina
* Formulier invullen
* Interessant moment

![](assets/dynamic-chat-release-3.png)

### De verbindingsstatus van de kalender in het Beheer van de Agent {#calendar-connection-status-in-agent-management}

Beheerders kunnen nu gemakkelijk zien welke agents met boekingsmachtigingen voor vergaderingen hun agenda&#39;s in Dynamic Chat hebben verbonden. Dit staat u toe om uw volledige verkoopteam te verzekeren wordt verbonden en bereid om vergaderingsverzoeken van Dynamic Chat goed te keuren.

![](assets/dynamic-chat-release-4.png)

### Minimale opzegging in configuratie van de agentenkalender {#minimum-notice-setting-in-agent-calendar-configuration}

De gebruikers rapporteerden dat de Webbezoekers vergaderingen op hun kalender met slechts 10 minuten van gevorderde kennisgeving boeken, zodat introduceerden wij een minimumbericht plaatsend in de configuratie van de agentenkalender en plaatsten de standaardlood tijd aan 24 uren.

![](assets/dynamic-chat-release-5.png)

### Gebruikersgedrag toevoegen/verwijderen bijgewerkt {#add-remove-user-behavior-updated}

Sommige gebruikers verklaarden dat zij problemen hadden met het toevoegen en verwijderen van agenten in Dynamische praatje, zodat maakten wij sommige veranderingen om deze kwesties te behandelen.

Wanneer een gebruiker aan Admin Console met levende praatje of vergadering het boeken toestemming wordt toegevoegd, zullen zij onmiddellijk in de lijst van het Beheer van de Agent verschijnen en beschikbaar zijn om aan Dialogi, de Omroepstromen toe te voegen, die regels, en teams verpletteren.

Wanneer een gebruiker met vergadering het boeken of de levende praatjetoestemmingen wordt verwijderd uit Admin Console, zullen zij onmiddellijk worden verwijderd uit Dynamic Chat, zullen niet meer voor levende praatje of vergadering het verpletteren beschikbaar zijn, en zullen niet meer tellen tegen vergunningsgrenzen.

### Verbeterde prestaties van het conversatieniveau {#improved-conversation-level-report-performance}

De rapporten Individuele dialoog en Conversational Flow Level zijn nu prestatiever en nauwkeuriger. Eerder konden dialoograpporten enkele seconden duren om te laden en waren de gegevens af en toe inconsistent met algemene prestatierapporten. De afzonderlijke dialoograpporten worden nu meteen geladen en de gegevens worden altijd uitgelijnd met algemene rapportgegevens.

![](assets/dynamic-chat-release-6.png)

### Machtigingsupdates {#permission-updates}

We schoonmaakten de machtigingsstructuur en namen in Adobe Admin Console om machtigingsbeheer intuïtiever te maken.

* De categorie &#39;Gesprek-beheer&#39; heet nu &#39;Gesprek&#39;
* De categorie &quot;vergaderingen&quot; heet nu &quot;Activiteiten&quot;
* De categorie &#39;Instellingen agent&#39; wordt nu &#39;Agenten&#39; genoemd
* De categorie &#39;Beheerinstellingen&#39; wordt nu &#39;Configuratie&#39; genoemd
* De categorie &#39;Live Chat&#39; is verwijderd en alle rechten voor live chat zijn verplaatst naar de categorie &#39;Agenten&#39;

![](assets/dynamic-chat-release-7.png)

### Steun voor hyperlinks in Agent Inbox {#support-for-hyperlinks-in-agent-inbox}

Wanneer live chatagents nu URL&#39;s delen met bezoekers in de chat, worden deze URL&#39;s aan hyperlinks gekoppeld, zodat bezoekers er gewoon op kunnen klikken om naar de pagina te navigeren, in plaats van de URL in hun browser te kopiëren en te plakken.

### Ga zeer belangrijk gedrag in dat in Agent Inbox wordt bijgewerkt {#enter-key-behavior-updated-in-agent-inbox}

Wij veranderden het terugkeer zeer belangrijke gedrag in Agent Inbox, zodat zal het drukken van de Terugkeer of Enter sleutel uw bericht verzenden en het drukken van Shift+Enter zal tot een lijnonderbreking leiden.

![](assets/dynamic-chat-release-8.png)

### Pagina met afgeronde lijnen verwijderd {#round-robin-page-removed}

Maak je geen zorgen! Ronde robin het verpletteren is nog volledig functioneel en werkt de zelfde manier het altijd heeft. Wij hebben enkel de pagina verwijderd die een vaak onnauwkeurige lijst van agenten en hun orde in de ronde robin toonde die rij verplettert.

Toen wij Dynamic Chat in 2022 vrijgaven, was er geen steun voor levende praatje, slechts vergaderingshet boeken, en de ronde robin die pagina verplettert werd ontworpen met enkel vergaderingshet boeken in mening. Met de introductie van levende praatje vorig jaar, werd de ronde robin pagina verouderd aangezien het niet nauwkeurig de complexere aard van ronde robin weerspiegelde die tussen agenten met zowel vergaderingshet boeken als levende praatjetoestemmingen verplettert. We hebben een aantal verschillende opties onderzocht om dit probleem aan te pakken, maar uiteindelijk hebben we besloten dat het volledig verwijderen ervan de beste optie was om verwarring te minimaliseren.

![](assets/dynamic-chat-release-9.png)

## Release van februari 2024 {#february-release}

**Releasedatum: 22 februari 2024**

### Pagina Conversaties {#conversations-page}

De nieuwe pagina van Gesprek voorziet u van één-stopshop om transcripties voor alle (geautomatiseerde en levende) gesprekken te bekijken die voor uw instantie, van zowel bekende als anonieme lood voorkwamen, die u van betere zichtbaarheid voorzien in hoe uw klanten met uw Dialogen, de Stromen van het Gesprek, en levende agenten in dienst nemen.

![](assets/dynamic-chat-release-10.png)

### Het datumbereik in het algemene dashboard is toegenomen van 90 dagen tot 24 maanden {#date-range-in-global-dashboard}

U hebt het gevraagd en we hebben het afgeleverd. U kunt nu de gegevens over de betrokkenheid van Dynamics Chat tot twee jaar bekijken in alle analytische dashboards.

### Voorwaardelijke vertakking in dialoogvensters {#conditional-branching-in-dialogues}

Met voorwaardelijke vertakking kunt u vertakkingen maken in uw dialoogvenster op basis van verschillende voorwaarden. U kunt nu verschillende inhoud presenteren aan verschillende personen in dezelfde dialoog op basis van de kenmerken van leads en bedrijven in Marketo Engage.

## Release januari 2024 {#january-release}

**Releasedatum: 24 januari 2024**

### Gelijktijdige instelling voor chatlimiet in agentbeheer {#Concurrent-live-chat-limit-setting}

Standaard kan elke live chatagent in uw instantie maximaal vijf live chatsessies tegelijk uitvoeren. Wij introduceerden een nieuwe het plaatsen in agentenbeheer die u toestaat om deze grens van 1 tot 10 aan te passen.

![](assets/dynamic-chat-release-11.png)
