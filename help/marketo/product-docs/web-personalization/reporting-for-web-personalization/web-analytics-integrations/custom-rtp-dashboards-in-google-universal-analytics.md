---
unique-page-id: 7504238
description: Aangepaste RTP-dashboards in Google Universal Analytics - Marketo Docs - Productdocumentatie
title: Aangepaste RTP-dashboards in Google Universal Analytics
exl-id: 712c71b6-74eb-4743-9ca8-50c912278e62
feature: Web Personalization
source-git-commit: 89995b2cd6fdc2f2e4ea43906304bdf16d367de1
workflow-type: tm+mt
source-wordcount: '759'
ht-degree: 0%

---

# Aangepaste RTP-dashboards in Google Universal Analytics {#custom-rtp-dashboards-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[ integreer RTP met de Universele Analytics van Google ](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

In dit artikel wordt uitgelegd hoe u RTP-dashboards kunt instellen in Google Universal Analytics (GUA). De gegevens die van RTP naar GUA worden verzonden kunnen opstelling als twee afzonderlijke geroepen douanedashboards zijn:

* RTP B2B
* RTP-betrokkenheid

## Een aangepast dashboard instellen {#setting-up-a-custom-dashboard}

1. Meld u aan bij Googles Analytics. Klik op **Meldend** in het hoogste menu. Klik **dashboards** en **+ Nieuw Dashboard van de Douane**.

   ![](assets/image2015-3-22-16-3a41-3a29.png)

1. Selecteer **Lege Canvas**, voeg de Naam van het a **Dashboard** toe en klik **creeer Dashboard**.

1. Klik **toevoegen Widget** om een nieuwe widget tot stand te brengen.

   ![](assets/image2015-3-22-16-3a46-3a48.png)

## RTP B2B-dashboard {#rtp-b-b-dashboard}

Met dit dashboard kunnen gebruikers de prestaties van hun website analyseren vanuit een B2B-perspectief.

Het verstrekt informatie zoals bezoekbron en onsite gedrag door industrie, opbrengst, grootte, op rekening-Gebaseerde lijsten, en doelsegmenten.

Het dashboard bestaat uit drie kolommen

* verkeersbron
* Segmentatie
* Ingebouwde boor omlaag

1. Creeer een nieuw dashboard genoemd **RTP B2B Dashboard** en bepaal de volgende widgets:

