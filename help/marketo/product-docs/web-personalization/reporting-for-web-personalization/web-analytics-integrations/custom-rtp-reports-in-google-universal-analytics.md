---
unique-page-id: 7504218
description: Aangepaste RTP-rapporten in Google Universal Analytics - Marketo Docs - Productdocumentatie
title: Aangepaste RTP-rapporten in Google Universal Analytics
exl-id: c8b1e653-03b8-48bc-b80d-3e6cdf3485c3
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '362'
ht-degree: 1%

---

# Aangepaste RTP-rapporten in Google Universal Analytics {#custom-rtp-reports-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[&#x200B; integreer RTP met de Universele Analytics van Google &#x200B;](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

In dit artikel wordt uitgelegd hoe u aangepaste RTP-rapporten instelt voor Google Universal Analytics (GUA).  De gegevens die van RTP naar GUA worden verzonden kunnen opstelling als twee afzonderlijke geroepen douanerapporten zijn:

* RTP B2B
* RTP-betrokkenheid

## Een [!UICONTROL Custom Report] instellen {#setting-up-a-custom-report}

1. Meld u aan bij Google Analytics.

1. Klik op **[!UICONTROL Customization]** in het bovenste menu.

1. Klik op **[!UICONTROL New Custom Report]**.

![](assets/image2015-3-22-16-3a10-3a48.png)

## RTP B2B-rapport {#rtp-b-b-report}

1. Noem het rapport **RTP B2B- Rapport**.

1. Geef het eerste tabblad een naam **[!UICONTROL Industry]** .

>[!NOTE]
>
>U **zult dit lusje** dupliceren en zult extra gelijkaardige degenen - stap 5) creëren

1. Selecteer het rapporttype **[!UICONTROL Explorer]** .

   ![](assets/image2015-3-22-16-3a15-3a25.png)

1. Selecteer in de sectie **[!UICONTROL Metric Groups]** de maatstaven die relevant zijn voor uw bedrijf.

   a. Wij bevelen het volgende aan:

   ![](assets/image2015-3-22-16-3a16-3a40.png)

1. Dit tabblad 4 keer dupliceren en een naam geven:

   1. **Industrie**
   1. **Groep**
   1. **Categorie**
   1. **ABM**
   1. **Organisaties**

   ![](assets/image2015-3-22-16-3a17-3a41.png)

1. In de **sectie van de Boor van Dimension** plaatst de relevante dimensies voor elk lusje zoals hieronder.

<table>
 <thead>
  <tr>
   <th>
    <div>
      Tabnaam
    </div></th>
   <th>
    <div>
      Dimension Drill downs
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

1. Stel geen filters in en stel dit rapport in op beschikbaar voor **[!UICONTROL All Web Site Data]** (of wijzig indien van toepassing voor specifieke analytische account).

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-3-22-16-3a21-3a23.png)

## RTP-betrokkenheidsrapport {#rtp-engagement-report}

1. Noem het rapport **RTP Rapport van de Betrokkenheid**.

1. Stel de eerste tabnaam in op **[!UICONTROL All Engagement]** .

>[!NOTE]
>
>U dupliceert dit tabblad en maakt aanvullende, vergelijkbare tabbladen (stap 5)

1. Selecteer het rapporttype **[!UICONTROL Explorer]** .

   ![](assets/image2015-3-22-16-3a23-3a36.png)

1. Selecteer in de sectie [!UICONTROL Metric Groups] de maatstaven die relevant zijn voor uw bedrijf. Hier volgt een aanbeveling:

   ![](assets/image2015-3-22-16-3a24-3a57.png)

1. Dit tabblad 4 keer dupliceren en een naam geven:

   1. **Al Betrokkenheid**
   1. **Betrokkenheid door Industrie**
   1. **Betrokkenheid door Groep**
   1. **Betrokkenheid door Categorie**
   1. **Betrokkenheid door ABM**

   ![](assets/image2015-3-22-16-3a26-3a21.png)

1. In de **2&rbrace; sectie van de Boor van Dimension** plaatst de relevante dimensies voor elk lusje zoals hieronder:

<table>
 <thead>
  <tr>
   <th>
    <div>
      Tabnaam
    </div></th>
   <th>
    <div>
      Dimension Drill downs
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
   <td><p><span class="uicontrol">Gebeurteniscategorie</span></p></td>
   <td>Regex</td>
   <td>RTP-Campagnes|RTP-Aanbevelingen|RTP-Segmenten</td>
   <td colspan="1">Hiermee filtert u alle andere aangepaste gebeurtenissen die niet gerelateerd zijn aan RTP</td>
  </tr>
  <tr>
   <td>Uitsluiten</td>
   <td><span class="uicontrol">Gebeurtenislabel</span></td>
   <td>Regex</td>
   <td>Aantal</td>
   <td colspan="1">Hiermee kunt u vanuit uw rapportencampagne filteren met # in de naam van de campagne</td>
  </tr>
 </tbody>
</table>

1. Stel dit rapport in op beschikbaar voor **[!UICONTROL All Web Site Data]** (of wijzig indien nodig).

   ![](assets/image2015-3-22-16-3a29-3a5.png)

1. Klik op **[!UICONTROL Save]**.

![](assets/image2015-3-22-16-3a30-3a0.png)

>[!MORELIKETHIS]
>
>[&#x200B; integreer RTP met de Universele Analytics van Google &#x200B;](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)
>
>[&#x200B; de Dashboards van de Douane RTP in Universele Analytics van Google &#x200B;](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-dashboards-in-google-universal-analytics.md)
