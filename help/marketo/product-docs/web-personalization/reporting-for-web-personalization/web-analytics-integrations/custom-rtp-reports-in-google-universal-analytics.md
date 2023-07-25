---
unique-page-id: 7504218
description: Aangepaste RTP-rapporten in Google Universal Analytics - Marketo Docs - Productdocumentatie
title: Aangepaste RTP-rapporten in Google Universal Analytics
exl-id: c8b1e653-03b8-48bc-b80d-3e6cdf3485c3
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '386'
ht-degree: 0%

---

# Aangepaste RTP-rapporten in Google Universal Analytics {#custom-rtp-reports-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[RTP integreren met Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

In dit artikel wordt uitgelegd hoe u aangepaste RTP-rapporten instelt voor Google Universal Analytics (GUA).  De gegevens die van RTP naar GUA worden verzonden kunnen opstelling als twee afzonderlijke geroepen douanerapporten zijn:

* RTP B2B
* RTP-betrokkenheid

## Een aangepast rapport instellen {#setting-up-a-custom-report}

1. Meld u aan bij Google Analytics.

1. Klikken op **Aanpassing** in het bovenste menu.

1. Klikken **+Nieuw aangepast rapport**.

![](assets/image2015-3-22-16-3a10-3a48.png)

## RTP B2B-rapport {#rtp-b-b-report}

1. Geef een naam op voor het rapport **RTP B2B-rapport**.

1. Geef de naam van het eerste tabblad **Industrie**.

>[!NOTE]
>
>U zult **Dit tabblad dupliceren** en maak aanvullende vergelijkbare versies - stap 5)

1. Selecteer **Verkenner** rapporttype.

   ![](assets/image2015-3-22-16-3a15-3a25.png)

1. In de **Metrische groepen** , selecteert u de maatstaven die relevant zijn voor uw bedrijf.

   a. We raden het volgende aan:

   ![](assets/image2015-3-22-16-3a16-3a40.png)

1. Dit tabblad 4 keer dupliceren en een naam geven:

   1. **Marktsegment**
   1. **Groep**
   1. **Categorie**
   1. **ABM**
   1. **Organisaties**

   ![](assets/image2015-3-22-16-3a17-3a41.png)

1. In de **Dimension boor downs** in de sectie worden de relevante afmetingen voor elk tabblad hieronder vastgesteld.

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Tabnaam 
    </div></th> 
   <th> 
    <div>
      Dimension boor downs
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Marktsegment</td> 
   <td><img src="assets/1.png" data-linked-resource-id="7514675" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Groep</td> 
   <td><img src="assets/2.png" data-linked-resource-id="7514674" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Categorie</td> 
   <td><img src="assets/3.png" data-linked-resource-id="7514673" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>ABM</td> 
   <td><img src="assets/5.png" data-linked-resource-id="7514677" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Organisaties</td> 
   <td><img src="assets/5.png" data-linked-resource-id="7514677" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
 </tbody> 
</table>

1. Stel geen filters in en stel dit rapport in op beschikbaar voor **Alle websitegegevens** (of, indien van toepassing, wijzigen voor een specifieke analytische rekening).

1. Klikken **Opslaan**.

   ![](assets/image2015-3-22-16-3a21-3a23.png)

## RTP-betrokkenheidsrapport {#rtp-engagement-report}

1. Geef een naam op voor het rapport **RTP-betrokkenheidsrapport**.

1. De eerste tabnaam instellen op **Alle betrokkenheid**.

>[!NOTE]
>
>U dupliceert dit tabblad en maakt aanvullende, vergelijkbare tabbladen (stap 5)

1. Selecteer **Verkenner** rapporttype.

   ![](assets/image2015-3-22-16-3a23-3a36.png)

1. Selecteer in de sectie Metrische groepen de maatstaven die relevant zijn voor uw bedrijf. Hier volgt een aanbeveling:

   ![](assets/image2015-3-22-16-3a24-3a57.png)

1. Dit tabblad 4 keer dupliceren en een naam geven:

   1. **Alle betrokkenheid**
   1. **Betrokkenheid van de industrie**
   1. **Betrokkenheid per groep**
   1. **Betrokkenheid per rubriek**
   1. **Betrokkenheid van ABM**

   ![](assets/image2015-3-22-16-3a26-3a21.png)

1. In de **Dimension boor downs** de relevante afmetingen voor elk tabblad als volgt instellen:

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Tabnaam 
    </div></th> 
   <th> 
    <div>
      Dimension boor downs 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Alle betrokkenheid</td> 
   <td><img src="assets/a.png" data-linked-resource-id="7514683" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Betrokkenheid van ABM</td> 
   <td><img width="277" src="assets/4.png" data-linked-resource-id="7514678" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Betrokkenheid per rubriek</td> 
   <td><img src="assets/a.png" data-linked-resource-id="7514683" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Betrokkenheid per groep</td> 
   <td><img src="assets/c.png" data-linked-resource-id="7514681" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Betrokkenheid van de industrie</td> 
   <td><img src="assets/b.png" data-linked-resource-id="7514682" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
 </tbody> 
</table>

1. Stel de volgende filters in:

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Inc/Exc 
    </div></th> 
   <th> 
    <div>
      Veld 
    </div></th> 
   <th> 
    <div>
      Type afstemmen 
    </div></th> 
   <th> 
    <div>
      Waarden 
    </div></th> 
   <th colspan="1"> 
    <div>
      Opmerkingen 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td><p>Inclusief</p></td> 
   <td><p>Gebeurteniscategorie</p></td> 
   <td>Regex</td> 
   <td>RTP-Campagnes|RTP-Recommendations|RTP-Segmenten</td> 
   <td colspan="1">Hiermee filtert u alle andere aangepaste gebeurtenissen die niet gerelateerd zijn aan RTP</td> 
  </tr> 
  <tr> 
   <td>Uitsluiten</td> 
   <td>Gebeurtenislabel</td> 
   <td>Regex</td> 
   <td>Aantal</td> 
   <td colspan="1">Hiermee kunt u vanuit uw rapportencampagne filteren met # in de naam van de campagne</td> 
  </tr> 
 </tbody> 
</table>

1. Dit rapport beschikbaar stellen voor **Alle websitegegevens** (of indien nodig wijzigen).

   ![](assets/image2015-3-22-16-3a29-3a5.png)

1. Klikken **Opslaan**.

![](assets/image2015-3-22-16-3a30-3a0.png)

>[!MORELIKETHIS]
>
>[RTP integreren met Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)
>
>[Aangepaste RTP-dashboards in Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-dashboards-in-google-universal-analytics.md)
