---
description: OP-Deliverability Management - Marketo Docs - Productdocumentatie
title: OP-Deliverability Management
hide: true
hidefromtoc: true
feature: Programs
source-git-commit: 6b54fe2830200c6673559a257065248390c6d212
workflow-type: tm+mt
source-wordcount: '261'
ht-degree: 0%

---

# OP-Deliverability Management {#op-deliverability-management}

Dit is een voorbeeld van best practices voor het beheer van de leveringszekerheid met behulp van een standaardprogramma voor Marketo&#39;s Engage, om de huidige staat van e-maillevering te beoordelen en chronische stormen en non-responders te beheren.

>[!NOTE]
>
>Vereist een aangepast tekenreeksveld &quot;Reden voor marketingonderbreking&quot; om te importeren. [Meer informatie](https://nation.marketo.com/community/product_and_support/support_solutions/blog/2016/04/18/how-to-monitor-deliverability-using-marketo){target="_blank"}.

Voor verdere strategische hulp of hulp die een programma aanpast, gelieve het Team van de Rekening van de Adobe te contacteren of te bezoeken [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} pagina.

## Kanaaloverzicht {#channel-summary}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Kanaal</th> 
   <th>Lidmaatschapsstatus</th>
   <th>Analysegedrag</th>
   <th>Programmatype</th>
  </tr> 
  <tr> 
   <td>Operationeel</td> 
   <td>01-Lid</td>
   <td>Operationeel</td>
   <td>Standaard</td>
  </tr>
 </tbody> 
</table>

## Vereiste velden {#prerequisite-fields}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Type</th> 
   <th>Vriendelijke naam</th>
   <th>API-naam</th>
  </tr>
  <tr> 
   <td>String</td> 
   <td>Reden voor schorsing van de verkoop</td>
   <td>MarketingSuspendedReason</td>
  </tr>
 </tbody> 
</table>

## Het programma bevat de volgende elementen {#program-contains-the-following-assets}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Type</th> 
   <th>Sjabloonnaam</th>
   <th>Elementnaam</th>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Marketing Suspend Chronic Non-Responders</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Marketingonderbreking van chronische blokkerende e-mails</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>"E-mail ongeldig" opnieuw instellen na e-mailupdate</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>"Marketing opgeschort" opnieuw instellen na e-mailupdate</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Beheren</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Controleren</td>
  </tr>
 </tbody> 
</table>

![](assets/op-deliverability-management-1.png)

## Conflictregels {#conflict-rules}

* **Programmatags**
   * Tags maken in dit abonnement - _Aanbevolen_
   * Negeren

* **Landingspagina-sjabloon met dezelfde naam**
   * Oorspronkelijke sjabloon kopiëren - _Aanbevolen_
   * Doelsjabloon gebruiken

* **Afbeeldingen met dezelfde naam**
   * Beide bestanden behouden - _Aanbevolen_
   * Item in dit abonnement vervangen

* **E-mailsjablonen met dezelfde naam**
   * Beide sjablonen behouden - _Aanbevolen_
   * Bestaande sjabloon vervangen

## Aanbevolen procedures {#best-practices}

* Elke gebouwde campagne moet een voorbeeld zijn op de best practices en niet specifiek voor uw gebruiksgevallen. Herinner me om de Slimme Campagnes bij te werken om uw specifieke pijnpunten en gegevensuitdagingen te richten.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.
