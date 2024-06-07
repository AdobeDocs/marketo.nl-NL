---
unique-page-id: 9437991
description: Triggers en filters voor mobiele slimme campagnes - Marketo Docs - Productdocumentatie
title: Triggers en filters voor mobiele slimme campagnes
exl-id: 76fc7a74-b27d-4898-a8ca-85c9c2828a28
feature: Smart Campaigns
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '820'
ht-degree: 0%

---

# Triggers en filters voor mobiele slimme campagnes {#triggers-and-filters-for-mobile-smart-campaigns}

U kunt triggers en filters instellen voor een slimme campagne voor mobiele apps.

Voor de meeste activiteiten zijn er een trigger, een filter en een inactiviteitsfilter. Gebruik inactiviteitsfilters om een handeling bij te houden, zoals tikken op een pushmelding, die _niet_ gebeuren.

* Mobiele app is/is geïnstalleerd
* Mobiele app is/is geopend
* Heeft/heeft mobiele toepassingsactiviteiten
* Heeft/heeft een mobiele App-sessie
* Taps/Tapping Mobile Push Notification

Er zijn alleen filters voor deze activiteit:

* Er is pushmelding verzonden - filter en inactiviteitsfilter

Zoek naar &quot;mobiele app&quot; in het rechterdeelvenster om alle triggers en filters voor de mobiele app weer te geven.

![](assets/triggers-and-filters-for-mobile-smart-campaigns-1.png)

## Restricties {#constraints}

Gebruik beperkingen met triggers en filters om de gegevens verder te sorteren.

![](assets/triggers-and-filters-for-mobile-smart-campaigns-2.png)

Alle triggers en filters, met uitzondering van het bericht Is pushbericht verzonden, bevatten de volgende twee standaardbeperkingen:

* Apparaattype - iPod, iPhone, iPhone 6 Plus, iPad mini, iPad, Android-smartphone, Android-tablet, onbekend (dit is een lijst met voorinstellingen)

* Platform - iPhone of Android

Sommige triggers en filters bieden aanvullende beperkingen, zoals:

* Toepassingsversie - Een manier om mensen aan te wijzen die zich niet in de nieuwste versie bevinden. Als de nieuwste versie van de app 2.0 is, kunt u deze bijvoorbeeld gebruiken om te zoeken naar personen die NIET aanwezig zijn in App versie 2.0

* Bron installeren - Momenteel is de enige optie API

* Landinstelling - De instelling op het apparaat

* Mobiele toepassing - De naam van specifieke app. Nuttig om op te geven of u meer dan één

* Platformversie - De versie van het besturingssysteem

* Sessieduur (seconden) - Sessietijd wanneer de app op de voorgrond staat

* Is gedrukt - **Waar** betekent dat pushmeldingen kunnen worden verzonden. **Onwaar** betekent dat dit niet mogelijk is. De persoon kan er bijvoorbeeld voor hebben gekozen geen pushberichten meer te ontvangen

## Triggers en filters {#triggers-and-filters}

**Heeft mobiele toepassing**

Gebruik dit filter om te zien wie uw app ooit heeft geïnstalleerd. Deze optie is alleen beschikbaar als filter.

>[!NOTE]
>
>Het filter vindt zowel de huidige als de vorige installatie, omdat Marketo het verwijderen van apps niet bijhoudt.

**Restricties** - Apparaattype, Platform, mobiele toepassing, mobiele toepassingsversie, apparaattype, bron installeren, is pushingeschakeld en Landinstelling

![](assets/triggers-and-filters-for-mobile-smart-campaigns-3.png)

>[!TIP]
>
>Het wordt aanbevolen Bevat mobiele app = true en Is Push Enabled = true op te geven en de naam van uw mobiele app op te geven bij het definiëren van de slimme lijst met personen die een pushmelding moeten ontvangen.

Mobiele app is/is geïnstalleerd

* Mobiele toepassing is geïnstalleerd - trigger

* Mobiele toepassing geïnstalleerd - filter

* NOT Mobile App geïnstalleerd - inactiviteitsfilter

**Restricties** - Apparaattype, Platform, App-versie, Landinstelling en Installatiebron

![](assets/triggers-and-filters-for-mobile-smart-campaigns-4.png)

