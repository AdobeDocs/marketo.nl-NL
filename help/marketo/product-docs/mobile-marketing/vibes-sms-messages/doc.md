---
description: Doc - Marketo Docs - Productdocumentatie
title: Doc
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: cd09ad43c08855af63131aa385c4fd406c963926
workflow-type: tm+mt
source-wordcount: '836'
ht-degree: 0%

---

# Doc {#doc}

Tekst

## Verklarende woordenlijst van SMS van Vibes {#vibes-sms-glossary}

<table>
<thead>
  <tr>
    <th>Term</th>
    <th>Definitie</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Acquisitiecampagne</td>
    <td>Een campagne om nieuwe abonnees op uw abonnementlijsten te verwerven. U kunt een abonnee toevoegen aan een acquisitiecampagne via een Marketo-webformulier of door een trefwoord te sms'en.</td>
  </tr>
  <tr>
    <td>Campagnebeheer</td>
    <td>Campagne Manager vindt u op het platform Vibes in het gedeelte waarin u een abonnementenlijst en een acceptatiecampagne kunt instellen. Gebruikers met een volledige licentie voor het Vibes-platform hebben toegang tot extra typen campagnes.</td>
  </tr>
  <tr>
    <td>Bedrijfs Sleutel</td>
    <td>company_key is een unieke alfanumerieke identificatie voor uw platformrekening. Als u veelvoudige bedrijfrekeningen in het platform van Vibes (zoals kindrekeningen) hebt, kunt u veelvoudige company_keys hebben. Elke instantie van Marketo Engage kan aan slechts één bedrijf worden in kaart gebracht Vibes_key.</td>
  </tr>
  <tr>
    <td>TCLP (oproep tot actie)</td>
    <td>Digitale of fysieke handtekening of verbaal script voor het verwerven van abonnees in een terugkerend tekstberichtenprogramma of abonnementenlijst. Kan online worden geplaatst, op sociale media, in e-mails, in gedrukte vorm, enz.</td>
  </tr>
  <tr>
    <td>Aangepast kort domein</td>
    <td>Als u de koppelingsstener van Vibes gebruikt, zal verkorte URL, door gebrek, onder de korte URL van Vibes verschijnen: https://vbs.cm/xxxxxx. Een aangepast kort domein is een domein dat uniek is voor uw merk. <a href="https://developer-platform.vibes.com/docs/creating-a-custom-short-domain">Meer informatie over aangepaste korte domeinen</a>.<p>
    Dit is alleen van toepassing op berichten die vanaf het platform van Vibes worden verzonden, met name de berichten van de aanschafcampagne en de korte code standaardberichten.<p>
    De Marketo URL shortener wordt aanbevolen als u klikgegevens wilt in uw Marketo-programma.</td>
  </tr>
  <tr>
    <td>Standaardberichten</td>
    <td>Verplichte berichten voor de korte code om op HELP, STOP, en niet erkende berichtverzoeken te antwoorden.</td>
  </tr>
  <tr>
    <td>Verbinding verbreken</td>
    <td>Verbinding verbreken is een vorm van opt-out omdat het mobiele nummer uit een dragernetwerk wordt verwijderd. Motivering voor het verbreken van de verbinding zijn onder meer: een account is volledig gesloten, een vooruitbetaalde rekening heeft onvoldoende financiële middelen of het nummer is om andere onbekende redenen uit het transportnetwerk verwijderd. Mobiele nummers die niet zijn aangesloten en niet zijn verzonden naar een andere mobiele provider, worden niet meer geabonneerd op alle abonnementlijsten in het Vibes-platform.</td>
  </tr>
  <tr>
    <td>Dubbele plug-in</td>
    <td>Een methode van verwerving die een potentiële abonnee vereist om hun toestemming te bevestigen om aan een abonnementlijst met een antwoordbevel, zoals "Y"of hun postcode worden toegevoegd. Het gebruiken van een dubbel opt-in herinnering kan u helpen aan staat en federale richtlijnen van het tekstoverseinen voldoen.</td>
  </tr>
  <tr>
    <td>Gebeurtenis</td>
    <td>Een gebeurtenis is een gedefinieerde gebeurtenis die naar het Vibes-platform kan worden verzonden en kan worden gebruikt om API-activering te activeren, inclusief het verzenden van berichten. Elke gebeurtenis bevat specifieke gegevens voor de gebeurtenis, waaronder een event_type, dat wordt gebruikt om te bepalen met welke API getriggerde berichtcampagne het overeenkomt. De gebeurtenis-API kan via Webhaak in Marketo Engage worden geactiveerd. Meer weten met onze <a href="https://developer-platform.vibes.com/reference/event-api">Referentie voor API van gebeurtenis</a>.</td>
  </tr>
  <tr>
    <td>Trefwoord</td>
    <td>Een kort woord of alfanumerieke tekenreeks die door de consument naar de korte code wordt verzonden om een mobiele ervaring te starten.</td>
  </tr>
  <tr>
    <td>Lange code (10DLC)</td>
    <td>Een afzender-id waarvan tweewegsberichten tussen het merk en de consument worden verzonden. US lange codes zijn 10 numerieke cijfers.</td>
  </tr>
  <tr>
    <td>MDN</td>
    <td>Mobiel mapnummer of het telefoonnummer van een persoon. MDN en mobiele-telefoonnummers zijn geen unieke id's in Marketo.</td>
  </tr>
  <tr>
    <td>Mobiele database</td>
    <td>Het mobiele gegevensbestand is het gegevensbestand waar Vibes abonneegegevens opslaat. Elke abonnee heeft een unieke "persoonrecord", waarbij het mobiele nummer en eventuele aangepaste velden worden ingevuld.</td>
  </tr>
  <tr>
    <td>Deelnemer</td>
    <td>Een persoon die een of meer mobiele interacties (zoals het verzenden van een tekstbericht) heeft met uw mobiele programma, maar zich niet op een abonnementenlijst heeft geabonneerd.</td>
  </tr>
  <tr>
    <td>Persoonsrecord</td>
    <td>Een persoonrecord is een verzameling gegevens voor een specifiek mobiel telefoonnummer. Elke persoonrecord krijgt ook een unieke person_key toegewezen ter identificatie. Marketo-id's zijn gekoppeld aan Vibes met behulp van het veld external_person_id. Meer informatie over persoonrecords in <a href="https://developer-platform.vibes.com/reference/person-api">Vibes Person API-documentatie</a>.</td>
  </tr>
  <tr>
    <td>Korte code</td>
    <td>Een afzender-id waarvan tweewegsberichten tussen het merk en de consument worden verzonden. US short codes zijn 5-6 numerieke cijfers. Canadese korte codes zijn 4-6 numerieke cijfers. De Marketo LaunchPoint-integratie in Vibes ondersteunt één korte code per instantie.</td>
  </tr>
  <tr>
    <td>SMS</td>
    <td>Short Message Service. Dit is een bericht dat alleen tekst bevat.</td>
  </tr>
  <tr>
    <td>Abonnementenlijsten</td>
    <td>Een lijst met mobiele nummers (en de bijbehorende persoonlijke gegevens) die toestemming hebben gegeven om terugkerende berichten van uw programma te ontvangen.</td>
  </tr>
  <tr>
    <td>Abonnement</td>
    <td>Een mobiel nummer dat is geabonneerd op een abonnementenlijst of -lijsten.</td>
  </tr>
  <tr>
    <td>Vibes Platform</td>
    <td>De website u login om uw campagnes te beheren. Ga naar <a href="https://nexus.us.vibes.com/">https://nexus.us.vibes.com/</a> toegang tot het Vibes-platform.</td>
  </tr>
</tbody>
</table>

## SMS-melding {#sms-reporting}

Tekst

Klik op SMS-bericht lokaal element > Dashboard weergeven; rapporten op berichtniveau

SCREENSHOT

SMS-progressie - geeft het totale aantal verzonden en het totale aantal geleverde berichten weer. De bedragen zijn bij het recht en als u over de bar beweegt, wordt het percentage getoond.

SCREENSHOT

In de grafiek Samenvatting wordt de berekende stuiteringsfrequentie weergegeven als een percentage. Houd de muisaanwijzer boven de scheidingsbalk om de snelheid van de levering per hoeveelheid en percentage weer te geven. Houd de muisaanwijzer boven het oranje gedeelte Bounce Rate van de balk om de bedragen en percentages voor de waarde Zachte Bounce en Hard Bounce te bekijken.

SCREENSHOT

Met de grafiek Activiteit over tijd kunt u Totaal verzonden of Totaal geleverd selecteren. Selecteer een geschikt bereik in de datumbereikkiezer.

SCREENSHOT
