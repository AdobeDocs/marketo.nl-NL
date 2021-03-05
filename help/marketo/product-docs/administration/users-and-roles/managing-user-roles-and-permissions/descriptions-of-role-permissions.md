---
unique-page-id: 6848747
description: Beschrijvingen van Rolmachtigingen - Marketo Docs - Productdocumentatie
title: Beschrijvingen van rolmachtigingen
translation-type: tm+mt
source-git-commit: 1649aae540204bb5de205e3f5b75ec7e968a7da4
workflow-type: tm+mt
source-wordcount: '1144'
ht-degree: 0%

---


# Beschrijvingen van roltoestemmingen {#descriptions-of-role-permissions}

Hieronder volgt een lijst van alle beschikbare toestemmingen die u aan uw rollen kunt toewijzen. Machtigingen zijn over het algemeen gekoppeld aan specifieke functionele gebieden binnen Marketo en kunnen u helpen bepalen tot welke gebieden en functionaliteit verschillende gebruikers toegang hebben.

Aanvullende informatie over machtigingen:

* Met de machtiging &quot;Toegang&quot; hebt u een rol toegewezen om dat deel van de toepassing weer te geven en soms te bewerken.
* Een rol heeft alleen toegang tot de submachtigingen (&quot;Maken&quot;, &quot;Verwijderen&quot;, enz.) als voor die rol &quot;Toegang&quot; is vereist voor dat deel van de toepassing. Bijvoorbeeld, als u iemand toestemming voor Edit Campaigns wilt geven, moeten zij algemene toestemming hebben om tot de Marketing Activiteiten toegang te hebben.
* Mogelijk kunt u handelingen of elementen zien die u niet mag gebruiken. Nochtans, als u probeert om tot hen toegang te hebben, zult u een berichtwaarschuwing over uw beperkte toegang zien.

## Beschikbare machtigingen {#available-permissions}

Wanneer u [een rol creeert of uitgeeft ](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md), kunt u selecteren welke van de volgende toestemmingen om voor die rol toe te staan door de aangewezen vakjes te controleren.

![](assets/createnewrole.png)

## Access Admin {#access-admin}

In de sectie Mijn account van Admin kunt u de instellingen weergeven en wijzigen.

