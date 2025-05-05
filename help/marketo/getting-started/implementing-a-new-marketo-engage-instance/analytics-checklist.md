---
description: Stel de sectie Analytics in voor uw nieuwe Marketo Engage-instantie.
title: Aanbevolen werkwijzen voor nieuwe instanties - Controlelijst voor analyse
feature: Getting Started
source-git-commit: 2c74c71c9311312f7e0991ed5598ccb09a9b1f15
workflow-type: tm+mt
source-wordcount: '1393'
ht-degree: 0%

---

# Aanbevolen werkwijzen voor nieuwe instanties: Analytics Checklist {#new-instance-best-practices-analytics-checklist}

De sectie Analytics biedt algemene rapporten die de prestaties van uw marketing inspanningen analyseren. Meer informatie over de stappen die nodig zijn om door de bestanden te navigeren.

Herinneren aan [checklists downloaden](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) en de voortgang volgen.

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
    <td><li>Identificeer en creeer de rapporten nodig voor gebruik in <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/creating-reports/understanding-my-reports-and-group-reports">Mijn rapporten</a> sectie. Gebruik deze privérapportsectie als de sandbox voor algemene rapporten. Ze zijn alleen beschikbaar voor de gebruiker die het rapport maakt.</li>
    <li>Gebruik de noemende overeenkomst van uw organisatie om het rapport en het gebruik te identificeren zodat kunt u rapporten in Mijn Rapporten met rapporten in de Rapporten van de Groep verzoenen.</li></td>
  </tr>
  <tr>
    <td>Groepsrapporten</td>
    <td><li>De Rapporten van de groep zijn de Globale Rapporten van uw organisatie en zouden over algemene activiteit voor uw organisatie moeten rapporteren.</li>
    <li>Overweeg om te maken <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/clone-a-report-to-group-reports" target="_blank">duidelijke kernrapporten</a> u verwacht dat elke bedrijfseenheid het vaakst gebruikt om de tijd te verminderen nodig om het rapport terug te trekken en gegevenscorrectheid te verzekeren. Zie details in het dialoogvenster <a href="#global-reports">De onderstaande tabel met algemene rapporten</a>.
    <ul><li>Het Rapport van de Prestaties van het volk (alle tijd en op tijd-gebaseerd) door bron, maand</li>
    <li>Rapport over de prestaties van het programma (per kostenmaand, op tijd gebaseerd)</li>
    <li>E-mailprestatierapport (op tijd gebaseerd)</li></ul>
    <li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/report-email-campaign-performance-across-workspaces" target="_blank">Globale rapportage inschakelen</a> in het lusje van de Opstelling van het rapport om de gegevens van al uw werkruimten in de rapporten van de Prestaties van de E-mailVerbinding en E-mailprestaties te omvatten. Als u meerdere werkruimten hebt, hoeft u deze alleen in te schakelen in de standaardwerkruimte.</li>
    <p><img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: Maak de <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists" target="_blank">Slimme lijst</a> met de filters die u in de meeste rapporten in de sectie van het Gegevensbestand wilt omvatten. Wanneer u de criteria voor de slimme lijst moet bijwerken, kunt u deze op één locatie bijwerken in plaats van ze in alle algemene rapporten bij te werken.</td>
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
    <li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/subscribe-to-a-basic-report">Abonnementen instellen</a> in de gewenste frequentie (dagelijks/wekelijks/maandelijks) voor de doorlopende bewaking van elk team. U kunt <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/manage-report-subscriptions">al uw abonnementen weergeven</a> op één plaats onder het tabblad Abonnementen in Analytics.</li></td>
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
    <td><li>Maak wereldwijde rapporten voor de hele werkruimte en bedrijfseenheid met de juiste e-mails geselecteerd.</li>
    <li>Maak een lokaal e-mailprestatierapport in al uw aanroepbare programmasjablonen.</li>
    <li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame">Een relevant tijdsbestek gebruiken</a> (bijvoorbeeld YTD, afgelopen 90 dagen, enz.) voor het rapport om een nauwkeurige mening van standaard e-mailovereenkomst en leveringsbondigheden te verstrekken.</li>
    <p><img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/email-setup/filtering-email-bot-activity">Filter 'Bot Activity' inschakelen in <strong>Beheer &gt; E-mail</strong></a> om het registreren te vermijden, of te identificeren als het registreren voor beide activiteiten wordt toegelaten. Het filter alleen toestaan opnemen <a href="https://nation.marketo.com/t5/product-documents/filtering-email-bot-activity-feature-latest-release/ta-p/324860">Geopende/geklikte activiteiten met de "Is Bot Activiteit"beperkt die aan "Onwaar"wordt geplaatst</a> in de Slimme Lijst van uw kloonable Globale Rapporten.</td>
  </tr>
  <tr>
    <td>Rapport over prestaties van mensen</td>
    <td><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Het wordt geadviseerd om een juiste te hebben <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags">kanaal- en tagstrategie</a> voor elke implementatie van het Marketo Engage voordat u de aangeschafte personen en het rendement van uw marketinginvesteringen per kanaal kunt bijhouden.
    <p>
    <li>Bepaal de criteria u zult gebruiken om de prestaties van uw programma's van de loodverwerving te meten en uw op tijd-gebaseerde (huidige jaar, laatste het rollen maandmening, of 180 dagen) standaardrapporten tot stand te brengen die op deze metriek worden gebaseerd: <ul><li>Verwervingsprogramma: Marketo Engage-programma dat wordt gecrediteerd voor het verkrijgen van de persoon.</li>
    <li>Bron persoon: De broncategorie voor hoe het verslag aan uw gegevensbestand (dat op de bronlijst van waarden in uw CRM wordt gebaseerd) bekend kwam te zijn
    </li></ul>
    <li>Meet mensen die per week of maand zijn gemaakt. Dit rapport zal u van een maatregel van uw de groeisnelheid van het Gegevensbestand voorzien en of u uw de groottelimiet van het Gegevensbestand nadert.</li>
    <li>Filter de metriek in de Rapporten van de Prestaties van Mensen door <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/add-custom-columns-to-a-person-report">het gebruiken van uw Slimme Lijsten als douanekolommen.</a></li>
    <p><img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: Creeer Slimme Lijsten voor de douanekolommen u aan het Rapport van de Prestaties van Mensen in het Gegevensbestand in plaats van de Activiteiten van de Marketing wilt toevoegen zodat kunt u de Slimme naam van de Lijst behoorlijk en duidelijk zien wanneer het in het rapport wordt geselecteerd.</td>
  </tr>
  <tr>
    <td>Programmaprestatierapport</td>
    <td><p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Dit rapport vereist dat u uw kanalen, progressiestatus, en successtappen hebt die in <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/tags/create-a-program-channel"><strong>Beheerder</strong> &gt; <strong>Tags</strong></a>.
    <p>
    <li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report">De effectiviteit van uw marketingtactiek meten</a> binnen selectieve programma's.</li>
    <li>Programmalidmaatschap beheren (met behulp van slimme campagnes het aankoopprogramma, de status en de successtatus bijwerken) volgens de beste praktijken in Marketing Activiteiten.</li>
    <li>Maatregel gebaseerd op de kosten voor het lopende jaar en de lopende twaalf maanden.
    <ul><li>Vergeet niet dat het handhaven van <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program">Kosten periode</a> is van essentieel belang voor het benutten van het voortgangsrapport van het programma.</li></ul></li>
    <p>
    <img src="assets/tip-icon.png" alt="notitiepictogram"> TIP: alle elementen samenvoegen en weergeven <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people">geïmporteerde lijsten</a> in de Rapporten van de Prestaties van het Programma, zorg ervoor uw teams het aangewezen Programma van de Aankoop voor het etiketteren selecteren. Overweeg <a href="https://experienceleague.adobe.com/nl/docs/marketo-learn/tutorials/programs-and-campaigns/default-programs/create-and-measure-default-programs">een standaardprogramma maken</a> om als het Programma van de Aankoop worden geselecteerd wanneer de ingevoerde lijsten niet op om het even welk kanaal van toepassing zijn. Hierdoor wordt gegarandeerd dat elke geïmporteerde persoon een geldig aankoopprogramma heeft dat betrekking heeft op bron, bedrijfseenheid, kanaal, enz., in plaats van een lege waarde.</td>
  </tr>
  <tr>
    <td>Prestatierapport voor bestemmingspagina</td>
    <td><li>Maak de <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report">Prestatierapport voor bestemmingspagina</a> als algemeen rapport zodat kunt u <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/filter-a-landing-page-performance-report">filteren en de getallen bekijken</a> van al uw Design Studio/Marketing Activiteiten die Pagina's op één plaats landen.</li>
    <li>Voor programma's met bestemmingspagina('s) kunt u <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report">het creëren van een specifiek lokaal rapport binnen het programmamalplaatje</a> zodat kunt u de prestaties op programmaniveau controleren.</li></td>
  </tr>
  <tr>
    <td>Rapport over activiteiten op webpagina</td>
    <td><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: alleen webpagina's (externe pagina's en Marketo-bestemmingspagina's) met <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website">de Munchkin JavaScript</a> enabled zal in dit rapport worden gevolgd. U kunt overwegen de JavaScript-code in het Tag Management-platform te plaatsen, bijvoorbeeld <a href="https://developers.marketo.com/blog/integrating-munchkin-with-google-tag-manager/">Google-tagbeheer</a>, om te voorkomen dat de code op elke webpagina wordt verhard.
    <p>
    <li>Maak de <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/web-page-activity-report">Rapport over activiteiten op webpagina</a> als een globaal rapport zodat u de aantallen van al uw Web-pagina's op één plaats kunt herzien. Merk op dat uw externe Web-pagina activiteiten slechts in de rapporten van de Activiteit van de Web-pagina worden weerspiegeld.</li></td>
  </tr>
