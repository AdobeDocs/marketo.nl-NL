---
unique-page-id: 37355569
description: Aangepaste velden voor programmalid - Marketo Docs - Productdocumentatie
title: Aangepaste velden voor programmalid
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# Aangepaste velden voor programmalid {#program-member-custom-fields}

Met aangepaste velden voor programmaleden kunt u programmaspecifieke gegevens voor elk lid verzamelen. Zij kunnen worden gebruikt in: Marketo-formulieren, filters en triggers van slimme lijsten en handelingen voor de stroom van slimme campagnes. De gegevens kunnen worden weergegeven op het tabblad Leden van het programma.

## Een aangepast veld voor programmalid maken {#create-a-program-member-custom-field}

1. Klik in Marketo op **Admin**.

   ![](assets/one.png)

1. Klik **Veld beheren**.

   ![](assets/two.png)

1. Klik op **Nieuw aangepast veld**.

   ![](assets/three.png)

1. Klik op de vervolgkeuzelijst Object en selecteer het gewenste object.

   ![](assets/four.png)

   >[!NOTE]
   >
   >Aangepaste velden voor personen en programmaleden kunnen niet dezelfde naam delen.

1. Vul de overige velden in en klik op **Maken**.

   ![](assets/five.png)

   >[!NOTE]
   >
   >Ondersteunde typen voor aangepaste velden voor programmaleden zijn: boolean, date, datetime, float, integer, string, URL. [Meer informatie over veldtypen](http://docs.marketo.com/x/Wwgt).

## Objectbeschrijvingen {#object-descriptions}

| Object | Beschrijving |
|---|---|
| Bedrijf | De naam van de met de persoon verbonden onderneming. |
| Opportunity | Een mogelijkheid kan met een persoon of account worden geassocieerd als een potentiële toekomstige verkoop. Zij gaan gewoonlijk Marketo door CRM, of via API in. |
| Persoon | Een individu in uw gegevensbestand van de Marketo dat u door marketing campagnes aangaat. |
| Programmalid | Persoon die ook lid is van een programma |

## Triggers en filters {#triggers-and-filters}

U kunt deze programmaspecifieke gegevens in slimme lijsten gebruiken via [triggers](http://docs.marketo.com/x/PoAR)en/of [filters](http://docs.marketo.com/x/2YAI).

![](assets/six.png)

## Te kennen zaken {#things-to-know}

* Aangepaste velden voor programmaleden zijn alleen beschikbaar in lokale middelen. Zij worden niet gesteund in de Studio van het Ontwerp omdat er geen manier is om het aan een specifiek programma te binden.
* U kunt een formulier (of een landingspagina met een formulier) dat aangepaste velden voor programmaleden bevat, niet klonen of verplaatsen naar de Design Studio.
* Aangepaste velden voor programmaleden kunnen niet worden gebruikt als tokens.
* Het programmalidobject kan maximaal 20 aangepaste velden hebben. Deze velden zijn beschikbaar voor elk programma.
* Wanneer u een lid van een programma verwijdert, als zij om het even welke gegevens op hun de douanegebied van het Lid van het Programma hebben, zullen de gegevens van dat gebied worden geschaad.
* Als u de gegevens wilt weergeven, klikt u op het tabblad Leden in het programma en maakt u een aangepaste weergave met de desbetreffende velden.
* Importeren en exporteren via [list](http://docs.marketo.com/x/egAk)en [API](http://developers.marketo.com/)worden ondersteund.
* Wanneer u twee personen samenvoegt, worden de aangepaste veldgegevens van het Lid van het Programma van de winnaar gebruikt. Maar als de winnaar er geen heeft, wordt de waarde van de verliezer gebruikt.

>[!MORELIKETHIS]
>
>[Een aangepast veld maken in Marketo](../../../../product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

