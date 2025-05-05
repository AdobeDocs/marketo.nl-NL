---
unique-page-id: 4719093
description: Websegmenten - Marketo Docs - Productdocumentatie
title: Websegmenten
exl-id: ec62c1ae-579a-4753-9b2d-18c7c2fa1ff5
feature: Web Personalization
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '2051'
ht-degree: 0%

---

# Websegmenten {#web-segments}

## Segment weergeven {#view-segment}

![](assets/image2014-11-11-20-3a24-3a5.png)

Op het tabblad Segmenten worden alle aangepaste gedefinieerde segmenten weergegeven die u instelt op basis van verschillende kenmerken.  **Een segment is een verzameling bezoekers die voldoen aan de opgegeven criteria die zijn gedefinieerd op de pagina &#39;Een segment instellen&#39;.**  Een segment kan bezoekers zijn uit een bepaalde branche, locatie of op basis van de onsite activiteit van de bezoeker.

In Personalisatie van het Web, kan een bezoeker meer dan één segment aanpassen. Als er bijvoorbeeld een segment is voor Amerikaanse bezoekers en een segment voor financiële ondernemingen, zou een webbezoeker van de Bank of America evenaren **beide** het segment voor bezoekers uit de VS en het segment voor financieringsmaatschappijen.

**GRAFIEK:**  Op de pagina Segmenten wordt een staafdiagram weergegeven met de geselecteerde segmenten op basis van het aantal bezoekers van het segment (y-as) en de segmentnaam (x-as).

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">Naam</th> 
   <th colspan="1" rowspan="1">Beschrijving</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1"><strong>Naam</strong></td> 
   <td colspan="1" rowspan="1">De titel van het segment</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong>Overeenkomsten</strong></p></td> 
   <td colspan="1" rowspan="1">Het aantal bezoekers dat voldoet aan de aangepaste, gedefinieerde criteria van het segment</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><strong>Campagne instellen</strong></td> 
   <td colspan="1" rowspan="1">Hiermee kunt u een campagne-CTA instellen die is gekoppeld aan de geselecteerde zoekterm</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong>Bezoekers</strong></td> 
   <td colspan="1">Een voorvertoning van de tabel met bezoekers die is gekoppeld aan de geselecteerde zoekterm</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><strong>Clickstream</strong></td> 
   <td colspan="1" rowspan="1">Hiermee geeft u een tabel weer met de activiteit en het URL-pad van de bezoeker op de site en de duur van het bezoek aan elke pagina </td> 
  </tr> 
 </tbody> 
</table>

Zie [segmentlabels maken en weergeven](/help/marketo/product-docs/web-personalization/using-web-segments/label-your-segment.md)

**Segmenten - Rechterdeelvenster**

![](assets/image2014-11-12-10-3a46-3a32.png)

Als u een segment in de tabel selecteert, worden aanvullende details over het segment in het rechterdeelvenster weergegeven.

Deze details omvatten:

* Naam van segment
* Aanmaakdatum segment
* De bijbehorende campagnes die de campagnes tonen die met het segment werken. Als u op het aantal reacties klikt, gaat u naar de pagina met campagnes waarop de campagne-CTA (Call to Action) voor het segment wordt weergegeven
* Het aantal overeenkomsten (het aantal bezoekers dat aan de segmentcriteria voldeed) voor het segment en het aantal afzonderlijke (unieke) bezoekers dat aan het segment voldeed. Wanneer u op de koppeling voor unieke bezoekers klikt, gaat u naar de pagina van de bezoeker waarop de resultaten van het segment worden weergegeven
* De eigenaar/gebruiker creator van het segment
* De domeinplaatsen verbonden aan het segment
* Een korte samenvatting van de geselecteerde criteria van het segment

## Een segment in- of uitschakelen {#enable-or-disable-a-segment}

![](assets/image2014-11-12-10-3a48-3a9.png)

