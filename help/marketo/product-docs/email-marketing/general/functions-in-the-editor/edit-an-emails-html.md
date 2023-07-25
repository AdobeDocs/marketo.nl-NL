---
unique-page-id: 1900554
description: Een HTML van een e-mail bewerken - Marketo Docs - Productdocumentatie
title: Een HTML van een e-mail bewerken
exl-id: 9dc8e44d-d9da-4bc2-950f-3ffbb976f5d5
feature: Email Editor
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---

# Een HTML van een e-mail bewerken {#edit-an-emails-html}

Soms moet u de onderliggende HTML van een e-mailbericht wijzigen. Soms kunt u een extern systeem gebruiken om de code van uw e-mail te ontwerpen en te bouwen. In beide gevallen kunt u gemakkelijk code importeren en/of bewerken vanuit de e-maileditor.

## HTML bewerken {#edit-html}

1. Selecteer uw e-mail en klik op **Concept bewerken**.

   ![](assets/teamspidey.jpg)

1. Klikken **Code bewerken**.

   ![](assets/two-4.png)

1. Breng de gewenste wijzigingen aan. Klikken **Opslaan** wanneer gereed.

   ![](assets/three-3.png)

   >[!NOTE]
   >
   >Wijzig wat je wilt. U kunt de volledige HTML vervangen of kleine aanpassingen aanbrengen.

1. Klik op de knop **Codehandelingen** vervolgkeuzelijst om de code te downloaden als een HTML-bestand, uw CSS in te line te zetten of de HTML te valideren.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >De beste manier voor e-mails is om al uw stijlen inline te maken. Verschillende e-mailclients ondersteunen CSS niet binnen de `<head>` sectie.

## Een e-mail verbreken via de sjabloon {#breaking-an-email-from-its-template}

Deze codewijzigingen **niet** een e-mailbericht uit de sjabloon opheffen:

* De inhoud van een willekeurige module bewerken (inclusief het toevoegen van nieuwe elementen in de module)
* Een nieuwe module toevoegen aan de container
* Een module verwijderen uit de container

* Het veranderen van mkto-specifieke attributen (bijvoorbeeld, &quot;mktoName&quot;of &quot;mktoImgUrl&quot;) van om het even welk Element buiten een Module
* De inhoud van een willekeurig element bewerken (RTF-bestand, afbeelding, video, enz.) buiten een module

Dit kunt u doen in de code-editor **zal** e-mailadres uit de sjabloon opheffen:

* Alles wijzigen in de code buiten een Element of Module
* Niet-mkto-kenmerken (bijvoorbeeld &quot;id&quot; of &quot;style&quot;) van een element buiten een module toevoegen of wijzigen
* Een element verwijderen dat zich buiten een module bevindt

## Zoeken in code {#search-code}

Met de functie Code zoeken kunt u op efficiënte wijze inhoud in de HTML-code van uw e-mail zoeken en vervangen.

1. Klik in de e-mailcode op **Zoeken in code**.

   ![](assets/five-2.png)

1. Ga wat in u wilt vinden en klik **Volgende zoeken** om vooruit te zoeken of **Vorige zoeken** naar achteren zoeken. U kunt ook **Vervangen** en **Alles vervangen**.

   ![](assets/six-1.png)

1. Klikken **Sluiten** wanneer gereed.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >De code van het onderzoek is ook beschikbaar in [E-mailsjablooneditor](/help/marketo/product-docs/email-marketing/general/email-editor-2/create-an-email-template.md).

We raden u aan uw e-mailberichten te blijven bewerken met de ingebouwde Marketo-functionaliteit, maar deze code-editor biedt wel flexibiliteit als dat nodig is.
