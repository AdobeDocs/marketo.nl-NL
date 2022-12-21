---
unique-page-id: 6095029
description: Conversies van Google AdWords instellen in het inkomstenmodel - Marketo Docs - Productdocumentatie
title: Conversies van Google AdWords instellen in het inkomstenmodel
exl-id: dd1259fc-d3f2-44ec-8055-f75d55263b36
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '503'
ht-degree: 0%

---

# Conversies van Google AdWords instellen in het inkomstenmodel {#set-google-adwords-conversions-in-the-revenue-model}

Koppel uw Google AdWords-account aan Marketo om automatisch offline conversiegegevens te uploaden van Marketo naar Google AdWords. Dan, van AdWords UI, zult u gemakkelijk kunnen zien welke klikken in gekwalificeerde lood, kansen en nieuwe klanten (of welke opbrengststadia u wilt volgen) na u resulteerden [aangepaste kolommen toevoegen](https://support.google.com/adwords/answer/3073556) in AdWords.

>[!NOTE]
>
>Dit is een push-integratie van Marketo naar Google AdWords. Conversiegegevens verschijnen _alleen_ in uw Google AdWords-portal, _niet in de gebruikersinterface van Marketo_.

Meer informatie over [De functie voor het importeren van offlineconversies van Google](https://support.google.com/adwords/answer/2998031?hl=en). Wijs AdWords off-line omzettingen aan één of meerdere stadia in een model van de Inkomsten toe. U kunt de toewijzing op drie manieren uitvoeren:

* Advertentieconversie
* Werkgebiedactie
* Toewijzing van adWoorden

U kunt een nieuwe AddWords off-line omzetting van Marketo tot stand brengen als u de Actie van het Stadium gebruikt.

>[!PREREQUISITES]
>
>[Google AdWords toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md)

## Advertentieconversie gebruiken {#use-adwords-conversion}

1. Ga naar de **Analyse** gebied.

   ![](assets/image2015-2-23-18-3a9-3a34.png)

1. Selecteer een model.

   ![](assets/image2015-2-23-18-3a3-3a12.png)

1. Klikken **Concept bewerken**.

   ![](assets/image2015-3-10-15-3a3-3a20.png)

1. Selecteer de inkomstenfase u aan een omzetting wilt in kaart brengen AdWords.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Selecteer **Advertentieconversie** Je wilt een kaart maken naar je Marketo-podium.

   ![](assets/image2015-2-26-16-3a46-3a15.png)

   Mooi! De conversiegegevens van de ADW-woorden worden geüpload naar de Google AdWords in de geselecteerde volgorde.

## Werkgebiedactie gebruiken {#use-stage-action}

U kunt ook een ADW-conversie toewijzen onder Werkgebiedhandelingen.

1. Selecteer de stap u aan een omzetting wilt in kaart brengen AdWords.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Onder de **Werkgebiedhandelingen** vervolgkeuzelijst, selecteren **Advertentieconversie instellen**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Selecteer een **Advertentieconversie**.

   ![](assets/image2015-2-26-16-3a54-3a47.png)

   **Tip**: Als u geen omzettingen AdWords hebt, creeer één door te klikken **+Nieuwe conversie**.

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. Klikken **Opslaan**.

   ![](assets/image2015-2-26-16-3a56-3a2.png)

1. Nadat u klaar bent met het in kaart brengen van al uw omzettingen AdWords in opbrengststadia, ga terug naar de summiere pagina. Selecteren **Modelhandelingen** en kiest u **Fases goedkeuren**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## Pro-tip: Nieuwe conversie toevoegen {#pro-tip-add-a-new-conversion}

Pro tip! Er kan een nieuwe offline AdWords-conversie worden gemaakt vanuit Marketo.

>[!CAUTION]
>
>Voor nieuwe omzettingen die zijn gemaakt met Marketo is de instelling &quot;optimalisatie&quot; ingeschakeld. Dit betekent dat Advertentiestrategieën worden toegestaan om uw biedingen voor die omzettingen te optimaliseren. U kunt deze instelling wijzigen vanuit uw AdWords-account.

1. Onder de **Werkgebiedhandelingen** vervolgkeuzelijst, selecteren **Advertentieconversie instellen**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Selecteren **Nieuwe conversie**.

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. Voer een **Conversienaam**. Klikken **Opslaan**.

   ![](assets/image2015-2-26-21-3a24-3a7.png)

   Uitstekend! Deze nieuwe conversie wordt weergegeven in uw AdWords-account.

## Toewijzing van adWoorden gebruiken {#use-adwords-mapping}

U kunt al uw modelstadia met uw Conversie AdWords in één plaats associëren gebruikend Toewijzingen AdWords.

1. Selecteren **Toewijzingen van adWoorden bewerken**.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. Selecteer het gewenste **Advertentieconversie** voor elk werkgebied dat u wilt bijhouden.

   ![](assets/image2015-2-26-17-3a6-3a15.png)

1. Nadat u de stadia hebt toegewezen, klikt u op **Opslaan**.

   ![](assets/image2015-2-26-17-3a7-3a48.png)

1. Nadat u klaar bent met het in kaart brengen van al uw omzettingen AdWords in opbrengststadia, ga terug naar de summiere pagina. Selecteren **Modelhandelingen** en kiest u **Fases goedkeuren**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

Als u de gegevens van de offline conversie wilt weergeven, moet u zich aanmelden bij uw AdWords-account. We raden je aan hun [Functie Aangepaste kolommen](https://support.google.com/adwords/answer/3073556) om conversietelling te maken voor elke offline conversie die u uit Marketo importeert.
