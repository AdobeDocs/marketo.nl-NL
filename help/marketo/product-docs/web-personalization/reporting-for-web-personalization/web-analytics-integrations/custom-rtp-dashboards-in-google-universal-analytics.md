---
unique-page-id: 7504238
description: Aangepaste RTP-dashboards in Google Universal Analytics - Marketo Docs - Productdocumentatie
title: Aangepaste RTP-dashboards in Google Universal Analytics
exl-id: 712c71b6-74eb-4743-9ca8-50c912278e62
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '748'
ht-degree: 0%

---

# Aangepaste RTP-dashboards in Google Universal Analytics {#custom-rtp-dashboards-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[RTP integreren met Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

In dit artikel wordt uitgelegd hoe u RTP-dashboards kunt instellen in Google Universal Analytics (GUA). De gegevens die van RTP naar GUA worden verzonden kunnen opstelling als twee afzonderlijke geroepen douanedashboards zijn:

* RTP B2B
* RTP-betrokkenheid

## Een aangepast dashboard instellen {#setting-up-a-custom-dashboard}

1. Meld u aan bij Google Analytics. Klikken op **Rapportage** in het bovenste menu. Klikken **Dashboards** en **+Nieuw aangepast dashboard**.

   ![](assets/image2015-3-22-16-3a41-3a29.png)

1. Selecteren **Leeg canvas**, voegt u een **Naam dashboard** en klik op **Dashboard maken**.

1. Klikken **Widget toevoegen** om een nieuwe widget te maken.

   ![](assets/image2015-3-22-16-3a46-3a48.png)

## RTP B2B-dashboard {#rtp-b-b-dashboard}

Met dit dashboard kunnen gebruikers de prestaties van hun website analyseren vanuit een B2B-perspectief.

Het verstrekt informatie zoals bezoekbron en onsite gedrag door industrie, opbrengst, grootte, op rekening-Gebaseerde lijsten, en doelsegmenten.

Het dashboard bestaat uit drie kolommen

* Verkeersbron
* Segmentatie
* Ingebouwde boor omlaag

1. Maak een nieuw dashboard met de naam **RTP B2B-dashboard** en definieert u de volgende widgets:

