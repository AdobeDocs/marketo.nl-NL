---
description: Predictieve filters - Marketo Docs - Productdocumentatie
title: Voorspelende filters
exl-id: 27736b80-cd8b-455d-9d73-c17d492d0906
feature: Predictive Audiences
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '408'
ht-degree: 0%

---

# Voorspelende filters {#predictive-filters}

Als onderdeel van voorspellende soorten publiek biedt Marketo een groep op AI/ML gebaseerde filters in slimme lijsten binnen slimme campagnes.

![ Beeld Één ](assets/predictive-filters-1.png)

>[!NOTE]
>
>De filters &quot;Waarschijnlijk bij te wonen&quot; en &quot;Waarschijnlijk te registreren&quot; kunnen alleen worden gebruikt in gebeurtenisprogramma&#39;s. &quot;Waarschijnlijkheid aan Unsubscribe,&quot;&quot;Lookalike van de Leden van het Programma,&quot;en &quot;Lookalike van Slimme Leden van de Lijst&quot;kan in alle programmatypen worden gebruikt.

## Waarschijnlijkheid om bij te wonen {#likelihood-to-attend}

Dit filter wordt gebruikt om uw publiek effectief te beperken. Dit helpt u richten en uitnodigen lood die een hogere waarschijnlijkheid van **hebben om** uw webinar of gebeurtenis bij te wonen. Merk op dat uw &quot;Waarschijnlijkheid aan programma&quot;uw huidig gebeurtenisprogramma zal zijn.

![ Beeld Twee ](assets/predictive-filters-2.png)

## Waarschijnlijkheid om te registreren {#likelihood-to-register}

Gelijkaardig aan de _Waarschijnlijkheid om_ filter bij te wonen, gebruik dit filter om uw publiek en doellood te beperken die een hogere waarschijnlijkheid van **hebben registrerend** voor uw webinar of gebeurtenis.

![ Beeld Drie ](assets/predictive-filters-3.png)

## Waarschijnlijkheid om af te melden {#likelihood-to-unsubscribe}

Hierdoor wordt het publiek gefilterd op basis van de vraag of het zeer waarschijnlijk is dat het abonnement de komende twee weken wordt opgezegd. U kunt dit gebruiken om hoog-vermoeiingslood te richten verschillend en effectiever. De drempel voor afmelden is dynamisch en wordt aangestuurd door een AI-model dat rekening houdt met verschillende kenmerken, waaronder de doorlooptijd in de database en de loodactiviteiten.

![ Beeld Vier ](assets/predictive-filters-4.png)

>[!NOTE]
>
>De mogelijkheid om filters bij te wonen/te registreren/op te zeggen moet samen met andere standaardfilters worden gebruikt.

## Lookalike van de Leden van het Programma/Lookalike van Slimme Leden van de Lijst {#lookalike-of-members}

Deze twee filters helpen u uw huidige publiek uitbreiden door extra lood te richten die aan leden van een ander programma of Slimme Lijst gelijkaardig zijn. De Lookalike-filters omvatten meer dan 50 factoren, zoals hoofdkenmerken, e-mailactiviteit, webactiviteit en betrokkenheid.

Klik op **[!UICONTROL Add Constraint]** om succescriteria te kiezen voor de leden van de geselecteerde programma&#39;s.

Klik op het pictogram **+** om eenvoudig meerdere programma&#39;s/slimme lijsten aan één filter toe te voegen.

![ Beeld Vijf ](assets/predictive-filters-5.png)

## Notities {#things-to-note}

* U kunt voorspellende filters op een Slimme Campagne toepassen zelfs als het ouderprogramma wordt gecreeerd alvorens de voorspellende filters worden toegelaten.
* Predictieve filters zijn niet beschikbaar voor triggercampagnes.
* Het klonen of verplaatsen van campagnes die voorspellende filters bevatten, wordt niet ondersteund.
* U kunt maximaal vijf voorspellende filters gebruiken in een slimme lijst.
* Als Marketo Engage een fout aantreft in de evaluatie van voorspellende filters, wordt de campagne automatisch afgebroken en ontvangt u een melding in het Marketo-meldingscentrum.
* Predictieve filters hebben momenteel een invoerlimiet van 1 miljoen gekwalificeerde personen.
* U kunt maximaal 50 actieve programma&#39;s met voorspellende filters hebben.
