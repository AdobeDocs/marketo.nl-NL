---
description: Dialoogvensters - Marketo Docs - Productdocumentatie
title: Dialoogvensters
hide: true
hidefromtoc: true
source-git-commit: d915a51337f9dbbccc924fd8f7e69257be39f4ef
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Dialoogvensters {#dialogues}

Dialogen zijn individuele praatjegesprekken. Leer hoe u ze visueel kunt aanpassen, kunt bepalen op welke pagina&#39;s ze worden weergegeven en kunt beslissen wat er wordt gezegd en wie het ziet.

## Een nieuw dialoogvenster maken {#create-a-new-dialogue}

1. Klik **Dialoogvensters**.

   ![](assets/dialogues-1.png)

1. Klik op de knop **Nieuw maken**.

   ![](assets/dialogues-2.png)

1. Voer een naam in (beschrijving is optioneel), stel het prioriteitsniveau in en klik op **Opslaan**.

   ![](assets/dialogues-3.png)

>[!NOTE]
>
>Het prioriteitsniveau bepaalt waar het dialoogvenster in uw lijst wordt weergegeven (bijv. prioriteit 1 houdt in dat het op de top staat ) .

## Criteria voor het publiek {#audience-criteria}

Net als in Marketo Smart Lists kunt u met de kenmerken Audience Criteria (criteria voor doelgroepen) een doelgroep definiëren. U kunt bekende of onbekende leads als doel instellen met afgeleide, lead- of bedrijfskenmerken (of een combinatie hiervan).

**Bekende leads**

Er zijn _veel_ kenmerkcombinaties om van te kiezen. In dit voorbeeld richten we ons op alle **bekende leads** in Californië die werken bij een bedrijf met meer dan 50 werknemers.

1. Pak **Lead State** attributen en sleep het aan het recht.

   ![](assets/dialogues-4.png)

1. _Standaard_ ingesteld op Isis. Typ in het veld Waarden selecteren de tekst CA (u kunt ook op de vervolgkeuzelijst klikken en in de lijst selecteren).

   ![](assets/dialogues-5.png)

1. Pak **Bedrijfsomvang** attributen en sleep het aan waar het _een attribuut hier_ sleept en laat vallen.

   ![](assets/dialogues-6.png)

   >[!NOTE]
   >
   >U kunt ook een kenmerk kiezen door op het pictogram **+** te klikken.

1. Klik op de vervolgkeuzelijst met operatoren en selecteer **Groter dan**.

   ![](assets/dialogues-7.png)

1. Typ 50 en klik ergens anders op het scherm om op te slaan.

   ![](assets/dialogues-8.png)

**Anonieme leads**

Er is een gemakkelijke manier aan specifiek richt lood die nog niet in uw gegevensbestand zijn. In dit voorbeeld richten we ons op alle **anonieme leads** in het gebied New York.

1. Pak het **e-mailattribuut** en sleep het naar rechts.

   ![](assets/dialogues-9.png)

1. Klik op de vervolgkeuzelijst met operatoren en selecteer **Is leeg**.

   ![](assets/dialogues-10.png)

1. Pak het **Inferred State** attribuut en sleep het aan waar het _belemmering en laat vallen een attribuut hier_ zegt.

   ![](assets/dialogues-11.png)

   >[!NOTE]
   >
   >Wanneer iemand uw website bezoekt, worden deze door [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) in het systeem opgeslagen. Wij kijken omhoog hun IP in een speciaal gegevensbestand en leiden allerlei goede info.

1. _Standaard_ ingesteld op Isis. Typ in het veld Waarden selecteren de waarde NY (u kunt ook op de vervolgkeuzelijst klikken en een waarde in de lijst selecteren).

   ![](assets/dialogues-12.png)

## Groepen toevoegen {#add-groups}

U kunt ook kenmerken groeperen, voor het geval dat u alle kenmerken samen met &quot;een&quot; van een andere wilt hebben.

VOLTOOID

## Doel {#target}

Hier voert u de URL&#39;s in waarop u een specifiek dialoogvenster wilt weergeven.

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

**Een stream maken**

Er zijn _veel_ streamcombinaties om te maken. In dit voorbeeld stellen we een vraag en bereiden we ons voor.

## Rapporten {#reports}

In het tabblad Rapporten geeft u de gegevens van de afgelopen 90 dagen weer. Elke rubriek wordt hieronder gedefinieerd.

<table>
 <tr>
  <td><strong>Totaal geactiveerd</strong></td>
  <td>De verhogingen telkens als een bezoeker voor kwalificeert/voor een Dialoog wordt getoond.
</td>
 </tr>
 <tr>
  <td><strong>Betrokken</strong></td>
  <td>Hiermee wordt het aantal stappen verhoogd wanneer een bezoeker op het chassisanker klikt om het dialoogvenster te openen.</td>
 </tr>
 <tr>
  <td><strong>Voltooid</strong></td>
  <td>Hiermee wordt elke keer dat een bezoeker het einde van een vertakking in een dialoogvenster bereikt.</td>
 </tr>
 <tr>
  <td><strong>Opgenomen leads</strong></td>
  <td>Elke keer dat een bezoeker een geldig e-mailadres in een dialoogstroom opgeeft, neemt de toename toe.</td>
 </tr>
 <tr>
  <td><strong>Opgenomen vergaderingen</strong></td>
  <td>Steeds wanneer een bezoeker een afspraak via de chatbot heeft gepland.</td>
 </tr>
 <tr>
  <td><strong>Doelstellingen bereikt</strong></td>
  <td>De toename telkens als een bezoeker een doel in om het even welke stroom van de Dialoog bereikt.</td>
 </tr>
</table>
