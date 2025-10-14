---
description: OP-Deliverability Management - Marketo Docs - Productdocumentatie
title: OP-Deliverability Management
feature: Programs
exl-id: 7b9bc9ee-65f4-4938-8598-6f8543042159
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '248'
ht-degree: 0%

---

# OP-Deliverability Management {#op-deliverability-management}

Dit is een voorbeeld van workflows voor het beheer van de leveringszekerheid die gebruikmaken van een Marketo Engage Default Program, om de huidige staat van e-maillevering te beoordelen en chronische hindernissen en non-responders te beheren.

>[!NOTE]
>
>Vereist een aangepast tekenreeksveld &quot;Reden voor marketingonderbreking&quot; om te importeren. [&#x200B; leer meer &#x200B;](https://nation.marketo.com/community/product_and_support/support_solutions/blog/2016/04/18/how-to-monitor-deliverability-using-marketo){target="_blank"}.

Voor verdere strategiehulp of hulp die een programma aanpassen, gelieve te contacteren het Team van de Rekening van Adobe of de [&#x200B; Adobe Professional Services &#x200B;](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} pagina te bezoeken.

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

## Het programma bevat de volgende Assets {#program-contains-the-following-assets}

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

* **de Markeringen van het Programma**
   * Creeer markeringen in dit abonnement - _Geadviseerde_
   * Negeren

* **het Bestaan malplaatje van de Pagina met de zelfde naam**
   * Origineel malplaatje van het exemplaar - _geadviseerde_
   * Doelsjabloon gebruiken

* **Beelden met de zelfde naam**
   * Houd beide dossiers - _geadviseerde_
   * Item in dit abonnement vervangen

* **E-mailmalplaatjes met de zelfde naam**
   * Houd beide malplaatjes - _geadviseerde_
   * Bestaande sjabloon vervangen

## Aanbevolen procedures {#best-practices}

* Elke gebouwde campagne moet een voorbeeld zijn op de best practices en niet specifiek voor uw gebruiksgevallen. Herinner me om de Slimme Campagnes bij te werken om uw specifieke pijnpunten en gegevensuitdagingen te richten.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.
