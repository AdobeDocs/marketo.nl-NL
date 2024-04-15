---
description: Opmerkingen bij de release Dynamic Chat - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release Dynamic Chat
hide: true
hidefromtoc: true
feature: Release Information, Dynamic Chat
source-git-commit: c2c95f36c710ba7a9ac75c2160c72e44b5f81a99
workflow-type: tm+mt
source-wordcount: '1237'
ht-degree: 0%

---

# Opmerkingen bij de release: april 2024 {#release-notes-apr-24}

De versies van de Adobe Dynamic Chat werken op een ononderbroken leveringsmodel dat voor een scalable benadering van eigenschapplaatsing toestaat. Soms zijn er meerdere releases per maand, dus raadpleeg je regelmatig voor de meest actuele informatie.

De standaardpagina Opmerkingen bij de release voor Marketo Engage [hier te vinden](/help/marketo/release-notes/current.md){target="_blank"}.

## Release april {#april-release}

**Releasedatum: 16 april 2024**

### Conversiestromen zijn nu beschikbaar voor klanten in het Select-pakket {#conversational-flows-select-package}

Toen wij vorig jaar de Stromen van het Gesprek van het Gesprek uitbrachten, konden de klanten op het Uitgezochte pakket van de Dynamic Chat slechts voordeel halen uit het vermogen als proef van 100 levensduurovereenkomsten. Conversationele stromen zijn nu volledig beschikbaar aan alle klanten op het Uitgezochte pakket.

De overeenkomsten van de Stroom van het gesprek zullen op de maandelijkse grens van 250 geëngageerde gesprekken voor klanten op het Uitgezochte pakket tellen.

### Callback-functies {#callback-functions}

Met callback-functies kunt u analytische gebeurtenissen voor Dynamics Chat verzamelen in externe systemen, zoals Adobe Analytics of Googles Analytics, terwijl bezoekers gesprekken met Dynamics Chat voeren. U schakelt Dynamic Chat analytics-gebeurtenissen in door een callback met de API te registreren om de gebeurtenissen te beluisteren. Hierdoor hebt u een meer holistische weergave van de betrokkenheid van uw Dynamic Chat die betrekking heeft op andere belangrijke gegevens, zoals webverkeer.

### Beschikbaarheidsvoorwaarden voor actieve agent toegevoegd aan voorwaardelijke vertakking {#live-agent-availability-conditional-branching}

Naast native en aangepaste Marketo-velden kunt u nu voorwaardelijke vertakking gebruiken om vertakkingen te maken op basis van de beschikbaarheid van agents. Dit is handig als u bezoekers alleen de optie wilt geven om met een actieve agent te spreken als er live agents beschikbaar zijn.

SCREENSHOT

### Voorwaarde voor slimme lijst toegevoegd aan voorwaardelijke vertakking {#smart-list-condition}

Met de toevoeging van de nieuwe voorwaarde van de Lijst van het Marketo Engage Slimme in voorwaardelijk vertakking, kunt u takken tot stand brengen die op reeds bestaand publiek worden gebaseerd u reeds in Marketo eerder dan het bepalen van publiek vertakkende voorwaarden in Dynamic Chat hebt gecreeerd.

SCREENSHOT

### Voorwaardelijke vertakking voor conversie-stromen {#conditional-branching-for-conversational-flows}

Eerder dit jaar hebben we voorwaardelijke vertakking voor Dialogen uitgebracht en nu kunt u ook profiteren van voorwaardelijke vertakking in Conversationele Stroom! Met voorwaardelijke vertakking kunt u vertakkingen in uw flow maken op basis van verschillende voorwaarden.

### Live chatten over conversatiestromen {#live-chat-for-conversational-flows}

We hebben vorig jaar live chatfunctionaliteit voor dialoogvensters uitgebracht en nu kunt u ook live chatsopdrachten toevoegen aan uw conversatiestromen. Als u Conversational Flows gebruikt met uw Marketo-formulieren, kunt u bevoegde bezoekers nu toestaan te chatten met een liveagent direct na het verzenden van het formulier.

### Recente activiteiten van het Marketo Engage in Agent Inbox {#recent-marketo-engage-activities-in-agent-inbox}

Wij hebben recente activiteiten van het Marketo Engage aan de Recente sectie van Activiteiten van de Agent Inbox toegevoegd zodat wanneer een bezoeker van de plaats om met een agent verzoekt te chatten, de agent gemakkelijk kan zien of de bezoeker onlangs aan om het even welke volgende activiteiten van Marketo (laatste 25 activiteiten) betrokken was:

* E-mail geopend
* Bezochte webpagina
* Formulier invullen
* Interessant moment

SCREENSHOT

### De verbindingsstatus van de kalender in het Beheer van de Agent {#calendar-connection-status-in-agent-management}

Beheerders kunnen nu gemakkelijk zien welke agents met boekingsmachtigingen voor vergaderingen hun agenda&#39;s in Dynamic Chat hebben verbonden. Dit staat u toe om ervoor te zorgen dat uw volledige verkoopteam wordt verbonden en bereid om vergaderingsverzoeken van Dynamic Chat goed te keuren.

SCREENSHOT

### Minimale opzegging in configuratie van de agentenkalender {#minimum-notice-setting-in-agent-calendar-configuration}

De klanten meldden dat de Webbezoekers vergaderingen op hun kalender met slechts 10 minuten van gevorderde kennisgeving boeken, zodat introduceerden wij een minimumbericht plaatsend in de configuratie van de agentenkalender en plaatsen de standaardlood tijd aan 24 uren.

SCREENSHOT

### Nieuwe meldingen in de app {#new-in-app-notifications}

We hebben drie nieuwe meldingen in de app geïntroduceerd om u op de hoogte te houden van de status van uw Dynamic Chat-instantie in real-time.

