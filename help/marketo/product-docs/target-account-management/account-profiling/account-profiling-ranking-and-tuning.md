---
unique-page-id: 15695924
description: Volgorde en afstemming van accountprofielen - Marketo-documenten - productdocumentatie
title: Volgorde en afstemming van accountprofielen
exl-id: 9c5d0a03-0ebe-43cc-95ef-faab19a7f673
feature: Target Account Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 0%

---

# Volgorde en afstemming van accountprofielen {#account-profiling-ranking-and-tuning}

Accountprofilering identificeert uw Ideal Customer Profile (ICP), plaatst bedrijven in uw database op basis van het ICP en voegt gegevens uit de ICP-indicator toe aan accounts die worden gepromoot als [!UICONTROL Named Accounts] .

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
   <td><strong><span class="uicontrol">Rang</span></strong></td>
   <td>
    <div>
      Accountnummer gebaseerd op het ideale klantprofiel. A is het best geschikt, D is het minst geschikt.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Propensiteit</span></strong></td>
   <td>
    <div>
      Geschatte stijging van de omrekeningskoers in vergelijking met een niet op ICP gebaseerde selectie van rekeningen.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Rekeningen (%)</span></strong></td>
   <td>
    <div>
      Percentage rekeningen in modelinput die deze rang hebben.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">% van modelbasis</span></strong></td>
   <td>
    <div>
      Percentage van de rekeningen op modelbasis met deze rang.
    </div></td>
  </tr>
 </tbody>
</table>

## Afstemmen model {#model-tuning}

Klik op de knop **[!UICONTROL Tune Model]** op het tabblad Model.

![](assets/two.png)

Er zijn verschillende tabbladen waaruit u kunt kiezen, zodat u deze grondig kunt aanpassen.

![](assets/tuning-page.png)

**Categorieën van de Indicator**

<table>
 <tbody>
  <tr>
   <td><strong><span class="uicontrol">Naleving</span></strong></td>
   <td>
    <div>
      Certificeringen, op naleving betrekking hebbende posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Bewerkingen</span></strong></td>
   <td>
    <div>
      Aan activiteiten gerelateerde posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">HR</span></strong></td>
   <td>
    <div>
      HR- of loonsoftware, HR-gerelateerde posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Engineering</span></strong></td>
   <td>
    <div>
      Technologieën, raamwerken, met engineering verband houdende posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Verkoop</span></strong></td>
   <td>
    <div>
      Oplossingen en software voor verkoop, verkoopgerelateerde posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Intentie</span></strong></td>
   <td>
    <div>
      Intentie-indicatoren.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">IT</span></strong></td>
   <td>
    <div>
      Hardware- en softwareoplossingen, technologieën, IT-gerelateerde posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Financiën</span></strong></td>
   <td>
    <div>
      Financieringssoftware, financiële posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Marketing</span></strong></td>
   <td>
    <div>
      Marketing technologieën en software, marketinggerelateerde posities/huur.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Bedrijven</span></strong></td>
   <td>
    <div>
      Forbes or Inc aanbiedingen of business partnership.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">Klantervaring en -relaties</span></strong></td>
   <td>
    <div>
      Het succes van de klant en de posities/de huur van klantenverhoudingen.
    </div></td>
  </tr>
 </tbody>
</table>

Houd de cursor boven de knopinfo voor een beschrijving van elke kolom.

![](assets/tool-tip.png)

Klik op de vervolgkeuzelijst [!UICONTROL Add ICP Indicator] om extra indicatoren in te voegen in uw model.

![](assets/add-icp.png)

Het controleren van [!UICONTROL Export] doos staat u toe om de indicator ICP op de [!UICONTROL Named Account] detailspagina te zien, evenals de geselecteerde indicator ICP als beperkingen in [ genoemd rekeningsfilters ](/help/marketo/product-docs/target-account-management/engage/account-filters.md) te gebruiken.

![](assets/export.png)

>[!NOTE]
>
>ICP-indicatoren worden opgenomen als beperkingen in **[!UICONTROL Member of Named Account]** Filters en Triggers.

[!UICONTROL Indicator Weightage] bepaalt het belang dat elke indicator in uw model krijgt.

![](assets/weightage.png)

Klik op **[!UICONTROL Refresh Model]** om deze wijzigingen van kracht te laten worden.

![](assets/refresh-button.png)

Wanneer u klaar bent met het aanpassen van uw model (nadat u het hebt vernieuwd), ga terug naar het tabblad Modelresultaten en klik op **[!UICONTROL Save & Apply Ranks]** .

![](assets/ranks.png)