Als u een segment wilt in- of uitschakelen, schakelt u het selectievakje van dat segment in de tabel in en schakelt u in het vervolgkeuzemenu Handeling kiezen onder aan de tabel de actie &quot;Inschakelen&quot; of &quot;Uitschakelen&quot; in. Wanneer een segment is uitgeschakeld, wordt het woord &quot;uitschakelen&quot; weergegeven onder de kolom Status.

## Segmenten maken {#create-segments}

Het segment dat u maakt, voldoet aan de specifieke criteria die u in het dialoogvenster **Segment instellen** pagina. U kunt uw segmenten ook aanpassen op basis van een combinatie van criteria, waarbij u zich richt op een specifiek publiek in uw campagne.

Een nieuw segment maken

Van de **Segmenten** pagina, klikt u **Nieuw maken** onder de grafiek. Het volgende scherm verschijnt.

![](assets/four.png)

Definieer algemene parameters voor uw segment:

* **Naam:**  Geef uw segment een naam.
* **Omschrijving:**  Geef een gedetailleerdere uitleg van de segmentcriteria.
* **Domeinen**  Selecteer het domein of de domeinen u in het segment wilt omvatten.
* **Segmentregellogica:**  Selecteer een EN/OR-logica om elk segmenteringskenmerk te maken
* **Timing:** Bepaal het niveau van bezoekersbetrokkenheid u in uw campagne wilt

   * **Bij binnenkomst**: Vraag van bezoeker komt op de website
   * **Na de eerste tot de negende klik**: Neem de bezoeker in dienst na een bepaalde hoeveelheid klikken op de website

>[!TIP]
>
>**Logica voor segmentregels**
>
>Er zijn drie filteropties:
>
>1. Alle filters gebruiken (1 en 2 en 3...)
>1. Alle filters gebruiken (1, 2 of 3...)
>1. Geavanceerde filters (met en/of expressies)
>
>    Met geavanceerde filters kunt u de segmentvoorwaarde bepalen. Voer de filternummers in, gescheiden door &quot;en&quot; en &quot;of&quot;.
>
>    * 1, 2 en 3
>    * 1 of 2 of 3
>
>    Het mengen van &quot;en&quot; en &quot;of&quot; vereist haakjes om logische intentie te verduidelijken. Bijvoorbeeld &quot;1 of 2 en 3&quot; moet als een van de volgende vermeldingen worden geschreven:
>
>    * 1 en 2 of 3
>    * (1 en 2) of 3
>
>    Geneste haakjes worden geaccepteerd voor complexere logica, bijvoorbeeld
>
>    * (1 en 2) of (3 en 4)
>    * 1 en 2 of (3 en 4)
>
>    Controleer uw logica na het invoegen, verwijderen of opnieuw rangschikken.

De attributen van het Segment van de belemmering en van het daling van de rechterzijkolom in de segmentredacteur op de linkerkant:

![](assets/five.png)

### Firmographics {#firmographics}

**Locatie**

Slepen en slepen **Locatie** in de segmentredacteur.

* Selecteer een van de volgende parameters:

   * **Inclusief** - Selecteer of u een locatie wilt opnemen in de campagne of deze wilt uitsluiten.
   * **Land selecteren om toe te voegen** - Selecteer in het keuzemenu het land dat u in het segment wilt opnemen. De landnaam wordt rechts weergegeven. U kunt meerdere landen kiezen.

Zodra het land wordt toegevoegd, kunt u de staat, de plaats en de postcode van het segment ook specificeren.

* **Selecteer een staat of provincie die u wilt toevoegen** - Selecteer in het keuzemenu de Amerikaanse staat of Canadese provincie die u wilt opnemen. U kunt meerdere selecties maken.
* **Postcode** - Voer de postcode in die u in het segment wilt opnemen.
* **Plaatsen** - Geef de stad of steden op die u wilt opnemen. Gebruik een puntkomma tussen steden.

