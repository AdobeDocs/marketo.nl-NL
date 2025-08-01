---
description: Stel de sectie Analytics in voor uw nieuwe Marketo Engage-exemplaar.
title: Aanbevolen werkwijzen voor nieuwe instanties - Controlelijst voor analyse
feature: Getting Started
exl-id: ddbb9bc7-d06a-4a2e-a560-9d308630ae3f
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '1393'
ht-degree: 0%

---

# Aanbevolen werkwijzen voor nieuwe instanties: Analytics Checklist {#new-instance-best-practices-analytics-checklist}

De sectie Analytics biedt algemene rapporten die de prestaties van uw marketing inspanningen analyseren. Meer informatie over de stappen die nodig zijn om door de bestanden te navigeren.

Herinner aan [ download de controlelijsten ](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) en volg uw vooruitgang.

## Boom {#tree}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Organisatie: Naamgeving, mappen en archivering</td>
    <td><li>Gebruik een rapport noemende overeenkomst om rapporten op het Globale lusje van Rapporten te onderscheiden.
    <ul><li>Een voorbeeld van een goede naamgevingsconventie is [Type rapport] [Global vs. BU-Specific Tag] [Beschrijving rapport], zoals [E-mailprestaties]-[Global]-[180 dagen e-mailservice].</li></ul><br>
    <li>Identificeer rapporten die met verschillende gebruikersgroepen binnen uw organisatie (b.v., verkoopteam, marketing leiderschap) zouden moeten worden gedeeld en organiseer de rapporten door omslag binnen de omslag van de Rapporten van de Groep in Analytics voor Globale Rapporten.</li>
    <li>Archivering moet worden beperkt tot de map Global Reports, aangezien dit altijd actuele rapporten zijn.   <ul><li>Archivering beperken tot organisatorische wijzigingen, zoals het reduceren of toevoegen van relevante bedrijfseenheden als u rapporteert op basis van een bedrijfseenheidsstructuur.</li></ul>
    </td>
  </tr>
  <tr>
    <td>Werkruimten (indien van toepassing)</td>
    <td><li>Repliceer de globale rapporten en de omslagstructuur over werkruimten om verenigbare rapportering voor uw teams te handhaven. Deze rapporten zouden in de omslag van de Rapporten van de Groep zijn.</li></td>
  </tr>
  <tr>
    <td>Mijn rapporten</td>
    <td><li>Identificeer en creeer de rapporten nodig voor gebruik in <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/creating-reports/understanding-my-reports-and-group-reports"> Mijn sectie van Rapporten </a>. Gebruik deze privérapportsectie als de sandbox voor algemene rapporten. Ze zijn alleen beschikbaar voor de gebruiker die het rapport maakt.</li>
    <li>Gebruik de noemende overeenkomst van uw organisatie om het rapport en het gebruik te identificeren zodat kunt u rapporten in Mijn Rapporten met rapporten in de Rapporten van de Groep verzoenen.</li></td>
  </tr>
  <tr>
    <td>Groepsrapporten</td>
    <td><li>De Rapporten van de groep zijn de Globale Rapporten van uw organisatie en zouden over algemene activiteit voor uw organisatie moeten rapporteren.</li>
    <li>Overweeg het creëren van <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/clone-a-report-to-group-reports" target="_blank"> kloneable kernrapporten </a> u elke bedrijfseenheid verwacht om het meest vaak te gebruiken om de tijd te verminderen nodig om het rapport te trekken en gegevenscorrectheid te verzekeren. Zie details in de <a href="#global-reports"> Globale lijst van Rapporten hieronder </a>.
    <ul><li>Het Rapport van de Prestaties van het volk (alle tijd en op tijd-gebaseerd) door bron, maand</li>
    <li>Rapport over de prestaties van het programma (per kostenmaand, op tijd gebaseerd)</li>
    <li>E-mailprestatierapport (op tijd gebaseerd)</li></ul>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/report-email-campaign-performance-across-workspaces" target="_blank"> zet "Globale Rapportering"</a> in het lusje van de Opstelling van het rapport aan om de gegevens van al uw werkruimten in de E-mailPrestaties en E-mail rapporten van de Prestaties van de Verbinding te omvatten. Als u meerdere werkruimten hebt, hoeft u deze alleen in te schakelen in de standaardwerkruimte.</li>
    <p><img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: Creeer de <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists" target="_blank"> Slimme Lijst </a> met de filters die u in de meeste rapporten in de sectie van het Gegevensbestand wilt omvatten. Wanneer u de criteria voor de slimme lijst moet bijwerken, kunt u deze op één locatie bijwerken in plaats van ze in alle algemene rapporten bij te werken.</td>
  </tr>
</tbody>
</table>

