---
unique-page-id: 11378814
description: Slimme accountlijsten - Marketo Docs - Productdocumentatie
title: Slimme accountlijsten
exl-id: fbdfb2b8-0061-467d-be89-527744a659a9
feature: Target Account Management
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '508'
ht-degree: 0%

---

# Slimme accountlijsten {#account-smart-lists}

Hieronder wordt beschreven hoe u uw hoogwaardige accounts snel en nauwkeurig kunt identificeren.

>[!NOTE]
>
>Deze functie is alleen beschikbaar voor gebruikers met zowel de invoegtoepassing voor het beheer van doelaccounts als een TAM met licentie.

## Een slimme accountlijst maken {#create-an-account-smart-list}

1. Ga in Marketo naar **Marketingactiviteiten**.

   ![](assets/account-smart-lists-1.png)

1. Zoek en selecteer het gewenste programma.

   ![](assets/account-smart-lists-2.png)

1. Klik op de knop **Nieuw** vervolgkeuzelijst en selecteer **Nieuw lokaal element**.

   ![](assets/account-smart-lists-3.png)

1. Klikken **Slimme accountlijst**.

   ![](assets/account-smart-lists-4.png)

1. Voer een naam in en klik op **Maken** (Beschrijving en labels zijn optioneel).

   ![](assets/account-smart-lists-5.png)

Uw slimme lijst met accounts is gemaakt. Zie hieronder voor stappen over het definiëren van de regels.

## Slimme-lijstregels account {#account-smart-list-rules}

De slimme Lijsten van de rekening werken zo gelijkaardig aan standaard Slimme Lijsten, met een opmerkelijke uitzondering: containers.

1. Als u uw slimme lijst met accounts wilt definiëren, klikt u op de knop **Slimme-lijstregels account** tab.

   ![](assets/account-smart-lists-6.png)

1. Kies de gewenste accountfilter(s). In dit voorbeeld kiezen we _Industrie is gezondheidszorg_.

   ![](assets/account-smart-lists-7.png)

   ![](assets/account-smart-lists-8.png)

   >[!NOTE]
   >
   >ICP-indicatorgegevens die in uw [Volgorde en afstemming van accountprofielen](/help/marketo/product-docs/target-account-management/account-profiling/account-profiling-ranking-and-tuning.md) worden weergegeven als aangepaste accountkenmerken voor gebruik in uw slimme lijst met accounts. Deze aangepaste kenmerkgegevens zijn gebaseerd op de datum waarop het accountprofielmodel is gemaakt/bijgewerkt.

1. Kies uw filter(s) voor overeenstemmende personen. In dit voorbeeld kiezen we _Staat is Californië_.

   ![](assets/account-smart-lists-9.png)

**OPTIONELE STAP**: Hier komen containers. Als u een extra filter voor overeenstemmende personen kiest, kunt u het onder het eerste filter neerzetten, of _in_ en maakt u een container. In dit voorbeeld maken we een container door deze toe te voegen _Functie is CFO_.

![](assets/account-smart-lists-10.png)

Zo ziet de container eruit.

![](assets/account-smart-lists-11.png)

>[!NOTE]
>
>Als u een container met filters maakt, wordt de regel &quot;en&quot; gemaakt. Dit betekent dat alleen alle gecombineerde resultaten worden geretourneerd. In dit voorbeeld, rekeningen bij een industrie van gezondheidszorg, samen met het worden gevestigd in Californië _en_ met iemand die als CFO wordt vermeld. Als u geen containers wilt gebruiken, laat u gewoon het filter onder of boven de bestaande onder- of boven.

En dat is het! Bekijk de onderstaande sectie om te zien hoe u de Smart List voor uw account kunt gebruiken.

>[!TIP]
>
>Net als bij standaard slimme lijsten kunt u geavanceerde logica gebruiken om de resultaten verder te verfijnen. Hiervoor hebt u ten minste drie filters nodig en in Account Smart List is één container (ongeacht het aantal filters dat de container zelf bevat) gelijk aan één filter.

## Handelingen voor Smart List van account {#account-smart-list-actions}

Op het tabblad Overzicht van de slimme lijst met accounts ziet u enkele actieopties.

**Exporteren**: Hiermee exporteert u de resultaten van uw slimme accountlijst als een CSV-bestand.

**Klonen**: Hiermee maakt u een kopie van de slimme lijst voor uw account.

**Verzenden naar advertentienetwerk**: Hiermee verzendt u de lijst naar LinkedIn als een nieuw gekoppeld publiek.

U kunt ook verwijzen naar uw Smart List voor account in een standaard Smart Campagne/List met de opdracht _Smart List voor personen die lid zijn van account_ filter.

![](assets/account-smart-lists-12.png)

>[!NOTE]
>
>De resultaten van de slimme lijst Personen die lid zijn van account tonen elke persoon in de geïdentificeerde account(s), niet alleen de personen die via de filters Gelijktijdige persoon in de slimme lijst met accounts zijn gevonden.

>[!NOTE]
>
>**Definitie**
>
>**Smart List voor personen die lid zijn van account**: In dit geval verwijst het woord &quot;lid&quot; naar de rekening zelf, dus &quot;persoon lid&quot; betekent de werkelijke personen (Marketo-administratie) in die rekeningen.