</tbody>
</table>

## Lokale rapporten {#local-reports}

Sommige rapporten van de Marketo Engage kunnen het best als lokale middelen binnen specifieke programma&#39;s in de Activiteiten van de Marketing worden opgesteld, aangezien hun typisch gebruik in een beperktere reeks programma&#39;s en activa is. U kunt basisrapporten instellen, zoals:

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
    <td><li>Een <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report" target="_blank">E-mailkoppelingprestaties</a> in programma's die e-mails en druppelcampagnes verzenden, zodat u kunt zien op welke koppelingen mensen klikken in uw e-mailbericht.</li></td>
  </tr>
  <tr>
    <td>Rapport Campagneactiviteiten</td>
    <td><li>Maak de <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/campaign-activity-report" target="_blank">Rapport Campagneactiviteiten</a> en kies een periode binnen uw operationele omslag in de Activiteiten van de Marketing.</li>
    <li>Stel rapporten in om de triggers voor elk gebruiksgeval te controleren en <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/filter-a-campaign-activity-report" target="_blank">campagnecilters toepassen</a> (bv. triggers voor het scoren van gedragingen, kwalificatietriggers voor de levenscyclus, triggers voor interessante momenten).</li></td>
  </tr>
  <tr>
    <td>Prestatierapport van de betrokkenheidsstream (indien van toepassing)</td>
    <td><li>Een <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/engagement-stream-performance-report" target="_blank">Prestatierapport voor betrokkenheidsstream</a> om de doeltreffendheid van inhoud en stroom te meten die binnen uw Programma van de Aansluiting worden opgesteld.</li>
    <li>Gebruik de opdracht <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/group-email-reports-by-segmentations" target="_blank">"Segmentatie"filter in het lusje van de Opstelling van het rapport</a> en groepeert de rapportageregels door de <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation" target="_blank">segment</a> (bijvoorbeeld persoonlijke bron, industrie) die in uw betrokkenheidsprogramma wordt gebruikt. Hierdoor krijgt u meer inzicht in de betrokkenheidspatronen van elk segment en kunt u strategische wijzigingen doorvoeren om uw betrokkenheidsprogramma te verbeteren (inhoud, stroom, stroomkring, enz.).</li></td>
  </tr>
</tbody>
</table>