## Abonnementen {#subscriptions}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Abonnementen</td>
    <td><li>Lijn uit met uw marketingleider voor mensen die de rapportresultaten en hun ervaring tijdens de implementatie moeten beoordelen.</li> <li>De abonnementen van het gebruik om gegevens aan behoefte-aan-weet mensen in uw organisatie te verspreiden zonder een genoemde gebruikersvergunning uit te putten.</li>
    <p><img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: Als u mensen tot de rapportgegevens in real time wilt toegang hebben, zult u hen als gebruikers moeten toevoegen zodat kunnen zij het rapport bekijken.
    <p>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/subscribe-to-a-basic-report"> de abonnementen van de opstelling </a> in de gewenste (dagelijkse/wekelijkse/maandelijkse) kring voor de aan de gang zijnde controle van elk team. U kunt ook <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/manage-report-subscriptions"> bekijken al uw abonnementen </a> in één plaats onder het lusje van Abonnementen in Analytics.</li></td>
  </tr>
</tbody>
</table>

## Algemene rapporten {#global-reports}

Identificeer rapporten die met verschillende gebruikersgroepen binnen uw organisatie (b.v., verkoopteam, marketing leiderschap) zouden moeten worden gedeeld. Creeer juiste omslagstructuur voor elk team/gebruikersgroep/bedrijfseenheid om de gekloonde rapporten binnen de Rapporten van de Groep te organiseren. U kunt algemene rapporten instellen, zoals:

<table>
<thead>
  <tr>
    <th style="width:20%">Rapporttype</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>E-mailprestatierapport</td>
    <td><li>Maak wereldwijde rapporten voor de hele Workspace/Business Unit met de juiste e-mails geselecteerd.</li>
    <li>Maak een lokaal e-mailprestatierapport in al uw aanroepbare programmasjablonen.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame"> gebruik een relevant tijdkader </a> (b.v., YTD, laatste 90 dagen, enz.) voor het rapport om een nauwkeurige mening van standaard e-mailovereenkomst en leveringsmaatstaven te verstrekken.</li>
    <p><img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/email-setup/filtering-email-bot-activity"> zet "Bot Activiteit"het filtreren in <strong> Admin &gt; E-mail </strong> </a> aan om het registreren te vermijden, of te identificeren als het registreren voor beide activiteiten wordt toegelaten. Omvat de filter om slechts <a href="https://nation.marketo.com/t5/product-documents/filtering-email-bot-activity-feature-latest-release/ta-p/324860"> Geopende/Geclificeerde activiteiten met "Is Brouwe Activiteit"beperkt toe te staan die aan "Vals"</a> in de Slimme Lijst van uw cloneable Globale Rapporten wordt geplaatst.</td>
  </tr>
  <tr>
    <td>Rapport over prestaties van mensen</td>
    <td><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Het wordt geadviseerd om een juiste <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags"> kanaal en markeringsstrategie </a> voor elke implementatie van Marketo Engage te hebben alvorens u de verworven mensen en ROI van uw marketing investeringen door kanaal kunt volgen.
    <p>
    <li>Bepaal de criteria u zult gebruiken om de prestaties van uw programma's van de loodverwerving te meten en uw op tijd-gebaseerde (huidige jaar, laatste het rollen maandmening, of 180 dagen) standaardrapporten tot stand te brengen die op deze metriek worden gebaseerd: <ul><li>Verwervingsprogramma: Marketo Engage-programma dat wordt gecrediteerd voor het verkrijgen van de persoon.</li>
    <li>Persoon Source: De broncategorie voor hoe de record bekend is geworden in uw database (gebaseerd op de bronlijst met waarden in uw CRM)
    </li></ul>
    <li>Meet mensen die per week of maand zijn gemaakt. Dit rapport zal u van een maatregel van uw de groeisnelheid van het Gegevensbestand voorzien en of u uw de groottelimiet van het Gegevensbestand nadert.</li>
    <li>Filter de metriek in de Rapporten van de Prestaties van Mensen door <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/add-custom-columns-to-a-person-report"> uw Slimme Lijsten als douanekolommen te gebruiken.</a></li>
    <p><img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: Creeer Slimme Lijsten voor de douanekolommen u aan het Rapport van de Prestaties van Mensen in het Gegevensbestand in plaats van de Activiteiten van de Marketing wilt toevoegen zodat kunt u de Slimme naam van de Lijst behoorlijk en duidelijk zien wanneer het in het rapport wordt geselecteerd.</td>
  </tr>
  <tr>
    <td>Programmaprestatierapport</td>
    <td><p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Dit rapport vereist dat u uw kanalen, progressiestatus, en successtappen hebt die in <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/tags/create-a-program-channel"> worden bepaald <strong> Admin </strong> &gt; <strong> Markeringen </strong> </a>.
    <p>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report"> Meet de doeltreffendheid van uw marketing tactiek </a> binnen selectieve programma's.</li>
    <li>Programmalidmaatschap beheren (met behulp van slimme campagnes het aankoopprogramma, de status en de successtatus bijwerken) volgens de beste praktijken in Marketing Activiteiten.</li>
    <li>Maatregel gebaseerd op de kosten voor het lopende jaar en de lopende twaalf maanden.
    <ul><li>Herinner dat het handhaven van <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program"> Kosten van de Periode </a> kritiek aan het leveraging van het Rapport van de Prestaties van het Programma is.</li></ul></li>
    <p>
    <img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: Om om het even welke <a href="https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people"> ingevoerde lijsten </a> in de Rapporten van de Prestaties van het Programma samen te voegen en te bekijken, verzeker uw teams het aangewezen Programma van de Verwerving voor het etiketteren. Overweeg <a href="https://experienceleague.adobe.com/nl/docs/marketo-learn/tutorials/programs-and-campaigns/default-programs/create-and-measure-default-programs"> creërend een standaardprogramma </a> om als het programma van de Aankoop worden geselecteerd wanneer de ingevoerde lijsten niet op om het even welk kanaal van toepassing zijn. Hierdoor wordt gegarandeerd dat elke geïmporteerde persoon een geldig aankoopprogramma heeft dat betrekking heeft op bron, bedrijfseenheid, kanaal, enz., in plaats van een lege waarde.</td>
  </tr>
  <tr>
    <td>Prestatierapport voor bestemmingspagina</td>
    <td><li>Creeer het <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report"> Aanvoerende Rapport van de Prestaties van de Pagina </a> als globaal rapport zodat kunt u <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/filter-a-landing-page-performance-report"> de aantallen </a> van al uw het Aanbrengen van de Studio/van de Marketing van het Ontwerp Pagina's in één plaats filtreren en herzien.</li>
    <li>Voor programma's met het Openen Pagina(s), overweeg <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report"> creërend een specifiek lokaal rapport binnen het programmamalplaatje </a> zodat kunt u de prestaties op het programmaniveau herzien.</li></td>
  </tr>
  <tr>
    <td>Rapport over activiteiten op webpagina</td>
    <td><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Slechts zullen de Web-pagina's (externe en Marketo Landing Pages) die <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website"> toegelaten Munchkin JavaScript </a> hebben in dit rapport worden gevolgd. Overweeg het plaatsen van de code van JavaScript in het Platform van Tag Management, zoals <a href="https://developers.marketo.com/blog/integrating-munchkin-with-google-tag-manager/"> de Manager van de Markering van Google </a>, om hardcoding de code op elke Web-pagina te vermijden.
    <p>
    <li>Creeer het <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/web-page-activity-report"> Rapport van de Activiteit van de Pagina van het Web </a> als globaal rapport zodat kunt u de aantallen van al uw Web-pagina's in één plaats herzien. Merk op dat uw externe Web-pagina activiteiten slechts in de rapporten van de Activiteit van de Web-pagina worden weerspiegeld.</li></td>
  </tr>