Mobiele app is/is geopend

* Mobiele app is geopend - trigger

* Mobiele app geopend - filter

* NOT Mobile App geopend - inactiviteitsfilter

**Restricties** - Type apparaat en platform

![](assets/triggers-and-filters-for-mobile-smart-campaigns-5.png)

Heeft/heeft mobiele toepassingsactiviteiten

Deze vormen een krachtige manier om aangepaste mobiele activiteiten te volgen. U moet met uw ontwikkelaar samenwerken om het volgen van de opstelling te plaatsen [voor Android](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android){target="_blank"} en [voor iOS](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#install-marketo-sdk-on-ios){target="_blank"}.

* Heeft mobiele toepassingsactiviteit - trigger

* Toepassingsactiviteit voor mobiele apparaten hebben ingeschakeld, filter

* Geen mobiele toepassingsactiviteit - inactiviteitsfilter

**Restricties** - Apparaattype, Platform, Mobiele App-versie, Landinstelling, Platformversie, plus vijf extra versies:

* Actie - Aangepaste mobiele activiteiten

* Type handeling - (optioneel) Tekstveld dat wordt gebruikt om meerdere handelingen te categoriseren

* Details van handeling - (optioneel) Tekstveld met aanvullende informatie over een handeling

* Metrisch - (optioneel) numeriek veld dat aanvullende informatie over een handeling bevat (bijvoorbeeld prijs)

* De Lengte van de actie (seconden) - (facultatieve) Numeriek gebied dat kan worden gebruikt om te vangen hoe lang het een gebruiker duurde om een actie te voltooien

Met de actievereisten kunt u de trigger en filters gebruiken om mobiele activiteiten zeer nauwkeurig bij te houden.

>[!NOTE]
>
>**Voorbeeld**
>
>Onder het actietype *Winkelen* Hier is een zeer specifieke actie, met andere beperkingen die het bepalen:
>
>* Een shirt kopen
>   * Het was rood
>   * Dat kost $30
>   * Het kostte 20 seconden om te kopen

Zo ziet het filter er in Marketo uit:

![](assets/triggers-and-filters-for-mobile-smart-campaigns-6.png)

>[!NOTE]
>
>**Voorbeeld**
>
>U kunt meerdere handelingen uitvoeren onder hetzelfde actietype. Je normale boodschappenervaring kan verschillende kolommen bevatten bij Winkelen. En wat sokken om mee te gaan?
>
>| Type handeling | Winkelen | Winkelen |
>|---|---|---|
>| Handeling | Gebleken overhemd | Gekochte broeken |
>| Details van handeling | Kleur | Kleur |
>| Metrisch handeling | Prijs | Prijs |

**Heeft/heeft een mobiele App-sessie**

* Heeft Mobile App-sessie - trigger

* App-sessie hebben gehad - filter

* Geen mobiele App-sessie - inactiviteitsfilter

**Restricties** - Type apparaat, Platform en Sessieduur (seconden)

![](assets/triggers-and-filters-for-mobile-smart-campaigns-7.png)

Taps/Tapping Push Notification

* Taps Push Notification - trigger

* Melding van pushbericht met aanraakopties - filter

* Melding van niet-getapte pushmelding - inactiviteitsfilter

**Restricties** - Apparaattype, Platform, Mobiele App-versie, pushmelding en platformversie

![](assets/triggers-and-filters-for-mobile-smart-campaigns-8.png)

>[!TIP]
>
>Gebruik het filter Inactiviteit van pushmelding niet aangeraakt om te zoeken naar mensen die niet hebben getikt op een pushmelding die onlangs naar hen is verzonden, zodat u deze via e-mail kunt volgen.

**Er is een pushmelding verzonden** Deze activiteit is alleen beschikbaar als filter.

* Er is pushmelding verzonden, filter

* Geen pushmelding verzonden - inactiviteitsfilter

**Restricties** - Push Notification en Mobile App

![](assets/triggers-and-filters-for-mobile-smart-campaigns-9.png)

>[!MORELIKETHIS]
>
>* [Een restrictie toevoegen aan een slim lijstfilter](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md){target="_blank"}
>* [Inactiviteitsfilters gebruiken in een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md){target="_blank"}
