---
unique-page-id: 2359798
description: Aanvullende landingspaginanamen toevoegen - Marketo Docs - Productdocumentatie
title: Aanvullende landingspaginanamen toevoegen
translation-type: tm+mt
source-git-commit: 2969e6f94f5fd781e2167ae2aa8680bb8d134754
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---


# Aanvullende landingspaginanamen toevoegen {#add-additional-landing-page-cnames}

U kunt bestemmingspagina CNAMEs willen toevoegen om verschillende URLs toe te staan om aan uw Marketo te richten landende pagina&#39;s. Als u de onderstaande stappen uitvoert, kunt u meerdere domeinen beheren.

>[!CAUTION]
>
>Cookies kunnen niet worden gedeeld in verschillende domeinen.

>[!TIP]
>
>**Hetzelfde topniveaudomein - Goed! Cookies worden gedeeld**.<br/> **go**.mijnbedrijf.com >  **info**.mijnbedrijf.nl
>
>**Verschillende topniveaudomeinen - Slecht! Cookies worden _niet_ gedeeld**.<br/> gaan.**mijnbedrijf**.com > ga.**mijnbedrijf**.com

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Uw accounttekenreeks zoeken {#find-your-account-string}

1. Ga naar **Admin** gebied en klik **Landing Pages**.

   ![](assets/image2014-9-16-15-3a19-3a54.png)

1. Kopieer **Account String** van de sectie **Settings**.

   ![](assets/image2014-9-16-15-3a20-3a2.png)

1. Noteer dit voor de volgende stap.

## Verzoek verzenden naar IT {#send-request-to-it}

1. Vraag uw afdeling van IT om volgende CNAME te installeren: (Vervang het woord [CNAME] met de NAAM van uw keus en [ACCOUNT STRING] met de tekst van de vorige stap).

   [CNAME].YourCompany.com >  [ACCOUNT STRING].mktoweb.com

## Nieuwe CNAME {#add-a-new-cname} toevoegen

1. Zodra uw afdeling van IT CNAME heeft gecreeerd, ga naar **Admin** dan **Landing Pages** klikken.

   ![](assets/image2014-9-16-15-3a20-3a20.png)

1. Klik **Nieuw** dan uitgezocht **Nieuwe Alias van het Domein**.

   ![](assets/image2014-9-16-15-3a20-3a28.png)

1. Voer uw **Domeinalias in.** De  **standaardpagina** wordt weergegeven als de bezoeker geen URL plaatst. Voer in dat geval in waar ze naartoe moeten.

   >[!NOTE]
   >
   >Voor de standaardpagina kunt u een openingspagina of een externe URL selecteren, zoals uw openbare website.

   ![](assets/image2014-9-16-15-3a20-3a36.png)

1. Voer uw **Standaardpagina** in en klik op **Maken**.

   ![](assets/image2014-9-16-15-3a20-3a43.png)

Mooi! Nu weet u wat te doen als u ooit een NAAM wilt toevoegen.