![](assets/image2015-3-22-16-3a50-3a3.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Kolom 1 - Verkeersbronnen
    </div></th> 
   <th> 
    <div> <strong>Kolom 2 - Segmentering</strong> 
    </div></th> 
   <th> 
    <div> <strong>Kolom 3 - Ingebouwde boor omlaag</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: Sessies per segment en kanaal</li> 
     <li>Type widget: Balk<br></li> 
     <li>Een staafdiagram maken met: Sessie</li> 
     <li>Gegroepeerd door: Gebeurtenislabel</li> 
     <li>Draaien door: Standaardkanaalgroepering</li> 
     <li>Filter: <br>Alleen tonen | Gebeurteniscategorie (bevattende) RTP-segmenten</li> 
    </ul><p><img width="300" src="assets/image2015-3-23-11-3a32-3a13.png" data-linked-resource-id="7504247" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: Aantal gebruikers met RTP-segmenten</li> 
     <li>Type: 2.1 Metrisch</li> 
     <li>De volgende metrische waarde tonen: Gebruikers<br></li> 
     <li>Filter: <br>Alleen tonen | Gebeurteniscategorie (bevattende) RTP-segmenten</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a6.png" data-linked-resource-id="7504249" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: Sessies van de industrie</li> 
     <li>Type: Schijf<br></li> 
     <li>Een cirkeldiagram maken met de volgende kenmerken: Sessies</li> 
     <li>Gegroepeerd door: RTP-industrie</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a27.png" data-linked-resource-id="7504250" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <th> 
    <ul> 
     <li><strong>Naam: Sessies via de industrie en kanalen</strong></li> 
     <li><strong>Type widget: Balk</strong></li> 
     <li><strong>Een staafdiagram maken met: Sessie</strong></li> 
     <li><strong>Gegroepeerd door: RTP-industrie</strong></li> 
     <li><strong>Draaien door: Standaardkanaalgroepering</strong><br><img width="300" src="assets/image2015-3-23-11-3a33-3a52.png" data-linked-resource-id="7504252" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></li> 
    </ul></th> 
   <th> 
    <ul> 
     <li><strong>Naam: Gesegmenteerde sessies per land</strong></li> 
     <li><strong>Type: Geomap</strong></li> 
     <li><strong>Geselecteerde metrisch plotten: Land | Sessies</strong></li> 
     <li><strong>Selecteer een gebied: De wereld</strong></li> 
     <li><strong>Filter: Alleen tonen | Gebeurteniscategorie (bevattende) RTP-segmenten</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a34-3a18.png" data-linked-resource-id="7504253" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li><strong>Naam: Sessies per RTP-categorie</strong></li> 
     <li><strong>Type: Schijf</strong></li> 
     <li><strong>Een cirkeldiagram maken met de volgende kenmerken: Sessies</strong></li> 
     <li><strong>Gegroepeerd door: RTP-categorie</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a35-3a1.png" data-linked-resource-id="7504254" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Naam: Bovenste doelsegmenten</li> 
     <li>Type: Balk</li> 
     <li>Een staafdiagram maken met: Gebruikers</li> 
     <li>Gegroepeerd door: Gebeurtenisactie</li> 
     <li>Filter: Alleen tonen | Gebeurteniscategorie (bevattende) RTP-segmenten</li> 
    </ul><p><img width="350" src="assets/add-a-widget.png" data-linked-resource-id="11382874" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li>Naam: Zittingen door RTP-Groepen</li> 
     <li>Type: Balk<br></li> 
     <li>Een staafdiagram maken met: Sessies</li> 
     <li>Gegroepeerd door: RTP-groep</li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a35-3a54.png" data-linked-resource-id="7504256" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Naam: Sessies en doelen per bovenste segment</li> 
     <li>Type: Tabel<br></li> 
     <li>De volgende kolommen weergeven: <br>Gebeurtenislabel | Sessies | Omzetsnelheid van de doelstelling</li> 
     <li>Filter: <br>Alleen tonen | Gebeurteniscategorie (bevattende) RTP-segmenten</li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a36-3a15.png" data-linked-resource-id="7504257" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
   <th> </th> 
  </tr> 
 </tbody> 
</table>

## RTP-betrokkenheidsdashboard {#rtp-engagement-dashboard}

Met dit dashboard kunnen gebruikers hun RTP-prestaties en aanbevelingen voor de engine voor services analyseren. Het biedt een vergelijking van avg. sessieduur en pagina&#39;s per sessie tussen:

* Niet-actief
* Gecentreerd (impressies en klikken op een gepersonaliseerde campagne)
* Klik op de engine voor aanbevelingen en de aanbevolen inhoud als eerste

Maak een nieuw dashboard met de naam **RTP-betrokkenheidsdashboard** en definieert u de volgende widgets:

![](assets/image2015-3-22-17-3a7-3a19.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div> <strong>Kolom 1 Campagne Belichting</strong> 
    </div></th> 
   <th> 
    <div> <strong>Kolom 2 Campagnes Klikthrough</strong> 
    </div></th> 
   <th> 
    <div> <strong>Kolom 3 Aanbevolen-engine</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: <strong>Totale TCLP (Betrokkenheid)</strong></li> 
     <li>Type: <strong>2.1 Metrisch </strong></li> 
     <li>De volgende metrische waarde tonen: <strong>Totaal aantal gebeurtenissen</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (bevat): RTP-Campaigns</strong><br><strong>[alleen tonen] Gebeurtenisactie (exact overeenkomend): Impressie</strong><strong>[niet tonen] Gebeurtenislabel (met): Aantal</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a37-3a55.png" data-linked-resource-id="7504259" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong>Totale TCLP (doorklikken)</strong></li> 
     <li>Type: <strong>2.1 Metrisch </strong></li> 
     <li>De volgende metrische waarde tonen: <strong>Totaal aantal gebeurtenissen</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (bevat): RTP-Campaigns</strong><br><strong>[alleen weergeven] Gebeurtenisactie (exact overeenkomend): Klikken</strong><strong>[niet tonen] Gebeurtenislabel (met): Aantal</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a38-3a12.png" data-linked-resource-id="7504261" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong>CRE - Totaal aantal klikken</strong></li> 
     <li>Type: <strong>2.1 Metrisch</strong><br></li> 
     <li>De volgende metrische waarde tonen: <strong>Pageviews</strong></li> 
     <li>Filter: <strong>[alleen tonen] Pagina (met): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a38-3a30.png" data-linked-resource-id="7504262" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> 
    <ul> 
     <li>Naam: <strong>Gem. Sessieduur (betrokkenheid)</strong></li> 
     <li>Type: <strong>2.1 Metrisch </strong></li> 
     <li>De volgende metrische waarde tonen: <strong>Gem. Sessieduur</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (exact overeenkomend): RTP-Campaigns</strong><br><strong>[alleen weergeven] Gebeurtenisactie (exact overeenkomend): indruk</strong><strong>[niet tonen] Gebeurtenislabel (met): Aantal</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a21.png" data-linked-resource-id="7504264" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Naam: <strong>Gem. Sessieduur (doorklikken)</strong></li> 
     <li>Type: <strong>2.1 Metrisch </strong></li> 
     <li>De volgende metrische waarde tonen: <strong>Gem. Sessieduur</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (exact overeenkomend): RTP-Campaigns</strong><br><strong>[alleen weergeven] Gebeurtenisactie (exact overeenkomend): klikken</strong><strong>[niet tonen] Gebeurtenislabel (met): Aantal</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a37.png" data-linked-resource-id="7504265" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Naam: <strong>CRE - aanbevolen inhoud bovenaan</strong></li> 
     <li>Type: <strong>Tabel</strong><br></li> 
     <li>De volgende kolommen weergeven: <br><strong>Paginatitel | Pageviews</strong><br></li> 
     <li>Filters:<br>Filter: <strong>[alleen tonen] Pagina (met): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a41-3a51.png" data-linked-resource-id="7504266" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: <strong>Pagina's/sessie (betrokkenheid)</strong></li> 
     <li>Type: <strong>2.1 Metrisch </strong></li> 
     <li>De volgende metrische waarde tonen: <strong>Pagina's/sessie</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (exact overeenkomend): RTP-Campaigns</strong></li> 
     <li><strong>[alleen weergeven] Gebeurtenisactie (exact overeenkomend): indruk</strong></li> 
     <li><strong>[niet tonen] Gebeurtenislabel (met): Aantal</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a10.png" data-linked-resource-id="7504267" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong>Pagina's/sessie (klikken via)</strong></li> 
     <li>Type: <strong>2.1 Metrisch </strong></li> 
     <li>De volgende metrische waarde tonen: <strong>Pagina's/sessie</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (exact overeenkomend): RTP-Campaigns</strong></li> 
     <li><strong>[alleen weergeven] Gebeurtenisactie (exact overeenkomend): klikken</strong></li> 
     <li><strong>[niet tonen] Gebeurtenislabel (met): Aantal</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a42-3a32.png" data-linked-resource-id="7504268" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Naam: <strong>Impressies door CTA</strong></li> 
     <li>Type: <strong>Tabel</strong></li> 
     <li>De volgende kolommen weergeven: <strong>Gebeurtenislabel | Totaal aantal gebeurtenissen | Gebruikers</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (exact overeenkomend): RTP-Campaigns</strong><br><strong>[alleen weergeven] Gebeurtenisactie (exact overeenkomend): indruk</strong><strong>[niet tonen] Gebeurtenislabel (met): Aantal</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a48.png" data-linked-resource-id="7504269" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Naam: <strong>Klikken door CTA</strong></li> 
     <li>Type: <strong>Tabel</strong></li> 
     <li>De volgende kolommen weergeven: <strong>Gebeurtenislabel | Totaal aantal gebeurtenissen | Gebruikers</strong></li> 
     <li>Filters:<br><strong>[alleen weergeven] Gebeurteniscategorie (exact overeenkomend): RTP-Campaigns</strong><br><strong>[alleen weergeven] Gebeurtenisactie (exact overeenkomend): klikken</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a43-3a4.png" data-linked-resource-id="7504270" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[RTP integreren met Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
>
>[Aangepaste RTP-rapporten in Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
