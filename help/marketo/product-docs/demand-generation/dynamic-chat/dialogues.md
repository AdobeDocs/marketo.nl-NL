---
description: Dialoogvensters - Marketo Docs - Productdocumentatie
title: Dialoogvensters
hide: true
hidefromtoc: true
source-git-commit: 50effc2aa1fc94251b4b75bec6dcc34bf3df8a2c
workflow-type: tm+mt
source-wordcount: '523'
ht-degree: 0%

---

# Dialoogvensters {#dialogues}

Dialogen zijn de individuele praatjegesprekken u opstelling. Leer hoe u ze visueel kunt aanpassen, kunt bepalen op welke pagina&#39;s ze worden weergegeven en kunt beslissen wat er wordt gezegd en wie het ziet.

## Een nieuw dialoogvenster maken {#create-a-new-dialogue}

1. Klik **Dialoogvensters**.

PICC

1. Klik op de knop **Nieuw maken**.

PICC

1. Voer een naam in (beschrijving is optioneel), stel het prioriteitsniveau in en klik op **Opslaan**.

PICC

>[!NOTE]
>
>Het prioriteitsniveau bepaalt waar het dialoogvenster in uw lijst wordt weergegeven (bijv. prioriteit = 1 betekent dat het helemaal bovenaan staat ) .

## Criteria voor het publiek {#audience-criteria}

Net als in Marketo Smart Lists kunt u met de kenmerken Audience Criteria (criteria voor doelgroepen) een doelgroep definiëren. U kunt bekende of onbekende leads als doel instellen met afgeleide, lead- of bedrijfskenmerken (of een combinatie hiervan).

Er zijn _veel_ kenmerkcombinaties om van te kiezen. In dit voorbeeld richten we ons op alle bekende leads in Californië die werken bij een bedrijf met meer dan 50 werknemers.

1. Pak de attributen van de Staat van de Lood en sleep het aan het recht.

PICC

1. _Standaard_ ingesteld op Isis. Typ in het veld Waarden selecteren de tekst CA (u kunt ook op de vervolgkeuzelijst klikken en in de lijst selecteren).

PICC

1. Pak de attributen van de Grootte van het Bedrijf en sleep het aan het recht.

PICC

1. Klik op de vervolgkeuzelijst met operatoren en selecteer Groter dan.

PICC

1. Typ 50 en klik ergens anders op het scherm om op te slaan.

PICC

HOE WORDT ANON LEADS VASTGELEGD

NOTA - misschien vermeld hoe de gevolgde werken/een gebruikscase tonen, leiden e-mail leeg is

## Groepen toevoegen {#add-groups}

U kunt ook kenmerken groeperen, voor het geval dat u alle kenmerken samen met &quot;een&quot; van een andere wilt hebben.

VOLTOOID

## Doel {#target}

Hier voert u de specifieke URL&#39;s in waarop u een specifiek dialoogvenster wilt weergeven.

Acceptabele indelingen:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>Het gebruiken van een asterisk doet dienst als vangst-all wilkaart. Zo zou `https://*.website.com` de dialoog op elke pagina van de plaats, met inbegrip van subdomeinen (bijvoorbeeld plaatsen: `support.website.com`). En `https://website.com/folder/*` zou het dialoogvenster op elke HTML-pagina in de volgende map plaatsen (bijvoorbeeld: in dit geval is de map &quot; sport &quot; , dus : website.com/sports/baseball.html, website.com/sports/football.html, enz.).

## Stream Designer {#stream-designer}

De stroomontwerper bevat verschillende kaarten u kunt toevoegen om het praatjegesprek te vormen.

<table>
 <tr>
  <td><strong>Bericht</strong></td>
  <td>Wordt gebruikt wanneer u een instructie wilt maken zonder reactie nodig (bijvoorbeeld: "Hoi! Alle items zijn vandaag 25% korting met code SAVE25").
</td>
 </tr>
 <tr>
  <td><strong>Vraag</strong></td>
  <td>Gebruik deze optie wanneer u een meerkeuzevraag wilt stellen, waarvan u de beschikbare antwoorden kunt opgeven (bijvoorbeeld: Welk type voertuig interesseert u? Reacties = SUV, Compact, Truck, enz.).</td>
 </tr>
 <tr>
  <td><strong>Gegevens vastleggen</strong></td>
  <td>Gebruik deze optie wanneer u gegevens wilt verzamelen. De drie velden waaruit u kunt kiezen zijn E-mailadres, Telefoonnummer en Tekst (zodat de bezoeker zijn eigen bericht kan schrijven).</td>
 </tr>
 <tr>
  <td><strong>Aanstellingsplanner</strong></td>
  <td>Biedt de bezoeker een kalender met beschikbare datums om een follow-up te plannen. De beschikbaarheid van de kalender wijst op [de volgende agent in lijn] (/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md#routing).</td>
 </tr>
 <tr>
  <td><strong>Doel</strong></td>
  <td>Dit is de enige kaart die bezoekers niet zullen zien. Het is aan u om te bepalen op welk punt een doel binnen de specifieke praatje wordt bereikt (bijvoorbeeld: Als u de e-mail van de bezoeker wilt verzamelen, plaatst u de Goal-kaart na Info Vastleggen in de Stroom).</td>
 </tr>
</table>

MOGELIJKE EIGEN SECTIE

ONDERSTAANDE VOORBEELD(EN) TONEN

## Rapporten {#reports}

Tekst