>[!TIP]
>
>**Welke segmentvoorwaarden kies ik? &#39;AND&#39; of &#39;OR&#39;?** OR werkt als een extra optie binnen elk gebied. De vooruitzichten behoeven slechts aan één criterium van de veelvoudige criteria te voldoen die binnen elk gebied worden geselecteerd om voor het segment in aanmerking te komen. (De vooruitzichten kunnen bijvoorbeeld van de V.S. zijn *of* van de defensie-industrie). EN functioneert als een aanvullende verplichte parameter waaraan voor dit segment moet worden voldaan. (De vooruitzichten moeten bijvoorbeeld zowel vanuit de VS als vanuit de defensie-industrie liggen). Binnen elk segmentatieprofiel kan elk afzonderlijk veld functioneren als zowel &quot;AND&quot; als &quot;OR&quot;, afhankelijk van de geselecteerde segmentvoorwaarde.

**Industrie** Onder de **Profielsegmentatie** sectie, schakel het selectievakje naast **Industrie**.

* Selecteer een van de volgende parameters:

   * **Inclusief** - Selecteer of u een bedrijfstak wilt opnemen in het segment of uitsluiten.
   * **Toe te voegen industrieën selecteren** - Selecteer de sector die u in het segment wilt opnemen. De industrie verschijnt onder de drop-down doos. U kunt kiezen uit meerdere industrieën.

**Organisatiegroep**

Onder de **Profielsegmentatie** sectie, schakel het selectievakje naast **Organisatie-groep.**

* Selecteer in het keuzemenu een van de volgende opties:

   * Fortune 500 - Omvat alleen Fortune 500-ondernemingen in dit segment
   * Fortune 1000 - Omvat alleen Fortune 1000-ondernemingen in dit segment
   * Global 2000 - Omvat de Global 2000-bedrijven in dit segment
   * Ondernemingen - Omvat organisaties met meer dan 1.000 werknemers en inkomsten van meer dan 250 miljoen dollar
   * SMB - omvat slechts kleine en middelgrote ondernemingen in dit segment

**-Benoemde accounts-**

**Organisaties**

* **Is afkomstig van deze ondernemingen (specifieke namen)**

   * Selecteer een bedrijf dat u als doel wilt instellen in de vervolgkeuzelijst &#39;Bedrijf selecteren om toe te voegen&#39;.
   * U kunt de exacte organisatienaam typen waarop u zich wilt richten. *Het is _altijd_ aanbevolen om lijsten met benoemde accounts te gebruiken in plaats van de namen handmatig in te voeren voor betere overeenkomsten (zie hieronder).

**Lijst met benoemde accounts**

Selecteren in een [Lijst met benoemde accounts](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-new-account-list.md) om de belangrijkste gerichte rekeningen te segmenteren.

![](assets/image2015-5-27-17-3a14-3a8.png)

>[!NOTE]
>
>Het aantal tussen de haakjes naast de Benoemde naam van de Lijst van de Rekening wordt gebruikt als indexverwijzing voor de lijst voor de Personalisatie van het Web [API voor lezen](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/web-personalization).

**ISP uitsluiten**

Sluit de Dienstverleners van Internet (ISPs) van het segment uit.

### Bekende personen {#known-people}

**Database**

De Personalisatie van het Web integreert met uw Gegevensbestand van Marketo, toestaand u om campagnes door bekende persoonattributen en gegevens te segmenteren en te personaliseren.

Selecteer Gegevensbestand, en selecteer een gebied van persoongegevens van drop-down. Selecteer de **+** om velden uit de vervolgkeuzelijst toe te voegen.

![](assets/seven.png)

U kunt gegevensvelden voor personen toevoegen of verwijderen uit Account Settings > Database

>[!TIP]
>
>Uw segmentcriteria maken op basis van alle gegevensvelden van personen uit Marketo, zoals functie, score, rol enz.
>
>Eg. &quot;Functie is gelijk aan GMO&quot; en &quot;Score is kleiner dan of gelijk aan 50&quot;

