---
unique-page-id: 15695924
description: Accountprofilering, rangschikking en afstemming - Marketo Docs - Productdocumentatie
title: Volgorde en afstemming van accountprofielen
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---


# Volgorde en afstemming van accountprofielen {#account-profiling-ranking-and-tuning}

Accountprofilering identificeert uw ideale klantprofiel (ICP), rangschikt bedrijven in uw database op basis van het ICP en voegt gegevens uit de ICP-indicator toe aan accounts die worden gepromoot als benoemde accounts.

## Modelresultaten {#model-results}

Alle bekende accounts zijn uitgesplitst naar rang. A is de hoogste graad, D is de laagste.

![](assets/results.png)

We raden u aan om het selectievakje Automatisch bevorderen in te schakelen, maar dit bespaart u veel tijd. Als u echter door elk account wilt gaan en deze handmatig [wilt](http://docs.marketo.com/display/DOCS/Discover+Accounts#DiscoverAccounts-DiscoverCRMAccounts)toevoegen, laat u het selectievakje uitgeschakeld.

<table> 
 <tbody> 
  <tr> 
   <td><strong>Rang</strong></td> 
   <td> 
    <div>
      Accountnummer gebaseerd op het ideale klantprofiel. A is het best geschikt, D is het minst geschikt. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Propensiteit</strong></td> 
   <td> 
    <div>
      Geschatte stijging van de omrekeningskoers in vergelijking met een niet op ICP gebaseerde selectie van rekeningen. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Rekeningen (%)</strong></td> 
   <td> 
    <div>
      Percentage rekeningen in modelinput die deze rang hebben. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>% van modelbasis</strong></td> 
   <td> 
    <div>
      Percentage van de rekeningen op modelbasis met deze rang. 
    </div></td> 
  </tr> 
 </tbody> 
</table>

## Afstemmen model {#model-tuning}

Klik op de knop Afstemmen op het tabblad Model.

![](assets/two.png)

U kunt uit verschillende tabbladen kiezen, zodat u deze grondig kunt aanpassen.

![](assets/tuning-page.png)

Indicatorcategorieën

| **Compatibiliteit** | Certificeringen, op naleving betrekking hebbende posities/huur. |
|---|---|
| **Bewerkingen** | Aan activiteiten gerelateerde posities/huur. |
| **HR** | HR- of loonsoftware, HR-gerelateerde posities/huur. |
| **Engineering** | Technologieën, raamwerken, met engineering verband houdende posities/huur. |
| **Verkoop** | Oplossingen en software voor verkoop, verkoopgerelateerde posities/huur. |
| **Intentie** | Intentie-indicatoren. |
| **IT** | Hardware- en softwareoplossingen, technologieën, IT-gerelateerde posities/huur. |
| **Financiën** | Financieringssoftware, financiële posities/huur. |
| **Marketing** | Marketing technologieën en software, marketinggerelateerde posities/huur. |
| **Zakelijk** | Forbes or Inc aanbiedingen of business partnership. |
| **Klantervaring en -relaties** | Het succes van de klant en de posities/de huur van klantenverhoudingen. |

Houd de muisaanwijzer boven de knopinfo voor een beschrijving van elke kolom.

![](assets/tool-tip.png)

Klik Add ICP Indicator drop-down om extra indicatoren in uw model op te nemen.

![](assets/add-icp.png)

Als u het vak Exporteren inschakelt, kunt u de ICP-indicator op de pagina met details van de benoemde account zien en de geselecteerde ICP-indicator gebruiken als beperkingen in [benoemde accountfilters](http://docs.marketo.com/display/DOCS/Account+Filters).

![](assets/export.png)

>[!NOTE]
>
>ICP-indicatoren worden opgenomen als beperkingen in **Lid van Filters en triggers voor benoemde accounts** .

Het Gewicht van de indicator is wat het niveau van belang controleert elke indicator in uw model ontvangt.

![](assets/weightage.png)

Klik op Model vernieuwen om deze wijzigingen van kracht te laten worden.

![](assets/refresh-button.png)

Wanneer u klaar bent met het aanpassen van uw model (nadat u het vernieuwt), ga terug naar het lusje van de Resultaten Model en klik **sparen &amp; past Spaties** toe.

![](assets/ranks.png)

