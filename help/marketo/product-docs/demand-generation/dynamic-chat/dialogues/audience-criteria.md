---
description: Criteria voor het publiek - Marketo Docs - Productdocumentatie
title: Criteria voor het publiek
exl-id: 9b70b03e-229e-469e-bd65-07aaf2dcbec6
source-git-commit: f71ac0398b3a93d2c46201a696dd41e6ccd89000
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Criteria voor het publiek {#audience-criteria}

Net als in Marketo Smart Lists kunt u met de kenmerken Audience Criteria (criteria voor doelgroepen) een doelgroep definiëren. U kunt bekende of onbekende personen als doel instellen met afgeleide, persoon- of bedrijfskenmerken (of een combinatie daarvan).

## Prioriteit {#priority}

De prioriteit bepaalt welke Dialoog een lood ontvangt in het geval zij voor meer dan één kwalificeren. Het is vastgesteld bij de eerste [uw dialoogvenster maken](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target=&quot;_blank&quot;}. U kunt de prioriteit voor een bestaand dialoogvenster wijzigen door het dialoogvenster te openen en naar **Dialoogdetails** op het tabblad Audience Criteria.

![](assets/audience-criteria-1.png)

## Gebeurtenissen {#events}

![](assets/audience-criteria-2.png)

Met gebeurtenissen kunt u bezoekers aanwijzen op basis van hoeveel ze schuiven of hoe lang ze zich op uw pagina/site bevinden. In het onderstaande voorbeeld richten we ons op bezoekers die al meer dan 20 seconden op een specifieke pagina staan.

1. Pak de **Tijd op pagina** en sleep deze naar rechts.

   ![](assets/audience-criteria-3.png)

1. Stel de tijd Groter dan in op 20 seconden.

   ![](assets/audience-criteria-4.png)

1. Voeg de URL van de gewenste pagina toe in het dialoogvenster [Doel](#target) sectie.

   ![](assets/audience-criteria-5.png)

## Attributen {#attributes}

![](assets/audience-criteria-6.png)

**Bekende personen**

Er zijn _veel_ te kiezen kenmerkcombinaties. In het onderstaande voorbeeld richten we ons op alle **bekende personen** in Californië, die werken bij een bedrijf met meer dan 50 werknemers.

1. Pak de **Persoonsstaat** en sleep het naar rechts.

   ![](assets/audience-criteria-7.png)

1. _Is_ is standaard ingesteld. Typ in het veld Waarden selecteren de tekst CA (u kunt ook op de vervolgkeuzelijst klikken en in de lijst selecteren).

   ![](assets/audience-criteria-8.png)

1. Pak de **Bedrijfsomvang** kenmerk en sleep het naar de gewenste locatie _een kenmerk hier slepen en neerzetten_.

   ![](assets/audience-criteria-9.png)

   >[!NOTE]
   >
   >U kunt ook een kenmerk kiezen door op het desbetreffende kenmerk te klikken **+** pictogram.

1. Klik op de vervolgkeuzelijst met operatoren en selecteer **Groter dan**.

   ![](assets/audience-criteria-10.png)

1. Typ 50 en klik ergens anders op het scherm om op te slaan.

   ![](assets/audience-criteria-11.png)

En dat is het!

**Anonieme mensen**

Er is een gemakkelijke manier om mensen specifiek te richten die nog niet in uw gegevensbestand zijn. In dit voorbeeld richten we ons op alles **anonieme mensen** in het gebied New York.

1. Pak de **Persoonsbericht** en sleep het naar rechts.

   ![](assets/audience-criteria-12.png)

1. Klik op de vervolgkeuzelijst met operatoren en selecteer **Is leeg**.

   ![](assets/audience-criteria-13.png)

1. Pak de **Overgenomen staat** kenmerk en sleep het naar de gewenste locatie _een kenmerk hier slepen en neerzetten_.

   ![](assets/audience-criteria-14.png)

   >[!NOTE]
   >
   >Wanneer iemand uw website bezoekt, [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) cookies ze en zet ze in het systeem. Wij kijken omhoog hun IP in een speciaal gegevensbestand en leiden allerlei goede info.

1. _Is_ is standaard ingesteld. Typ in het veld Waarden selecteren de waarde NY (u kunt ook op de vervolgkeuzelijst klikken en een waarde in de lijst selecteren).

   ![](assets/audience-criteria-15.png)

## Groepen toevoegen {#add-groups}

U kunt ook kenmerken groeperen, voor het geval dat u alle kenmerken samen met &quot;alle of een&quot; van een ander kenmerk wilt hebben. U kunt meerdere groepen toevoegen.

![](assets/audience-criteria-16.png)

![](assets/audience-criteria-17.png)

## Doel {#target}

Hier voert u de URL&#39;s in waarop u een specifiek dialoogvenster wilt weergeven. U kunt ook uitsluitingen toevoegen.

Acceptabele indelingen:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>Het gebruiken van een asterisk doet dienst als vangst-all wilkaart. Dus `https://*.website.com` zou het dialoogvenster op elke pagina van de site plaatsen, inclusief subdomeinen (bijvoorbeeld: `support.website.com`). en `https://website.com/folder/*` zou het dialoogvenster op elke HTML-pagina in de volgende map plaatsen (bijvoorbeeld: in dit geval is de map &quot; sport &quot; , dus : website.com/sports/baseball.html, website.com/sports/football.html, enz.).

**Uitsluitingen**

Uitsluitingen gebruiken om ervoor te zorgen dat uw dialoogvenster dit doet **niet** worden weergegeven op een specifieke pagina of een specifiek gebied van uw site. Uitsluitingen hebben dezelfde indeling als insluitingen.

![](assets/audience-criteria-18.png)

>[!MORELIKETHIS]
>
>* [Een dialoogvenster maken](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target=&quot;_blank&quot;}
>* [Stream Designer](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/stream-designer.md){target=&quot;_blank&quot;}
>* [Rapporten](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/reports.md){target=&quot;_blank&quot;}

