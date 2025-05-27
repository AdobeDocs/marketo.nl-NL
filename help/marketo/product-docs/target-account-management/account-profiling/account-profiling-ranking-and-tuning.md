---
unique-page-id: 15695924
description: Volgorde en afstemming van accountprofielen - Marketo-documenten - productdocumentatie
title: Volgorde en afstemming van accountprofielen
exl-id: 9c5d0a03-0ebe-43cc-95ef-faab19a7f673
feature: Target Account Management
source-git-commit: 2f978d814f4cf2d4d2ca9ead0c1a3e5c15430520
workflow-type: tm+mt
source-wordcount: '401'
ht-degree: 0%

---

# Volgorde en afstemming van accountprofielen {#account-profiling-ranking-and-tuning}

Accountprofilering identificeert uw ideale klantprofiel (ICP), rangschikt bedrijven in uw database op basis van het ICP en voegt gegevens uit de ICP-indicator toe aan accounts die worden gepromoot als benoemde accounts.

>[!IMPORTANT]
>
>Accountprofilering is vanaf 2025 niet meer beschikbaar voor nieuwe gebruikers. Het zal voor bestaande gebruikers blijven werken.

## Modelresultaten {#model-results}

Alle bekende accounts zijn uitgesplitst naar rang. A is de hoogste graad, D is de laagste.

![](assets/results.png)

We raden u aan om het selectievakje Automatisch bevorderen in te schakelen, maar dit bespaart u veel tijd. Nochtans, als u door elke rekening wilt gaan en [ hen manueel ](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md#discover-crm-accounts) toevoegen, verlaat eenvoudig de doos ongecontroleerd.

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

Er zijn verschillende tabbladen waaruit u kunt kiezen, zodat u deze grondig kunt aanpassen.

![](assets/tuning-page.png)

**Categorieën van de Indicator**

<table> 
 <tbody> 
  <tr> 
   <td><strong>Naleving</strong></td> 
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
   <td><strong>Bedrijven</strong></td> 
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

Houd de cursor boven de knopinfo voor een beschrijving van elke kolom.

![](assets/tool-tip.png)

Klik Add ICP Indicator drop-down om extra indicatoren in uw model op te nemen.

![](assets/add-icp.png)

Het controleren van de doos van de Uitvoer staat u toe om de indicator ICP op de Benoemde pagina van de Details van de Rekening te zien, evenals de geselecteerde indicator ICP als beperkingen in [ genoemd rekeningsfilters ](/help/marketo/product-docs/target-account-management/engage/account-filters.md) te gebruiken.

![](assets/export.png)

>[!NOTE]
>
>De indicatoren ICP zijn inbegrepen als beperkingen in **Lid van Benoemde Filters en Trekkers van de Rekening**.

Het Gewicht van de indicator is wat het niveau van belang controleert elke indicator in uw model ontvangt.

![](assets/weightage.png)

Klik op Model vernieuwen om deze wijzigingen van kracht te laten worden.

![](assets/refresh-button.png)

Wanneer u klaar bent het stemmen van uw model (nadat u het verfrist), ga terug naar het Modellusje van Resultaten en klik **sparen &amp; pas Spaties** toe.

![](assets/ranks.png)
