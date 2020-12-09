---
unique-page-id: 7504218
description: Aangepaste RTP-rapporten in Google Universal Analytics - Marketo Docs - Productdocumentatie
title: Aangepaste RTP-rapporten in Google Universal Analytics
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 0%

---


# Aangepaste RTP-rapporten in Google Universal Analytics {#custom-rtp-reports-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[RTP integreren met Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)

In dit artikel wordt uitgelegd hoe u aangepaste RTP-rapporten voor Google Universal Analytics (GUA) kunt instellen.  De gegevens die van RTP naar GUA worden verzonden kunnen opstelling als twee afzonderlijke geroepen douanerapporten zijn:

* RTP B2B
* RTP-betrokkenheid

## Een aangepast rapport instellen {#setting-up-a-custom-report}

1. Meld u aan bij Google Analytics.
1. Klik op **Aanpassing **in het hoogste menu.
1. Klik op **+Nieuw aangepast rapport.**

** ![](assets/image2015-3-22-16-3a10-3a48.png)

**

## RTP B2B-rapport {#rtp-b-b-report}

1. Geef het rapport de naam **RTP B2B Report**.
1. Naam van het eerste tabblad **Industrie **

   1. (Opmerking: u gaat dit tabblad **** dupliceren en aanvullende vergelijkbare tabbladen maken (stap 5)

1. Selecteer het rapporttype** Verkenner**.\
   ** ![](assets/image2015-3-22-16-3a15-3a25.png)

   **

1. Selecteer in de sectie **Metrische groepen** de maatstaven die relevant zijn voor uw bedrijf.

   1. We raden het volgende aan:\
      ** ![](assets/image2015-3-22-16-3a16-3a40.png)

      **

1. Dit tabblad 4 keer dupliceren en een naam geven:

   1. **Industrie**
   1. **Groep**
   1. **Categorie**
   1. **ABM**
   1. **Organisaties**

   ![](assets/image2015-3-22-16-3a17-3a41.png)

1. In de sectie **Dimension boor** stelt u de relevante afmetingen voor elk tabblad in, zoals hieronder.

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
   <td>Industrie</td> 
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

1. Stel geen filters in en stel dit rapport in op beschikbaar voor **Alle gegevens van de website ** (of wijzig indien van toepassing voor de specifieke account Analytics).
1. Klik op **Opslaan**.\
   ![](assets/image2015-3-22-16-3a21-3a23.png)

## RTP-betrokkenheidsrapport {#rtp-engagement-report}

1. Geef het rapport de naam **RTP Engagement Report.**
1. De eerste tabnaam instellen op **Alle betrokkenheid**

   1. (Opmerking: u gaat dit tabblad dupliceren en aanvullende vergelijkbare tabbladen maken (stap 5)

1. Selecteer het rapporttype van de **Ontdekkingsreiziger** .\
   ![](assets/image2015-3-22-16-3a23-3a36.png)

1. Selecteer in de sectie Metrische groepen de maatstaven die relevant zijn voor uw bedrijf. Hier volgt een aanbeveling:\
   ![](assets/image2015-3-22-16-3a24-3a57.png)

1. Dit tabblad 4 keer dupliceren en een naam geven:

   1. **Alle betrokkenheid**
   1. **Betrokkenheid van de industrie**
   1. **Betrokkenheid per groep**
   1. **Betrokkenheid per rubriek**
   1. **Betrokkenheid van ABM**

   ** ![](assets/image2015-3-22-16-3a26-3a21.png)\**

1. In de sectie **Dimension boor** stelt u de relevante afmetingen voor elk tabblad als volgt in:

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
1. 

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
   <td>#</td> 
   <td colspan="1">Hiermee kunt u vanuit uw rapportencampagne filteren met # in de naam van de campagne</td> 
  </tr> 
 </tbody> 
</table>

1. Stel dit rapport in op beschikbaar voor **Alle gegevens van de website **(of wijzig indien nodig)

   ![](assets/image2015-3-22-16-3a29-3a5.png)

1. Klik op **Opslaan**.

![](assets/image2015-3-22-16-3a30-3a0.png)

>[!NOTE]
>
>**Verwante artikelen**
>
>[RTP integreren met Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)
>
>[Aangepaste RTP-dashboards in Google Universal Analytics](custom-rtp-dashboards-in-google-universal-analytics.md)

