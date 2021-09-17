---
description: Dialoogvensters - Marketo Docs - Productdocumentatie
title: Dialoogvensters
hide: true
hidefromtoc: true
source-git-commit: c46902686f1d5af63a51f5eaae2dc0e6afe99629
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---

# Dialoogvensters {#dialogues}

Dialogen zijn de specifieke praatjegesprekken u opstelling. Ze kunnen worden aangepast door te kijken, en wat er wordt gezegd en wie het ziet.

## Een nieuw dialoogvenster maken {#create-a-new-dialogue}

1. Klik **Dialoogvensters**.

PICC

1. Klik op de knop **Nieuw maken**.

PICC

1. Voer een naam in (beschrijving is optioneel), stel het prioriteitsniveau in en klik op **Opslaan**.

PICC

>[!NOTE]
>
>PRIORITAIR NIVEAU VERKLAREN

## Criteria voor het publiek {#audience-criteria}

Net als in Marketo Smart Lists kunt u met de kenmerken Audience Criteria (criteria voor doelgroepen) een doelgroep definiëren.

Er zijn verschillende kenmerken waaruit u kunt kiezen. In dit voorbeeld kiezen wij Loodstaat _is_ Californië en de Grootte _is groter dan_ 50.

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
>Het gebruiken van een asterisk doet dienst als vangst-all wilkaart. Zo `https://*.website.com` zou de dialoog op elke pagina van de plaats, met inbegrip van subdomeinen (bijvoorbeeld plaatsen: support.website.com). En `https://website.com/folder/*` zou het dialoogvenster op elke HTML-pagina in de volgende map plaatsen (bijvoorbeeld: in dit geval is de map &quot; sport &quot; , dus : website.com/sports/baseball.html, website.com/sports/football.html, enz.).