* Access Audit Trail - geeft gebruikers toegang tot zowel Asset Audit Trail als Admin Audit Trail
* Toegang tot kanalen - Gebruikers hebben alleen toegang om de Kanaaltag te wijzigen, niet andere aangepaste tags
* Toegang tot communicatielimiet - geeft gebruikers toegang om een communicatielimiet in Admin in te schakelen
* Toegang CRM - geeft gebruikers toegang tot CRM, zoals Salesforce of de Dynamica van Microsoft, in Admin
* Toegang [Data.com](https://Data.com) - Biedt gebruikers toegang tot de Data.com-stroomactie
* Toegang tot e-mailbeheerder - Gebruikers krijgen toegang tot e-mailbeheerder om de standaardinstellingen te wijzigen, zoals het afmelden en brandmerken van domeinen
* Access Event Partners - Biedt gebruikers toegang tot LaunchPoint in Admin
* Toegangsveldbeheer - geeft gebruikers toegang tot veldbeheer in Admin
* Toegang tot bestanden uploaden - Gebruikers kunnen afbeeldingen en bestanden uploaden naar Design Studio
* Toegang tot bestemmingspagina&#39;s - geeft gebruikers toegang tot bestemmingspagina&#39;s in Admin
* Toegangslocatie - Gebruikers hebben toegang tot de locatie in Admin voor het instellen van de standaardtaal, -landinstelling, -tijdzone en -valuta
* Toegangsgeschiedenis voor aanmelding - geeft gebruikers toegang tot registratiegeschiedenis van gebruiker in audittrail
* De Montages van de Login van de toegang - verleent gebruikers toegang tot Login Montages in Admin voor Veiligheid, IP Beperkingen, en de Slimme montages van het Rapport van de Lijst
* Toegang tot aangepaste markttoegang - geeft gebruikers toegang tot aangepaste marktactiviteiten in Admin
* Toegang tot aangepast object markeren - geeft gebruikers toegang tot aangepaste objecten Marketo in Admin
* Toegang tot Munchkin - Met GI krijgen gebruikers toegang tot Munchkin in Admin, voor het instellen van trackingcode, het bijhouden van personen en het inschakelen van API-configuratie
* De Analyse van de Cyclus van de Opbrengst van de toegang - geeft gebruikers toegang tot de Analytics van de Cyclus van de Opbrengst in Admin, voor het plaatsen van Samenvatting en Attributie van de Synchronisatie
* De Rollen van de toegang - verleent gebruikers toegang om rollen te beheren en uit te geven, maar niet gebruikers
* Access Sales Insight - geeft gebruikers toegang tot het beheer van Sales Insight in Admin, voor het instellen van Status, API-configuratie, Person Scores en andere instellingen
* Toegang Single Sign-On - Gebruikers krijgen toegang om Single Sign-On te beheren in Admin, om SAML in te schakelen en met SAML-instellingen te werken en pagina-URL&#39;s om te leiden
* Toegang tot slimme campagne - geeft gebruikers toegang tot slimme campagne in Admin, voor het beperken van limieten voor gekwalificeerde personen
* Toegang tot SOAP API: geeft gebruikers toegang tot het beheer van SOAP API&#39;s in webservices in Admin
* Toegangstcodes - Hiermee geeft u gebruikers toegang tot alle aangepaste tags behalve de Kanaaltag
* Toegang tot schatkist - geeft gebruikers toegang tot de experimentele functies in de Treasure Chest in Admin
* Gebruikers benaderen - Gebruikers hebben toegang tot het bewerken en beheren van gebruikers (maar niet van rollen) in Admin
* Toegang tot webhaken - Geeft gebruikers in Admin toegang tot webhooks voor het instellen van details en responstoewijzingen
* Toegang tot werkruimten en partities - biedt gebruikers toegang tot het maken, bewerken en verwijderen van werkruimten en partities in Admin

## Toegang-API {#access-api}

Biedt gebruikers alleen de **API** **Role** toegang tot de hieronder vermelde afzonderlijke API&#39;s.

* Middelen goedkeuren
* Campagne uitvoeren
* Alleen-lezen activiteit
* Metagegevens activiteit alleen-lezen
* Alleen-lezen elementen
* Alleen-lezen campagne
* Bedrijf met alleen-lezen
* Alleen-lezen aangepast object
* Alleen-lezen persoon
* Benoemd account (alleen-lezen)
* Opportunity, alleen-lezen
* Alleen-lezen verkoper
* Leesschrijfactiviteit
* Metagegevens leesschrijfactiviteit
* Read-Write Middelen
* Campagne voor schrijven
* Read-Write Bedrijf
* Aangepast object lezen/schrijven
* Leesschrijfpersoon
* Benoemd account voor lezen/schrijven
* Opportunity voor lezen/schrijven
* Verkooppersoon voor lezen/schrijven

## Access Analytics {#access-analytics}

Biedt gebruikers toegang tot de tabbladen Analytics, Email Insights, Reports en de drie onderstaande items, tenzij deze zijn uitgeschakeld.

* De Ontdekkingsreiziger van de Inkomsten van de toegang - Unchecking verwijdert de toegang van de gebruiker tot Ontdekkingsreiziger van de Inkomsten
* Rapport verwijderen - Als de controle ongedaan wordt gemaakt, kan de gebruiker rapporten verwijderen
* Analytische gegevens exporteren - Als de controle ongedaan wordt gemaakt, kan de gebruiker geen analysegegevens exporteren

## Presentations {#access-calendar-presentations} openen

Biedt gebruikers toegang tot kalenderpresentaties - maakt het mogelijk de Presentations-knop onderaan weer te geven.

* Kalender Presentations bewerken - Hiermee kunnen gebruikers presentaties bewerken in de agenda

## Open Design Studio {#access-design-studio}

Biedt gebruikers toegang tot het lusje van de Studio van het Ontwerp en mening van de boom, maar niet tot details.

* Toegang tot e-mail
   * E-mail bewerken - Hiermee geeft u gebruikers toestemming om e-mailberichten te bewerken, te maken en te klonen
      * E-mail operationeel maken - Hiermee geeft u gebruikers toestemming om een e-mail operationeel te maken. Zie: [Een e-mail operationeel maken](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)

      * E-mail goedkeuren - Hiermee kunnen gebruikers e-mailberichten goedkeuren.
      * E-mail verwijderen - Hiermee kunnen gebruikers e-mailberichten verwijderen.
      * Stel het brandingdomein in. Hiermee kunnen gebruikers met brandingdomeinen werken. Zie: [Voeg een extra brandingdomein toe](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/add-an-additional-branding-domain.md)

* Toegang tot e-mailsjabloon

   * E-mailsjabloon goedkeuren
   * E-mailsjabloon verwijderen
   * E-mailsjabloon bewerken - E-mailsjablonen bewerken, maken en klonen

* Toegangsformulier

   * Formulier verwijderen
   * Formulier bewerken - Formulieren bewerken, maken en klonen

* Afbeelding openen

   * Afbeelding verwijderen
   * Afbeelding uploaden

* Openingspagina openen

   * Openingspagina goedkeuren
   * Openingspagina verwijderen
   * Openingspagina bewerken - bestemmingspagina&#39;s bewerken, maken en klonen

* Openingspagina-sjabloon openen

   * Landingspaginamplate goedkeuren
   * Landingspagina-sjabloon verwijderen
   * Landingspagina-sjabloon bewerken: sjablonen voor bestemmingspagina&#39;s bewerken, maken en klonen

* Toegangsfragment

   * Fragment goedkeuren
   * Fragment verwijderen
   * Fragment bewerken

* Toegang tot sociale app

   * Sociale app goedkeuren
   * Sociale app verwijderen
   * Sociale app bewerken

## Database {#access-database} openen

Bekijk de database en bekijk en bewerk slimme/statische lijsten.

* Segmentering toegang

   * Segmentatie goedkeuren
   * Segmentatie verwijderen
   * Segmentering bewerken

* Geavanceerde lijstimport
* Persoon verwijderen
* Lijst verwijderen
* Persoon bewerken - Hiermee voorkomt u handmatig bewerken en doorlopen van stappen in één stroom. u kunt mensen nog steeds bewerken door campagnes tegen hen uit te voeren
* Persoon exporteren - Werkbladen exporteren vanuit uw databaselijsten
* Aangepast object importeren
* Lijst importeren
* Personen samenvoegen
* Voer de Enige Acties van de Stroom in - laat gebruikers toe om **de waarde van Gegevens van de Verandering** debietstap op mensen van het gegevensbestand in werking te stellen

* Opportuniteitsgegevens weergeven - Verbergt de opportuniteitsinformatie op de pagina met persoonlijke details

## Toegang tot marketingactiviteiten {#access-marketing-activities}

Bekijk het tabblad Marketingactiviteiten, campagnes en campagnemappen.

* SMS-bericht benaderen

   * SMS-bericht goedkeuren
   * SMS-bericht verwijderen
   * SMS-bericht bewerken

* Pushmelding openen

   * Pushmelding goedkeuren
   * Pushmelding verwijderen
   * Pushmelding bewerken

* Toegangsonderscheidingen
* Triggercampagne activeren
* E-mailprogramma goedkeuren
* Kloonmarketingmiddel
* Marketing-element verwijderen
* Campagnebeperkingen bewerken
* Marketing-element bewerken
* Importprogramma
* Lijstimport
* Batchcampagne plannen

Toegang tot SEO

* SEO beheren
* StandaardSEO

## Targeting and Personalization {#targeting-and-personalization}

* Webpersonalisatie beheren
* CRE-campagneeditor
* CRE Campaign Launcher
* Webcampagne-editor
* Web Campaign Launcher

Werkruimtebeheer

* Beheerderstoegang voor een specifieke werkruimte (alleen als Workspaces is ingeschakeld)
* Elementen verplaatsen tussen werkruimten (alleen als Werkruimten is ingeschakeld)
