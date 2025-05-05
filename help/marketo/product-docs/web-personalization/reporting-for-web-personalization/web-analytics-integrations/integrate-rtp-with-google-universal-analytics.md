---
unique-page-id: 4720125
description: Integratie van RTP met Google Universal Analytics - Marketo Docs - Productdocumentatie
title: RTP integreren met Google Universal Analytics
exl-id: e8fc8730-c91d-44ad-8843-aa5b38f1ebd1
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '456'
ht-degree: 0%

---

# RTP integreren met Google Universal Analytics {#integrate-rtp-with-google-universal-analytics}

## Intro {#intro}

Hefboomwerking Google Universal Analytics (GUA) met Marketo Real-Time Personalization&#39;s (RTP) firmographic and personalization data om uw online marketinginspanningen beter te meten en te analyseren.

In dit artikel wordt uitgelegd hoe u het Marketo Real-Time Personalization (RTP)-platform instelt en integreert met de accounts van Google Universal Analytics (GUA). RTP de gegevens kunnen aan uw rekening worden toegevoegd GUA die u toestaat om de prestaties van organisaties, industrieën, firmographics en segmenten te bekijken RTP die uw website bezoeken.

**Google Universal Analytics**

Google Universal Analytics met RTP-gegevens biedt u een beter inzicht in de manier waarop B2B-gebruikers met uw online-inhoud werken en helpt u betere resultaten te meten en te behalen uit uw personalisatiecampagnes. [Meer informatie over Google Universal Analytics](https://support.google.com/analytics/answer/2790010/?hl=en&amp;authuser=1).

>[!NOTE]
>
>**Alleen voor gebruikers van Google-tagbeheer**
>
>Er hoeft geen codering of speciale configuratie te worden uitgevoerd. Controleer of u de volgende checklist invult:
>
>* RTP-afmetingen worden gemaakt in Google Universal Analytics
>* [De RTP-tag is correct geïnstalleerd in Google-tagbeheer](https://docs.marketo.com/display/public/DOCS/Implementing+RTP+using+Google+Tag+Manager)
>* Google Universal Analytics Integration is ingeschakeld in de accountinstellingen van RTP
>* [Google Universal Analytics-tag is correct geconfigureerd in Google Tag Manager](https://support.google.com/tagmanager/answer/6107124?hl=en)
>* [De tag Google Tag Manager is correct geïnstalleerd op uw website](https://developers.google.com/tag-manager/quickstart)

## Aangepaste Dimension instellen in GUA {#set-up-custom-dimensions-in-gua}

1. In Google Analytics,

   1. Ga naar **Beheer**
   1. Selecteer **Account.**
   1. Selecteer **Eigenschap.**
   1. Selecteren **Aangepaste definities** en **Aangepaste Dimension**.

      ![](assets/image2014-11-29-11-3a2-3a32.png)

1. Voeg een nieuwe aangepaste dimensie toe. Klikken **+Nieuwe aangepaste Dimension**

   ![](assets/image2014-11-29-11-3a8-3a16.png)

1. Voeg het volgende toe **Aangepaste Dimension:**

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
>**Aangepaste Dimension-namen** moet exact zijn zoals gedefinieerd in de bovenstaande tabel (anders worden aangepaste RTP-dashboards en -rapporten in GUA niet correct weergegeven)

1. Voeg de **Naam**. Bereik selecteren als **Sessie**. Klikken **Maken**.

   ![](assets/image2014-11-29-11-3a12-3a51.png)

Uw lijst Aangepaste Dimension moet er zo uitzien.

![](assets/image2014-11-29-11-36-50-version-2.png)

Zodra u de Dimension van de Douane in GUA hebt geactiveerd, ga naar het platform RTP om deze dimensies binnen RTP toe te laten.

## Activeer de integratie GUA in uw rekening RTP {#activate-the-gua-integration-in-your-rtp-account}

1. Ga in het platform RTP naar **Accountinstellingen.**

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. Onder **Accountinstellingen**, klikt u op **Domein**.
1. Onder **Analyse**, klikt u op **Google Universal Analytics**.
1. Draaien **Aan** de relevante Dimension en Gebeurtenissen van de Douane om deze gegevens van RTP aan Google Universal Analytics toe te voegen.
1. Voer de **Indexnummer** van de dimensie uitgelijnd met het indexnummer in GUA.
1. Klikken **Opslaan**.

![](assets/image2014-11-29-11-31-23-version-2.png)

>[!NOTE]
>
>Het indexnummer voor de aangepaste Dimension is te vinden in GUA onder Aangepaste Dimension.
>
>Voorbeeld: RTP-Industry Index Number is gelijk aan 1, RTP-Organization Index Number is gelijk aan 2.

## Oude dashboards verwijderen in Google Analytics {#remove-old-dashboards-in-google-analytics}

1. In Google Analytics. Ga naar **Rapportage.**
1. Klikken op **Dashboards.**
1. Selecteer een **Dashboard** (RTP B2B- of RTP-prestaties)
1. Klikken **Dashboard verwijderen**.

![](assets/image2014-11-29-11-3a42-3a55.png)
