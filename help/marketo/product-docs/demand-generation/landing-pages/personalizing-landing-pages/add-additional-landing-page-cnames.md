---
unique-page-id: 2359798
description: Extra landingpagina-CNAME's toevoegen - Marketo Docs - Productdocumentatie
title: Aanvullende landingspaginanamen toevoegen
exl-id: eb5a7f69-552e-49a2-91db-a784f4639cd0
source-git-commit: 6c1699ce986608e8b9d991f21fd649f9330e3d12
workflow-type: tm+mt
source-wordcount: '0'
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

1. Ga naar de **Beheer** gebied.

   ![](assets/add-additional-landing-page-cnames-1.png)

1. Klikken **Mijn account**.

   ![](assets/add-additional-landing-page-cnames-2.png)

1. Blader omlaag naar &quot;Ondersteuningsinformatie&quot; en kopieer uw Munchkin-id.

   ![](assets/add-additional-landing-page-cnames-3.png)

## Verzoek verzenden naar IT {#send-request-to-it}

1. Vraag uw afdeling van IT om volgende CNAME te installeren: (Vervang het woord [CNAME] met de NAAM van uw keuze en [Munchkin-id] met de tekst uit de vorige stap).

   [CNAME].YourCompany.com > [Munchkin-id].mktoweb.com

## Een nieuwe NAAM toevoegen {#add-a-new-cname}

1. Zodra uw afdeling van IT CNAME heeft gecreeerd, ga naar **Beheer** gebied.

   ![](assets/add-additional-landing-page-cnames-4.png)

1. Klikken **Openingspagina&#39;s**.

   ![](assets/add-additional-landing-page-cnames-5.png)

1. Klikken **Nieuw** Selecteer vervolgens **Nieuwe domeinalias**.

   ![](assets/add-additional-landing-page-cnames-6.png)

1. Voer uw **Domeinalias.** De **Standaardpagina** wordt weergegeven als de bezoeker geen URL plaatst. Voer in dat geval in waar ze naartoe moeten.

   >[!NOTE]
   >
   >Voor de standaardpagina kunt u een openingspagina of een externe URL selecteren, zoals uw openbare website.

   ![](assets/add-additional-landing-page-cnames-7.png)

1. Voer uw **Standaardpagina** en klik op **Maken**.

   ![](assets/add-additional-landing-page-cnames-8.png)

Mooi! Nu weet u wat te doen als u ooit een NAAM wilt toevoegen.