**Marketo-e-mailcampagne** U kunt campagnes segmenteren en personaliseren door de e-mailverwijzing van een bezoeker die op een Marketo-e-mail klikt en op de site arriveert. Segment door de Naam van het Programma van Marketo of de Naam van de Campagne en vervolg het gesprek van e-mail aan Web. Selecteer + om gebieden van drop-down toe te voegen.

![](assets/image2015-5-27-17-3a20-3a34.png)

**Status**

Bepaal uw segment volgens de status van een vooruitzicht: gekend of anoniem.

* Bekend - selecteer deze optie van de drop-down doos voor bekende bezoekers. Een bezoeker is bekend wanneer hij of zij een formulier op uw website indient en op de pagina Personen voor webpersonalisatie wordt weergegeven.
* Anoniem - Selecteer deze optie in het keuzemenu voor anonieme bezoekers.

![](assets/image2015-5-27-17-3a23-3a2.png)

### Gedrag {#behavioral}

**Bezoeken -** Definieer het segment op basis van het gedrag van de bezoeker of identificeer het segment.

* Aantal bezoeken - Selecteer deze optie in het keuzemenu om het aantal bezoeken voor vooruitzichten op de website te specificeren.

   * Selecteer Gelijk aan, Gelijk aan of Groter dan, of Gelijk aan of minder dan van de drop-down doos.

* Specifieke bezoeken - Selecteer deze optie in het keuzemenu om een specifieke bezoeker op te geven.

   * Voer in het tekstvak rechts het bezoekersnummer in dat u wilt bijhouden. Het unieke identificatienummer van de bezoeker van de Personalisatie van het Web kan worden gevonden wanneer het klikken op een bezoeker (op de bezoekerspagina) en de Vastgestelde Campagne op het juiste zijpaneel. De bezoeker-id bevindt zich in het gedeelte Geavanceerde instellingen. De bezoekersidentiteitskaart kan ook in URL (b.v. VISITOR=JZJIFJNUI60PZ8Y97BHTY9BL8PKWS) worden gevonden.

**Zoekvoorwaarden** - Definieer een segment volgens de zoektermen van een perspectief.