![](assets/image2015-3-22-16-3a50-3a3.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Kolom 1 - Verkeersbronnen
    </div></th> 
   <th> 
    <div> <strong> Kolom 2 - Segmentatie </strong> 
    </div></th> 
   <th> 
    <div> <strong> Kolom 3 - Ingebouwde Boor neer </strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: sessies per segment en kanaal</li> 
     <li>Type widget: balk<br></li> 
     <li>Een staafdiagram maken met de weergave Sessie</li> 
     <li>Gegroepeerd door: Gebeurtenislabel</li> 
     <li>Draaien door: standaardkanaalgroepering</li> 
     <li>Filter: <br> Alleen tonen | Gebeurtenissencategorie (bevattende) RTP-segmenten</li> 
    </ul><p><img width="300" src="assets/image2015-3-23-11-3a32-3a13.png" data-linked-resource-id="7504247" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: # van gebruikers die door RTP worden gesegmenteerd</li> 
     <li>Type: 2.1 metrisch</li> 
     <li>De volgende meting weergeven: Gebruikers<br></li> 
     <li>Filter: <br> Alleen tonen | Gebeurtenissencategorie (bevattende) RTP-segmenten</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a6.png" data-linked-resource-id="7504249" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: Sessies per bedrijfstak</li> 
     <li>Type: Schijf<br></li> 
     <li>Een cirkeldiagram maken met de presentatie: sessies</li> 
     <li>Gegroepeerd door: RTP-Industry</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a27.png" data-linked-resource-id="7504250" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <th> 
    <ul> 
     <li><strong>Naam: Sessies op branche en kanalen</strong></li> 
     <li><strong>Type widget: balk</strong></li> 
     <li><strong>Een staafdiagram maken met de weergave Sessie</strong></li> 
     <li><strong>Gegroepeerd door: RTP-Industry</strong></li> 
     <li><strong>Draaien door: standaardkanaalgroepering</strong><br><img width="300" src="assets/image2015-3-23-11-3a33-3a52.png" data-linked-resource-id="7504252" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></li> 
    </ul></th> 
   <th> 
    <ul> 
     <li><strong>Naam: Gesegmenteerde sessies per land</strong></li> 
     <li><strong>Type: Geomap</strong></li> 
     <li><strong>Metrisch perceel geselecteerd: Land | Sessies</strong></li> 
     <li><strong>Selecteer een gebied: De wereld</strong></li> 
     <li><strong>Filter: Alleen tonen | Gebeurtenissencategorie (bevattende) RTP-segmenten</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a34-3a18.png" data-linked-resource-id="7504253" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li><strong>Naam: Sessies per RTP-categorie</strong></li> 
     <li><strong>Type: Schijf</strong></li> 
     <li><strong>Een cirkeldiagram maken met de presentatie: sessies</strong></li> 
     <li><strong>Gegroepeerd door: RTP-Categorie</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a35-3a1.png" data-linked-resource-id="7504254" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Naam: bovenste doelsegmenten</li> 
     <li>Type: balk</li> 
     <li>Een staafdiagram maken met de weergave Gebruikers</li> 
     <li>Gegroepeerd door: Gebeurtenisactie</li> 
     <li>Filter: Alleen tonen | Gebeurtenissencategorie (bevattende) RTP-segmenten</li> 
    </ul><p><img width="350" src="assets/add-a-widget.png" data-linked-resource-id="11382874" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li>Naam: Zittingen door RTP-Groepen</li> 
     <li>Type: balk<br></li> 
     <li>Een staafdiagram maken met de weergave Sessies</li> 
     <li>Gegroepeerd door: RTP-Group</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a35-3a54.png" data-linked-resource-id="7504256" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Naam: Sessies en doelen per bovenste segment</li> 
     <li>Type: Tabel<br></li> 
     <li>Toon de volgende kolommen: <br> Etiket van de Gebeurtenis | Sessies | Omzetsnelheid doel</li> 
     <li>Filter: <br> Alleen tonen | Gebeurtenissencategorie (bevattende) RTP-segmenten</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a36-3a15.png" data-linked-resource-id="7504257" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> </th> 
  </tr> 
 </tbody> 
</table>

## RTP-betrokkenheidsdashboard {#rtp-engagement-dashboard}

Met dit dashboard kunnen gebruikers hun RTP-prestaties en aanbevelingen voor de engine voor services analyseren. Het biedt een vergelijking van avg. sessieduur en pagina&#39;s per sessie tussen:

* Niet-actief
* Gecentreerd (impressies en klikken op een gepersonaliseerde campagne)
* Klik op de engine voor aanbevelingen en de aanbevolen inhoud als eerste

Creeer een nieuw dashboard genoemd **Dashboard van de Betrokkenheid RTP** en bepaal de volgende widgets:

![](assets/image2015-3-22-17-3a7-3a19.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div> <strong> Kolom 1 CampagneBelichting </strong> 
    </div></th> 
   <th> 
    <div> <strong> Kolom 2 Campagnes Klikthrough </strong> 
    </div></th> 
   <th> 
    <div> <strong> Kolom 3 de Motor van de Aanbeveling </strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: <strong> Totale CTA (Betrokkenheid) </strong></li> 
     <li>Type: <strong> 2.1 Metrisch </strong></li> 
     <li>Toon volgende metrisch: <strong> Totale Gebeurtenissen </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (bevat): RTP-Campagnes </strong><br> <strong> [tonen slechts] de Actie van de Gebeurtenis (precies het in orde brengen): Indrukking </strong> [tonen niet] het Etiket van de Gebeurtenis (die bevat: #</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a37-3a55.png" data-linked-resource-id="7504259" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong> Totale CTA (Klikthrough) </strong></li> 
     <li>Type: <strong> 2.1 Metrisch </strong></li> 
     <li>Toon volgende metrisch: <strong> Totale Gebeurtenissen </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (bevat): RTP-Campagnes </strong><br> <strong> [tonen slechts] de Actie van de Gebeurtenis (exact aanpassing): Klik </strong> <strong> [tonen niet] het Etiket van de Gebeurtenis (die) bevatten: #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a38-3a12.png" data-linked-resource-id="7504261" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong> CRE - Totale Klikken </strong></li> 
     <li>Type: <strong> 2.1 Metrisch </strong><br></li> 
     <li>Toon volgende metrisch: <strong> Pegeviews </strong></li> 
     <li>Filter: <strong>[alleen tonen] Pagina (met): rcmd </strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a38-3a30.png" data-linked-resource-id="7504262" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> 
    <ul> 
     <li>Naam: <strong> Avg. De Duur van de zitting (Betrokkenheid) </strong></li> 
     <li>Type: <strong> 2.1 Metrisch </strong></li> 
     <li>Toon volgende metrisch: <strong> Avg. Sessieduur </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (precies aanpassing): RTP-Campagnes </strong><br> <strong> [tonen slechts] de Actie van de Gebeurtenis (exact aanpassing): indruk </strong> <strong> [tonen niet] het Etiket van de Gebeurtenis (die) bevatten: #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a41-3a21.png" data-linked-resource-id="7504264" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Naam: <strong> Avg. De Duur van de zitting (Klikthrough) </strong></li> 
     <li>Type: <strong> 2.1 Metrisch </strong></li> 
     <li>Toon volgende metrisch: <strong> Avg. Sessieduur </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (precies aanpassing): RTP-Campagnes </strong><br> <strong> [tonen slechts] de Actie van de Gebeurtenis (exact aanpassing): klikt </strong> <strong> [tonen niet] het Etiket van de Gebeurtenis (die) bevatten: #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a41-3a37.png" data-linked-resource-id="7504265" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Naam: <strong> CRE - Hoogste Geadviseerde Inhoud </strong></li> 
     <li>Type: <strong> Lijst </strong><br></li> 
     <li>Toon de volgende kolommen: <br><strong> Titel van de Pagina | Pageviews </strong><br></li> 
     <li>Filters:<br> Filter: <strong> [tonen slechts] Pagina (die) bevat: rcmd </strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a41-3a51.png" data-linked-resource-id="7504266" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: <strong> Pagina's/Zitting (Betrokkenheid) </strong></li> 
     <li>Type: <strong> 2.1 Metrisch </strong></li> 
     <li>Toon volgende metrisch: <strong> Pagina's/Zitting </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (precies aanpassing): RTP-Campagnes </strong></li> 
     <li><strong>[alleen tonen] Gebeurtenisactie (exact overeenkomend): impositie</strong></li> 
     <li><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a10.png" data-linked-resource-id="7504267" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong> Pagina's/Zitting (Klikthrough) </strong></li> 
     <li>Type: <strong> 2.1 Metrisch </strong></li> 
     <li>Toon volgende metrisch: <strong> Pagina's/Zitting </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (precies aanpassing): RTP-Campagnes </strong></li> 
     <li><strong>[alleen tonen] Gebeurtenisactie (exact overeenkomend): klikt</strong></li> 
     <li><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a32.png" data-linked-resource-id="7504268" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: <strong> Impressies door CTA </strong></li> 
     <li>Type: <strong> Lijst </strong></li> 
     <li>Toon de volgende kolommen: <strong> Etiket van de Gebeurtenis | Totaal aantal gebeurtenissen | Gebruikers </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (precies aanpassing): RTP-Campagnes </strong><br> <strong> [tonen slechts] de Actie van de Gebeurtenis (exact aanpassing): indruk </strong> <strong> [tonen niet] het Etiket van de Gebeurtenis (die) bevatten: #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a48.png" data-linked-resource-id="7504269" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong> Klikthrough door CTA </strong></li> 
     <li>Type: <strong> Lijst </strong></li> 
     <li>Toon de volgende kolommen: <strong> Etiket van de Gebeurtenis | Totaal aantal gebeurtenissen | Gebruikers </strong></li> 
     <li>Filters:<br><strong> [tonen slechts] de Categorie van de Gebeurtenis (precies aanpassing): RTP-Campagnes </strong><br> <strong> [tonen slechts] de Actie van de Gebeurtenis (precies aanpassing): klikt </strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a43-3a4.png" data-linked-resource-id="7504270" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[ integreer RTP met de Universele Analytics van Google ](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
>
>[ de Rapporten van RTP van de Douane in Universele Analytics van Google ](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
