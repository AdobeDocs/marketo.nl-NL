---
description: Een interactief webinar promoten - Marketo Docs - Productdocumentatie
title: Een interactief webinar promoten
feature: Interactive Webinars
exl-id: d26f91ce-3a95-4247-9a52-085260bb15e8
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '785'
ht-degree: 0%

---

# Een interactief webinar promoten {#promoting-an-interactive-webinar}

Het bevorderen van een Interactief Webinar is gelijkaardig aan het bevorderen van een partner webinar via Launchpoint. Wanneer u een interactief webinar-gebeurtenisprogramma maakt, kunt u leden toevoegen door een campagne uit te voeren of door leden naar het programma te importeren. Als u de leden wilt controleren die aan het Interactive Webinars Event Program zijn toegevoegd, klikt u op het tabblad **[!UICONTROL Members]** .

![](assets/promoting-an-interactive-webinar-1.png)

## Overzicht {#overview}

Nadat de leden zijn toegevoegd of geïmporteerd, kunt u in het Interactive Webinar-gebeurtenisprogramma een e-mailcampagne maken om een uitnodiging naar alle programmaleden te verzenden en hun status te wijzigen in &quot;uitgenodigd&quot; nadat de e-mail is bezorgd.

>[!NOTE]
>
>Als u een cohost of presentator als publieksleden wilt toevoegen aan het interactieve webinar-gebeurtenisprogramma, moet u een andere e-mailid voor deze personen gebruiken. Als dit niet het geval is, wordt er een fout met de tekst &#39;Deze e-mail is al geregistreerd&#39; weergegeven.

Het e-mailbericht kan specifieke details van het programma bevatten, evenals een URL voor de bestemmingspagina die de ontvanger omleidt naar een specifieke pagina waar meer informatie over het webinar (bijvoorbeeld inhoud, informatie over de presentator, enz.) kan worden toegevoegd. Deze landingspagina kan worden gemaakt als een lokaal element in het Interactive Webinars Event Program.

U kunt registratie voor dit webinar vragen door een formulier op de Openingspagina in te schakelen en de klik van het formulier te koppelen aan ingeschakelde registratie in het Interactive Webinar Event Program. Vervolgens kan een campagne worden gemaakt waarin formulierverzendingen als trigger worden gebruikt en de status van het programma wordt gewijzigd van &quot;uitgenodigd&quot; in &quot;geregistreerd&quot;.

>[!NOTE]
>
>De overgang van &quot;uitgenodigd&quot; naar &quot;geregistreerd&quot; vindt niet automatisch plaats in interactieve webinars, omdat er meerdere triggers kunnen zijn die de overgang maken.

Zodra een lid in de &quot;geregistreerde&quot;programmastatus in een Interactief Programma van de Gebeurtenis van Webinar is geweest, wordt een registratie automatisch gemaakt aan webinar die in Adobe Connect wordt gecreeerd. Registratiegegevens zoals Voornaam, Achternaam en E-mailadres worden vervolgens overgebracht naar Adobe Connect. Dit betekent dat zodra de gebruiker zich bij webinar als deelnemer aansluit, de informatie aan de presentator of de gastheer tijdens webinar beschikbaar zal zijn.

Binnen een paar minuten na registratie wordt de webinar-URL voor het lid ingevuld op het tabblad Leden. Als u de kolom voor Webinar URL niet kunt vinden, zorg ervoor dat die kolom aan uw mening is toegevoegd. Dit is een gepersonaliseerde URL voor elk geregistreerd lid om het webinar in geplande tijd zonder enige authentificatie te kunnen ingaan. Tokens die intern worden uitgewisseld, zorgen voor de authenticatie van de leden.

U kunt het `{{member.webinar url}}` [ teken ](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"} gebruiken om Webinar URL aan individuele leden in een e-mailcampagne te omvatten om mee te delen dat zij in de gebeurtenis zijn geregistreerd en het aansluiten van URL te gebruiken om webinar bij de geplande tijd in te gaan. De tokens van de kalender kunnen in de zelfde e-mailcampagne worden gebruikt om ervoor te zorgen dat het webinar programma aan de kalenders van de leden kan worden toegevoegd.

De verbindingen zijn beschikbaar op de rechterkant van het lusje van het Overzicht in uw Programma van de Gebeurtenis om een Openende Pagina evenals een e-mailcampagne tot stand te brengen. De rest bevorderingen met betrekking tot een gebeurtenis blijven het zelfde als partner webinars gebruikend de integratie van Launchpoint.

![](assets/promoting-an-interactive-webinar-2.png)

Met interactieve webinars kunt u registratie aanvragen voor, tijdens of na een webinar. In alle gevallen, zou u eenvoudig Webinar URL met het lood moeten delen. Als u op de koppeling klikt voordat het webinar begint, worden de koppelingen naar een pre-webinar landingpagina verzonden. Als u erop klikt tijdens het webinar, gaat u naar het webinar dat wordt uitgevoerd. Als u erop klikt na het webinar, wordt het webinar opgenomen.

## Interactieve webinars Tokens {#interactive-webinars-tokens}

Gebruik tokens om interactieve webinars in e-mails te promoten zonder handmatig webinar-details toe te voegen. Dit verbetert de algehele efficiëntie, aangezien eventuele wijzigingen in de webinar-metagegevens (zoals de titel van het webinar, de begindatum, enzovoort) automatisch in uw elementen worden doorgevoerd.

![](assets/promoting-an-interactive-webinar-3.png)

>[!NOTE]
>
>Interactieve Webinar-tokens worden momenteel niet ondersteund in Landing Pages.

**Lijst van tokens**

<table><thead>
  <tr>
    <th>Token</th>
    <th>Definitie</th>
  </tr></thead>
<tbody>
  <tr>
    <td>program.webinarCapacity</td>
    <td>Het maximumaantal deelnemers dat kan deelnemen aan het interactieve webinar.</td>
  </tr>
  <tr>
    <td>program.webinarDuration</td>
    <td>De duur waarvoor het interactieve webinar gepland is.</td>
  </tr>
  <tr>
    <td>program.webinarEndDate</td>
    <td>De einddatum voor het geplande interactieve webinar.</td>
  </tr>
  <tr>
    <td>program.webinarEndTime</td>
    <td>De geplande eindtijd van het interactieve webinar.</td>
  </tr>
  <tr>
    <td>program.webinarGenericURL</td>
    <td>De generieke opname-URL die kan worden gedeeld met het publiek na het webinar. Deze URL is niet bedoeld om live te worden gevolgd bij het webinar en houdt de activiteit van het publiek niet bij.</td>
  </tr>
  <tr>
    <td>program.webinarLanguage</td>
    <td>De taal waarin het webinar wordt gehouden.</td>
  </tr>
  <tr>
    <td>program.webinarStartDate</td>
    <td>De startdatum van het geplande interactieve webinar.</td>
  </tr>
  <tr>
    <td>program.webinarStartTime</td>
    <td>De geplande begintijd van het interactieve webinar.</td>
  </tr>
  <tr>
    <td>program.webinarTimezone</td>
    <td>De tijdzone waarin Interactive Webinar is gepland.</td>
  </tr>
  <tr>
    <td>program.webinarTitle</td>
    <td>De titel van het interactieve webinar dat zichtbaar is voor het publiek op de Webinar Entry Screens.</td>
  </tr>
</tbody></table>