* Tekst
* Tekst
* Tekst

### Gebruikersgedrag toevoegen/verwijderen bijgewerkt {#add-remove-user-behavior-updated}

Sommige klanten laten ons weten over kwesties zij met het toevoegen van en het verwijderen van agenten in Dynamische praatje hadden, zodat hebben wij sommige veranderingen aangebracht om deze kwesties te behandelen.

Wanneer een gebruiker aan Admin Console met levende praatje of vergadering het boeken toestemming wordt toegevoegd, zullen zij onmiddellijk in de lijst van het Beheer van de Agent verschijnen en beschikbaar zijn om aan Dialogen, de Omroepende Stromen, het verpletteren van regels, en teams toe te voegen.

Wanneer een gebruiker met vergadering het boeken of de levende praatjetoestemmingen wordt verwijderd uit Admin Console, zullen zij onmiddellijk worden verwijderd uit Dynamic Chat, zullen niet meer voor levende praatje of vergadering het verpletteren beschikbaar zijn, en zullen niet meer tegen vergunningsgrenzen tellen.

### Verbeterde prestaties van het conversatieniveau {#improved-conversation-level-report-performance}

De rapporten Individuele dialoog en Conversational Flow Level zijn nu prestatiever en nauwkeuriger. Eerder konden dialoograpporten enkele seconden duren om te laden en waren de gegevens soms inconsistent met de algemene prestatierapporten. De afzonderlijke dialoograpporten worden nu meteen geladen en de gegevens worden altijd uitgelijnd met algemene rapportgegevens.

SCREENSHOT

### Machtigingsupdates {#permission-updates}

We schoonmaakten de machtigingsstructuur en namen in Adobe Admin Console om machtigingsbeheer intuïtiever te maken.

* De categorie van het Beheer van de dialoog wordt nu genoemd Gesprek
* De categorie Vergaderingen heet nu Activiteiten
* De categorie Instellingen van agent wordt nu agents genoemd
* De categorie Beheerinstellingen wordt nu Configuratie genoemd
* De categorie Live Chat is verwijderd en alle live chatrechten zijn verplaatst naar de categorie Agenten

SCREENSHOT

### Ondersteuning voor hyperlinks in inbox van agent {#support-for-hyperlinks-in-agent-inbox}

Wanneer live chatagents nu URL&#39;s delen met bezoekers in de chat, worden deze URL&#39;s aan hyperlinks gekoppeld, zodat bezoekers er gewoon op kunnen klikken om naar de pagina te navigeren, in plaats van de URL in hun browser te kopiëren en plakken.

### Ga zeer belangrijk gedrag in dat in Agent Inbox wordt bijgewerkt {#enter-key-behavior-updated-in-agent-inbox}

Wij veranderden het terugkeer zeer belangrijke gedrag in Agent Inbox zodat het drukken van de Terugkeer of Enter sleutel uw bericht zal verzenden en het drukken Shift+Enter zal tot een lijnonderbreking leiden.

SCREENSHOT

### Pagina met afgeronde lijnen verwijderd {#round-robin-page-removed}

Maak je geen zorgen! Ronde robin het verpletteren is nog volledig functioneel en werkt de zelfde manier die het altijd heeft. Wij hebben enkel de pagina verwijderd die een vaak onnauwkeurige lijst van agenten en hun orde in de ronde lijn liet zien die rij verplettert.

Om één of andere context te verstrekken, toen wij Dynamic Chat in 2022 vrijgaven, was er geen steun voor levende praatje, slechts vergaderings het boeken en de ronde robin verpletterende pagina werd ontworpen slechts met vergadering het boeken in mening. Met de introductie van levende praatje vorig jaar, werd de ronde robin pagina verouderd omdat het niet nauwkeurig de complexere aard van ronde robin weerspiegelde die tussen agenten met zowel vergaderingshet boeken als levende praatjetoestemmingen verplettert. We hebben een aantal verschillende opties onderzocht om dit probleem aan te pakken, maar uiteindelijk hebben we besloten dat het volledig verwijderen ervan de beste optie was om verwarring te minimaliseren.

## Release februari {#february-release}

**Releasedatum: 22 februari 2024**

### Pagina Conversaties {#conversations-page}

De nieuwe pagina van de Gesprek voorziet u van één stopshop om transcripties voor alle (geautomatiseerde en levende) gesprekken te bekijken die voor uw instantie, van zowel bekende als anonieme lood voorkwamen, die u van betere zichtbaarheid voorzien in hoe uw klanten met uw Dialogen, de Stroom van het Gesprek en levende agenten in dienst nemen.

SCREENSHOT

Het datumbereik in het algemene dashboard is toegenomen van 90 dagen tot 24 maanden

U hebt het gevraagd en we hebben het afgeleverd. U kunt nu de gegevens over de betrokkenheid van Dynamics Chat tot twee jaar bekijken in alle analytische dashboards.

### Voorwaardelijke vertakking in dialoogvensters {#conditional-branching-in-dialogues}

Met voorwaardelijke vertakking kunt u vertakkingen maken in uw dialoogvenster op basis van verschillende voorwaarden. Nu kunt u verschillende inhoud presenteren aan verschillende personen in dezelfde dialoog op basis van de kenmerken van leads en bedrijven in Marketo.

## Release januari {#january-release}

**Releasedatum: 24 januari 2024**

### Gelijktijdige instelling voor chatlimiet in agentbeheer {#Concurrent-live-chat-limit-setting}

Standaard kan elke live chatagent in uw instantie maximaal vijf live chatsessies tegelijk uitvoeren. Wij introduceerden een nieuwe het plaatsen in agentenbeheer die u toestaat om deze grens van 1 tot 10 aan te passen.

SCREENSHOT
