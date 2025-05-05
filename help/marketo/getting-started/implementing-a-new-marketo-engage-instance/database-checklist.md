---
description: Opstelling de sectie van het Gegevensbestand voor uw nieuwe instantie van het Marketo Engage.
title: Aanbevolen werkwijzen voor nieuwe instanties - Controlelijst voor database
feature: Getting Started
exl-id: 996ea2db-a00c-48e5-97a8-00f869c261b1
source-git-commit: df8087dbaf2b621d0d877eba1c16f160ee9bf460
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 0%

---

# Aanbevolen werkwijzen voor nieuwe instanties: checklist database {#new-instance-best-practices-database-checklist}

De sectie van het Gegevensbestand is waar u de belangrijkste attributen van de mensen in uw geval zult vinden. Leer meer over de noodzakelijke stappen om door verschillende lijsten en segmentaties in uw Gegevensbestand te navigeren, evenals het beheren van personenverslagen.

Herinneren aan [checklists downloaden](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) en de voortgang volgen.

## Slimme systeemlijsten {#system-smart-lists}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Alle personen</td>
    <td><li>Bepaal het uitvoeren van een 1:1 synchronisatie met uw CRM of het toepassen van filters om te beperken wie zich van systeem aan systeem beweegt en wanneer.</li> 
    <li>Bekijk het totale aantal personen en verhandelbare personen in uw <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/database-dashboard.html?lang=nl-NL" target="_blank">Marketo Engage-database</a>.</li></td>
  </tr>
  <tr>
    <td>Lijst van gewezen personen</td>
    <td><li>Definieer de criteria voor lijst van gewezen personen. Voeg de domeinen van de concurrent aan uw <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.html?lang=nl-NL" target="_blank">lijst van gewezen personen</a> om te voorkomen dat ze een e-mail ontvangen.</li></td>
  </tr>
  <tr>
    <td>Marketing opgeschort</td>
    <td><li>Definiëren <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe#marketing-suspended" target="_blank">Marketing opgeschort</a> criteria.</li></td>
  </tr>
  <tr>
    <td>Verzonden e-mailadressen </td>
    <td><li>Definieer de criteria voor teruggestuurde e-mailadressen.</li>
    <li>Controleer de personen in de categorie 'Ongeldig e-mailadres' en bepaal of hun e-mails nodig zijn <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/hard-and-soft-bounces-in-email.html?lang=nl-NL" target="_blank">handmatig opnieuw instellen</a>.</li></td>
  </tr>
  <tr>
    <td>Mogelijke duplicaten</td>
    <td><li>Bekijk de personen in de lijst Mogelijke duplicaten.</li> 
    <li>Definieer uw dubbele beheerstrategie om te bepalen of u wilt <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.html?lang=nl-NL" target="_blank">personen handmatig samenvoegen</a>.</li>  
    <li>Als u een integratie van CRM hebt, bepaal een proces en een rekening voor <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people#effect-in-salesforce" target="_blank">het effect van het samenvoegen van leads in uw CRM</a>.</li></td>
  </tr>
  <tr>
    <td>Geen overnameprogramma</td>
    <td><li>Stel campagnes op in uw programmasjablonen waarin een overnameprogramma wordt ingesteld, vooral als u globale formulieren gebruikt.</li></td>
  </tr>
  <tr>
    <td>Mensen zonder abonnement</td>
    <td><li>Controleer uw criteria voor <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html?lang=nl-NL" target="_blank">Mensen zonder abonnement</a>.</li></td>
  </tr>
</tbody>
</table>

## Slimme lijsten groeperen {#group-smart-lists}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Slimme lijsten groeperen</td>
    <td><li>Houd er rekening mee dat u slimme lijsten voor groepen maakt, zodat er geen dubbele lijsten zijn.</li>
    <li>Houd de hoofdlijsten bij in de database.</li></td>
  </tr>
</tbody>
</table>

## Segmentatie {#segmentation}

<table>
<thead>
  <tr>
    <th style="width:21%">Gebied</th>
    <th style="width:79%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Segmentatie</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.html?lang=nl-NL" target="_blank">Segmenten maken</a> op basis van uw bedrijfsbehoeften. Elk abonnement is beperkt tot 20 segmentaties en 100 segmenten binnen elke segmentatie.</li></td>
  </tr>
</tbody>
</table>
