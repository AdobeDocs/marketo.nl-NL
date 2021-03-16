---
unique-page-id: 15695924
description: Accountprofilering, rangschikking en afstemming - Marketo Docs - Productdocumentatie
title: Volgorde en afstemming van accountprofielen
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---


# Volgorde en afstemming van accountprofielen {#account-profiling-ranking-and-tuning}

Accountprofilering identificeert uw ideale klantprofiel (ICP), rangschikt bedrijven in uw database op basis van het ICP en voegt gegevens uit de ICP-indicator toe aan accounts die worden gepromoot als benoemde accounts.

## Modelresultaten {#model-results}

Alle bekende accounts zijn uitgesplitst naar rang. A is de hoogste graad, D is de laagste.

![](assets/results.png)

We raden u aan om het selectievakje Automatisch bevorderen in te schakelen, maar dit bespaart u veel tijd. Nochtans, als u door elk rekening wilt gaan en [voeg hen manueel ](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md#discover-crm-accounts) toe, verlaat eenvoudig de doos ongecontroleerd.

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

**Indicatorcategorieën**

<table> 
 <tbody> 
  <tr> 
   <td><strong>Compatibiliteit</strong></td> 
   <td> 
    <div>
      Certificeringen, op naleving betrekking hebbende posities/huur. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Bewerkingen</strong></td> 
   <td> 
    <div>
      Aan activiteiten gerelateerde posities/huur. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>HR</strong></td> 
   <td> 
    <div>
      HR- of loonsoftware, HR-gerelateerde posities/huur.
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Engineering</strong></td> 
   <td> 
    <div>
      Technologieën, raamwerken, met engineering verband houdende posities/huur. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Verkoop</strong></td> 
   <td> 
    <div>
      Oplossingen en software voor verkoop, verkoopgerelateerde posities/huur. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Intentie</strong></td> 
   <td> 
    <div>
      Intentie-indicatoren. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>IT</strong></td> 
   <td> 
    <div>
      Hardware- en softwareoplossingen, technologieën, IT-gerelateerde posities/huur.
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Financiën</strong></td> 
   <td> 
    <div>
      Financieringssoftware, financiële posities/huur. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Marketing</strong></td> 
   <td> 
    <div>
      Marketing technologieën en software, marketinggerelateerde posities/huur. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Zakelijk</strong></td> 
   <td> 
    <div>
      Forbes or Inc aanbiedingen of business partnership. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Klantervaring en -relaties</strong></td> 
   <td> 
    <div>
      Het succes van de klant en de posities/de huur van klantenverhoudingen.
    </div></td> 
  </tr> 
 </tbody> 
</table>

Houd de muisaanwijzer boven de knopinfo voor een beschrijving van elke kolom.

![](assets/tool-tip.png)

Klik Add ICP Indicator drop-down om extra indicatoren in uw model op te nemen.

![](assets/add-icp.png)

Als u het vak Exporteren inschakelt, kunt u de ICP-indicator op de pagina met gegevens over benoemde accounts zien en de geselecteerde ICP-indicator gebruiken als beperkingen in [benoemde accountfilters](/help/marketo/product-docs/target-account-management/engage/account-filters.md).

![](assets/export.png)

>[!NOTE]
>
>ICP-indicatoren worden opgenomen als beperkingen in **Lid van Benoemde account** Filters en Triggers.

Het Gewicht van de indicator is wat het niveau van belang controleert elke indicator in uw model ontvangt.

![](assets/weightage.png)

Klik op Model vernieuwen om deze wijzigingen van kracht te laten worden.

![](assets/refresh-button.png)

Wanneer u klaar bent met het stemmen van uw model (nadat u het verfrist), ga terug naar het Modellusje van Resultaten en klik **sparen &amp; toepassen Ranks**.

![](assets/ranks.png)
