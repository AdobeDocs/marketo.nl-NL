---
unique-page-id: 1900554
description: HTML van e-mail bewerken - Marketo Docs - Productdocumentatie
title: HTML van een e-mail bewerken
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# HTML van een e-mail bewerken {#edit-an-emails-html}

Soms moet u de onderliggende HTML van een e-mail wijzigen. Soms kunt u een extern systeem gebruiken om de code van uw e-mail te ontwerpen en te bouwen. In beide gevallen kunt u gemakkelijk code importeren en/of bewerken vanuit de e-maileditor.

## HTML bewerken {#edit-html}

1. Selecteer uw e-mail en klik op Concept **** bewerken.

   ![](assets/teamspidey.jpg)

1. Klik op Code **** bewerken.

   ![](assets/two-4.png)

1. Breng de gewenste wijzigingen aan. Klik op **Opslaan** als u klaar bent.

   ![](assets/three-3.png)

   >[!NOTE]
   >
   >Wijzig wat je wilt. U kunt de volledige HTML vervangen of kleine aanpassingen aanbrengen.

1. Klik op de vervolgkeuzelijst **Codehandelingen** om de code te downloaden als een HTML-bestand, uw CSS in te line of de HTML te valideren.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >De beste manier voor e-mails is om al uw stijlen inline te maken. Verschillende e-mailclients ondersteunen CSS in de `<head>` sectie niet.

## Een e-mail verbreken via de sjabloon {#breaking-an-email-from-its-template}

Met deze codewijzigingen **wordt geen** e-mail uit de sjabloon verbroken:

* De inhoud van een willekeurige module bewerken (inclusief het toevoegen van nieuwe elementen in de module)
* Een nieuwe module toevoegen aan de container
* Een module verwijderen uit de container

* Het veranderen van mkto-specifieke attributen (bijvoorbeeld, &quot;mktoName&quot;of &quot;mktoImgUrl&quot;) van om het even welk Element buiten een Module
* De inhoud van een willekeurig element bewerken (RTF-bestand, afbeelding, video, enz.) buiten een module

Deze dingen u in de coderedacteur kunt doen **zullen** e-mail van zijn malplaatje breken:

* Alles wijzigen in de code buiten een Element of Module
* Niet-mkto-kenmerken (bijvoorbeeld &quot;id&quot; of &quot;style&quot;) van een element buiten een module toevoegen of wijzigen
* Een element verwijderen dat zich buiten een module bevindt

## Zoeken in code {#search-code}

Met de functie Code zoeken kunt u op efficiënte wijze inhoud in de HTML-code van uw e-mail zoeken en vervangen.

1. Klik in de e-mailcode op **Zoeken**.

   ![](assets/five-2.png)

1. Voer in wat u wilt zoeken en klik op Volgende **** zoeken om vooruit te zoeken of Vorige **** zoeken om achteruit te zoeken. U kunt ook Alles **vervangen** en **Alles** vervangen.

   ![](assets/six-1.png)

1. Klik op **Sluiten** als u klaar bent.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >De code van het onderzoek is ook beschikbaar in de redacteur [van het Malplaatje van de](http://docs.marketo.com/display/DOCS/Create+a+New+Email+Template)E-mail.

We raden u aan uw e-mailberichten te blijven bewerken met de ingebouwde functionaliteit van Marketo, maar deze code-editor biedt wel flexibiliteit als dat nodig is.
