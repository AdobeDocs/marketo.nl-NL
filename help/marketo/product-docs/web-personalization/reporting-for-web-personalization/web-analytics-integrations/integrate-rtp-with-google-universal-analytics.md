---
unique-page-id: 4720125
description: Integratie van RTP met Google Universal Analytics - Marketo Docs - Productdocumentatie
title: RTP integreren met Google Universal Analytics
exl-id: e8fc8730-c91d-44ad-8843-aa5b38f1ebd1
feature: Web Personalization
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '368'
ht-degree: 0%

---

# RTP integreren met [!DNL Google Universal Analytics] {#integrate-rtp-with-google-universal-analytics}

## Intro {#intro}

Gebruik [!DNL Google Universal Analytics] (GUA) met de firmografische en personalisatiegegevens van [!DNL Marketo Real-Time Personalization] (RTP) om uw online marketinginspanningen beter te meten en te analyseren.

In dit artikel wordt uitgelegd hoe u het [!DNL Marketo Real-Time Personalization] (RTP)-platform instelt en integreert met [!DNL Google Universal Analytics] (GUA)-accounts. RTP de gegevens kunnen aan uw rekening worden toegevoegd GUA die u toestaat om de prestaties van organisaties, industrieën, firmographics en segmenten te bekijken RTP die uw website bezoeken.

**[!DNL Google Universal Analytics]**

[!DNL Google Universal Analytics] met de gegevens van RTP verstrekt u een beter inzicht in hoe de gebruikers van B2B met uw online inhoud in wisselwerking staan en helpen meten en betere resultaten van uw verpersoonlijkingscampagnes krijgen. [ las meer over  [!DNL Google Universal Analytics] ](https://support.google.com/analytics/answer/2790010/?hl=en&authuser=1).

>[!NOTE]
>
>**voor slechts de Gebruikers van de Manager van de Markering van Google**
>
>Er hoeft geen codering of speciale configuratie te worden uitgevoerd. Controleer of u de volgende checklist invult:
>
>* RTP-afmetingen worden gemaakt in [!DNL Google Universal Analytics]
>* [ RTP de markering wordt behoorlijk geïnstalleerd in de Manager van de Markering van Google ](https://docs.marketo.com/display/public/DOCS/Implementing+RTP+using+Google+Tag+Manager)
>* [!DNL Google Universal Analytics] Integratie is ingeschakeld in de accountinstellingen van RTP
>* [[!DNL Google Universal Analytics]  de markering wordt behoorlijk gevormd in de Manager van de Markering van Google ](https://support.google.com/tagmanager/answer/6107124?hl=en)
>* [ de markering van de Manager van de Markering van Google wordt behoorlijk geïnstalleerd uw website ](https://developers.google.com/tag-manager/quickstart)

## Aangepaste afmetingen instellen in GUA {#set-up-custom-dimensions-in-gua}

1. In Google Analytics:

   1. Ga naar **[!UICONTROL Admin]**
   1. Selecteer de **[!UICONTROL Account].**
   1. Selecteer de **[!UICONTROL Property].**
   1. Selecteer **[!UICONTROL Custom Definitions]** en **[!UICONTROL Custom Dimensions]** .
      ![](assets/image2014-11-29-11-3a2-3a32.png)

1. Voeg een nieuwe aangepaste dimensie toe. Klikken **[!UICONTROL +New Custom Dimension]**

   ![](assets/image2014-11-29-11-3a8-3a16.png)

1. Voeg het volgende toe **[!UICONTROL Custom Dimensions]:**

<table>
 <tbody>
  <tr>
   <td><p><strong>Aangepaste Dimension-naam</strong></p></td>
   <td><p><strong>Toepassingsgebied</strong></p></td>
   <td><p><strong>Actief</strong></p></td>
  </tr>
  <tr>
   <td><p><strong>RTP-organisatie</strong></p></td>
   <td><p>Sessie</p></td>
   <td><p align="center">✓</p></td>
  </tr>
  <tr>
   <td><p><strong>RTP-industrie</strong></p></td>
   <td><p>Sessie</p></td>
   <td><p align="center">✓</p></td>
  </tr>
  <tr>
   <td><p><strong>RTP-categorie</strong></p></td>
   <td><p>Sessie</p></td>
   <td><p align="center">✓</p></td>
  </tr>
  <tr>
   <td><p><strong>RTP-groep</strong></p></td>
   <td><p>Sessie</p></td>
   <td><p align="center">✓</p></td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>**de Namen van Dimension van de Douane** moeten precies zijn zoals die in de lijst hierboven worden bepaald (anders zullen de de dashboards en rapporten van douane RTP in GUA niet correct tonen)

1. Voeg de lus **[!UICONTROL Name]** toe. Selecteer het bereik als **[!UICONTROL Session]** . Klik op **[!UICONTROL Create]**.

   ![](assets/image2014-11-29-11-3a12-3a51.png)

Je lijst Aangepaste Dimension moet er zo uitzien.

![](assets/image2014-11-29-11-36-50-version-2.png)

Zodra u de Dimensies van de Douane in GUA hebt geactiveerd, ga naar het platform RTP om deze afmetingen binnen RTP toe te laten.

## Activeer de integratie GUA in uw rekening RTP {#activate-the-gua-integration-in-your-rtp-account}

1. Ga in het platform RTP naar **[!UICONTROL Account Settings].**

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. Klik onder **[!UICONTROL Account Settings]** op **[!UICONTROL Domain]** .
1. Klik onder **[!UICONTROL Analytics]** op **[!UICONTROL Google Universal Analytics]** .
1. Draai **[!UICONTROL On]** de relevante afmetingen en gebeurtenissen van de Douane om deze gegevens van RTP aan [!DNL Google Universal Analytics] toe te voegen.
1. Voer in GUA de **[!UICONTROL Index number]** van de dimensie die is uitgelijnd met het indexnummer in.
1. Klik op **[!UICONTROL Save]**.

![](assets/image2014-11-29-11-31-23-version-2.png)

>[!NOTE]
>
>Het indexnummer voor de aangepaste Dimension is te vinden in GUA onder Aangepaste afmetingen.
>
>Voorbeeld: RTP-Industry Index Number is gelijk aan 1, RTP-Organization Index Number is gelijk aan 2.

## Oude dashboards verwijderen in Google Analytics {#remove-old-dashboards-in-google-analytics}

1. In Google Analytics. Ga naar **[!UICONTROL Reporting].**
1. Klik op **[!UICONTROL Dashboards].**
1. Selecteer een **[!UICONTROL Dashboard]** (RTP B2B- of RTP-prestaties)
1. Klik op **[!UICONTROL Delete Dashboard]**.

![](assets/image2014-11-29-11-3a42-3a55.png)
