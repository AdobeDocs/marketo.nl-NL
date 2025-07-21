---
unique-page-id: 12979858
description: Veelgestelde vragen over prestaties - Marketo Docs - Productdocumentatie
title: Veelgestelde vragen over prestaties
exl-id: cee791c3-1845-4fca-b803-c0dc1c644549
feature: Reporting
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '1343'
ht-degree: 0%

---

# [!UICONTROL Performance Insights] Veelgestelde vragen {#performance-insights-faq}

## Wat is de definitie van &quot;succes&quot; op het tabblad [!UICONTROL Engagement] ? {#what-is-the-definition-of-success-in-the-engagement-tab}

Succes is een maatstaf voor betekenisvolle interactie in Marketo. Het doel van een programma is een zinvolle interactie met de persoon of het vooruitzicht tot stand te brengen. Het succes wordt duidelijk wanneer een persoon de status bereikt die dat doel bereikt. Het kan een webinar bijwonen, op een koppeling in een e-mail klikken of een webformulier invullen. Het succes hangt af van het programmakanaal.

>[!NOTE]
>
>In een webinar programma, kunnen er veelvoudige statussen zijn, zoals: Uitgenodigd, Geregistreerd, en Bijgewoond. Uitgenodigde of Geregistreerd zijn geen zinvolle interacties omdat mensen niet echt naar het webinar kijken. Bijgewoond wordt beschouwd als succes in dit geval.

## Zal MPI met om het even welke CRM werken? {#will-mpi-work-with-any-crm}

Ja. Technisch gezien communiceert MPI niet rechtstreeks met de CRM voor gegevenssynchronisatie. MPI gebruikt gegevens die zijn opgeslagen in de Marketo Analytics Data Warehouse. Aangezien de CRM-synchronisatie plaatsvindt in de toepassing Lead Management, worden gegevens correct weergegeven door alle door Marketo ondersteunde CRM-systemen die zijn geïntegreerd in de toepassing Lead Management. De velden voor CRM-mogelijkheden moeten echter correct worden toegewezen aan de opportuniteitsvelden van Marketo.

## Ik heb geen andere producten van de Analytics van de Marketing (ARB, RCE, RCA, de Analyse van het Programma). Werkt MPI voor mij? {#i-do-not-have-any-other-marketing-analytics-products-arb-rce-rca-program-analysis-will-mpi-work-for-me}

MPI is een onafhankelijke add-on bij de toepassing Lead Management. Hiervoor is het gebruik van andere analytische producten niet vereist.

## RCA toont me ook de gegevens van de programmaprestaties. Is er een verschil tussen de gegevens die in MPI en RCA worden getoond? {#rca-shows-me-program-performance-data-as-well-is-there-a-difference-between-the-data-shown-in-mpi-and-rca}

Nee. MPI produceert gegevens van het zelfde gegevenspakhuis zoals RCA. Daarom zult u geen gegevensverschillen tussen beide zien. Met RCA kunt u uw eigen rapporten direct maken. MPI biedt u toegang tot eenvoudig te begrijpen visuele dashboards.

## Ik wil niet dat sommige van mijn programma&#39;s (bijvoorbeeld Operationeel) in MPI worden weergegeven. Hoe kan ik de zichtbaarheid van specifieke programma&#39;s controleren? {#i-don-t-want-some-of-my-programs-e-g-operational-to-show-up-in-mpi-how-do-i-control-the-visibility-of-specific-programs}

U kunt de zichtbaarheid van uw programma&#39;s bepalen door het gedrag Analytics van uw programma&#39;s in te stellen op Operationeel. Hierdoor wordt het programma uitgesloten van analytische berekeningen.

>[!NOTE]
>
>Leer meer over het plaatsen van analysegedrag [ hier ](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/edit-analytics-behavior-settings.md).

## Ik voer een multikanaalcampagne voor een nieuwe productlancering. Hoe kan ik de prestaties voor deze campagne op alle verschillende kanalen op één plaats bekijken? {#i-am-running-a-multi-channel-campaign-for-a-new-product-launch-how-can-i-view-the-performance-for-this-campaign-across-all-the-different-channels-in-one-place}

We raden u aan om programmatags te gebruiken voor programma&#39;s die deel uitmaken van een dergelijke campagne. Programmatags worden automatisch gesynchroniseerd met MPI en u kunt deze filteren in alle MPI-dashboards om de campagneprestaties van meerdere kanalen te bekijken.

## Zal ik toegang tot attributie montages hebben als ik geen RCA heb? {#will-i-have-access-to-attribution-settings-if-i-do-not-have-rca}

