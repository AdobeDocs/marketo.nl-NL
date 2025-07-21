---
unique-page-id: 2359798
description: Extra landingpagina-CNAME's toevoegen - Marketo Docs - Productdocumentatie
title: Aanvullende landingspaginanamen toevoegen
exl-id: eb5a7f69-552e-49a2-91db-a784f4639cd0
feature: Landing Pages
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# Aanvullende landingspaginanamen toevoegen {#add-additional-landing-page-cnames}

U kunt landingspagina&#39;s toevoegen om verschillende URL&#39;s toe te staan om naar de Marketo-bestemmingspagina&#39;s te wijzen. Als u de onderstaande stappen uitvoert, kunt u meerdere domeinen beheren.

>[!CAUTION]
>
>Cookies kunnen niet worden gedeeld in verschillende domeinen.

>[!TIP]
>
>**Zelfde hoogste niveaudomein - Goed! Cookies worden gedeeld**.<br/> **ga** .mycompany.com > **info** .mycompany.com
>
>**Verschillende hoogste niveaudomeinen - Slecht! De cookies zijn _niet_ gedeeld**.<br/> go.**mijnbedrijf**.com > gaat.**mijnbedrijf**.com

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Ga naar het **Admin** gebied.

   ![](assets/add-additional-landing-page-cnames-1.png)

1. Klik **Mijn Rekening**.

   ![](assets/add-additional-landing-page-cnames-2.png)

1. Blader omlaag naar &quot;Ondersteuningsinformatie&quot; en kopieer uw Munchkin-id.

   ![](assets/add-additional-landing-page-cnames-3.png)

## Verzoek verzenden naar IT {#send-request-to-it}

1. Vraag uw afdeling van IT om volgende CNAME te opstelling: (Vervang het woord [ CNAME ] met de NAAM van uw keus en [ identiteitskaart van Munchkin ] met de tekst van de vorige stap).

   [ .YourCompany.com ] identiteitskaart van Munchkin [ .mktoweb.com]

## Een nieuwe NAAM toevoegen {#add-a-new-cname}

1. Zodra uw afdeling van IT CNAME heeft gecreeerd, ga naar het **Admin** gebied.

   ![](assets/add-additional-landing-page-cnames-4.png)

1. Klik **het Bestaan Pagina&#39;s**.

   ![](assets/add-additional-landing-page-cnames-5.png)

1. Klik op **[!UICONTROL New]** en selecteer vervolgens **[!UICONTROL New Domain Alias]** .

   ![](assets/add-additional-landing-page-cnames-6.png)

1. Voer uw **[!UICONTROL Domain Alias]in.** De **[!UICONTROL Default Page]** wordt weergegeven als de bezoeker geen URL plaatst. Voer in dat geval in waar ze naartoe moeten.

   >[!NOTE]
   >
   >Voor [!UICONTROL Default Page] kunt u een bestemmingspagina of een externe URL selecteren, zoals uw openbare website.

   ![](assets/add-additional-landing-page-cnames-7.png)

1. Voer uw **[!UICONTROL Default Page]** in en klik op **[!UICONTROL Create]** .

   ![](assets/add-additional-landing-page-cnames-8.png)

Mooi! Nu weet u wat te doen als u ooit een NAAM wilt toevoegen.