* De bezoeker heeft gezocht naar - Van de drop-down lijst, selecteer de termijnen u van uw bezoekersonderzoek wilt volgen, of uw eigen onderzoekstermijnen toevoegen. (Er is geen behoefte aan &#42; jokerteken op zoektermen als standaard ingesteld om woordgroepen op te nemen die de zoekterm bevatten).

**Referenties** - Voeg URL&#39;s toe waarnaar de bezoeker heeft verwezen.

* Selecteer verwijzingen die u wilt toevoegen - Selecteer in de vervolgkeuzelijst de verwijzingssites die u wilt bijhouden of voeg uw eigen verwijzing toe. Als deze optie is geselecteerd, worden de verwijzingen weergegeven in het onderstaande vak. (Gebruik &#42; als jokerteken is toegestaan)

**Inclusief pagina&#39;s** - Houd de vooruitzichten voor specifieke pagina&#39;s bij die op uw website worden bezocht.

* URL-overeenkomsten - Voeg de URL toe van specifieke webpagina&#39;s die u wilt bijhouden. U kunt meerdere URL&#39;s toevoegen door deze te scheiden met een puntkomma. (Gebruik &#42; als jokerteken is toegestaan).

**Pagina&#39;s uitsluiten** - Sluit specifieke pagina&#39;s uit die u niet wilt afstemmen in het segment. (Gebruik &#42; als jokerteken is toegestaan).

* URL komt niet overeen - Voeg de URL toe van specifieke webpagina&#39;s die u wilt uitsluiten van bijhouden. U kunt meerdere URL&#39;s toevoegen door deze te scheiden met een puntkomma

![](assets/segment-extra.png)

### Apparaat/browser {#device-browser}

**Mobiel besturingssysteem**

Het mobiele besturingssysteem naar de Segment-editor slepen

![](assets/image2015-5-27-17-3a45-3a3.png)

* **Type bezoeker**<br />
  **Mobiel besturingssysteem** - Selecteer in het keuzemenu een of meer vermelde mobiele besturingssystemen. Het geselecteerde mobiele besturingssysteem wordt hieronder weergegeven.

   * De bezoeker gebruikt elk mobiel apparaat
   * De bezoeker gebruikt dit specifieke apparaat/besturingssysteem
   * De bezoeker gebruikt geen mobiel apparaat

* **Apparaat**  - Selecteer in de vervolgkeuzelijst een of meer apparaten (Apple, Samsung, LG, HTC, Nexus, Blackberry, enz.). De geselecteerde apparaten worden hieronder weergegeven.

**Browser**

Doelbezoeker die specifieke browsertypen en/of versies gebruikt.

* Browsertype - Selecteer een of meer internetbrowsers in het keuzemenu. De geselecteerde browsers worden hieronder weergegeven.
* Browserversie - voer de browserversie in die u aan het segment wilt toevoegen. U kunt meerdere versies selecteren door elke versie te scheiden met een komma. (Gebruik &#42; als jokerteken is toegestaan).

### API {#api}

**Gebeurtenissen gegevens** - Segmentbezoekers die specifieke gebeurtenissen van de Gegevens van de Douane teweegbrengen

Voeg de waarde van de Gebeurtenis toe u wilt richten. Bijvoorbeeld uit gegevensbronnen van derden.

**Context-API van gebruiker**

Web Personalization API call  [lees hier meer over .](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/web-personalization)

>[!TIP]
>
>**Jokertekens gebruiken -** Wanneer u een zoekterm of URL wilt opnemen die iets in de zoekopdracht bevat, dat wil zeggen &quot;[google.com](https://google.com)&quot; of &quot;zoekterm product&quot;, noemen we dit een jokerteken en het moet worden ingevoerd met een sterretje - dit kleine kerel&#42; - aan elk uiteinde. Alles wat er van komt [google.com](https://google.com) moet worden ingevoerd zoals &#42; [google.com](https://google.com)&#42;

## Segmenten bewerken {#edit-segments}

U kunt een segment bewerken dat is gemaakt.

1. Ga naar **Segmenten**.

   ![](assets/image2014-11-12-11-3a38-3a22.png)

1. In de **Segmenten** tabel, klik op het pictogram Bewerken ( ![](assets/segment-edit.png)) van het segment dat u wilt bewerken. De **Segment instellen** pagina wordt geopend met het geselecteerde segment.
1. Pas eventuele bewerkingen of wijzigingen toe die u op het segment wilt aanbrengen.
1. Klikken **Opslaan**.

## Segmenten verwijderen {#delete-segments}

U kunt segmenten verwijderen die u hebt gemaakt.

1. Van de **Segmenten** Selecteer een segment hierboven.
1. Klik op het verwijderpictogram ( ![](assets/segment-delete.png) ) van het segment dat u wilt verwijderen.
1. Er wordt een bevestigingsbericht weergegeven waarin wordt bevestigd dat u het dialoogvenster **Segment**.

>[!NOTE]
>
>U kunt geen segment verwijderen dat aan een campagne is gekoppeld. Eerst moet u de campagne en dan het segment schrappen.

Geweldig! Nu u de sectie van Segmenten begrijpt, leren wij over campagnes.

>[!MORELIKETHIS]
>
>* [Een basiswebsegment maken](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md)
>* [Een nieuwe webcampagne voor dialoog maken](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)
>* [Nieuwe webcampagne maken in zone](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-in-zone-web-campaign.md)
>* [Nieuwe widgetwebcampagne maken](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md)
