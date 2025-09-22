---
description: Gedrag verwacht - Marketo Docs - Productdocumentatie
title: Verwacht gedrag
hide: true
hidefromtoc: true
exl-id: d19130cf-186e-4aad-be32-6aad18c9d08b
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---

# Verwacht gedrag {#expected-behavior}

In dit artikel vindt u informatie over het verwachte gedrag dat aan [!UICONTROL Predictive Audiences] (PA) is gekoppeld.

## Overwegingen met betrekking tot gegevens en privacy

* Alle vereiste gegevensverwerking voor de AI/ML-modellen vindt plaats in Noord-Amerika.
* In AI/ML-modellen wordt geen gebruik gemaakt van specifieke informatie over lood, zoals voornaam of achternaam, geslacht, e-mail, contactnummers, enz. Modellen maken alleen gebruik van algemene kenmerken die zijn afgeleid van afBEELDMATERIAAL en activiteitenlogboeken.

**voor [!UICONTROL Predictive Audiences], kunt u het volgende gedrag** verwachten

* PA is toegankelijk in zowel [!DNL Marketo Sky] als [!DNL Marketo Classic] ervaring. De beschikbaarheid van specifieke functies is als volgt:
   * Predictieve filters - [!DNL Sky/Classic]
   * Geprojecteerde registraties - [!DNL Sky/Classic]
   * Prognoses waarschijnlijkheid op regelniveau - [!DNL Sky/Classic]
   * Doelstellingen en reeksspatiëring - alleen [!DNL Sky]
   * Inzichten en aanbevelingen - alleen [!DNL Sky]
* De aanvankelijke activering neemt **24-48 uren** voor alle processen om te voltooien nadat PA is toegelaten. Alle voorspellende soorten publiek en voorspellende filters worden weergegeven in de interface, maar het kan tot 24 uur duren voordat deze functies beginnen te werken.
* **Voorspelingen zullen slechts voor nieuwe campagnes worden geproduceerd die nadat de eigenschap wordt geactiveerd worden gecreeerd.**

**er zijn sommige extra overwegingen specifiek voor voorspellende filters**:

* Registratie- en Aanwezigheidswaarheidsfilters kunnen alleen worden gebruikt met gebeurtenis- of webinar-programma&#39;s. De filters Lookalike en Unsubscribe kunnen in e-mail, gebeurtenis, en webinar programma&#39;s worden gebruikt.
* U kunt voorspellende filters op een slimme campagne zelfs toepassen als het ouderprogramma wordt gecreeerd alvorens de voorspellende filters worden toegelaten.
* Predictieve filters zijn niet beschikbaar voor triggercampagnes.
* Om een slimme campagne te kunnen uitvoeren, moeten waarschijnlijke filters worden gebruikt in combinatie met andere gewone filters.
* De functie Opgeslagen regels is niet beschikbaar voor gebruik in campagnes die voorspellende filters bevatten.
* U kunt **tot 5** vooruitlopende filters in een slimme lijst gebruiken.
* De voorspellende filters kunnen a **maximum van 1 miljoen gekwalificeerde lood** verwerken.
* U kunt **tot 50 actieve programma&#39;s** met vooruitlopende filters hebben. Een actief programma is elk programma dat voorspellende filters gebruikt en minstens één keer gepland is.

## Wanneer zijn geplande registraties niet beschikbaar?

Geprojecteerde registraties zijn niet beschikbaar in de volgende gebruiksgevallen:

* als het programma is gemaakt voordat het publiek met voorspellingen werd toegevoegd
* wanneer de status van het programma niet aan systeemstatussen in kaart wordt gebracht
* wanneer er geen leden van het programma zijn
* wanneer er in de afgelopen zes maanden geen vergelijkbare programma&#39;s zijn geweest die aan de vereiste criteria voldoen
