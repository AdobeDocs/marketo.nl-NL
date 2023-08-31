---
description: Predictieve filters - Marketo Docs - Productdocumentatie
title: Voorspelende filters
exl-id: 27736b80-cd8b-455d-9d73-c17d492d0906
feature: Predictive Audiences
source-git-commit: 9019cb4b81fb3acd744e644d51059644af454e5e
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# Voorspelende filters {#predictive-filters}

Als onderdeel van voorspellende soorten publiek biedt Marketo een groep op AI/ML gebaseerde filters in slimme lijsten binnen slimme campagnes.

![Afbeelding één](assets/predictive-filters-1.png)

>[!NOTE]
>
>De filters &quot;Waarschijnlijk bij te wonen&quot; en &quot;Waarschijnlijk in te schrijven&quot; kunnen alleen worden gebruikt in gebeurtenis- of e-mailprogramma&#39;s. &quot;Waarschijnlijkheid aan Unsubscribe,&quot;&quot;Lookalike van de Leden van het Programma,&quot;en &quot;Lookalike van Slimme Leden van de Lijst&quot;kan in alle programmatypen worden gebruikt.

## Waarschijnlijkheid om bij te wonen {#likelihood-to-attend}

Dit filter wordt gebruikt om uw publiek effectief te beperken. Hierdoor kunt u leads zoeken en uitnodigen die een hogere waarschijnlijkheid hebben **bijwonen** uw webinar of gebeurtenis. Merk op dat uw &quot;Waarschijnlijkheid aan programma&quot;uw huidig gebeurtenisprogramma zal zijn.

![Afbeelding twee](assets/predictive-filters-2.png)

## Waarschijnlijkheid om te registreren {#likelihood-to-register}

Vergelijkbaar met de _Waarschijnlijkheid om bij te wonen_ filter, gebruik dit filter om uw publiek en doelleads te versmallen die een hogere kans hebben op **registreren** voor uw webinar of gebeurtenis.

![Afbeelding drie](assets/predictive-filters-3.png)

## Waarschijnlijkheid om af te melden {#likelihood-to-unsubscribe}

Hierdoor wordt het publiek gefilterd op basis van de vraag of het zeer waarschijnlijk is dat het abonnement de komende twee weken wordt opgezegd. U kunt dit gebruiken om hoog-vermoeiingslood te richten verschillend en effectiever. De drempel voor afmelden is dynamisch en wordt aangestuurd door een AI-model dat rekening houdt met verschillende kenmerken, waaronder de doorlooptijd in de database en de loodactiviteiten.

![Afbeelding vier](assets/predictive-filters-4.png)

>[!NOTE]
>
>De mogelijkheid om filters bij te wonen/te registreren/op te zeggen moet samen met andere standaardfilters worden gebruikt.

## Lookalike van de Leden van het Programma/Lookalike van Slimme Leden van de Lijst {#lookalike-of-members}

Deze twee filters helpen u uw huidige publiek uitbreiden door extra lood te richten die aan leden van een ander programma of Slimme Lijst gelijkaardig zijn. De Lookalike-filters omvatten meer dan 50 factoren, zoals hoofdkenmerken, e-mailactiviteit, webactiviteit en betrokkenheid.

Klikken **[!UICONTROL Add Constraint]** kiezen voor succescriteria voor de leden van de geselecteerde programma&#39;s.

Klik op de knop **+** om eenvoudig meerdere programma&#39;s/slimme lijsten aan één filter toe te voegen.

![Afbeelding vijf](assets/predictive-filters-5.png)

## Notities {#things-to-note}

* U kunt voorspellende filters op een Slimme Campagne toepassen zelfs als het ouderprogramma wordt gecreeerd alvorens de voorspellende filters worden toegelaten.
* Predictieve filters zijn niet beschikbaar voor triggercampagnes.
* Het klonen of verplaatsen van campagnes die voorspellende filters bevatten, wordt niet ondersteund.
* U kunt maximaal vijf voorspellende filters gebruiken in een slimme lijst.
* Als het Marketo Engage een fout in de evaluatie van vooruitlopende filters ontmoet, zal de campagnelooppas automatisch afbreken en u zult een bericht in het het kennisgevingscentrum van Marketo ontvangen.
* Predictieve filters hebben momenteel een invoerlimiet van 1 miljoen gekwalificeerde personen.
* U kunt maximaal 50 actieve programma&#39;s met voorspellende filters hebben.
