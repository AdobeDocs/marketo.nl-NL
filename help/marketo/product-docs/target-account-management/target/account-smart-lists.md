---
unique-page-id: 11378814
description: Slimme accountlijsten - Marketo Docs - Productdocumentatie
title: Slimme accountlijsten
exl-id: fbdfb2b8-0061-467d-be89-527744a659a9
feature: Target Account Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '428'
ht-degree: 0%

---

# Slimme accountlijsten {#account-smart-lists}

Hieronder wordt beschreven hoe u uw hoogwaardige accounts snel en nauwkeurig kunt identificeren.

>[!NOTE]
>
>Deze functie is alleen beschikbaar voor gebruikers met zowel de [!UICONTROL Target Account Management] add-on als een TAM-licentie.

## Een [!UICONTROL Account Smart List] maken {#create-an-account-smart-list}

1. Ga in Marketo naar **[!UICONTROL Marketing Activities]** .

   ![](assets/account-smart-lists-1.png)

1. Zoek en selecteer het gewenste programma.

   ![](assets/account-smart-lists-2.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL New]** en selecteer **[!UICONTROL New Local Asset]** .

   ![](assets/account-smart-lists-3.png)

1. Klik op **[!UICONTROL Account Smart List]**.

   ![](assets/account-smart-lists-4.png)

1. Voer een naam in en klik op **[!UICONTROL Create]** (Beschrijving en labels zijn optioneel).

   ![](assets/account-smart-lists-5.png)

Uw [!UICONTROL Account Smart List] is gemaakt! Zie hieronder voor stappen over het definiëren van de regels.

## [!UICONTROL Account Smart List] Regels {#account-smart-list-rules}

[!UICONTROL Account Smart Lists] werkt net als standaard slimme lijsten, met een opmerkelijke uitzondering: containers.

1. Klik op de tab [!UICONTROL Account Smart List] om de **[!UICONTROL Account Smart List Rules]** -tab te definiëren.

   ![](assets/account-smart-lists-6.png)

1. Kies de gewenste accountfilter(s). In dit voorbeeld kiezen we _[!UICONTROL Industry]is[!UICONTROL Healthcare]_ .

   ![](assets/account-smart-lists-7.png)

   ![](assets/account-smart-lists-8.png)

   >[!NOTE]
   >
   >ICP indicatorgegevens die in uw [&#x200B; het Profileren van de Rekening het Profileren Rangschikken en het Tunnen &#x200B;](/help/marketo/product-docs/target-account-management/account-profiling/account-profiling-ranking-and-tuning.md) werden gebruikt zullen als de Attributen van de douaneRekening voor gebruik in uw Slimme Lijst van de Rekening verschijnen. Deze aangepaste kenmerkgegevens zijn gebaseerd op de datum waarop het accountprofielmodel is gemaakt/bijgewerkt.

1. Kies uw filter(s) voor overeenstemmende personen. In dit voorbeeld kiezen wij _Staat Californië_ is.

   ![](assets/account-smart-lists-9.png)

**OPTIONELE STAP**: Hier is waar de containers binnen komen. Als u een extra Gelijke Filter van de Persoon kiest, kunt u het onder eerste laten vallen, of _in_ het, creërend een container. In dit voorbeeld creëren wij een container door _Titel van de Baan toe te voegen is CFO_.

![](assets/account-smart-lists-10.png)

Zo ziet de container eruit.

![](assets/account-smart-lists-11.png)

>[!NOTE]
>
>Als u een container met filters maakt, wordt de regel &quot;en&quot; gemaakt. Dit betekent dat alleen alle gecombineerde resultaten worden geretourneerd. In dit voorbeeld, rekeningen met een industrie van gezondheidszorg, samen met worden gevestigd in Californië _en_ met iemand die als CFO wordt vermeld. Als u geen containers wilt gebruiken, laat u gewoon het filter onder of boven de bestaande onder- of boven.

En dat is het! Bekijk de onderstaande sectie om te zien hoe u uw [!UICONTROL Account Smart List] kunt gebruiken.

>[!TIP]
>
>Net als bij standaard slimme lijsten kunt u geavanceerde logica gebruiken om de resultaten verder te verfijnen. Hiervoor hebt u ten minste drie filters nodig en in [!UICONTROL Account Smart Lists] is één container (ongeacht het aantal filters dat de container zelf bevat) gelijk aan één filter.

## [!UICONTROL Account Smart List] Handelingen {#account-smart-list-actions}

Op het tabblad Overzicht van uw [!UICONTROL Account Smart List] ziet u enkele actieopties.

**[!UICONTROL Export]**: hiermee exporteert u de resultaten van uw [!UICONTROL Account Smart List] als een CSV-bestand.

**[!UICONTROL Clone]**: hiermee maakt u een kopie van de [!UICONTROL Account Smart List] .

**[!UICONTROL Send to Ad Network]**: verzendt de lijst naar [!DNL LinkedIn] als een nieuw Gelijkend publiek.

U kunt ook naar uw [!UICONTROL Account Smart List] in een standaard slimme campagne/lijst verwijzen met het filter _[!UICONTROL People Member of Account Smart List]_.

![](assets/account-smart-lists-12.png)

>[!NOTE]
>
>De resultaten van de [!UICONTROL People Member of Account Smart List] tonen elke persoon in de geïdentificeerde account(s), niet alleen de personen die via de filters Gelijktijdige persoon in de slimme lijst met accounts zijn gevonden.

>[!NOTE]
>
>**Definitie**
>
>**[!UICONTROL People Member of Account Smart List]**: In dit geval verwijst het woord &quot;lid&quot; naar de account zelf, dus &quot;persoon lid&quot; verwijst naar de werkelijke personen (Marketo-records) in die accounts.
