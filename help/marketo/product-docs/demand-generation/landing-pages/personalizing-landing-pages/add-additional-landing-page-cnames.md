---
unique-page-id: 2359798
description: Extra landingpagina-CNAME's toevoegen - Marketo Docs - Productdocumentatie
title: Aanvullende landingspaginanamen toevoegen
exl-id: eb5a7f69-552e-49a2-91db-a784f4639cd0
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---

# Aanvullende landingspaginanamen toevoegen {#add-additional-landing-page-cnames}

U kunt landingspagina&#39;s toevoegen om verschillende URL&#39;s toe te staan om naar de Marketo-bestemmingspagina&#39;s te wijzen. Als u de onderstaande stappen uitvoert, kunt u meerdere domeinen beheren.

>[!CAUTION]
>
>Cookies kunnen niet worden gedeeld in verschillende domeinen.

>[!TIP]
>
>**Hetzelfde topniveaudomein - Goed! Cookies worden gedeeld**.<br/> **gaan**.mijnbedrijf.nl > **info**.mijnbedrijf.nl
>
>**Verschillende topniveaudomeinen - Slecht! Cookies zijn _niet_ gedeeld**.<br/> gaan.**mijnbedrijf**.com > Ga.**mijnbedrijf**.com

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## De tekenreeks van uw account zoeken {#find-your-account-string}

1. Ga naar de **Beheer** gebied en klik **Openingspagina&#39;s**.

   ![](assets/image2014-9-16-15-3a19-3a54.png)

1. Kopieer de **Rekeningreeks** van de **Instellingen** sectie.

   ![](assets/image2014-9-16-15-3a20-3a2.png)

1. Noteer dit voor de volgende stap.

## Verzoek verzenden naar IT {#send-request-to-it}

1. Vraag uw afdeling van IT om volgende CNAME te installeren: (Vervang het woord [CNAME] met de NAAM van uw keuze en [ACCOUNTTEKENREEKS] met de tekst uit de vorige stap).

   [CNAME].YourCompany.com > [ACCOUNTTEKENREEKS].mktoweb.com

## Een nieuwe NAAM toevoegen {#add-a-new-cname}

1. Zodra uw afdeling van IT CNAME heeft gecreeerd, ga naar **Beheer** klik vervolgens op **Openingspagina&#39;s**.

   ![](assets/image2014-9-16-15-3a20-3a20.png)

1. Klikken **Nieuw** Selecteer vervolgens **Nieuwe domeinalias**.

   ![](assets/image2014-9-16-15-3a20-3a28.png)

1. Voer uw **Domeinalias.** De **Standaardpagina** wordt weergegeven als de bezoeker geen URL plaatst. Voer in dat geval in waar ze naartoe moeten.

   >[!NOTE]
   >
   >Voor de standaardpagina kunt u een openingspagina of een externe URL selecteren, zoals uw openbare website.

   ![](assets/image2014-9-16-15-3a20-3a36.png)

1. Voer uw **Standaardpagina** en klik op **Maken**.

   ![](assets/image2014-9-16-15-3a20-3a43.png)

Mooi! Nu weet u wat te doen als u ooit een NAAM wilt toevoegen.