</tbody>
</table>

## Lokale rapporten {#local-reports}

Sommige Marketo Engage-rapporten kunnen het best worden gebruikt als lokale middelen binnen specifieke programma&#39;s bij marketingactiviteiten, aangezien hun typische gebruik in een beperktere reeks programma&#39;s en middelen ligt. U kunt basisrapporten instellen, zoals:

<table>
<thead>
  <tr>
    <th style="width:20%">Rapporttype</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>E-mailkoppelingprestaties</td>
    <td><li>Creeer een <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report" target="_blank"> Rapport van de Prestaties van de Verbinding van de E-mail </a> binnen programma's die e-mail en uw druppelcampagnes verzenden om u van inzichten in de verbindingen te voorzien die mensen klikken op in uw e-mail verzendt.</li></td>
  </tr>
  <tr>
    <td>Rapport Campagneactiviteiten</td>
    <td><li>Creeer het <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/campaign-activity-report" target="_blank"> Rapport van de Activiteit van de Campagne </a> en kies een periode binnen uw operationele omslag in de Activiteiten van de Marketing.</li>
    <li>De opstellingsrapporten om de trekkers voor elk gebruiksgeval te controleren en <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/filter-a-campaign-activity-report" target="_blank"> voeren campagnecilters </a> (b.v., het Scoren van het Gedrag trekkers, de kwalificatietrekkers van de Levenscyclus, het Interesten de trekkers van Momenten) toe.</li></td>
  </tr>
  <tr>
    <td>Prestatierapport van de betrokkenheidsstream (indien van toepassing)</td>
    <td><li>Creeer een <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/engagement-stream-performance-report" target="_blank"> Rapport van de Prestaties van de Stroom van de Betrokkenheid </a> om de doeltreffendheid van inhoud en stroom te meten die binnen uw Programma van de Betrokkenheid wordt opgesteld.</li>
    <li>Overweeg het gebruiken van de <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/group-email-reports-by-segmentations" target="_blank"> "filter van de Segmentatie"in het lusje van de Opstelling van het rapport </a> en het groeperen van de rapporteringsgegevens door het <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation" target="_blank"> segment </a> (b.v., persoonbron, industrie) die in uw Programma van de Aansluiting wordt gebruikt. Hierdoor krijgt u meer inzicht in de betrokkenheidspatronen van elk segment en kunt u strategische wijzigingen doorvoeren om uw betrokkenheidsprogramma te verbeteren (inhoud, stroom, stroomkring, enz.).</li></td>
  </tr>
</tbody>
</table>
