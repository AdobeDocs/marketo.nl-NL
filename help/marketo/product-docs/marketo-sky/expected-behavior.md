---
description: Gedrag verwacht - Marketo Docs - Productdocumentatie
title: Verwacht gedrag
hide: true
hidefromtoc: true
exl-id: d19130cf-186e-4aad-be32-6aad18c9d08b
source-git-commit: fb77478cdcd2b455e9f2359e16aca50143ce492c
workflow-type: tm+mt
source-wordcount: '385'
ht-degree: 0%

---

# Verwacht gedrag {#expected-behavior}

In dit artikel vindt u informatie over het verwachte gedrag dat is gekoppeld aan het voorspellende publiek.

## Overwegingen met betrekking tot gegevens en privacy

* Alle vereiste gegevensverwerking voor de AI/ML-modellen vindt plaats in Noord-Amerika.
* In AI/ML-modellen wordt geen gebruik gemaakt van specifieke informatie over lood, zoals voornaam of achternaam, geslacht, e-mail, contactnummers, enz. Modellen maken alleen gebruik van algemene kenmerken die zijn afgeleid van afBEELDMATERIAAL en activiteitenlogboeken.

**Voor voorspellend publiek kunt u het volgende gedrag verwachten**

* PA is zowel in Marketo Sky als in Marketo Classic toegankelijk. De beschikbaarheid van specifieke functies is als volgt:
   * Predictieve filters - [!DNL Sky/Classic]
   * Geprojecteerde registraties - [!DNL Sky/Classic]
   * Prognoses waarschijnlijkheid op loodniveau - [!DNL Sky/Classic]
   * Doelstellingen en reeksspatiëring - [!DNL Sky] alleen
   * Inzichten en aanbevelingen - [!DNL Sky] alleen
* Initiële activering **24-48 uur** voor alle processen om te voltooien nadat PA is toegelaten. Alle voorspellende soorten publiek en voorspellende filters worden weergegeven in de interface, maar het kan tot 24 uur duren voordat deze functies beginnen te werken.
* **Er worden alleen voorspellingen gegenereerd voor nieuwe campagnes die worden gemaakt nadat de functie is geactiveerd.**

**Er zijn enkele aanvullende overwegingen die specifiek zijn voor voorspellende filters**:

* Registratie- en Aanwezigheidswaarheidsfilters kunnen alleen worden gebruikt met gebeurtenis- of webinar-programma&#39;s. De filters Lookalike en Unsubscribe kunnen in e-mail, gebeurtenis, en webinar programma&#39;s worden gebruikt.
* U kunt voorspellende filters op een slimme campagne zelfs toepassen als het ouderprogramma wordt gecreeerd alvorens de voorspellende filters worden toegelaten.
* Predictieve filters zijn niet beschikbaar voor triggercampagnes.
* Om een slimme campagne te kunnen uitvoeren, moeten waarschijnlijke filters worden gebruikt in combinatie met andere gewone filters.
* De functie Opgeslagen regels is niet beschikbaar voor gebruik in campagnes die voorspellende filters bevatten.
* U kunt **maximaal 5** voorspellende filters in een slimme lijst.
* Predictieve filters kunnen een **maximaal 1 miljoen gekwalificeerde leads**.
* U kunt **maximaal 50 actieve programma&#39;s** met voorspellende filters. Een actief programma is elk programma dat voorspellende filters gebruikt en minstens één keer gepland is.

## Wanneer zijn geplande registraties niet beschikbaar?

Geprojecteerde registraties zijn niet beschikbaar in de volgende gebruiksgevallen:

* als het programma is gemaakt voordat het publiek met voorspellingen werd toegevoegd
* wanneer de status van het programma niet aan systeemstatussen in kaart wordt gebracht
* wanneer er geen leden van het programma zijn
* wanneer er in de afgelopen zes maanden geen vergelijkbare programma&#39;s zijn geweest die aan de vereiste criteria voldoen