U krijgt toegang tot attributie-instellingen als u MPI hebt, ongeacht of u RCA hebt of niet.

## Ik krijg een waarschuwing in MPI wanneer ik me aanmeld om me te vertellen dat mijn attributie-instellingen onjuist zijn. Wat is er mis? {#i-get-an-alert-in-mpi-when-i-log-in-telling-me-that-my-attribution-settings-are-incorrect-what-s-wrong}

MPI berekent of al uw mogelijkheden al dan niet worden opgenomen in analyses. Als dat niet het geval is, wordt u gevraagd of u de attributie-instellingen (Expliciet, Impliciet, Hybrid) wilt wijzigen en meer mogelijkheden wilt opnemen.

Mogelijk ontbreken er ook kansen omdat de programmakosten ontbreken in uw programma&#39;s. Controleer het gedrag Analytics van uw programma&#39;s. Ze kunnen zijn:

1. Standaard - Het standaardgedrag is dat het programma ALLEEN in MPI wordt opgenomen als er ten minste één periode kosten zijn, zelfs als er nul dollar is toegewezen.

1. Inclusief - Met deze optie zorgt u ervoor dat het programma beschikbaar is in MPI, ongeacht of u kosten voor een periode hebt opgenomen.

1. [ Operationeel ](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs.md#operational-programs) - deze optie resulteert in het programma niet die in MPI verschijnt.

>[!NOTE]
>
>De Kosten van de periode **moeten** opstelling voor Succes en Nieuwe Namen zijn die in het dashboard van de Betrokkenheid melden. Dit dashboard gebruikt gegevens van de Kosten van de Periode om successen en nieuwe namen samen te voegen. Als Periode-kosten niet is ingesteld, rapporteert het betrokkenheidsdashboard niet correct, ongeacht de bovenstaande instellingen voor Analytics-gedrag.

## Waarom mis ik kansen in MPI? {#why-am-i-missing-some-opportunities-in-mpi}

Twee belangrijke redenen waarom u kansen in MPI kunt missen zijn:

1. Attributie-instelling is ingesteld op Expliciet, maar er zijn geen contactpersonen toegewezen voor de mogelijkheden
1. Periode-kosten worden niet in uw programma&#39;s opgenomen

MPI berekent of al uw mogelijkheden al dan niet worden opgenomen in analyses. Als dat niet het geval is, wordt u gevraagd of u de attributie-instellingen (Expliciet, Impliciet, Hybrid) wilt wijzigen en meer mogelijkheden wilt opnemen.

Mogelijk ontbreken er ook kansen omdat de programmakosten ontbreken in uw programma&#39;s. De waarschuwing komt op tafel, maar er wordt niet op gewezen welke programma&#39;s kosten missen. Controleer de instellingen van uw programma om kosten op te nemen. Zo weet u zeker dat al uw programma&#39;s en mogelijkheden in MPI worden opgenomen.

## Waarom zie ik geen Aangepaste Gebieden, Type van Opportunity en filters ABM op het dashboard van de Overeenkomst? {#why-do-i-not-see-custom-fields-opportunity-type-and-abm-filters-on-the-engagement-dashboard}

Aangepaste velden, opportuniteitstype en ABM-filters zijn allemaal kenmerken die te maken hebben met een opportuniteit. Met het dashboard Betrokkenheid kunt u uw betrokkenheid en aanwinst van leads meten, ongeacht of ze aan een opportuniteit zijn gekoppeld. Aangezien het dashboard Betrokkenheid geen rekening houdt met opportuniteit, zijn de Aangepaste velden, het Type opportunity en de Filters ABM niet van toepassing.

## Ik wil een gebied van de Kans van aangepaste Salesforce voor opbrengstrapportering in plaats van het standaardgebied van het Bedrag van de Kans van Salesforce gebruiken. Zal MPI mij toestaan dat te doen? {#i-want-to-use-a-custom-salesforce-opportunity-field-for-revenue-reporting-instead-of-the-standard-salesforce-opportunity-amount-field-will-mpi-allow-me-to-do-that}

Ja. [ de Steun van Marketo ](https://nation.marketo.com/t5/Support/ct-p/Support) kan het gebied van het Bedrag van de Kans van Marketo aan een gebied van de Kans van douaneSalesforce opnieuw in kaart brengen zolang het gebiedstype valuta is. Aangezien MPI naar het veld voor de Marketo Opportunity-hoeveelheid verwijst, kan MPI de gegevens uit het opnieuw toegewezen veld voor aangepaste Salesforce gebruiken.

>[!NOTE]
>
>Na het opnieuw toewijzen, zal MPI de gegevens tonen die door:gaan. Het historische bedrag zal niet veranderd worden.

## Als ik geen mogelijkheden gebruik, kan ik dan nog steeds MPI gebruiken? {#if-i-don-t-use-opportunities-can-i-still-use-mpi}

MPI is ontworpen om u in staat te stellen de programmaprestaties te meten van de bovenkant van de trechter tot de impact op de inkomsten. Als u geen kansen gebruikt, zult u nog kunnen:

* Bekijk de prestaties van uw programma&#39;s voor de verpleging voor de betrokkenheid van het publiek.
* Geef de prestaties van uw programma&#39;s voor het aanschaffen van leads weer.
* U kunt de prestaties van multikanaalcampagnes bekijken via programmatags.
* Bekijk de trends voor de betrokkenheid van het publiek voor de afgelopen 12 maanden.
* Sla prestatiegegevens op en exporteer deze naar PowerPoint.

## Kan ik het succes van op rekening-gebaseerde strategieën in MPI meten? {#can-i-measure-the-success-of-account-based-strategies-in-mpi}

Ja. MPI integreert met [ Marketo TAM ](https://docs.marketo.com/display/DOCS/Account+Based+Marketing+Overview) om ABM- rekeningslijsten in MPI foutloos te trekken. U kunt het ABM filter van de Lijst van de Rekening gebruiken om de gewenste ABM lijst te kiezen om gegevens door te filtreren.

## Is de toewijzing onmiddellijk beschikbaar wanneer ik MPI aanschaf? {#is-attribution-instantly-available-when-i-purchase-mpi}

De Marketo Attribution-mogelijkheden zijn beschikbaar voor onze klanten wanneer ze MPI aanschaffen. Nochtans, [ juiste opstelling ](/help/marketo/product-docs/reporting/performance-insights/setting-up-performance-insights.md) wordt vereist om ervoor te zorgen dat de kansen en de programmagegevens correct in MPI stromen.

## Wat moet ik doen om attributie in te stellen? {#what-do-i-have-to-do-to-set-up-attribution}

1. Opportunity instellen

   1. Ervoor zorgen dat de mogelijkheden worden gesynchroniseerd met uw CRM
   1. Als uw montages van de Attributie aan Expliciet worden geplaatst, zorg ervoor de contactrollen op kansen worden bevolkt
   1. We raden u aan de instelling Attributie te wijzigen in Hybrid
   1. Programma instellen

      1. Programmakosten opnemen in uw programma&#39;s
      1. Controleer het analysegedrag om aan te geven of een programma in de analyse moet worden opgenomen
      1. De succescriteria instellen voor elk kanaal dat u hebt
      1. Tie Person naar programma&#39;s

         1. Zorg ervoor dat het overnameprogramma en de overnamedatum zijn ingesteld voor elke persoon in de database, zodat First Touch Attribution werkt.
         1. Zorg ervoor dat uw programma&#39;s successtatussen instellen voor mensen in uw database

>[!TIP]
>
>Alle vereiste opstellingsstappen zijn gedetailleerd in [ dit artikel ](/help/marketo/product-docs/reporting/performance-insights/setting-up-performance-insights.md).

## Wat is het verschil tussen MPI en de Analysator van het Programma? {#whats-the-difference-between-mpi-and-the-program-analyzer}

Met Program Analyzer kunt u uw programma&#39;s vergelijken met maximaal vier metingen. Met MPI kunt u uw kanaal- en programmabijdrage analyseren voor een gekozen metrische waarde, zoals Succes, Nieuwe kansen gemaakt, enzovoort. Het staat u ook toe om de 12 maanden kanaaltrend te bekijken die op één specifieke metrisch wordt gebaseerd u hebt gekozen.

## Wat is het verschil tussen MPI en Advanced Report Builder? {#whats-the-difference-between-mpi-and-the-advanced-report-builder}

De geavanceerde Report Builder (ook wel RCE genoemd), is ontworpen voor zelfserverrapportage (of ad-hocrapportage), meestal uitgevoerd door marketingactiviteiten. MPI is ontworpen om marketingleiders en marketers met één klik toegang te geven tot prestatieanalyse. Minimale installatie is vereist.

## Wat is er gebeurd met de optie Vorig jaar in het datumfilter van de bijdrage? {#what-happened-to-the-previous-year-option-in-contributions-date-filter}

We hebben de selectie voor het vorige jaar tijdelijk verwijderd. U kunt de prestatiegegevens van het hele jaar nog steeds bekijken met de selectie Aangepast datumbereik.
