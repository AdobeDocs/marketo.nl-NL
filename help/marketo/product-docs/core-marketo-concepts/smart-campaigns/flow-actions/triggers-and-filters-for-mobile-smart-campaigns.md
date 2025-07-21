---
unique-page-id: 9437991
description: Triggers en filters voor mobiele slimme campagnes - Marketo Docs - Productdocumentatie
title: Triggers en filters voor mobiele slimme campagnes
exl-id: 76fc7a74-b27d-4898-a8ca-85c9c2828a28
feature: Smart Campaigns
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '814'
ht-degree: 0%

---

# Triggers en filters voor mobiele slimme campagnes {#triggers-and-filters-for-mobile-smart-campaigns}

U kunt triggers en filters instellen voor een slimme campagne voor mobiele apps.

Voor de meeste activiteiten zijn er een trigger, een filter en een inactiviteitsfilter. De inactiviteitsfilters van het gebruik om een actie, zoals het tikken van een duw bericht te volgen, dat _niet_ gebeurde.

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

* Apparaattype - [!DNL iPod], iPhone, [!DNL iPhone 6 Plus] , [!DNL iPad mini], iPad, Android smartphone, Android-tablet, onbekend (dit is een lijst met voorinstellingen)

* Platform - iPhone of Android

Sommige triggers en filters bieden aanvullende beperkingen, zoals:

* Toepassingsversie - Een manier om mensen aan te wijzen die zich niet in de nieuwste versie bevinden. Als de nieuwste versie van de app 2.0 is, kunt u deze bijvoorbeeld gebruiken om te zoeken naar personen die NIET aanwezig zijn in App versie 2.0

* Source installeren - De enige optie is momenteel API

* Landinstelling - De instelling op het apparaat

* Mobiele toepassing - De naam van specifieke app. Nuttig om op te geven of u meer dan één

* Platformversie - De versie van het besturingssysteem

* Sessieduur (seconden) - Sessietijd wanneer de app op de voorgrond staat

* Is Ingeschakeld van de Duw - **Waar** betekent dat de duw- berichten kunnen worden verzonden. **Vals** betekent dat zij niet kunnen; bijvoorbeeld, kan de persoon uit het ontvangen van dupberichten hebben gekozen

## Triggers en filters {#triggers-and-filters}

**heeft Mobiele toepassing**

Gebruik dit filter om te zien wie uw app ooit heeft geïnstalleerd. Deze optie is alleen beschikbaar als filter.

>[!NOTE]
>
>Het filter vindt zowel de huidige als de vorige installatie, omdat Marketo het verwijderen van apps niet bijhoudt.

**Beperkingen** - het Type van Apparaat, Platform, Mobiele App, Mobiele Versie van de Toepassing, het Type van Apparaat, installeert Source, wordt Ingedrukt, en Scène toegelaten

![](assets/triggers-and-filters-for-mobile-smart-campaigns-3.png)

>[!TIP]
>
>Het wordt aanbevolen Bevat mobiele app = true en Is Push Enabled = true op te geven en de naam van uw mobiele app op te geven bij het definiëren van de slimme lijst met personen die een pushmelding moeten ontvangen.

Mobiele app is/is geïnstalleerd

* Mobiele toepassing is geïnstalleerd - trigger

* Mobiele toepassing geïnstalleerd - filter

* NOT Mobile App geïnstalleerd - inactiviteitsfilter

**Beperkingen** - het Type van Apparaat, Platform, de Versie van de App, de Scène, en installeer Source

![](assets/triggers-and-filters-for-mobile-smart-campaigns-4.png)

Mobiele app is/is geopend

* Mobiele app is geopend - trigger

* Mobiele app geopend - filter

* NOT Mobile App geopend - inactiviteitsfilter

**Beperkingen** - het Type van Apparaat en Platform

![](assets/triggers-and-filters-for-mobile-smart-campaigns-5.png)

Heeft/heeft mobiele toepassingsactiviteiten

Deze vormen een krachtige manier om aangepaste mobiele activiteiten te volgen. U zult met uw ontwikkelaar aan opstelling het volgen [ voor Android ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android){target="_blank"} en [ voor iOS ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#install-marketo-sdk-on-ios){target="_blank"} moeten werken.

* Heeft mobiele toepassingsactiviteit - trigger

* Toepassingsactiviteit voor mobiele apparaten hebben ingeschakeld, filter

* Geen mobiele toepassingsactiviteit - inactiviteitsfilter

**Beperkingen** - het Type van Apparaat, Platform, Mobiele Versie van de Toepassing, Scène, de Versie van het Platform, plus vijf extra degenen:

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
>Onder het handelingstype van *het Knippen*, is hier een zeer specifieke actie, met de andere beperkingen die het bepalen:
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

**heeft/had Mobiele App Zitting**

* Heeft Mobile App-sessie - trigger

* App-sessie hebben gehad - filter

* Geen mobiele App-sessie - inactiviteitsfilter

**Beperkingen** - het Type van Apparaat, Platform, en de Lengte van de Zitting (seconden)

![](assets/triggers-and-filters-for-mobile-smart-campaigns-7.png)

Taps/Tapping Push Notification

* Taps Push Notification - trigger

* Melding van pushbericht met aanraakopties - filter

* Melding van niet-getapte pushmelding - inactiviteitsfilter

**Beperkingen** - het Type van Apparaat, Platform, de Mobiele Versie van de Toepassing, het Bericht van de Duw, en de Versie van het Platform

![](assets/triggers-and-filters-for-mobile-smart-campaigns-8.png)

>[!TIP]
>
>Gebruik het filter Inactiviteit van pushmelding niet aangeraakt om te zoeken naar mensen die niet hebben getikt op een pushmelding die onlangs naar hen is verzonden, zodat u deze via e-mail kunt volgen.

**werd Verzonden het Bericht van de Duw** Deze activiteit is beschikbaar slechts als filter.

* Er is pushmelding verzonden, filter

* Geen pushmelding verzonden - inactiviteitsfilter

**Beperkingen** - het Bericht van de duw en Mobiele App

![](assets/triggers-and-filters-for-mobile-smart-campaigns-9.png)

>[!MORELIKETHIS]
>
>* [ voeg een Beperking aan een Slimme Filter van de Lijst toe ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md){target="_blank"}
>* [ Filters van de Inactiviteit van het Gebruik in een Slimme Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md){target="_blank"}
